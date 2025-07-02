---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

title: Doxygen Internals
slug: /api/
custom_edit_url: null
keywords:
  - doxygen
  - reference

---

<div class="doxyPage">




<a id="mainpage"></a>

Generated on Thursday, June 26, 2025 at 10:59 AM

## Introduction {#autotoc_md0}


This page provides a high-level overview of the internals of doxygen, with links to the relevant parts of the code. This document is intended for developers who want to work on doxygen. Users of doxygen are referred to the <a href="https://www.doxygen.nl/manual/index.html">User Manual</a>.

The generic starting point of the application is of course the <a href="/web-doxygen/docs/api/files/src/main-cpp/#a3c04138a5bfe5d72780bb7e82a18e627">main()</a> function.

## Configuration options {#autotoc_md1}


Configuration file data is stored in singleton class <a href="/web-doxygen/docs/api/namespaces/config">Config</a> and can be accessed using wrapper macros <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString()</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt()</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config\_getList()</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config\_getEnum()</a>, and <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool()</a> depending on the type of the option.

The format of the configuration file (options and types) is defined by the file <code>config.xml</code>. As part of the build process, the python script <code>configgen.py</code> will create the files <code>configoptions.cpp</code>, <code>configvalues.h</code> and <code>configvalues.cpp</code> from this, which serves as the input for the configuration file parser that is invoked using <a href="/web-doxygen/docs/api/namespaces/config/#a88ed583dc36b1439108163403cc4224f">Config::parse()</a>. The script <code>configgen.py</code> will also create the documentation for the configuration items, creating the file <code>config.doc</code>.

## Gathering Input files {#autotoc_md2}


After the configuration is known, the input files are searched using <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles()</a> and any tag files are read using <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile()</a>

## Parsing Input files {#autotoc_md3}


The function <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae28f1a48382c964843997257b8d171f9">parseFilesSingleThreading()</a> takes care of parsing all files (in case <code>NUM\_PROC\_THREADS!=1</code>, the function <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af69cff788100ddb682f88658018d3969">parseFilesMultiThreading()</a> is used instead).

These functions use the <a href="/web-doxygen/docs/api/classes/parsermanager">ParserManager</a> singleton factory to create a suitable parser object for each file. Each parser implements two abstract interfaces: <a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a> en <a href="/web-doxygen/docs/api/classes/codeparserinterface">CodeParserInterface</a>. The <a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a> is used to collect information about the symbols that can be documented but does not look into the body of functions. The <a href="/web-doxygen/docs/api/classes/codeparserinterface">CodeParserInterface</a> is used for syntax highlighting, but also to collect the symbol references needed for cross reference relations.

If the parser indicates it needs preprocessing via <a href="/web-doxygen/docs/api/classes/outlineparserinterface/#a0df8efc6ad67956cf54b7dec68c932b4">OutlineParserInterface::needsPreprocessing()</a>, doxygen will call <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile()</a> on the file.

A second step is to convert multiline C++-style comments into C style comments for easier processing later on. As side effect of this step also aliases (ALIASES option) are resolved. The function that performs these 2 tasks is called <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments()</a>.

<em>Note:</em> Alias resolution should better be done in a separate step as it is now coupled to C/C++ code and does not work automatically for other languages!

The third step is the actual language parsing and is done by calling <a href="/web-doxygen/docs/api/classes/outlineparserinterface/#a40c002cf93d56d617f3ca92ff9b0a210">OutlineParserInterface::parseInput()</a> on the parser interface returned by the <a href="/web-doxygen/docs/api/classes/parsermanager">ParserManager</a>.

The result of parsing is a tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> objects. Each <a href="/web-doxygen/docs/api/classes/entry">Entry</a> object roughly contains the raw data for a symbol and is later converted into a <a href="/web-doxygen/docs/api/classes/definition">Definition</a> object.

When a parser finds a special comment block in the input, it will do a first pass parsing via <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock()</a>. During this pass the comment block is split into multiple parts if needed. Some data that is later needed is extracted like section labels, xref items, and formulas. Also <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> markup is processed via <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process()</a> during this pass.

## Resolving relations {#autotoc_md4}


The <a href="/web-doxygen/docs/api/classes/entry">Entry</a> objects created and filled during parsing and stored as a tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> nodes, which is kept in memory.

Doxygen does a number of tree walks over the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> nodes in the tree to build up the data structures needed to produce the output.

