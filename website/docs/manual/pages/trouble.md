---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/trouble
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Troubleshooting




## Known Problems {#knowproblems}


<ul class="doxyList ">
<li>Doxygen is <em>not</em> a real compiler, it is only a lexical scanner. This means that it can and will not detect errors in your source code.</li>
<li>Doxygen has a built-in preprocessor, but this works slightly different than the C preprocessor. Doxygen assumes a header file is properly guarded against multiple inclusion, and that each include file is standalone (i.e. it could be placed at the top of a source file without causing compiler errors). As long as this is true (and this is a good design practice) you should not encounter problems.</li>
<li>Since it is impossible to test all possible code fragments, it is very well possible, that some valid piece of C/C++ code is not handled properly. If you find such a piece, please send it to me, so I can improve Doxygen's parsing capabilities. Try to make the piece of code you send as small as possible, to help me narrow down the search.</li>
<li>Doxygen does not work properly if there are multiple classes, structs or unions with the same name in your code. It should not crash however, rather it should ignore all of the classes with the same name except one.</li>
<li>Some commands do not work inside the arguments of other commands. Inside a HTML link (i.e. <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_A_HREF">&lt;A HREF="..."&gt;</a>...<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endA">&lt;/A&gt;</a>) for instance other commands (including other HTML commands) do not work! The sectioning commands are an important exception.</li>
<li>Redundant braces can confuse Doxygen in some cases. For example:


<pre><code>  void f (int);
</code></pre>


is properly parsed as a function declaration, but


<pre><code>  const int (a);
</code></pre>


is also seen as a function declaration with name <span class="doxyComputerOutput">int</span>, because only the syntax is analyzed, not the semantics. If the redundant braces can be detected, as in


<pre><code>  int *(a[20]);
</code></pre>


then Doxygen will remove the braces and correctly parse the result.</li>
<li>Not all names in code fragments that are included in the documentation are replaced by links (for instance when using <a href="/web-doxygen/docs/pages/config/#cfg_source_browser">SOURCE_BROWSER</a> = <span class="doxyComputerOutput">YES</span>) and links to overloaded members may point to the wrong member. This also holds for the "Referenced by" list that is generated for each function.

For a part this is because the code parser isn't smart enough at the moment. I'll try to improve this in the future. But even with these improvements not everything can be properly linked to the corresponding documentation, because of possible ambiguities or lack of information about the context in which the code fragment is found.</li>
<li>It is not possible to insert a non-member function f in a class A using the <a href="/web-doxygen/docs/pages/commands/#cmdrelates">\relates</a> or <a href="/web-doxygen/docs/pages/commands/#cmdrelatesalso">\relatesalso</a> command, if class A already has a member with name f and the same argument list.</li>
<li>There is only very limited support for member specialization at the moment. It only works if there is a specialized template class as well.</li>
<li>Not all special commands are properly translated to RTF.</li>
<li>Version 1.8.6 of dot (and maybe earlier versions too) do not generate proper map files, causing the graphs that Doxygen generates not to be properly clickable.</li>
<li>PHP only: Doxygen requires that all PHP statements (i.e. code) is wrapped in a functions/methods, otherwise you may run into parse problems.</li>
</ul>

## How to Help {#howtohelp}


<p>The development of Doxygen highly depends on your input!</p>


<p>If you are trying Doxygen let me know what you think of it (do you miss certain features?). Even if you decide not to use it, please let me know why.</p>


## How to report a bug {#bug_reports}


<p>Bugs are tracked in GitHub's <a href="https://github.com/doxygen/doxygen/issues">issue tracker</a>. Before submitting a <a href="https://github.com/doxygen/doxygen/issues/new">new bug</a>, first <a href="https://github.com/doxygen/doxygen/issues">search</a> through the database if the same bug has already been submitted by others. If you believe you have found a new bug, please <a href="https://github.com/doxygen/doxygen/issues/new">report it</a>.</p>


<p>If you are unsure whether or not something is a bug, please ask help first (subscription is required) on the <a href="https://sourceforge.net/p/doxygen/mailman/">users mailing list</a> or at <a href="https://stackoverflow.com/questions/tagged/doxygen">Stack Overflow</a> using the <span class="doxyComputerOutput">doxygen</span> label.</p>


<p>If you send only a (vague) description of a bug, you are usually not very helpful and it will cost me much more time to figure out what you mean. In the worst-case your bug report may even be completely ignored by me, so always try to include the following information in your bug report:</p>


<ul class="doxyList ">
<li>The version of Doxygen you are using (for instance 1.5.3, use <span class="doxyComputerOutput">doxygen --version</span> if you are not sure or <span class="doxyComputerOutput">doxygen --Version</span> for a bit more information).</li>
<li>The name and version number of your operating system (for instance Ubuntu Linux 18.04 LTS)</li>
<li>It is usually a good idea to send along the configuration file as well, but please use Doxygen with the <span class="doxyComputerOutput">-s</span> flag while generating it to keep it small (use <span class="doxyComputerOutput">doxygen -s -u [configName]</span> to strip the comments from an existing configuration file. Better even to use the <span class="doxyComputerOutput">-x</span> or the <span class="doxyComputerOutput">-x_noenv</span> flag on the used <span class="doxyComputerOutput">[configName]</span> to get the differences between the used settings and the Doxygen default settings, so <span class="doxyComputerOutput">doxygen -x [configName]</span>).</li>
<li>The easiest (and often the only) way for me to fix bugs is if you can attach a small example demonstrating the problem you have to the bug report, so I can reproduce it on my machine. Please make sure the example is valid source code (could potentially compile) and that the problem is really captured by the example (I often get examples that do not trigger the actual bug!). If you intend to send more than one file please zip or tar the files together into a single file for easier processing. Note that when reporting a new bug you'll get a chance to attach a file to it only <em>after</em> submitting the initial bug description.</li>
<li>Before submitting, consider also running Doxygen with some debugging flags, run <span class="doxyComputerOutput">doxygen -d</span> for all flags. The option <span class="doxyComputerOutput">preprocessor</span> might give you hints on how Doxygen is understanding your input files.</li>
</ul>

<p>You can (and are encouraged to) add a patch for a <a href="https://github.com/doxygen/doxygen/issues">reported bug</a>. If you do so, please use "issue #NUMBER TITLE" as a title in the <a href="https://github.com/doxygen/doxygen/compare">pull request form</a>, where "NUMBER" and "TITLE" refer to the associated issue on GitHub.</p>


<p>If you have ideas how to fix existing bugs and limitations please discuss them on the <a href="https://sourceforge.net/p/doxygen/mailman/">developers mailing list</a> (subscription required). Patches can also be sent directly to <a href="mailto:doxygen@gmail.com">doxygen@gmail.com</a> if you prefer not to send them via the bug tracker or mailing list.</p>


<p>For patches please use "diff -uN" or include the files you modified. If you send more than one file please tar or zip everything, so I only have to save and download one file.</p>

 
Go to the <a href="/docs/pages/features/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
