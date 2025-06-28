---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/starting
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Getting started




<p>The executable <span class="doxyComputerOutput">doxygen</span> is the main program that parses the sources and generates the documentation. See section <a href="/web-doxygen/docs/pages/doxygen-usage">Doxygen usage</a> for more detailed usage information.</p>

<p>Optionally, the executable <span class="doxyComputerOutput">doxywizard</span> can be used, which is a <a href="/web-doxygen/docs/pages/doxywizard-usage">graphical front-end</a> for editing the configuration file that is used by Doxygen and for running Doxygen in a graphical environment. For macOS Doxywizard will be started by clicking on the Doxygen application icon.</p>

<p>The following figure shows the relation between the tools and the flow of information between them (it looks complex but that's only because it tries to be complete):</p>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/infoflow.png"></img>
  <figcaption>Doxygen information flow</figcaption>
</figure></p>

## Step 0: Check if Doxygen supports your programming/hardware description language {#step0}


<p>First, assure that your programming/hardware description language has a reasonable chance of being recognized by Doxygen. These programming languages are supported by default: C, C++, Lex, C#, Objective-C, IDL, Java, PHP, Python, Fortran and D. Doxygen also supports the hardware description language VHDL by default. It is possible to configure certain file type extensions to use certain parsers: see the <a href="/web-doxygen/docs/pages/config/#cfg_extension_mapping">Configuration/ExtensionMappings</a> for details. Also, completely different languages can be supported by using preprocessor programs: see the <a href="https://www.doxygen.org/helpers.html">Helpers page</a> for details.</p>

## Step 1: Creating a configuration file {#step1}


<p>Doxygen uses a configuration file to determine all of its settings. Each project should get its own configuration file. A project can consist of a single source file, but can also be an entire source tree that is recursively scanned.</p>

<p>To simplify the creation of a configuration file, Doxygen can create a template configuration file for you. To do this call <span class="doxyComputerOutput">doxygen</span> from the command line with the <span class="doxyComputerOutput">-g</span> option:</p>


<pre><code>doxygen -g &lt;config-file&gt;
</code></pre>


<p>where &lt;config-file&gt; is the name of the configuration file. If you omit the file name, a file named <span class="doxyComputerOutput">Doxyfile</span> will be created. If a file with the name &lt;config-file&gt; already exists, Doxygen will rename it to &lt;config-file&gt;.bak before generating the configuration template. If you use <span class="doxyComputerOutput">-</span> (i.e. the minus sign) as the file name then Doxygen will try to read the configuration file from standard input (<span class="doxyComputerOutput">stdin</span>), which can be useful for scripting.</p>

<p>The configuration file has a format that is similar to that of a (simple) Makefile. It consists of a number of assignments (tags) of the form:</p>

<p><span class="doxyComputerOutput">TAGNAME = VALUE</span> or 
<br/>
 <span class="doxyComputerOutput">TAGNAME = VALUE1 VALUE2 ... </span>
<br/></p>

<p>You can probably leave the values of most tags in a generated template configuration file to their default value. See section <a href="/web-doxygen/docs/pages/config">Configuration</a> for more details about the configuration file.</p>

<p>If you do not wish to edit the configuration file with a text editor, you should have a look at <a href="/web-doxygen/docs/pages/doxywizard-usage">Doxywizard</a>, which is a GUI front-end that can create, read and write Doxygen configuration files, and allows setting configuration options by entering them via dialogs.</p>

<p>For a small project consisting of a few C and/or C++ source and header files, you can leave <a href="/web-doxygen/docs/pages/config/#cfg_input">INPUT</a> tag empty and Doxygen will search for sources in the current directory.</p>

<p>If you have a larger project consisting of a source directory or tree you should assign the root directory or directories to the <a href="/web-doxygen/docs/pages/config/#cfg_input">INPUT</a> tag, and add one or more file patterns to the <a href="/web-doxygen/docs/pages/config/#cfg_file_patterns">FILE_PATTERNS</a> tag (for instance <span class="doxyComputerOutput">*.cpp *.h</span>). Only files that match one of the patterns will be parsed (if the patterns are omitted a list of typical patterns is used for the types of files Doxygen supports). For recursive parsing of a source tree you must set the <a href="/web-doxygen/docs/pages/config/#cfg_recursive">RECURSIVE</a> tag to <span class="doxyComputerOutput">YES</span>. To further fine-tune the list of files that is parsed the <a href="/web-doxygen/docs/pages/config/#cfg_exclude">EXCLUDE</a> and <a href="/web-doxygen/docs/pages/config/#cfg_exclude_patterns">EXCLUDE_PATTERNS</a> tags can be used. To omit all <span class="doxyComputerOutput">test</span> directories from a source tree for instance, one could use:</p>


<pre><code>EXCLUDE_PATTERNS = */test/*
</code></pre>


<p><a id="default_file_extension_mapping"></a>Doxygen looks at the file's extension to determine how to parse a file, using the following table:</p>

<table class="doxyTable">
<tr>
<th align="right">Extension</th>
<th>Language</th>
<th align="right">Extension</th>
<th>Language</th>
<th align="right">Extension</th>
<th>Language</th>
</tr>
<tr>
<td align="right">.dox</td>
<td>C / C++</td>
<td align="right">.HH</td>
<td>C / C++</td>
<td align="right">.py</td>
<td>Python</td>
</tr>
<tr>
<td align="right">.doc</td>
<td>C / C++</td>
<td align="right">.hxx</td>
<td>C / C++</td>
<td align="right">.pyw</td>
<td>Python</td>
</tr>
<tr>
<td align="right">.c</td>
<td>C / C++</td>
<td align="right">.hpp</td>
<td>C / C++</td>
<td align="right">.f</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.cc</td>
<td>C / C++</td>
<td align="right">.h++</td>
<td>C / C++</td>
<td align="right">.for</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.cxx</td>
<td>C / C++</td>
<td align="right">.mm</td>
<td>C / C++</td>
<td align="right">.f90</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.cpp</td>
<td>C / C++</td>
<td align="right">.txt</td>
<td>C / C++</td>
<td align="right">.f95</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.c++</td>
<td>C / C++</td>
<td align="right">.idl</td>
<td>IDL</td>
<td align="right">.f03</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.cppm</td>
<td>C / C++</td>
<td align="right">.ddl</td>
<td>IDL</td>
<td align="right">.f08</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.ccm</td>
<td>C / C++</td>
<td align="right">.odl</td>
<td>IDL</td>
<td align="right">.f18</td>
<td>Fortran</td>
</tr>
<tr>
<td align="right">.cxxm</td>
<td>C / C++</td>
<td align="right">.java</td>
<td>Java</td>
<td align="right">.vhd</td>
<td>VHDL</td>
</tr>
<tr>
<td align="right">.c++m</td>
<td>C / C++</td>
<td align="right">.cs</td>
<td>C#</td>
<td align="right">.vhdl</td>
<td>VHDL</td>
</tr>
<tr>
<td align="right">.ii</td>
<td>C / C++</td>
<td align="right">.d</td>
<td>D</td>
<td align="right">.ucf</td>
<td>VHDL</td>
</tr>
<tr>
<td align="right">.ixx</td>
<td>C / C++</td>
<td align="right">.php</td>
<td>PHP</td>
<td align="right">.qsf</td>
<td>VHDL</td>
</tr>
<tr>
<td align="right">.ipp</td>
<td>C / C++</td>
<td align="right">.php4</td>
<td>PHP</td>
<td align="right">.l</td>
<td>Lex</td>
</tr>
<tr>
<td align="right">.i++</td>
<td>C / C++</td>
<td align="right">.php5</td>
<td>PHP</td>
<td align="right">.md</td>
<td>Markdown</td>
</tr>
<tr>
<td align="right">.inl</td>
<td>C / C++</td>
<td align="right">.inc</td>
<td>PHP</td>
<td align="right">.markdown</td>
<td>Markdown</td>
</tr>
<tr>
<td align="right">.h</td>
<td>C / C++</td>
<td align="right">.phtml</td>
<td>PHP</td>
<td align="right">.ice</td>
<td>Slice</td>
</tr>
<tr>
<td align="right">.H</td>
<td>C / C++</td>
<td align="right">.m</td>
<td>Objective-C</td>
<td align="right">&nbsp;</td>
<td>&nbsp;</td>
</tr>
<tr>
<td align="right">.hh</td>
<td>C / C++</td>
<td align="right">.M</td>
<td>Objective-C</td>
<td align="right">&nbsp;</td>
<td>&nbsp;</td>
</tr>
</table>

<p>Please note that the above list might contain more items than that by default set in the <a href="/web-doxygen/docs/pages/config/#cfg_file_patterns">FILE_PATTERNS</a>.</p>

<p>Any extension that is not parsed can be set by adding it to <a href="/web-doxygen/docs/pages/config/#cfg_file_patterns">FILE_PATTERNS</a> and when the appropriate <a href="/web-doxygen/docs/pages/config/#cfg_extension_mapping">EXTENSION_MAPPING</a> is set.</p>

<p><a id="extract_all"></a>If you start using Doxygen for an existing project (thus without any documentation that Doxygen is aware of), you can still get an idea of what the structure is and how the documented result would look like. To do so, you must set the <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT_ALL</a> tag in the configuration file to <span class="doxyComputerOutput">YES</span>. Then, Doxygen will pretend everything in your sources is documented. Please note that as a consequence warnings about undocumented members will not be generated as long as <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT_ALL</a> is set to <span class="doxyComputerOutput">YES</span>.</p>

<p>To analyze an existing piece of software it is useful to cross-reference a (documented) entity with its definition in the source files. Doxygen will generate such cross-references if you set the <a href="/web-doxygen/docs/pages/config/#cfg_source_browser">SOURCE_BROWSER</a> tag to <span class="doxyComputerOutput">YES</span>. It can also include the sources directly into the documentation by setting <a href="/web-doxygen/docs/pages/config/#cfg_inline_sources">INLINE_SOURCES</a> to <span class="doxyComputerOutput">YES</span> (this can be handy for code reviews for instance).</p>

## Step 2: Running Doxygen {#step2}


<p>To generate the documentation you can now enter:</p>


<pre><code>doxygen &lt;config-file&gt;
</code></pre>


<p>Depending on your settings Doxygen will create <span class="doxyComputerOutput">html</span>, <span class="doxyComputerOutput">rtf</span>, <span class="doxyComputerOutput">latex</span>, <span class="doxyComputerOutput">xml</span>, <span class="doxyComputerOutput">man</span>, and/or docbook directories inside the output directory. As the names suggest these directories contain the generated documentation in HTML, RTF, <code>{\LaTeX}</code>, XML, Unix-Man page, and DocBook format.</p>

<p>The default output directory is the directory in which <span class="doxyComputerOutput">doxygen</span> is started. The root directory to which the output is written can be changed using the <a href="/web-doxygen/docs/pages/config/#cfg_output_directory">OUTPUT_DIRECTORY</a>. The format specific directory within the output directory can be selected using the <a href="/web-doxygen/docs/pages/config/#cfg_html_output">HTML_OUTPUT</a>, <a href="/web-doxygen/docs/pages/config/#cfg_rtf_output">RTF_OUTPUT</a>, <a href="/web-doxygen/docs/pages/config/#cfg_latex_output">LATEX_OUTPUT</a>, <a href="/web-doxygen/docs/pages/config/#cfg_xml_output">XML_OUTPUT</a>, <a href="/web-doxygen/docs/pages/config/#cfg_man_output">MAN_OUTPUT</a>, and <a href="/web-doxygen/docs/pages/config/#cfg_docbook_output">DOCBOOK_OUTPUT</a>. tags of the configuration file. If the output directory does not exist, <span class="doxyComputerOutput">doxygen</span> will try to create it for you (but it will <em>not</em> try to create a whole path recursively, like <span class="doxyComputerOutput">mkdir -p</span> does).</p>

### HTML output {#html_out}


<p>The generated HTML documentation can be viewed by pointing a HTML browser to the <span class="doxyComputerOutput">index.html</span> file in the <span class="doxyComputerOutput">html</span> directory. For the best results a browser that supports cascading style sheets (CSS) should be used (I'm using Mozilla Firefox, Google Chrome, Safari, and sometimes IE8, IE9, and Opera to test the generated output).</p>

<p>Some of the features the HTML section (such as <a href="/web-doxygen/docs/pages/config/#cfg_generate_treeview">GENERATE_TREEVIEW</a> or the search engine) require a browser that supports Dynamic HTML and JavaScript enabled.</p>

### LaTeX output {#latex_out}


<p>The generated <code>{\LaTeX}</code> documentation must first be compiled by a <code>{\LaTeX}</code> compiler (I use a recent teTeX distribution for Linux and macOS and MikTex for Windows). To simplify the process of compiling the generated documentation, <span class="doxyComputerOutput">doxygen</span> writes a <span class="doxyComputerOutput">Makefile</span> into the <span class="doxyComputerOutput">latex</span> directory (on the Windows platform also a <span class="doxyComputerOutput">make.bat</span> batch file is generated).</p>

<p>The contents and targets in the <span class="doxyComputerOutput">Makefile</span> depend on the setting of <a href="/web-doxygen/docs/pages/config/#cfg_use_pdflatex">USE_PDFLATEX</a>. If it is disabled (set to <span class="doxyComputerOutput">NO</span>), then typing <span class="doxyComputerOutput">make</span> in the <span class="doxyComputerOutput">latex</span> directory a <span class="doxyComputerOutput">dvi</span> file called <span class="doxyComputerOutput">refman.dvi</span> will be generated. This file can then be viewed using <span class="doxyComputerOutput">xdvi</span> or converted into a PostScript file <span class="doxyComputerOutput">refman.ps</span> by typing <span class="doxyComputerOutput">make ps</span> (this requires <span class="doxyComputerOutput">dvips</span>).</p>

<p>To put 2 pages on one physical page use <span class="doxyComputerOutput">make ps_2on1</span> instead. The resulting PostScript file can be send to a PostScript printer. If you do not have a PostScript printer, you can try to use ghostscript to convert PostScript into something your printer understands.</p>

<p>Conversion to PDF is also possible if you have installed the ghostscript interpreter; just type <span class="doxyComputerOutput">make pdf</span> (or <span class="doxyComputerOutput">make pdf_2on1</span>).</p>

<p>To get the best results for PDF output you should set the <a href="/web-doxygen/docs/pages/config/#cfg_pdf_hyperlinks">PDF_HYPERLINKS</a> and <a href="/web-doxygen/docs/pages/config/#cfg_use_pdflatex">USE_PDFLATEX</a> tags to <span class="doxyComputerOutput">YES</span>. In this case the <span class="doxyComputerOutput">Makefile</span> will only contain a target to build <span class="doxyComputerOutput">refman.pdf</span> directly.</p>

### RTF output {#rtf_out}


<p>Doxygen combines the RTF output to a single file called refman.rtf. This file is optimized for importing into the Microsoft Word. Certain information is encoded using so called fields. To show the actual value you need to select all (Edit - select all) and then toggle fields (right click and select the option from the drop down menu).</p>

### XML output {#xml_out}


<p>The XML output consists of a structured "dump" of the information gathered by Doxygen. Each compound (class/namespace/file/...) has its own XML file and there is also an index file called <span class="doxyComputerOutput">index.xml</span>.</p>

<p>A file called <span class="doxyComputerOutput">combine.xslt</span> XSLT script is also generated and can be used to combine all XML files into a single file.</p>

<p>Doxygen also generates two XML schema files <span class="doxyComputerOutput">index.xsd</span> (for the index file) and <span class="doxyComputerOutput">compound.xsd</span> (for the compound files). This schema file describes the possible elements, their attributes and how they are structured, i.e. it the describes the grammar of the XML files and can be used for validation or to steer XSLT scripts.</p>

<p>In the <span class="doxyComputerOutput">addon/doxmlparser</span> directory you can find a parser library for reading the XML output produced by Doxygen in an incremental way (see <span class="doxyComputerOutput">addon/doxmlparser/doxmparser/index.py</span> and <span class="doxyComputerOutput">addon/doxmlparser/doxmlparser/compound.py</span> for the interface of the library)</p>

### Man page output {#man_out}


<p>The generated man pages can be viewed using the <span class="doxyComputerOutput">man</span> program. You do need to make sure the man directory is in the man path (see the <span class="doxyComputerOutput">MANPATH</span> environment variable). Note that there are some limitations to the capabilities of the man page format, so some information (like class diagrams, cross references and formulas) will be lost.</p>

### DocBook output {#docbook_out}


<p>Doxygen can also generate output in the <a href="https://docbook.org/">DocBook</a> format. How to process the DocBook output is beyond the scope of this manual.</p>

## Step 3: Documenting the sources {#step3}


<p>Although documenting the sources is presented as step 3, in a new project this should of course be step 1. Here I assume you already have some code and you want Doxygen to generate a nice document describing the API and maybe the internals and some related design documentation as well.</p>

<p>If the <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT_ALL</a> option is set to <span class="doxyComputerOutput">NO</span> in the configuration file (the default), then Doxygen will only generate documentation for <em>documented</em> entities. So how do you document these? For members, classes and namespaces there are basically two options:</p>

<ol class="doxyList" type="1">
<li>Place a <em>special</em> documentation block in front of the declaration or definition of the member, class or namespace. For file, class and namespace members it is also allowed to place the documentation directly after the member.

See section <a href="/web-doxygen/docs/pages/docblocks/#specialblock">Special comment blocks</a> to learn more about special documentation blocks.</li>
<li>Place a special documentation block somewhere else (another file or another location) <em>and</em> put a <em>structural command</em> in the documentation block. A structural command links a documentation block to a certain entity that can be documented (e.g. a member, class, namespace or file).

See section <a href="/web-doxygen/docs/pages/docblocks/#structuralcommands">Documentation at other places</a> to learn more about structural commands.</li>
</ol>

<p>The advantage of the first option is that you do not have to repeat the name of the entity.</p>

<p>Files can only be documented using the second option, since there is no way to put a documentation block before a file. Of course, file members (functions, variables, typedefs, defines) do not need an explicit structural command; just putting a special documentation block in front or behind them will work fine.</p>

<p>The text inside a special documentation block is parsed before it is written to the HTML and/or <code>{\LaTeX}</code> output files.</p>

<p>During parsing the following steps take place:</p>

<ul class="doxyList ">
<li>Markdown formatting is replaced by corresponding HTML or special commands.</li>
<li>The special commands inside the documentation are executed. See section <a href="/web-doxygen/docs/pages/commands">Special Commands</a> for an overview of all commands.</li>
<li>If a line starts with some whitespace followed by one or more asterisks (<span class="doxyComputerOutput">*</span>) and then optionally more whitespace, then all whitespace and asterisks are removed.</li>
<li>All resulting blank lines are treated as a paragraph separators. This saves you from placing new-paragraph commands yourself in order to make the generated documentation readable.</li>
<li>Links are created for words corresponding to documented classes (unless the word is preceded by a %; then the word will not be linked and the % sign is removed).</li>
<li>Links to members are created when certain patterns are found in the text. See section <a href="/web-doxygen/docs/pages/autolink">Automatic link generation</a> for more information on how the automatic link generation works.</li>
<li>HTML tags that are in the documentation are interpreted and converted to <code>{\LaTeX}</code> equivalents for the <code>{\LaTeX}</code> output. See section <a href="/web-doxygen/docs/pages/htmlcmds">HTML Commands</a> for an overview of all supported HTML tags.</li>
</ul>
 
Go to the <a href="/docs/pages/docblocks/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
