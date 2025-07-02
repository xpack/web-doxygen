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

<b>Note that this section is still under construction!</b>

The following picture shows how source files are processed by Doxygen.

<figure>
  <img src="/web-doxygen/img/doxygen-manual/archoverview.svg"></img>
  <figcaption>Data flow overview</figcaption>
</figure>

The following sections explain the steps above in more detail.

### Config parser

The configuration file that controls the settings of a project is parsed and the settings are stored in the singleton class <code>Config</code> in <code>src/config.h</code>. The parser itself is written using <code>flex</code> and can be found in <code>src/config.l</code>. This parser is also used directly by Doxywizard, so it is put in a separate library.

Each configuration option has one of 5 possible types: <code>String</code>, <code>List</code>, <code>Enum</code>, <code>Int</code>, or <code>Bool</code>. The values of these options are available through the global functions <code>Config\_getXXX()</code>, where <code>XXX</code> is the type of the option. The argument of these functions is a string naming the option as it appears in the configuration file. For instance: <code>Config\_getBool(GENERATE\_TESTLIST)</code> returns a reference to a boolean value that is <code>TRUE</code> if the test list was enabled in the configuration file.

The function <code>readConfiguration()</code> in <code>src/doxygen.cpp</code> reads the command line options and then calls the configuration parser.

### C Preprocessor

The input files mentioned in the configuration file are (by default) fed to the C Preprocessor (after being piped through a user defined filter if available).

The way the preprocessor works differs somewhat from a standard C Preprocessor. By default it does not do macro expansion, although it can be configured to expand all macros. Typical usage is to only expand a user specified set of macros. This is to allow macro names to appear in the type of function parameters for instance.

Another difference is that the preprocessor parses, but not actually includes code when it encounters a <code>#include</code> (with the exception of <code>#include</code> found inside { ... } blocks). The reasons behind this deviation from the standard is to prevent feeding multiple definitions of the same functions/classes to Doxygen's parser. If all source files would include a common header file for instance, the class and type definitions (and their documentation) would be present in each translation unit.

