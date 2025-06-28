---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/arch
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Doxygen's Internals




### Doxygen's internals

<p><b>Note that this section is still under construction!</b></p>

<p>The following picture shows how source files are processed by Doxygen.</p>

<p><figure>
  <img src="/web-doxygen/img/doxygen-manual/archoverview.svg"></img>
  <figcaption>Data flow overview</figcaption>
</figure></p>

<p>The following sections explain the steps above in more detail.</p>

### Config parser

<p>The configuration file that controls the settings of a project is parsed and the settings are stored in the singleton class <span class="doxyComputerOutput">Config</span> in <span class="doxyComputerOutput">src/config.h</span>. The parser itself is written using <span class="doxyComputerOutput">flex</span> and can be found in <span class="doxyComputerOutput">src/config.l</span>. This parser is also used directly by Doxywizard, so it is put in a separate library.</p>

<p>Each configuration option has one of 5 possible types: <span class="doxyComputerOutput">String</span>, <span class="doxyComputerOutput">List</span>, <span class="doxyComputerOutput">Enum</span>, <span class="doxyComputerOutput">Int</span>, or <span class="doxyComputerOutput">Bool</span>. The values of these options are available through the global functions <span class="doxyComputerOutput">Config_getXXX()</span>, where <span class="doxyComputerOutput">XXX</span> is the type of the option. The argument of these functions is a string naming the option as it appears in the configuration file. For instance: <span class="doxyComputerOutput">Config_getBool(GENERATE_TESTLIST)</span> returns a reference to a boolean value that is <span class="doxyComputerOutput">TRUE</span> if the test list was enabled in the configuration file.</p>

<p>The function <span class="doxyComputerOutput">readConfiguration()</span> in <span class="doxyComputerOutput">src/doxygen.cpp</span> reads the command line options and then calls the configuration parser.</p>

### C Preprocessor

<p>The input files mentioned in the configuration file are (by default) fed to the C Preprocessor (after being piped through a user defined filter if available).</p>

<p>The way the preprocessor works differs somewhat from a standard C Preprocessor. By default it does not do macro expansion, although it can be configured to expand all macros. Typical usage is to only expand a user specified set of macros. This is to allow macro names to appear in the type of function parameters for instance.</p>

<p>Another difference is that the preprocessor parses, but not actually includes code when it encounters a <span class="doxyComputerOutput">#include</span> (with the exception of <span class="doxyComputerOutput">#include</span> found inside { ... } blocks). The reasons behind this deviation from the standard is to prevent feeding multiple definitions of the same functions/classes to Doxygen's parser. If all source files would include a common header file for instance, the class and type definitions (and their documentation) would be present in each translation unit.</p>

