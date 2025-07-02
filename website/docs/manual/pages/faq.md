---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/faq
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Frequently Asked Questions




## How to get information on the index page in HTML? {#faq_index}


You should use the <a href="/web-doxygen/docs/pages/commands/#cmdmainpage">\\mainpage</a> command inside a comment block like this:


<pre><code>/*! \mainpage My Personal Index Page
 *
 * \section intro_sec Introduction
 *
 * This is the introduction.
 *
 * \section install_sec Installation
 *
 * \subsection step1 Step 1: Opening the box
 *
 * etc...
 */
</code></pre>


## Help, some/all of the members of my class / file / namespace are not documented? {#fac_al}


Check the following:

<ol class="doxyList" type="1">
<li>Is your class / file / namespace documented? If not, it will not be extracted from the sources unless <a href="/web-doxygen/docs/pages/config/#cfg_extract_all">EXTRACT_ALL</a> is set to <span class="doxyComputerOutput">YES</span> in the configuration file.</li>
<li>Are the members private? If so, you must set <a href="/web-doxygen/docs/pages/config/#cfg_extract_private">EXTRACT_PRIVATE</a> to <span class="doxyComputerOutput">YES</span> to make them appear in the documentation.</li>
<li>Is there a function macro in your class that does not end with a semicolon (e.g. MY_MACRO())? If so then you have to instruct Doxygen's preprocessor to remove it.

This typically boils down to the following settings in the configuration file:

<pre><code>ENABLE_PREPROCESSING   = YES
MACRO_EXPANSION        = YES
EXPAND_ONLY_PREDEF     = YES
PREDEFINED             = MY_MACRO()=
</code></pre>

Please read the <a href="/web-doxygen/docs/pages/preprocessing">preprocessing</a> section of the manual for more information.</li>
</ol>

## When I set EXTRACT\_ALL to NO none of my functions are shown in the documentation {#faq_extract_all}


In order for global functions, variables, enums, typedefs, and defines to be documented you should document the file in which these commands are located using a comment block containing a <a href="/web-doxygen/docs/pages/commands/#cmdfile">\\file</a> (or <a href="/web-doxygen/docs/pages/commands/#cmdfile">@file</a>) command.

Alternatively, you can put all members in a group (or topic) using the <a href="/web-doxygen/docs/pages/commands/#cmdingroup">\\ingroup</a> command and then document the group using a comment block containing the <a href="/web-doxygen/docs/pages/commands/#cmddefgroup">\\defgroup</a> command.

For member functions or functions that are part of a namespace you should document either the class or namespace.

## My file with a custom extension is not parsed (properly) (anymore) {#faq_ext_mapping}


Doxygen only parses files that are specified as input (via the <a href="/web-doxygen/docs/pages/config/#cfg_input">INPUT</a> tag) and that match a specified extension (mentioned in <a href="/web-doxygen/docs/pages/config/#cfg_file_patterns">FILE\_PATTERNS</a>) The list of files is then reduced by excluding files listed as <a href="/web-doxygen/docs/pages/config/#cfg_exclude">EXCLUDE</a> or files that match the patterns set by <a href="/web-doxygen/docs/pages/config/#cfg_exclude_patterns">EXCLUDE\_PATTERNS</a>.

In the past Doxygen parsed all files with an unknown extension as C files which could lead to undesired results. Since version 1.8.8, Doxygen requires that you specify a mapping that tells for a certain file extension, which parser to use. This mapping is specified using the <a href="/web-doxygen/docs/pages/config/#cfg_extension_mapping">EXTENSION\_MAPPING</a> tag. If no mapping is specified the file's contents will be ignored.

## How can I make Doxygen ignore some code fragment? {#faq_code}


The new and easiest way is to add one comment block with a <a href="/web-doxygen/docs/pages/commands/#cmdcond">\\cond</a> command at the start and one comment block with a <a href="/web-doxygen/docs/pages/commands/#cmdendcond">\\endcond</a> command at the end of the piece of code that should be ignored. This should be within the same file of course.

But you can also use Doxygen's preprocessor for this: If you put


<pre><code>#ifndef DOXYGEN_SHOULD_SKIP_THIS

 /* code that must be skipped by Doxygen */

#endif /* DOXYGEN_SHOULD_SKIP_THIS */
</code></pre>


around the blocks that should be hidden and put:


<pre><code>  PREDEFINED = DOXYGEN_SHOULD_SKIP_THIS
</code></pre>


in the configuration file then all blocks should be skipped by Doxygen as long as <a href="/web-doxygen/docs/pages/config/#cfg_enable_preprocessing">ENABLE\_PREPROCESSING</a> is set to <span class="doxyComputerOutput">YES</span>.