The preprocessor is written using <code>flex</code> and can be found in <code>src/pre.l</code>. For condition blocks (<code>#if</code>) evaluation of constant expressions is needed. For this a <code>yacc</code> based parser is used, which can be found in <code>src/constexp.y</code> and <code>src/constexp.l</code>.

The preprocessor is invoked for each file using the <code>preprocessFile()</code> function declared in <code>src/pre.h</code>, and will append the preprocessed result to a character buffer. The format of the character buffer is


<pre><code>0x06 file name 1
0x06 preprocessed contents of file 1
...
0x06 file name n
0x06 preprocessed contents of file n
</code></pre>


### Language parser

The preprocessed input buffer is fed to the language parser, which is implemented as a big state machine using <code>flex</code>. It can be found in the file <code>src/scanner.l</code>. There is one parser for all languages (C/C++/Java/IDL). The state variables <code>insideIDL</code> and <code>insideJava</code> are uses at some places for language specific choices.

The task of the parser is to convert the input buffer into a tree of entries (basically an abstract syntax tree). An entry is defined in <code>src/entry.h</code> and is a blob of loosely structured information. The most important field is <code>section</code> which specifies the kind of information contained in the entry.

Possible improvements for future versions:

<ul class="doxyList ">
<li>Use one scanner/parser per language instead of one big scanner.</li>
<li>Move the first pass parsing of documentation blocks to a separate module.</li>
<li>Parse defines (these are currently gathered by the preprocessor, and ignored by the language parser).</li>
</ul>

### Data organizer

This step consists of many smaller steps, that build dictionaries of the extracted classes, files, namespaces, variables, functions, packages, pages, and groups. Besides building dictionaries, during this step relations (such as inheritance relations), between the extracted entities are computed.

Each step has a function defined in <code>src/doxygen.cpp</code>, which operates on the tree of entries, built during language parsing. Look at the "Gathering information" part of <code>parseInput()</code> for details.

The result of this step is a number of dictionaries, which can be found in the Doxygen "namespace" defined in <code>src/doxygen.h</code>. Most elements of these dictionaries are derived from the class <code>Definition</code>; The class <code>MemberDef</code>, for instance, holds all information for a member. An instance of such a class can be part of a file ( class <code>FileDef</code> ), a class ( class <code>ClassDef</code> ), a namespace ( class <code>NamespaceDef</code> ), a group ( class <code>GroupDef</code> ), or a Java package ( class <code>PackageDef</code> ).

### Tag file parser

If tag files are specified in the configuration file, these are parsed by a SAX based XML parser, which can be found in <code>src/tagreader.cpp</code>. The result of parsing a tag file is the insertion of <code>Entry</code> objects in the entry tree. The field <code>Entry::tagInfo</code> is used to mark the entry as external, and holds information about the tag file.

### Documentation parser

Special comment blocks are stored as strings in the entities that they document. There is a string for the brief description and a string for the detailed description. The documentation parser reads these strings and executes the commands it finds in it (this is the second pass in parsing the documentation). It writes the result directly to the output generators.

The parser is written in C++ and can be found in <code>src/docparser.cpp</code>. The tokens that are eaten by the parser come from <code>src/doctokenizer.l</code>. Code fragments found in the comment blocks are passed on to the source parser.

The main entry point for the documentation parser is <code>validatingParseDoc()</code> declared in <code>src/docparser.h</code>. For simple texts with special commands <code>validatingParseText()</code> is used.

### Source parser

If source browsing is enabled or if code fragments are encountered in the documentation, the source parser is invoked.

The code parser tries to cross-reference to source code it parses with documented entities. It also does syntax highlighting of the sources. The output is directly written to the output generators.

The main entry point for the code parser is <code>parseCode()</code> declared in <code>src/code.h</code>.

### Output generators

After data is gathered and cross-referenced, Doxygen generates output in various formats. For this it uses the methods provided by the abstract class <code>OutputGenerator</code>. In order to generate output for multiple formats at once, the methods of <code>OutputList</code> are called instead. This class maintains a list of concrete output generators, where each method called is delegated to all generators in the list.

To allow small deviations in what is written to the output for each concrete output generator, it is possible to temporarily disable certain generators. The OutputList class contains various <code>disable()</code> and <code>enable()</code> methods for this. The methods <code>OutputList::pushGeneratorState()</code> and <code>OutputList::popGeneratorState()</code> are used to temporarily save the set of enabled/disabled output generators on a stack.

The XML is generated directly from the gathered data structures. In the future XML will be used as an intermediate language (IL). The output generators will then use this IL as a starting point to generate the specific output formats. The advantage of having an IL is that various independently developed tools written in various languages, could extract information from the XML output. Possible tools could be:

<ul class="doxyList ">
<li>an interactive source browser</li>
<li>a class diagram generator</li>
<li>computing code metrics.</li>
</ul>

### Debugging

Since Doxygen uses a lot of <code>flex</code> code it is important to understand how <code>flex</code> works (for this one should read the <code>man</code> page) and to understand what it is doing when <code>flex</code> is parsing some input. Fortunately, when <code>flex</code> is used with the <code>-d</code> option it outputs what rules matched. This makes it quite easy to follow what is going on for a particular input fragment.

To make it easier to toggle debug information for a given <code>flex</code> file I wrote the following <code>perl</code> script, which automatically adds or removes <code>-d</code> from the correct line in the <code>Makefile:</code>


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


Another way to get rules matching / debugging information from the <code>flex</code> code is setting <code>LEX\_FLAGS</code> with <code>make</code> (<code>make LEX\_FLAGS=-d</code>).

By default a debug version of Doxygen (i.e. an executable created with the <code>CMake</code> setting <code>-DCMAKE\_BUILD\_TYPE=Debug</code>) will automatically have the <code>flex</code> debugging information for all <code>flex codefile</code>s.

Note that by running Doxygen with <code>-d lex</code> you get information about which <code>flex codefile</code> is used. To see the information of the flex parser, which is compiled with the flex debug option, you have to specify <code>-d lex:&lt;flex codefile&gt;</code> when running Doxygen.

Note that the information with respect to the lex parsing goes to <code>stderr</code> and that the other debug output goes by default to <code>stdout</code> unless one uses <code>-d stderr</code>.

### Testing

Doxygen has a small set of tests available to test, some, code integrity. The tests can be run by means of the command <code>make tests</code>. When only one or a few tests are required one can set the variable <code>TEST\_FLAGS</code> when running the test e.g. <code>make TEST\_FLAGS="--id 5" tests</code> or for multiple tests <code>make TEST\_FLAGS="--id 5 --id 7" tests</code>. For a full set of possibilities give the command <code>make TEST\_FLAGS="--help" tests</code>. It is also possible to specify the <code>TEST\_FLAGS</code> as an environment variable (works also for testing through Visual Studio projects), e.g. <code>setenv TEST\_FLAGS "--id 5 --id 7"</code> and <code>make tests</code>.

### Doxyfile differences

In case one has to communicate through e.g. a forum the configuration settings that are different from the standard Doxygen configuration file settings one can run the Doxygen command: with the <code>-x</code> option and the name of the configuration file (default is <code>Doxyfile</code>). The output will be a list of the not default settings (in <code>Doxyfile</code> format). Alternatively also <code>-x\_noenv</code> is possible which is identical to the <code>-x</code> option but without replacing the environment variables and the <code>CMake</code> type replacement variables.
 
Return to the <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