The resulting data structures are all children of the generic base class called <a href="/web-doxygen/docs/api/classes/definition">Definition</a> which holds all non-specific data for a symbol definition.

<a href="/web-doxygen/docs/api/classes/definition">Definition</a> is an abstract base class. Concrete subclasses are

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>: for storing class/struct/union related data</li>
<li><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a>: for storing C++20 concept definitions</li>
<li><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a>: for storing namespace related data</li>
<li><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>: for storing file related data</li>
<li><a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a>: for storing directory related data</li>
</ul>

For doxygen specific concepts the following subclasses are available

<ul class="doxyList ">
<li><a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>: for storing grouping related data</li>
<li><a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a>: for storing page related data</li>
</ul>

Finally the data for members of classes, namespaces, and files is stored in the subclass <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>. This class is used for functions, variables, enums, etc, as indicated by <a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">MemberDef::memberType()</a>.

## Producing tracing and debug output {#autotoc_md5}


Within doxygen there are a number of ways to obtain debug output. Besides the invasive method of putting print statements in the code there are a number of easier ways to get debug information.

For a debug build (build option <code>-DCMAKE\_BUILD\_TYPE=Debug</code>) these options are always available, but for a release build some debug capabilities have to be enabled explicitly (see build options <code>-Denable\_tracing=YES</code> and <code>-Denable\_lex\_debug=YES</code>).

To enable tracing use the <code>-t</code> option. You can optionally specify a name of a trace file, if omitted <code>trace.txt</code> will be used. When running doxygen with tracing enabled, doxygen will write a lot of internal information to the trace file, which can be used (by experts) to diagnose problems.

During a run of doxygen it is possible to specify the <code>-d</code> command line option with one of the following values (each option has to be preceded by <code>-d</code>):

<ul class="doxyList ">
<li><code>preprocessor</code>
<br/>
 Shows the results of the preprocessing phase, i.e. results from include files, <code>#define</code> statements etc., definitions in the doxygen configuration file like: <code>EXPAND_ONLY_PREDEF</code>, <code>PREDEFINED</code> and <code>MACRO_EXPANSION</code>.</li>
