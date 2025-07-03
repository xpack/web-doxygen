---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/pages/pg-cmds-int
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Overview of introduction of internal special commands




<p>The following table gives an overview of the doxygen internal special commands and the version in which they were introduced.</p>



<ul class="doxyTocList">
<li><a class="doxyTocListItem" href="#cmdialias">\ialias</a></li>
<li><a class="doxyTocListItem" href="#cmdendicode">\endicode</a></li>
<li><a class="doxyTocListItem" href="#cmdendiliteral">\endiliteral</a></li>
<li><a class="doxyTocListItem" href="#cmdendiskip">\endiskip</a></li>
<li><a class="doxyTocListItem" href="#cmdendiverbatim">\endiverbatim</a></li>
<li><a class="doxyTocListItem" href="#cmdianchor">\ianchor</a></li>
<li><a class="doxyTocListItem" href="#cmdicode">\icode</a></li>
<li><a class="doxyTocListItem" href="#cmdifile">\ifile</a></li>
<li><a class="doxyTocListItem" href="#cmdiline">\iline</a></li>
<li><a class="doxyTocListItem" href="#cmdilinebr">\ilinebr</a></li>
<li><a class="doxyTocListItem" href="#cmdiliteral">\iliteral</a></li>
<li><a class="doxyTocListItem" href="#cmdiprefix">\iprefix</a></li>
<li><a class="doxyTocListItem" href="#cmdiraise">\iraise</a></li>
<li><a class="doxyTocListItem" href="#cmdiskip">\iskip</a></li>
<li><a class="doxyTocListItem" href="#cmdiverbatim">\iverbatim</a></li>
</ul>

<hr/>


## \\ialias{name} {#cmdialias}


<p>This command is used to prevent endless recursive expansion of aliases. For an alias <span class="doxyComputerOutput">name</span> the command <span class="doxyComputerOutput"> is inserted after its expansion, and then the expanded string is reparsed, but until the </span> is processed the <span class="doxyComputerOutput">name</span> is not considered for further alias expansion.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.11.0</p></dd>
</dl>


<hr/>


## \\ianchor{title} anchor {#cmdianchor}


<p>This command has a similar syntax and function as the command <span class="doxyComputerOutput">\anchor</span>, but is internally used for the <span class="doxyComputerOutput">@page</span> command in markdown files. Unlike <span class="doxyComputerOutput">\anchor</span> it has an additional <span class="doxyComputerOutput">title</span> option that is used as the link text in references to the page.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.7</p></dd>
</dl>


<hr/>


## \\ilinebr {#cmdilinebr}


<p>Internal doxygen command to simulate an end of line, but without advancing the line counter. In this way it is possible to have multiple commands on one line that read till the end of line. This command is internally used by doxygen and for replacement of the <span class="doxyComputerOutput">^^</span> in <span class="doxyComputerOutput">ALIASES</span> settings. This command sees to it that e.g. warning messages stay correct when a command is replaced internally by multiple commands.</p>


<p>Temporarily also as <span class="doxyComputerOutput">@_ilinebr</span> (doxygen version 1.8.14) and <span class="doxyComputerOutput">\_ilinebr</span> (doxygen version 1.8.15 till 1.8.18)</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.8.19</p></dd>
</dl>


<hr/>


## \\ifile &lt;filename&gt; {#cmdifile}


<p>Internal doxygen command to reset the current filename in a documentation block so that doxygen can give a better warning about the original source of a problem when a documentation block is constructed from multiple files.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.5</p></dd>
</dl>


<hr/>


## \\iline &lt;linenr&gt; {#cmdiline}


<p>Internal doxygen command to reset the current line counter in a documentation block so that doxygen can give a better warning about the original source of a problem when a documentation block is constructed from multiple files or blocks from one file.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.2</p></dd>
</dl>


<hr/>


## \\icode\['{'&lt;word&gt;'}'\] {#cmdicode}