<p>The preprocessor is written using <span class="doxyComputerOutput">flex</span> and can be found in <span class="doxyComputerOutput">src/pre.l</span>. For condition blocks (<span class="doxyComputerOutput">#if</span>) evaluation of constant expressions is needed. For this a <span class="doxyComputerOutput">yacc</span> based parser is used, which can be found in <span class="doxyComputerOutput">src/constexp.y</span> and <span class="doxyComputerOutput">src/constexp.l</span>.</p>

<p>The preprocessor is invoked for each file using the <span class="doxyComputerOutput">preprocessFile()</span> function declared in <span class="doxyComputerOutput">src/pre.h</span>, and will append the preprocessed result to a character buffer. The format of the character buffer is</p>


<pre><code>0x06 file name 1
0x06 preprocessed contents of file 1
...
0x06 file name n
0x06 preprocessed contents of file n
</code></pre>


### Language parser

<p>The preprocessed input buffer is fed to the language parser, which is implemented as a big state machine using <span class="doxyComputerOutput">flex</span>. It can be found in the file <span class="doxyComputerOutput">src/scanner.l</span>. There is one parser for all languages (C/C++/Java/IDL). The state variables <span class="doxyComputerOutput">insideIDL</span> and <span class="doxyComputerOutput">insideJava</span> are uses at some places for language specific choices.</p>

<p>The task of the parser is to convert the input buffer into a tree of entries (basically an abstract syntax tree). An entry is defined in <span class="doxyComputerOutput">src/entry.h</span> and is a blob of loosely structured information. The most important field is <span class="doxyComputerOutput">section</span> which specifies the kind of information contained in the entry.</p>

<p>Possible improvements for future versions:</p>

<ul class="doxyList ">
<li>Use one scanner/parser per language instead of one big scanner.</li>
<li>Move the first pass parsing of documentation blocks to a separate module.</li>
<li>Parse defines (these are currently gathered by the preprocessor, and ignored by the language parser).</li>
</ul>

### Data organizer

<p>This step consists of many smaller steps, that build dictionaries of the extracted classes, files, namespaces, variables, functions, packages, pages, and groups. Besides building dictionaries, during this step relations (such as inheritance relations), between the extracted entities are computed.</p>

<p>Each step has a function defined in <span class="doxyComputerOutput">src/doxygen.cpp</span>, which operates on the tree of entries, built during language parsing. Look at the "Gathering information" part of <span class="doxyComputerOutput">parseInput()</span> for details.</p>

<p>The result of this step is a number of dictionaries, which can be found in the Doxygen "namespace" defined in <span class="doxyComputerOutput">src/doxygen.h</span>. Most elements of these dictionaries are derived from the class <span class="doxyComputerOutput">Definition</span>; The class <span class="doxyComputerOutput">MemberDef</span>, for instance, holds all information for a member. An instance of such a class can be part of a file ( class <span class="doxyComputerOutput">FileDef</span> ), a class ( class <span class="doxyComputerOutput">ClassDef</span> ), a namespace ( class <span class="doxyComputerOutput">NamespaceDef</span> ), a group ( class <span class="doxyComputerOutput">GroupDef</span> ), or a Java package ( class <span class="doxyComputerOutput">PackageDef</span> ).</p>

### Tag file parser

<p>If tag files are specified in the configuration file, these are parsed by a SAX based XML parser, which can be found in <span class="doxyComputerOutput">src/tagreader.cpp</span>. The result of parsing a tag file is the insertion of <span class="doxyComputerOutput">Entry</span> objects in the entry tree. The field <span class="doxyComputerOutput">Entry::tagInfo</span> is used to mark the entry as external, and holds information about the tag file.</p>

### Documentation parser

<p>Special comment blocks are stored as strings in the entities that they document. There is a string for the brief description and a string for the detailed description. The documentation parser reads these strings and executes the commands it finds in it (this is the second pass in parsing the documentation). It writes the result directly to the output generators.</p>

<p>The parser is written in C++ and can be found in <span class="doxyComputerOutput">src/docparser.cpp</span>. The tokens that are eaten by the parser come from <span class="doxyComputerOutput">src/doctokenizer.l</span>. Code fragments found in the comment blocks are passed on to the source parser.</p>

<p>The main entry point for the documentation parser is <span class="doxyComputerOutput">validatingParseDoc()</span> declared in <span class="doxyComputerOutput">src/docparser.h</span>. For simple texts with special commands <span class="doxyComputerOutput">validatingParseText()</span> is used.</p>

### Source parser

<p>If source browsing is enabled or if code fragments are encountered in the documentation, the source parser is invoked.</p>

<p>The code parser tries to cross-reference to source code it parses with documented entities. It also does syntax highlighting of the sources. The output is directly written to the output generators.</p>

<p>The main entry point for the code parser is <span class="doxyComputerOutput">parseCode()</span> declared in <span class="doxyComputerOutput">src/code.h</span>.</p>

### Output generators

<p>After data is gathered and cross-referenced, Doxygen generates output in various formats. For this it uses the methods provided by the abstract class <span class="doxyComputerOutput">OutputGenerator</span>. In order to generate output for multiple formats at once, the methods of <span class="doxyComputerOutput">OutputList</span> are called instead. This class maintains a list of concrete output generators, where each method called is delegated to all generators in the list.</p>

<p>To allow small deviations in what is written to the output for each concrete output generator, it is possible to temporarily disable certain generators. The OutputList class contains various <span class="doxyComputerOutput">disable()</span> and <span class="doxyComputerOutput">enable()</span> methods for this. The methods <span class="doxyComputerOutput">OutputList::pushGeneratorState()</span> and <span class="doxyComputerOutput">OutputList::popGeneratorState()</span> are used to temporarily save the set of enabled/disabled output generators on a stack.</p>

<p>The XML is generated directly from the gathered data structures. In the future XML will be used as an intermediate language (IL). The output generators will then use this IL as a starting point to generate the specific output formats. The advantage of having an IL is that various independently developed tools written in various languages, could extract information from the XML output. Possible tools could be:</p>

<ul class="doxyList ">
<li>an interactive source browser</li>
<li>a class diagram generator</li>
<li>computing code metrics.</li>
</ul>

### Debugging

<p>Since Doxygen uses a lot of <span class="doxyComputerOutput">flex</span> code it is important to understand how <span class="doxyComputerOutput">flex</span> works (for this one should read the <span class="doxyComputerOutput">man</span> page) and to understand what it is doing when <span class="doxyComputerOutput">flex</span> is parsing some input. Fortunately, when <span class="doxyComputerOutput">flex</span> is used with the <span class="doxyComputerOutput">-d</span> option it outputs what rules matched. This makes it quite easy to follow what is going on for a particular input fragment.</p>

<p>To make it easier to toggle debug information for a given <span class="doxyComputerOutput">flex</span> file I wrote the following <span class="doxyComputerOutput">perl</span> script, which automatically adds or removes <span class="doxyComputerOutput">-d</span> from the correct line in the <span class="doxyComputerOutput">Makefile:</span></p>


<pre><code>#!/usr/bin/perl

$file = shift @ARGV;
print "Toggle debugging mode for $file\n";
if (!-e "../src/${file}.l")
{
  print STDERR "Error: file ../src/${file}.l does not exist!\n";
  exit 1;
}
system("touch ../src/${file}.l");
unless (rename "src/CMakeFiles/doxymain.dir/build.make","src/CMakeFiles/doxymain.dir/build.make.old") {
  print STDERR "Error: cannot rename src/CMakeFiles/doxymain.dir/build.make!\n";
  exit 1;
}
if (open(F,"&lt;src/CMakeFiles/doxymain.dir/build.make.old")) {
  unless (open(G,"&gt;src/CMakeFiles/doxymain.dir/build.make")) {
    print STDERR "Error: opening file build.make for writing\n";
    exit 1;
  }
  print "Processing build.make...\n";
  while (&lt;F&gt;) {
    if ( s/flex \$\(LEX_FLAGS\) -d(.*) ${file}.l/flex \$(LEX_FLAGS)$1 ${file}.l/ ) {
      print "Disabling debug info for $file\n";
    }
    elsif ( s/flex \$\(LEX_FLAGS\)(.*) ${file}.l$/flex \$(LEX_FLAGS) -d$1 ${file}.l/ ) {
      print "Enabling debug info for $file.l\n";
    }
    print G "$_";
  }
  close F;
  unlink "src/CMakeFiles/doxymain.dir/build.make.old";
}
else {
  print STDERR "Warning file src/CMakeFiles/doxymain.dir/build.make does not exist!\n";
}

# touch the file
$now = time;
utime $now, $now, $file;
</code></pre>


<p>Another way to get rules matching / debugging information from the <span class="doxyComputerOutput">flex</span> code is setting <span class="doxyComputerOutput">LEX_FLAGS</span> with <span class="doxyComputerOutput">make</span> (<span class="doxyComputerOutput">make LEX_FLAGS=-d</span>).</p>

<p>By default a debug version of Doxygen (i.e. an executable created with the <span class="doxyComputerOutput">CMake</span> setting <span class="doxyComputerOutput">-DCMAKE_BUILD_TYPE=Debug</span>) will automatically have the <span class="doxyComputerOutput">flex</span> debugging information for all <span class="doxyComputerOutput">flex codefile</span>s.</p>

<p>Note that by running Doxygen with <span class="doxyComputerOutput">-d lex</span> you get information about which <span class="doxyComputerOutput">flex codefile</span> is used. To see the information of the flex parser, which is compiled with the flex debug option, you have to specify <span class="doxyComputerOutput">-d lex:&lt;flex codefile&gt;</span> when running Doxygen.</p>

<p>Note that the information with respect to the lex parsing goes to <span class="doxyComputerOutput">stderr</span> and that the other debug output goes by default to <span class="doxyComputerOutput">stdout</span> unless one uses <span class="doxyComputerOutput">-d stderr</span>.</p>

### Testing

<p>Doxygen has a small set of tests available to test, some, code integrity. The tests can be run by means of the command <span class="doxyComputerOutput">make tests</span>. When only one or a few tests are required one can set the variable <span class="doxyComputerOutput">TEST_FLAGS</span> when running the test e.g. <span class="doxyComputerOutput">make TEST_FLAGS="--id 5" tests</span> or for multiple tests <span class="doxyComputerOutput">make TEST_FLAGS="--id 5 --id 7" tests</span>. For a full set of possibilities give the command <span class="doxyComputerOutput">make TEST_FLAGS="--help" tests</span>. It is also possible to specify the <span class="doxyComputerOutput">TEST_FLAGS</span> as an environment variable (works also for testing through Visual Studio projects), e.g. <span class="doxyComputerOutput">setenv TEST_FLAGS "--id 5 --id 7"</span> and <span class="doxyComputerOutput">make tests</span>.</p>

### Doxyfile differences

<p>In case one has to communicate through e.g. a forum the configuration settings that are different from the standard Doxygen configuration file settings one can run the Doxygen command: with the <span class="doxyComputerOutput">-x</span> option and the name of the configuration file (default is <span class="doxyComputerOutput">Doxyfile</span>). The output will be a list of the not default settings (in <span class="doxyComputerOutput">Doxyfile</span> format). Alternatively also <span class="doxyComputerOutput">-x_noenv</span> is possible which is identical to the <span class="doxyComputerOutput">-x</span> option but without replacing the environment variables and the <span class="doxyComputerOutput">CMake</span> type replacement variables.</p>
 
Return to the <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