## How can I change what is after the #include in the class documentation? {#faq_code_inc}


In most cases you can use <a href="/web-doxygen/docs/pages/config/#cfg_strip_from_inc_path">STRIP\_FROM\_INC\_PATH</a> to strip a user defined part of a path.

You can also document your class as follows


<pre><code>/*! \class MyClassName include.h path/include.h
 *
 *  Docs for MyClassName
 */
</code></pre>


To make Doxygen put 
<br/>

<br/>
 <span class="doxyComputerOutput"> #include &lt;path/include.h&gt; </span>

in the documentation of the class MyClassName regardless of the name of the actual header file in which the definition of MyClassName is contained.

If you want Doxygen to show that the include file should be included using quotes instead of angle brackets you should type:


<pre><code>/*! \class MyClassName myhdr.h "path/myhdr.h"
 *
 *  Docs for MyClassName
 */
</code></pre>


## How can I use tag files in combination with compressed HTML? {#faq_chm}


If you want to refer from one compressed HTML file <span class="doxyComputerOutput">a.chm</span> to another compressed HTML file called <span class="doxyComputerOutput">b.chm</span>, the link in <span class="doxyComputerOutput">a.chm</span> must have the following format:


<pre><code>&lt;a href="mk:@MSITStore:b.chm::/file.html"&gt;
</code></pre>


Unfortunately this only works if both compressed HTML files are in the same directory.

As a result you must rename the generated <span class="doxyComputerOutput">index.chm</span> files for all projects into something unique and put all <span class="doxyComputerOutput">.chm</span> files in one directory.

Suppose you have a project <em>a</em> referring to a project <em>b</em> using tag file <span class="doxyComputerOutput">b.tag</span>, then you could rename the <span class="doxyComputerOutput">index.chm</span> for project <em>a</em> into <span class="doxyComputerOutput">a.chm</span> and the <span class="doxyComputerOutput">index.chm</span> for project <em>b</em> into <span class="doxyComputerOutput">b.chm</span>. In the configuration file for project <em>a</em> you write:


<pre><code>TAGFILES = b.tag=mk:@MSITStore:b.chm::
</code></pre>


## I don't like the quick index that is put above each HTML page, what do I do? {#faq_html}


You can disable the index by setting <a href="/web-doxygen/docs/pages/config/#cfg_disable_index">DISABLE\_INDEX</a> to <span class="doxyComputerOutput">YES</span>. Then you can put in your own header file by writing your own header and feed that to <a href="/web-doxygen/docs/pages/config/#cfg_html_header">HTML\_HEADER</a>.

## The overall HTML output looks different, while I only wanted to use my own html header file {#faq_html_header}


You probably forgot to include the stylesheet <span class="doxyComputerOutput">doxygen.css</span> that Doxygen generates. You can include this by putting


<pre><code>&lt;LINK HREF="doxygen.css" REL="stylesheet" TYPE="text/css"&gt;
</code></pre>


in the HEAD section of the HTML page.

## Why does Doxygen use Qt? {#faq_use_qt}


In the past (prior to version 1.9.2) Doxygen used a part of Qt 2.x for various utility classes. These have been replaced by STL container classes in the meantime.

The GUI front-end called Doxywizard is based on a modern version of Qt. Doxygen itself can also be used without the GUI.

## How can I exclude all test directories from my directory tree? {#faq_excl_dir}


Simply put an exclude pattern like this in the configuration file:


<pre><code>EXCLUDE_PATTERNS = */test/*
</code></pre>


## Doxygen automatically generates a link to the class MyClass somewhere in the running text. How do I prevent that at a certain place? {#faq_class}


Put a % in front of the class name. Like this: %MyClass. Doxygen will then remove the % and keep the word unlinked.

## My favorite programming language is X. Can I still use Doxygen? {#faq_pgm_X}


No, not as such; Doxygen needs to understand the structure of what it reads. If you don't mind spending some time on it, there are several options:

<ul class="doxyList ">
<li>If the grammar of X is close to C or C++, then it is probably not too hard to tweak <span class="doxyComputerOutput">src/scanner.l</span> a bit so the language is supported. This is done for all other languages directly supported by Doxygen (i.e. Java, IDL, C#, PHP).</li>
<li>If the grammar of X is somewhat different than you can write an input filter that translates X into something similar enough to C/C++ for Doxygen to understand (this approach is taken for VB, Object Pascal, and JavaScript, see <a href="https://www.doxygen.org/helpers.html">https://www.doxygen.org/helpers.html</a>).</li>
<li>If the grammar is completely different one could write a parser for X and write a backend that produces a similar syntax tree as is done by <span class="doxyComputerOutput">src/scanner.l</span> (and also by <span class="doxyComputerOutput">src/tagreader.cpp</span> while reading tag files).</li>
</ul>

## Help! I get the cryptic message "input buffer overflow, can't enlarge buffer because scanner uses REJECT" {#faq_lex}


This error happens when Doxygen's lexical scanner has a rule that matches more than 256K of input characters in one go. I've seen this happening on a very large generated file (&gt;256K lines), where the built-in preprocessor converted it into an empty file (with &gt;256K of newlines). Another case where this might happen is if you have lines in your code with more than 256K characters.

If you have run into such a case and want me to fix it, you should send me a code fragment that triggers the message. To work around the problem, put some line-breaks into your file, split it up into smaller parts, or exclude it from the input using EXCLUDE.

Another way to work around this problem is to use the cmake command with the option:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">-Denlarge_lex_buffers=&lt;size&gt;</span></span></div>

</div>


where <span class="doxyComputerOutput">&lt;size&gt;</span> is the new size of the input (<span class="doxyComputerOutput">YY\_BUF\_SIZE</span>) and read (<span class="doxyComputerOutput">YY\_READ\_BUF\_SIZE</span>) buffer. In case this option is not given the default value of 262144 (i.e. 256K) will be used.

## When running make in the latex directory I get "TeX capacity exceeded". Now what? {#faq_latex}


You can edit the texmf.cfg file to increase the default values of the various buffers and then run "texconfig init".

## Why are dependencies via STL classes not shown in the dot graphs? {#faq_stl}


Doxygen is unaware of the STL classes, unless the option <a href="/web-doxygen/docs/pages/config/#cfg_builtin_stl_support">BUILTIN\_STL\_SUPPORT</a> is turned on.

## I have problems getting the search engine to work with PHP5 and/or windows {#faq_search}


Please read <a href="/docs/pages/searching/">this</a> for hints on where to look.

## Can I configure Doxygen from the command line? {#faq_cmdline}


Not via command line options, but Doxygen can read from <span class="doxyComputerOutput">stdin</span>, so you can pipe things through it. Here's an example how to override an option in a configuration file from the command line (assuming a UNIX like environment):


<pre><code>( cat Doxyfile ; echo "PROJECT_NUMBER=1.0" ) | doxygen -
</code></pre>


For Windows command line the following would do the same:


<pre><code>( type Doxyfile &amp; echo PROJECT_NUMBER=1.0 ) | doxygen.exe -
</code></pre>


For Windows Powershell (checked with version 5.1) the following would do the same:


<pre><code>&amp;{ type Doxyfile ; echo "PROJECT_NUMBER=1.0" } | doxygen -
</code></pre>


If multiple options with the same name are specified then Doxygen will use the last one. To append to an existing option you can use the += operator.

## How did Doxygen get its name? {#faq_name}


Doxygen got its name from playing with the words documentation and generator.


<pre><code>documentation -&gt; docs -&gt; dox
generator -&gt; gen
</code></pre>


At the time I was looking into <span class="doxyComputerOutput">lex</span> and <span class="doxyComputerOutput">yacc</span>, where a lot of things start with "yy", so the "y" slipped in and made things pronounceable (the proper pronouncement is Docs-ee-gen, so with a long "e").

## What was the reason to develop Doxygen? {#faq_why}


I once wrote a GUI widget based on the Qt library (it is still available at <a href="https://sourceforge.net/projects/qdbttabular/">https://sourceforge.net/projects/qdbttabular/</a> but hasn't been updated since 2002). Qt had nicely generated documentation (using an internal tool which <a href="https://rant.gulbrandsen.priv.no/udoc/history">they didn't want to release</a>) and I wrote similar docs by hand. This was a nightmare to maintain, so I wanted a similar tool. I looked at Doc++ but that just wasn't good enough (it didn't support signals and slots and did not have the Qt look and feel I had grown to like), so I started to write my own tool...

## How to prevent interleaved output {#faq_bin}


When redirecting all the console output of Doxygen, i.e. messages and warnings, this can be interleaved or in a non-expected order. The, technical, reason for this is that the <span class="doxyComputerOutput">stdout</span> can be buffered. It is possible to overcome this by means of the <span class="doxyComputerOutput">-b</span> of Doxygen, like e.g <span class="doxyComputerOutput">doxygen -b &gt; out.txt 2&gt;&amp;1</span>. Note this might cost a little more time though.

Go to the <a href="/docs/pages/trouble/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