<p>This command has a similar syntax and function as the command <span class="doxyComputerOutput">\code</span>, but is internally used for markdown fenced code blocks (i.e. <span class="doxyComputerOutput">```</span> and <span class="doxyComputerOutput">~~~</span> type of blocks) to replace these markers. The <span class="doxyComputerOutput">\code</span> command cannot be used as in that case the block cannot contain a <span class="doxyComputerOutput">\endcode</span> as this would terminate the <span class="doxyComputerOutput">\code</span> block.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.5</p></dd>
</dl>


<hr/>


## \\endicode {#cmdendicode}


<p>Ends a block of text that was started with a <a href="#cmdicode">\icode</a> command.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.5</p></dd>
</dl>


<hr/>


## \\iliteral\['{'&lt;option&gt;'}'\] {#cmdiliteral}


<p>This command is to replace the Java documentation commands <span class="doxyComputerOutput">{@literal .... }</span> and <span class="doxyComputerOutput">{@code ...}</span>. The text in the blocks will not be interpreted by doxygen in any way. The text in the <span class="doxyComputerOutput">{@literal</span> will put as is text in the output. The text in the <span class="doxyComputerOutput">{@code</span> will be replaced by a code block with class <span class="doxyComputerOutput">JavaDocCode</span> i.e. <span class="doxyComputerOutput">&lt;code class="JavaDocCode"&gt;...&lt;/code&gt;</span>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.3</p></dd>
</dl>


<hr/>


## \\endiliteral {#cmdendiliteral}


<p>Ends a block of text that was started with a <a href="#cmdiliteral">\iliteral</a> command.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.3</p></dd>
</dl>


<hr/>


## \\iverbatim {#cmdiverbatim}


<p>This command has a similar function as the command <span class="doxyComputerOutput">\verbatim</span>, but is internally used for markdown code blocks (i.e. blocks of text indented with at least 4 extra spaces compared to the previous block) and python unformatted docstrings (i.e. <span class="doxyComputerOutput">'''</span> type of blocks) to replace these markers. The <span class="doxyComputerOutput">\verbatim</span> command cannot be used as in that case the block cannot contain a <span class="doxyComputerOutput">\endverbatim</span> as this would terminate the <span class="doxyComputerOutput">\verbatim</span> block.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.5</p></dd>
</dl>


<hr/>


## \\iraise &lt;amount&gt; {#cmdiraise}


<p>Internal doxygen command to increase the section level by a given <span class="doxyComputerOutput">amount</span>. After processing <span class="doxyComputerOutput">\iraise 1</span> for instance, a <span class="doxyComputerOutput">\section s1</span> will be treated as a <span class="doxyComputerOutput">\subsection s1</span>. Inserted when processing <span class="doxyComputerOutput">\include{doc}</span> with the <span class="doxyComputerOutput">raise</span> option.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.11.0</p></dd>
</dl>


<hr/>


## \\iskip {#cmdiskip}


<p>Internal doxygen command to suppress evaluation of whitespace to determine the indentation of a comment block. Evaluation will continue as normal when the matching <a href="#cmdendiskip">\endiskip</a> command is found. Inserted when processing commands that contain literal text like <span class="doxyComputerOutput">\startuml</span>, <span class="doxyComputerOutput">\verbatim</span>, <span class="doxyComputerOutput">&lt;code&gt;</span> etc.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.12.0</p></dd>
</dl>


<hr/>


## \\iprefix "&lt;label&gt;" {#cmdiprefix}


<p>Internal doxygen command to prefix section labels references for <span class="doxyComputerOutput">\ref</span> and <span class="doxyComputerOutput">\link</span> commands. After processing <span class="doxyComputerOutput">\iprefix "pf_"</span> for instance, a <span class="doxyComputerOutput">\ref s1</span> will be treated as if <span class="doxyComputerOutput">\ref pf_s1</span> was written. Inserted internally when processing <span class="doxyComputerOutput">\include{doc}</span> with the <span class="doxyComputerOutput">prefix</span> option.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.11.0</p></dd>
</dl>


<hr/>


## \\endiskip {#cmdendiskip}


<p>Ends a block of text that was started with a <a href="#cmdiskip">\iskip</a> command.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.12.0</p></dd>
</dl>


<hr/>


## \\endiverbatim {#cmdendiverbatim}


<p>Ends a block of text that was started with a <a href="#cmdiverbatim">\iverbatim</a> command.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>doxygen version 1.9.5</p></dd>
</dl>


<hr/>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
