---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/additional
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Additional Documentation




## Custom Pages {#custom_pages}


<p>Doxygen can be also be used to create custom pages that are not part of the API of your library/program. The purpose of such pages is to enrich your documentation with anything else that you think the user may find useful.</p>


<p>To create custom pages, use one of the supported file extension: <span class="doxyComputerOutput">.dox</span>, <span class="doxyComputerOutput">.txt</span>, or <span class="doxyComputerOutput">.md</span>. Doxygen will treat a .dox or .txt file as a C/C++ source file, and a .md file as a Markdown file.</p>


<p>For a .dox or .txt file, one can use a single Doxygen comment, like so:</p>


<p><span class="doxyComputerOutput">manual/index.dox</span></p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** \mainpage My Library Manual</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">- Building</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">- Basics</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">- Examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>

</div>


<p>You'll note that the <a href="/web-doxygen/docs/pages/commands/#cmdmainpage">\mainpage</a> command was used, which tells Doxygen to use this page as, well, the main page. For other pages, prefix them with the <a href="/web-doxygen/docs/pages/commands/#cmdpage">\page</a> command.</p>


<p>By default Doxygen will not know about these custom files, so we'll need to let it know through the <span class="doxyComputerOutput">INPUT</span> attribute in our Doxyfile. For the about example add this line to your Doxyfile:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">INPUT  = manual/index.dox</span></span></div>

</div>


<p>Next, we may want to add the instructions on how to build the project, so we create <span class="doxyComputerOutput">manual/building/index.dox</span>. As you read a bit more of the documentation, you will find out that Doxygen supports a subset of the <a href="/web-doxygen/docs/pages/htmlcmds">HTML</a> tags, so we can write the following:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/** \page Building</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;h2&gt;Linux&lt;/h2&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;p&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  A simple way to build this project is with cmake, clone the repository, cd into the root of the project and run:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;/p&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;pre&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  &lt;code&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    mkdir my_build</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    cmake -S . -B my_build</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    cd my_build</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">    cmake --build .</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  &lt;/code&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;/pre&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">*/</span></span></div>

</div>


<p>But you can of course also do the same using the popular <a href="/web-doxygen/docs/pages/markdown">Markdown</a> notation:</p>



<pre><code># Building

## Linux

A simple way to build this project is with cmake, clone the repository,
cd into the root of the project and run:

    mkdir my_build
    cmake -S . -B my_build
    cd my_build
    cmake --build .
</code></pre>


## Scaling Up {#scaling}


### Automatically Adding Files {#automatically_adding_files}


<p>At this point we could now go ahead and add <span class="doxyComputerOutput">manual/building/index.dox</span> to our INPUT's with comma separation, but this might become annoying over time as we build up our manual, instead we'll just change it reference our manual folder:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">INPUT                  = manual/</span></span></div>

</div>


<p>And set</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">RECURSIVE              = YES</span></span></div>

</div>


<p>To make sure as we add any subdirectories of the manual as we create more organization and content.</p>


### Side Panel Treeview {#treeview}


<p>As your manual scales up, you might want to also have a nice tree view to show you where you are in the manual to stay organized. This is easy enough to set up, turn it on with</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">GENERATE_TREEVIEW      = YES</span></span></div>

</div>


<p>In your <span class="doxyComputerOutput">Doxyfile</span>.</p>


<p>You'll recall that our <span class="doxyComputerOutput">manual/index.dox</span> file is pretty bland, without any links pointing anywhere, by using the <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a> command we can add links between various topics, and doing so will automatically start to populate our treeview.</p>


<p>If you notice that your tree is more like a pile of leaves then you can remedy this by checking out <a href="/web-doxygen/docs/pages/grouping/#subpaging">Subpaging</a>.</p>


<p>This discussion should give you some direction on how to build a scalable manual to enrich your documentation, from here you might want to customize your <a href="/web-doxygen/docs/pages/customize/#layout">layout</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
