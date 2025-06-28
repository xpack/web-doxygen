---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/external
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Linking to external documentation




<p>If your project depends on external libraries or tools, there are several reasons to not include all sources for these with every run of Doxygen:</p>

<dl class="doxyVariableList">
<dt>Disk space:</dt>
<dd>Some documentation may be available outside of the output directory of Doxygen already, for instance somewhere on the web. You may want to link to these pages instead of generating the documentation in your local output directory.</dd>
<dt>Compilation speed:</dt>
<dd>External projects typically have a different update frequency from your own project. It does not make much sense to let Doxygen parse the sources for these external project over and over again, even if nothing has changed.</dd>
<dt>Memory:</dt>
<dd>For very large source trees, letting Doxygen parse all sources may simply take too much of your system's memory. By dividing the sources into several "packages", the sources of one package can be parsed by Doxygen, while all other packages that this package depends on, are linked in externally. This saves a lot of memory.</dd>
<dt>Availability:</dt>
<dd>For some projects that are documented with Doxygen, the sources may just not be available.</dd>
<dt>Copyright issues:</dt>
<dd>If the external package and its documentation are copyright someone else, it may be better - or even necessary - to reference it rather than include a copy of it with your project's documentation. When the author forbids redistribution, this is necessary. If the author requires compliance with some license condition as a precondition of redistribution, and you do not want to be bound by those conditions, referring to their copy of their documentation is preferable to including a copy.</dd>
</dl>

<p>If any of the above apply, you can use Doxygen's tag file mechanism. A tag file is basically a compact representation of the entities found in the external sources. Doxygen can both generate and read tag files.</p>

<p>To generate a tag file for your project, simply put the name of the tag file after the <a href="/web-doxygen/docs/pages/config/#cfg_generate_tagfile">GENERATE_TAGFILE</a> option in the configuration file.</p>

<p>To combine the output of one or more external projects with your own project you should specify the name of the tag files after the <a href="/web-doxygen/docs/pages/config/#cfg_tagfiles">TAGFILES</a> option in the configuration file.</p>

<p>A tag file typically only contains a relative location of the documentation from the point where Doxygen was run. So when you include a tag file in other project you have to specify where the external documentation is located in relation this project. You can do this in the configuration file by assigning the (relative) location to the tag files specified after the <a href="/web-doxygen/docs/pages/config/#cfg_tagfiles">TAGFILES</a> configuration option. If you use a relative path it should be relative with respect to the directory where the HTML output of your project is generated; so a relative path from the HTML output directory of a project to the HTML output of the other project that is linked to.</p>

<dl class="doxySectionUser">
<dt>Example: </dt>
<dd>
<p>Suppose you have a project <span class="doxyComputerOutput">proj</span> that uses two external projects called <span class="doxyComputerOutput">ext1</span> and <span class="doxyComputerOutput">ext2</span>. The directory structure looks as follows:</p>
</dd>
</dl>


<dl class="doxySectionUser">
<dt></dt>
<dd>
<pre><code>&lt;root&gt;
  +- proj
  |   +- html               HTML output directory for proj
  |   +- src                sources for proj
  |   |- proj.cpp
  +- ext1
  |   +- html               HTML output directory for ext1
  |   |- ext1.tag           tag file for ext1
  +- ext2
  |   +- html               HTML output directory for ext2
  |   |- ext2.tag           tag file for ext2
  |- proj.cfg               Doxygen configuration file for proj
  |- ext1.cfg               Doxygen configuration file for ext1
  |- ext2.cfg               Doxygen configuration file for ext2
</code></pre>
</dd>
</dl>


<dl class="doxySectionUser">
<dt></dt>
<dd>
<p>Then the relevant parts of the configuration files look as follows:</p>
</dd>
</dl>


<dl class="doxySectionUser">
<dt></dt>
<dd>
<p>proj.cfg:</p>


<pre><code>OUTPUT_DIRECTORY  = proj
INPUT             = proj/src
TAGFILES          = ext1/ext1.tag=../../ext1/html \
                    ext2/ext2.tag=../../ext2/html
</code></pre>


<p>ext1.cfg:</p>


<pre><code>OUTPUT_DIRECTORY  = ext1
GENERATE_TAGFILE  = ext1/ext1.tag
</code></pre>


<p>ext2.cfg:</p>


<pre><code>OUTPUT_DIRECTORY  = ext2
GENERATE_TAGFILE  = ext2/ext2.tag
</code></pre>
</dd>
</dl>

 
Go to the <a href="/docs/pages/faq/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
