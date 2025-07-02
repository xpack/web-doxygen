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




The following table gives an overview of the doxygen internal special commands and the version in which they were introduced.


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


This command is used to prevent endless recursive expansion of aliases. For an alias <code>name</code> the command <code> is inserted after its expansion, and then the expanded string is reparsed, but until the </code> is processed the <code>name</code> is not considered for further alias expansion.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.11.0</dd>
</dl>


<hr/>


## \\ianchor{title} anchor {#cmdianchor}


This command has a similar syntax and function as the command <code>\\anchor</code>, but is internally used for the <code>@page</code> command in markdown files. Unlike <code>\\anchor</code> it has an additional <code>title</code> option that is used as the link text in references to the page.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.7</dd>
</dl>


<hr/>


## \\ilinebr {#cmdilinebr}


Internal doxygen command to simulate an end of line, but without advancing the line counter. In this way it is possible to have multiple commands on one line that read till the end of line. This command is internally used by doxygen and for replacement of the <code>^^</code> in <code>ALIASES</code> settings. This command sees to it that e.g. warning messages stay correct when a command is replaced internally by multiple commands.

Temporarily also as <code>@\_ilinebr</code> (doxygen version 1.8.14) and <code>\\\_ilinebr</code> (doxygen version 1.8.15 till 1.8.18)

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.8.19</dd>
</dl>


<hr/>


## \\ifile &lt;filename&gt; {#cmdifile}


Internal doxygen command to reset the current filename in a documentation block so that doxygen can give a better warning about the original source of a problem when a documentation block is constructed from multiple files.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.5</dd>
</dl>


<hr/>


## \\iline &lt;linenr&gt; {#cmdiline}


Internal doxygen command to reset the current line counter in a documentation block so that doxygen can give a better warning about the original source of a problem when a documentation block is constructed from multiple files or blocks from one file.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.2</dd>
</dl>


<hr/>


## \\icode\['{'&lt;word&gt;'}'\] {#cmdicode}


This command has a similar syntax and function as the command <code>\\code</code>, but is internally used for markdown fenced code blocks (i.e. <code>```</code> and <code>\~\~\~</code> type of blocks) to replace these markers. The <code>\\code</code> command cannot be used as in that case the block cannot contain a <code>\\endcode</code> as this would terminate the <code>\\code</code> block.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.5</dd>
</dl>


<hr/>


## \\endicode {#cmdendicode}


Ends a block of text that was started with a <a href="#cmdicode">\\icode</a> command.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.5</dd>
</dl>


<hr/>


## \\iliteral\['{'&lt;option&gt;'}'\] {#cmdiliteral}


This command is to replace the Java documentation commands <code>{@literal .... }</code> and <code>{@code ...}</code>. The text in the blocks will not be interpreted by doxygen in any way. The text in the <code>{@literal</code> will put as is text in the output. The text in the <code>{@code</code> will be replaced by a code block with class <code>JavaDocCode</code> i.e. <code>&lt;code class="JavaDocCode"&gt;...&lt;/code&gt;</code>.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.3</dd>
</dl>


<hr/>


## \\endiliteral {#cmdendiliteral}


Ends a block of text that was started with a <a href="#cmdiliteral">\\iliteral</a> command.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.3</dd>
</dl>


<hr/>


## \\iverbatim {#cmdiverbatim}


This command has a similar function as the command <code>\\verbatim</code>, but is internally used for markdown code blocks (i.e. blocks of text indented with at least 4 extra spaces compared to the previous block) and python unformatted docstrings (i.e. <code>'''</code> type of blocks) to replace these markers. The <code>\\verbatim</code> command cannot be used as in that case the block cannot contain a <code>\\endverbatim</code> as this would terminate the <code>\\verbatim</code> block.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.5</dd>
</dl>


<hr/>


## \\iraise &lt;amount&gt; {#cmdiraise}


Internal doxygen command to increase the section level by a given <code>amount</code>. After processing <code>\\iraise 1</code> for instance, a <code>\\section s1</code> will be treated as a <code>\\subsection s1</code>. Inserted when processing <code>\\include{doc}</code> with the <code>raise</code> option.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.11.0</dd>
</dl>


<hr/>


## \\iskip {#cmdiskip}


Internal doxygen command to suppress evaluation of whitespace to determine the indentation of a comment block. Evaluation will continue as normal when the matching <a href="#cmdendiskip">\\endiskip</a> command is found. Inserted when processing commands that contain literal text like <code>\\startuml</code>, <code>\\verbatim</code>, <code>&lt;code&gt;</code> etc.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.12.0</dd>
</dl>


<hr/>


## \\iprefix "&lt;label&gt;" {#cmdiprefix}


Internal doxygen command to prefix section labels references for <code>\\ref</code> and <code>\\link</code> commands. After processing <code>\\iprefix "pf\_"</code> for instance, a <code>\\ref s1</code> will be treated as if <code>\\ref pf\_s1</code> was written. Inserted internally when processing <code>\\include{doc}</code> with the <code>prefix</code> option.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.11.0</dd>
</dl>


<hr/>


## \\endiskip {#cmdendiskip}


Ends a block of text that was started with a <a href="#cmdiskip">\\iskip</a> command.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.12.0</dd>
</dl>


<hr/>


## \\endiverbatim {#cmdendiverbatim}


Ends a block of text that was started with a <a href="#cmdiverbatim">\\iverbatim</a> command.

<dl class="doxySectionUser">
<dt>Since</dt>
<dd>doxygen version 1.9.5</dd>
</dl>


<hr/>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