<li><code>nolineno</code>
<br/>
 In case the line numbers in the results of the preprocessing phase are not wanted they can be removed by means of this option (without <code>-d preprocessor</code> this option has no effect.</li>
<li><code>commentcnv</code>
<br/>
 Shows the results of the comment conversion, the comment conversion does the following:

<ul class="doxyList ">
<li>It converts multi-line C++ style comment blocks (that are aligned) to C style comment blocks (if <code>MULTILINE_CPP_IS_BRIEF</code> is set to <code>NO</code>).</li>
<li>It replaces aliases with their definition (see <code>ALIASES</code>)</li>
<li>It handles conditional sections (<code>\cond ... \endcond</code> blocks)</li>
</ul></li>
<li><code>commentscan</code>
<br/>
 Will print each comment block before and after the comment is interpreted by the comment scanner.</li>
<li><code>printtree</code>
<br/>
 Give the results in pretty print way, i.e. in an XML like way with each level indented by a <code>"."</code> (dot).</li>
<li><code>time</code>
<br/>
 Provides information of the different stages of the doxygen process.</li>
<li><code>extcmd</code>
<br/>
 Shows which external commands are executed and which pipes are opened.</li>
<li><code>markdown</code>
<br/>
 Will print each comment block before and after <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> processing.</li>
<li><code>filteroutput</code>
<br/>
 Gives the output of the output as result of the filter command (when a filter command is specified)</li>
<li><code>cite</code>
<br/>
 Retains the temporary files as created and used for the non LaTeX output results of the generation of the bibliographical references.</li>
<li><code>fortranfixed2free</code>
<br/>
 Shows the result of the conversion of Fortran fixed formatted files to Fortran free formatted files as done by doxygen.</li>
<li><code>plantuml</code>
<br/>
 Shows information about the plantuml process run and the used input / output filenames, the content of the input file.</li>
<li><code>rtf</code>
<br/>

<ul class="doxyList ">
<li>Shows the original names and the anchors names (called bookmarks in RTF) where they are mapped to.</li>
<li>At the end of the generation of the RTF files these files are merged into one large RTF file, with this option the original files are retained.</li>
</ul></li>
<li><code>qhp</code>
<br/>

<ul class="doxyList ">
<li>The qhp file is created with indentation for better readability (normally no indentation so the file is smaller).</li>
<li>When the setting <code>QHG_LOCATION</code> is pointing to the <code>qhelpgenerator</code> besides generating the <code>qch</code> file also some extra checks are done by means of the <code>-c</code> flag of the <code>qhelpgenerator</code>.</li>
</ul></li>
<li><code>tag</code>
<br/>
 Shows the results of reading the tag files.</li>
<li><code>alias</code>
<br/>
 Show the results of the <code>ALIASES</code> resolving process</li>
<li><code>entries</code>
<br/>
 Dump the tree of Entries as found by doxygen</li>
<li><code>formula</code>
<br/>
 Don't remove the intermediate files generated by the creation of the images with the formulas.</li>
<li><code>sections</code>
<br/>
 Show the sections as found by doxygen</li>
<li><code>lex</code>
<br/>
 Provide output of the <code>lex</code> files used. When a lexer is started and when a lexer ends the name of the <code>lex</code> file is given so it is possible to see in which lexer the problem occurs. This makes it easier to select the file to be compiled in <code>lex</code> debug mode.</li>
<li><code>lex:lexer</code>
<br/>
 Enables output for a specific lexer only, where <code>lexer</code> should be replaced by the name of the specific lexer.</li>
</ul>

## Producing output {#autotoc_md6}


TODO

## Documentation Topics TODO {#autotoc_md7}


<ul class="doxyList ">
<li><a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> of files in Model / Parser / Generator categories</li>
<li><a href="/web-doxygen/docs/api/classes/index">Index</a> files based on <a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a>

<ul class="doxyList ">
<li>HTML navigation</li>
<li>HTML Help (chm)</li>
<li>Documentation Sets (XCode)</li>
<li>Qt Help (qhp)</li>
<li>Eclipse Help</li>
</ul></li>
<li>Search index

<ul class="doxyList ">
<li>JavaScript based</li>
<li>Server based</li>
<li>External</li>
</ul></li>
<li>Citations

<ul class="doxyList ">
<li>via bibtex</li>
</ul></li>
<li>Various processing steps for a comment block

<ul class="doxyList ">
<li>comment conversion</li>
<li>comment scanner</li>
<li>markdown processor</li>
<li>doc tokenizer</li>
<li>doc parser</li>
<li>doc visitors</li>
</ul></li>
<li>Diagrams and Images

<ul class="doxyList ">
<li>builtin</li>
<li>via Graphviz dot</li>
<li>via mscgen</li>
<li>PNG generation</li>
</ul></li>
<li>Output formats: <a href="/web-doxygen/docs/api/classes/outputgenerator">OutputGenerator</a>, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>, and <a href="/web-doxygen/docs/api/classes/docvisitor">DocVisitor</a>

<ul class="doxyList ">
<li>Html: <a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor">HtmlDocVisitor</a></li>
<li>Latex: <a href="/web-doxygen/docs/api/classes/latexgenerator">LatexGenerator</a> and <a href="/web-doxygen/docs/api/classes/latexdocvisitor">LatexDocVisitor</a></li>
<li>RTF: <a href="/web-doxygen/docs/api/classes/rtfgenerator">RTFGenerator</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor">RTFDocVisitor</a></li>
<li>Man: <a href="/web-doxygen/docs/api/classes/mangenerator">ManGenerator</a> and <a href="/web-doxygen/docs/api/classes/mandocvisitor">ManDocVisitor</a></li>
<li>XML: <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor">XmlDocVisitor</a></li>
<li>print: debugging via <a href="/web-doxygen/docs/api/classes/printdocvisitor">PrintDocVisitor</a></li>
<li>text: <a href="/web-doxygen/docs/api/classes/textdocvisitor">TextDocVisitor</a> for tooltips</li>
<li>perlmod</li>
</ul></li>
<li>i18n via <a href="/web-doxygen/docs/api/classes/translator">Translator</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp">language.cpp</a></li>
<li>Customizing the layout via <a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a></li>
<li>Parsers

<ul class="doxyList ">
<li>C Preprocessing

<ul class="doxyList ">
<li>const expression evaluation</li>
</ul></li>
<li>C link languages</li>
<li>Python</li>
<li>Fortran</li>
<li>VHDL</li>
<li>Tag files</li>
</ul></li>
<li>Marshaling to/from disk</li>
<li>Portability functions</li>
<li>Utility functions</li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
