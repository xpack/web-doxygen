---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/markdown
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# Markdown support




<p><a href="https://daringfireball.net/projects/markdown/">Markdown</a> support was introduced in Doxygen version 1.8.0. It is a plain text formatting syntax written by John Gruber, with the following underlying design goal:</p>

<blockquote class="doxyBlockQuote">

<p>The design goal for Markdown's formatting syntax is to make it as readable as possible. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions. While Markdown's syntax has been influenced by several existing text-to-HTML filters, the single biggest source of inspiration for Markdown's syntax is the format of plain text email.</p>

</blockquote>

<p>In the <a href="#markdown_std">next section</a> the standard Markdown features are briefly discussed. The reader is referred to the <a href="https://daringfireball.net/projects/markdown/">Markdown site</a> for more details.</p>


<p>Some enhancements were made, for instance <a href="https://michelf.ca/projects/php-markdown/extra/">PHP Markdown Extra</a>, and <a href="https://github.github.com/github-flavored-markdown/">GitHub flavored Markdown</a>. The section <a href="#markdown_extra">Markdown Extensions</a> discusses the extensions that Doxygen supports.</p>


<p>Finally section <a href="#markdown_dox">Doxygen specifics</a> discusses some specifics for Doxygen's implementation of the Markdown standard.</p>


## Standard Markdown {#markdown_std}


### Paragraphs {#md_para}


<p>Even before Doxygen had Markdown support it supported the same way of paragraph handling as Markdown: to make a paragraph you just separate consecutive lines of text by one or more blank lines.</p>


<p>An example:</p>



<pre><code>Here is text for one paragraph.

We continue with more text in another paragraph.
</code></pre>


### Headers {#md_headers}


<p>Just like Markdown, Doxygen supports two types of headers</p>


<p>Level 1 or 2 headers can be made as the follows</p>



<pre><code>This is a level 1 header
========================

This is a level 2 header
------------------------
</code></pre>


<p>A header is followed by a line containing only ='s or -'s. Note that the exact amount of ='s or -'s is not important as long as there are at least two.</p>


<p>Alternatively, you can use #'s at the start of a line to make a header. The number of #'s at the start of the line determines the level (up to 6 levels are supported). You can end a header by any number of #'s.</p>


<p>Here is an example:</p>



<pre><code># This is a level 1 header

### This is level 3 header #######
</code></pre>


### Block quotes {#md_blockquotes}


<p>Block quotes can be created by starting each line with one or more &gt;'s, similar to what is used in text-only emails.</p>



<pre><code>&gt; This is a block quote
&gt; spanning multiple lines
</code></pre>


<p>Lists and code blocks (see below) can appear inside a quote block. Quote blocks can also be nested.</p>


<p>Note that Doxygen requires that you put a space after the (last) &gt; character to avoid false positives, i.e. when writing</p>



<pre><code>0  if OK\n
&gt;1 if NOK
</code></pre>


<p>the second line will not be seen as a block quote.</p>


### Lists {#md_lists}


<p>Simple bullet lists can be made by starting a line with -, +, or *.</p>



<pre><code>- Item 1

  More text for this item.

- Item 2
  + nested list item.
  + another nested item.
- Item 3
</code></pre>


<p>List items can span multiple paragraphs (if each paragraph starts with the proper indentation) and lists can be nested. You can also make a numbered list like so</p>



<pre><code>1. First item.
2. Second item.
</code></pre>


<p>Make sure to also read <a href="#mddox_lists">Lists Extensions</a> for Doxygen specifics.</p>


### Code Blocks {#md_codeblock}


<p>Preformatted verbatim blocks can be created by indenting each line in a block of text by at least 4 extra spaces</p>



<pre><code>This a normal paragraph

    This is a code block

We continue with a normal paragraph again.
</code></pre>


<p>Doxygen will remove the mandatory indentation from the code block. Note that you cannot start a code block in the middle of a paragraph (i.e. the line preceding the code block must be empty).</p>


<p>See section <a href="#mddox_code_blocks">Code Block Indentation</a> for more info how Doxygen handles indentation as this is slightly different than standard Markdown.</p>


### Horizontal Rulers {#md_rulers}


<p>A horizontal ruler will be produced for lines containing at least three or more hyphens, asterisks, or underscores. The line may also include any amount of whitespace.</p>


<p>Examples:</p>



<pre><code>- - -
______
</code></pre>


<p>Note that using asterisks in comment blocks does not work. See <a href="#mddox_stars">Use of asterisks</a> for details.
<br/>
 Note that when using hyphens and the previous line is not empty you have to use at least one whitespace in the sequence of hyphens otherwise it might be seen as a level 2 header (see <a href="#md_headers">Headers</a>).</p>


### Emphasis {#md_emphasis}


<p>To emphasize a text fragment you start and end the fragment with an underscore or star. Using two stars or underscores will produce strong emphasis. Three stars or underscores will combine the emphasis from the previous two options.</p>


<p>Examples:</p>



<pre><code> *single asterisks*

 _single underscores_

 **double asterisks**

 __double underscores__

 ***triple asterisks***

 ___triple underscores___
</code></pre>


<p>See section <a href="#mddox_emph_spans">Emphasis and strikethrough limits</a> for more info how Doxygen handles emphasis / strikethrough spans slightly different than standard / Markdown GitHub Flavored Markdown.</p>


### Strikethrough {#md_strikethrough}


<p>To strikethrough a text fragment you start and end the fragment with two tildes.</p>


<p>Examples:</p>



<pre><code> ~~double tilde~~
</code></pre>


<p>See section <a href="#mddox_emph_spans">Emphasis and strikethrough limits</a> for more info how Doxygen handles emphasis / strikethrough spans slightly different than standard Markdown / GitHub Flavored Markdown.</p>


### code spans {#md_codespan}


<p>To indicate a span of code, you should wrap it in backticks (<span class="doxyComputerOutput"> ` </span>). Unlike code blocks, code spans appear inline in a paragraph. An example:</p>



<pre><code>Use the `printf()` function.
</code></pre>


<p>To show a literal backtick or single quote inside a code span use double backticks, i.e.</p>



<pre><code>To assign the output of command `ls` to `var` use ``var=`ls```.

To assign the text 'text' to `var` use ``var='text'``.
</code></pre>


<p>See section <a href="#mddox_code_spans">Code Spans Limits</a> for more info how Doxygen handles code spans slightly different than standard Markdown.</p>


### Links {#md_links}


<p>Doxygen supports both styles of make links defined by Markdown: <em>inline</em> and <em>reference</em>.</p>


<p>For both styles the link definition starts with the link text delimited by [square brackets].</p>


#### Inline Links {#md_inlinelinks}


<p>For an inline link the link text is followed by a URL and an optional link title which together are enclosed in a set of regular parenthesis. The link title itself is surrounded by quotes.</p>


<p>Examples:</p>



<pre><code>[The link text](http://example.net/)
[The link text](http://example.net/ "Link title")
[The link text](/relative/path/to/index.html "Link title")
[The link text](somefile.html)
</code></pre>


<p>In addition Doxygen provides a similar way to link a documented entity:</p>



<pre><code>[The link text](@ref MyClass)
</code></pre>


<p>in case the first non whitespace character of the reference is a <span class="doxyComputerOutput">#</span> this is interpreted as a Doxygen link and replaced as a <a href="/web-doxygen/docs/pages/commands/#cmdref">@ref</a> command:</p>



<pre><code>[The link text](#MyClass)
</code></pre>


<p>will be interpreted as:</p>



<pre><code>@ref MyClass "The link text"
</code></pre>


#### Reference Links {#md_reflinks}


<p>Instead of putting the URL inline, you can also define the link separately and then refer to it from within the text.</p>


<p>The link definition looks as follows:</p>



<pre><code>[link name]: http://www.example.com "Optional title"
</code></pre>


<p>Instead of double quotes also single quotes or parenthesis can be used for the title part.</p>


<p>Once defined, the link looks as follows</p>



<pre><code>[link text][link name]
</code></pre>


<p>If the link text and name are the same, also</p>



<pre><code>[link name][]
</code></pre>


<p>or even</p>



<pre><code>[link name]
</code></pre>


<p>can be used to refer to the link. Note that the link name matching is not case sensitive as is shown in the following example:</p>



<pre><code>I get 10 times more traffic from [Google] than from
[Yahoo] or [MSN].

[google]: http://google.com/        "Google"
[yahoo]:  http://search.yahoo.com/  "Yahoo Search"
[msn]:    http://search.msn.com/    "MSN Search"
</code></pre>


<p>Link definitions will not be visible in the output.</p>


<p>Like for inline links Doxygen also supports @ref inside a link definition:</p>



<pre><code>[myclass]: @ref MyClass "My class"
</code></pre>


### Images {#md_images}


<p>Markdown syntax for images is similar to that for links. The only difference is an additional ! before the link text.</p>


<p>Examples:</p>



<pre><code>![Caption text](/path/to/img.jpg)
![Caption text](/path/to/img.jpg "Image title")
![Caption text][img def]
![img def]

[img def]: /path/to/img.jpg "Optional Title"
</code></pre>


<p>Also here you can use @ref to link to an image:</p>



<pre><code>![Caption text](@ref image.png)
![img def]

[img def]: @ref image.png "Caption text"
</code></pre>


<p>The caption text is optional.</p>



:::info
<p>Don't forget to add the path of the image to the <a href="/web-doxygen/docs/pages/config/#cfg_image_path">IMAGE_PATH</a>.</p>
:::


### Automatic Linking {#md_autolink}


<p>To create a link to an URL or e-mail address Markdown supports the following syntax:</p>



<pre><code>&lt;http://www.example.com&gt;
&lt;https://www.example.com&gt;
&lt;ftp://www.example.com&gt;
&lt;mailto:address@example.com&gt;
&lt;address@example.com&gt;
</code></pre>


<p>Note that Doxygen will also produce the links without the angle brackets.</p>


## Markdown Extensions {#markdown_extra}


### Table of Contents {#md_toc}


<p>Doxygen supports a special link marker <span class="doxyComputerOutput">[TOC]</span> which can be placed in a page to produce a table of contents at the start of the page, listing all sections.</p>


<p>Note that using <span class="doxyComputerOutput">[TOC]</span> is the same as using a <a href="/web-doxygen/docs/pages/commands/#cmdtableofcontents">\tableofcontents</a> command.</p>


<p>Note that the <a href="/web-doxygen/docs/pages/config/#cfg_toc_include_headings">TOC_INCLUDE_HEADINGS</a> has to be set to a value &gt; 0 otherwise no table of contents is shown when using <a href="#md_headers">Markdown Headers</a>.</p>


### Tables {#md_tables}


<p>Of the features defined by "Markdown Extra" is support for <a href="https://michelf.ca/projects/php-markdown/extra/#table">simple tables</a>:</p>


<p>A table consists of a header line, a separator line, and at least one row line. Table columns are separated by the pipe (|) character.</p>


<p>Here is an example:</p>



<pre><code>First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
</code></pre>


<p>which will produce the following table:</p>


<table class="doxyTable">
<tr>
<th>First Header</th>
<th>Second Header</th>
</tr>
<tr>
<td>Content Cell</td>
<td>Content Cell</td>
</tr>
<tr>
<td>Content Cell</td>
<td>Content Cell</td>
</tr>
</table>

<p>Column alignment can be controlled via one or two colons at the header separator line:</p>



<pre><code>| Right | Center | Left  |
| ----: | :----: | :---- |
| 10    | 10     | 10    |
| 1000  | 1000   | 1000  |
</code></pre>


<p>which will look as follows:</p>


<table class="doxyTable">
<tr>
<th align="right">Right</th>
<th align="center">Center</th>
<th align="left">Left</th>
</tr>
<tr>
<td align="right">10</td>
<td align="center">10</td>
<td align="left">10</td>
</tr>
<tr>
<td align="right">1000</td>
<td align="center">1000</td>
<td align="left">1000</td>
</tr>
</table>

<p>Additionally, column and row spans are supported. Using a caret ("^") in a cell indicates that the cell above should span rows. Sequences of carets may be used for any number of row spans. For example:</p>



<pre><code>| Right | Center | Left  |
| ----: | :----: | :---- |
| 10    | 10     | 10    |
| ^     | 1000   | 1000  |
</code></pre>


<p>which will look as follows:</p>


<table class="doxyTable">
<tr>
<th align="right">Right</th>
<th align="center">Center</th>
<th align="left">Left</th>
</tr>
<tr>
<td rowspan="2" align="right">10</td>
<td align="center">10</td>
<td align="left">10</td>
</tr>
<tr>
<td align="center">1000</td>
<td align="left">1000</td>
</tr>
</table>

<p>Column spans are supported by means of directly adjacent vertical bars ("|"). Each additional vertical bar indicates an additional column to be spanned. To put it another way, a single vertical bar indicates a single column span, two vertical bars indicates a 2 columns span, and so on. For example:</p>



<pre><code>| Right | Center | Left  |
| ----: | :----: | :---- |
| 10    | 10     | 10    |
| 1000  |||
</code></pre>


<p>which will look as follows:</p>


<table class="doxyTable">
<tr>
<th align="right">Right</th>
<th align="center">Center</th>
<th align="left">Left</th>
</tr>
<tr>
<td align="right">10</td>
<td align="center">10</td>
<td align="left">10</td>
</tr>
<tr>
<td colspan="3" align="right">1000</td>
</tr>
</table>

<p>For more complex tables in Doxygen please have a look at: <a href="/web-doxygen/docs/pages/tables">Including tables</a></p>


### Fenced Code Blocks {#md_fenced}


<p>Another feature defined by "Markdown Extra" is support for <a href="https://michelf.ca/projects/php-markdown/extra/#fenced-code-blocks">fenced code blocks</a>:</p>


<p>A fenced code block does not require indentation, and is defined by a pair of "fence lines". Such a line consists of 3 or more tilde (~) characters on a line. The end of the block should have the same number of tildes. Here is an example:</p>



<pre><code>This is a paragraph introducing:

~~~~~~~~~~~~~~~~~~~~~
a one-line code block
~~~~~~~~~~~~~~~~~~~~~
</code></pre>


<p>By default the output is the same as for a normal code block.</p>


<p>For languages supported by Doxygen you can also make the code block appear with syntax highlighting. To do so you need to indicate the typical file extension that corresponds to the programming language after the opening fence. For highlighting according to the Python language for instance, you would need to write the following:</p>



<pre><code>~~~~~~~~~~~~~{.py}
# A class
class Dummy:
    pass
~~~~~~~~~~~~~
</code></pre>


<p>which will produce:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment"># A class</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Dummy:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">pass</span></span></div>

</div>


<p>and for C you would write:</p>



<pre><code>~~~~~~~~~~~~~~~{.c}
int func(int a,int b) { return a*b; }
~~~~~~~~~~~~~~~
</code></pre>


<p>which will produce:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> func(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> a,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> b) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> a*b; }</span></span></div>

</div>


<p>The dot is optional, the curly braces are optional when the that language name begins with an alphabetical character and further characters are alphanumerical characters or a plus sign.</p>


<p>Another way to denote fenced code blocks is to use 3 or more backticks (```):</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">```</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">also a fenced code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">```</span></span></div>

</div>


<p>For the image formats <span class="doxyComputerOutput">dot</span>, <span class="doxyComputerOutput">msc</span> and <span class="doxyComputerOutput">plantuml</span> the fenced block will be shown as an image provided the image format is enabled (see <a href="/web-doxygen/docs/pages/config/#cfg_have_dot">HAVE_DOT</a> and <a href="/web-doxygen/docs/pages/config/#cfg_plantuml_jar_path">PLANTUML_JAR_PATH</a>), otherwise it is shown as plain code.</p>


<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">```plantuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Alice -&gt; Bob</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">```</span></span></div>

</div>


<p>or</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">```plantuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">@startuml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Alice -&gt; Bob</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">@enduml</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">```</span></span></div>

</div>


### Header Id Attributes {#md_header_id}


<p>Standard Markdown has no support for labeling headers, which is a problem if you want to link to a section.</p>


<p>PHP Markdown Extra allows you to label a header by adding the following to the header</p>



<pre><code>Header 1                {#labelid}
========

## Header 2 ##          {#labelid2}
</code></pre>


<p>To link to a section in the same comment block you can use</p>



<pre><code>[Link text](#labelid)
</code></pre>


<p>to link to a section in general, Doxygen allows you to use <a href="/web-doxygen/docs/pages/commands/#cmdref">@ref</a></p>



<pre><code>[Link text](@ref labelid)
</code></pre>


<p>Note this only works for the headers of level 1 to 4.</p>


### Image Attributes {#md_image_attributes}


<p>Standard Markdown has no support for controlling image dimensions which results in less flexibility when writing docs.</p>


<p>PHP Markdown Extra allows you to add extra attributes to an image as in:</p>



<pre><code>![Caption text](/path/to/img.jpg){attributes}
</code></pre>


<p>To allow for output format specific attributes the following syntax is supported</p>



<pre><code>![Caption text](/path/to/img.jpg){format: attributes, format: attributes}
</code></pre>


<p>For a description of the possibilities see the paragraph <a href="/web-doxygen/docs/pages/commands/#image_sizeindicator">Size indication</a> for the <a href="/web-doxygen/docs/pages/commands/#cmdimage">\image</a> command.</p>


<p>For example:</p>



<pre><code>![Doxygen Logo](https://www.doxygen.org/images/doxygen.png){html: width=50%, latex: width=5cm}
</code></pre>


## Doxygen specifics {#markdown_dox}


<p>Even though Doxygen tries to following the Markdown standard as closely as possible, there are couple of deviation and Doxygen specifics additions.</p>


### Including Markdown files as pages {#md_page_header}


<p>Doxygen can process files with Markdown formatting. For this to work the extension for such a file should be <span class="doxyComputerOutput">.md</span> or <span class="doxyComputerOutput">.markdown</span> (see <a href="/web-doxygen/docs/pages/config/#cfg_extension_mapping">EXTENSION_MAPPING</a> if your Markdown files have a different extension, and use <span class="doxyComputerOutput">md</span> as the name of the parser). Each file is converted to a page (see the <a href="/web-doxygen/docs/pages/commands/#cmdpage">page</a> command for details). Doxygen will not create a dedicated page if the Markdown file starts with a dedicated command (a.o. <span class="doxyComputerOutput">\defgroup</span>, <span class="doxyComputerOutput">\dir</span>) to avoid creating an empty page when the file only contains directory or group documentation. A <span class="doxyComputerOutput">README.md</span> file in a subdirectory will be treated as directory documentation, unless it is explicitly overruled by a dedicated command (a.o. <span class="doxyComputerOutput">@page</span>, <span class="doxyComputerOutput">@mainpage</span>) to create a new page.</p>


<p>By default the name and title of the page are derived from the file name. If the file starts with a level 1 header however, it is used as the title of the page. If you specify a label for the header (as shown in <a href="#md_header_id">Header Id Attributes</a>) Doxygen will use that as the page name.</p>


<p>If the label is called <span class="doxyComputerOutput">index</span> or <span class="doxyComputerOutput">mainpage</span> Doxygen will put the documentation on the front page (<span class="doxyComputerOutput">index.html</span>).</p>


<p>Here is an example of a file <span class="doxyComputerOutput">README.md</span> that will appear as the main page when processed by Doxygen:</p>



<pre><code>My Main Page                         {#mainpage}
============

Documentation that will appear on the main page
</code></pre>


<p>If a page has a label you can link to it using <a href="/web-doxygen/docs/pages/commands/#cmdref">@ref</a> as is shown above. To refer to a markdown page without such label you can simple use the file name of the page, e.g.</p>



<pre><code>See [the other page](other.md) for more info.
</code></pre>


### Treatment of HTML blocks {#md_html_blocks}


<p>Markdown is quite strict in the way it processes block-level HTML:</p>

<blockquote class="doxyBlockQuote">

<p>block-level HTML elements — e.g. <span class="doxyComputerOutput">&lt;div&gt;</span>, <span class="doxyComputerOutput">&lt;table&gt;</span>, <span class="doxyComputerOutput">&lt;pre&gt;</span>, <span class="doxyComputerOutput">&lt;p&gt;</span>, etc. — must be separated from surrounding content by blank lines, and the start and end tags of the block should not be indented with tabs or spaces.</p>

</blockquote>

<p>Doxygen does not have this requirement, and will also process Markdown formatting inside such HTML blocks. The only exception is <span class="doxyComputerOutput">&lt;pre&gt;</span> blocks, which are passed untouched (handy for ASCII art).</p>


<p>Doxygen will not process Markdown formatting inside verbatim or code blocks, and in other sections that need to be processed without changes (for instance formulas or inline dot graphs).</p>


### Code Block Indentation {#mddox_code_blocks}


<p>Markdown allows both a single tab or 4 spaces to start a code block. Since Doxygen already replaces tabs by spaces before doing Markdown processing, the effect will only be same if TAB_SIZE in the configuration file has been set to 4. When it is set to a higher value spaces will be present in the code block. A lower value will prevent a single tab to be interpreted as the start of a code block.</p>


<p>With Markdown any block that is indented by 4 spaces (and 8 spaces inside lists) is treated as a code block. This indentation amount is absolute, i.e. counting from the start of the line.</p>


<p>Since Doxygen comments can appear at any indentation level that is required by the programming language, it uses a relative indentation instead. The amount of indentation is counted relative to the preceding paragraph. In case there is no preceding paragraph (i.e. you want to start with a code block), the minimal amount of indentation of the whole comment block is used as a reference.</p>


<p>In most cases this difference does not result in different output. Only if you play with the indentation of paragraphs the difference is noticeable:</p>



<pre><code>text

 text

  text

   code
</code></pre>


<p>In this case Markdown will put the word code in a code block, whereas Doxygen will treat it as normal text, since although the absolute indentation is 4, the indentation with respect to the previous paragraph is only 1.</p>


<p>Note that list markers are not counted when determining the relative indent:</p>



<pre><code>1.  Item1

    More text for item1

2.  Item2

        Code block for item2
</code></pre>


<p>For Item1 the indentation is 4 (when treating the list marker as whitespace), so the next paragraph "More text..." starts at the same indentation level and is therefore not seen as a code block.</p>


### Emphasis and strikethrough limits {#mddox_emph_spans}


<p>Unlike standard Markdown and GitHub Flavored Markdown Doxygen will not touch internal underscores or stars or tildes, so the following will appear as-is:</p>



<pre><code>a_nice_identifier
</code></pre>


<p>Furthermore, a <span class="doxyComputerOutput">*</span> or <span class="doxyComputerOutput">_</span> only starts an emphasis and a <span class="doxyComputerOutput">~</span> only starts a strikethrough if</p>


<ul class="doxyList ">
<li>it is followed by an alphanumerical character, and</li>
<li>it is preceded by a space, newline, or one the following characters <span class="doxyComputerOutput">&lt;{([,:;</span></li>
</ul>

<p>An emphasis or a strikethrough ends if</p>


<ul class="doxyList ">
<li>it is not followed by an alphanumerical character, and</li>
<li>it is not preceded by a space, newline, or one the following characters <span class="doxyComputerOutput">({[&lt;=+-\@</span></li>
</ul>

<p>The span of the emphasis or strikethrough is limited to a single paragraph.</p>


<p>Lastly, note that when you want to put emphasis on a piece of text at the start of a line by means of <span class="doxyComputerOutput">*</span>s within a C-style Doxygen comment block (i.e. <span class="doxyComputerOutput">/</span><span class="doxyComputerOutput">** ... *</span><span class="doxyComputerOutput">/</span>) that does not have leading <span class="doxyComputerOutput">*</span> as column "lineup", then Doxygen will see the sequence of <span class="doxyComputerOutput">*</span>s at the beginning of the line as "lineup" and not as emphasis. So the following will not render as bold:</p>



<pre><code>/**
 **this is not bold**
 */
</code></pre>


<p>however this will render as bold:</p>



<pre><code>/**
 * **this is bold**
 */
</code></pre>


### Code Spans Limits {#mddox_code_spans}


<p>Note that unlike standard Markdown, Doxygen leaves the following untouched.</p>



<pre><code>A `cool' word in a `nice' sentence.
</code></pre>


<p>In other words; a single quote cancels the special treatment of a code span wrapped in a pair of backtick characters. This extra restriction was added for backward compatibility reasons.</p>


<p>In case you want to have single quotes inside a code span, don't use one backtick but two backticks around the code span.</p>


### Lists Extensions {#mddox_lists}


<p>With Markdown two lists separated by an empty line are joined together into a single list which can be rather unexpected and many people consider it to be a bug. Doxygen, however, will make two separate lists as you would expect.</p>


<p>Example:</p>



<pre><code>- Item1 of list 1
- Item2 of list 1

1. Item1 of list 2
2. Item2 of list 2
</code></pre>


<p>With Markdown the actual numbers you use to mark the list have no effect on the HTML output Markdown produces. I.e. standard Markdown treats the following as one list with 3 numbered items:</p>



<pre><code>1. Item1
1. Item2
1. Item3
</code></pre>


<p>Doxygen however requires that the numbers used as marks are in strictly ascending order, so the above example would produce 3 lists with one item. An item with an equal or lower number than the preceding item, will start a new list. For example:</p>



<pre><code>1. Item1 of list 1
3. Item2 of list 1
2. Item1 of list 2
4. Item2 of list 2
</code></pre>


<p>will produce:</p>


<ol class="doxyList" type="1">
<li>Item1 of list 1</li>
<li>Item2 of list 1</li>
</ol>

<ol class="doxyList" type="1">
<li>Item1 of list 2</li>
<li>Item2 of list 2</li>
</ol>

<p>Historically Doxygen has an additional way to create numbered lists by using <span class="doxyComputerOutput">-#</span> markers:</p>



<pre><code>-# item1
-# item2
</code></pre>


<p>Lists with as indicator a checked or unchecked check box are by using <span class="doxyComputerOutput">- [ ]</span> or <span class="doxyComputerOutput">- [x]</span> or <span class="doxyComputerOutput">- [X]</span> as markers:</p>



<pre><code>- [ ] unchecked
- [x] checked
</code></pre>


### Use of asterisks {#mddox_stars}


<p>Special care has to be taken when using *'s in a comment block to start a list or make a ruler.</p>


<p>Doxygen will strip off any leading *'s from the comment before doing Markdown processing. So although the following works fine</p>



<pre><code>    /** A list:
     *  * item1
     *  * item2
     */
</code></pre>


<p>When you remove the leading *'s Doxygen will strip the other stars as well, making the list disappear!</p>


<p>Rulers created with *'s will not be visible at all. They only work in Markdown files.</p>


### Limits on markup scope {#mddox_limits}


<p>To avoid that a stray * or _ matches something many paragraphs later, and shows everything in between with emphasis, Doxygen limits the scope of a * and _ to a single paragraph.</p>


<p>For a code span, between the starting and ending backtick only two new lines are allowed.</p>


<p>Also for links there are limits; the link text, and link title each can contain only one new line, the URL may not contain any newlines.</p>


### Support for GitHub Alerts {#mddox_github_alerts}


<p>In the GitHub version of markdown there is the support for so called alerts, the syntax is similar to a one level block quote followed by <span class="doxyComputerOutput">[!&lt;alert&gt;]</span> where <span class="doxyComputerOutput">&lt;alert&gt;</span> can be one of <span class="doxyComputerOutput">note</span>, <span class="doxyComputerOutput">warning</span>, <span class="doxyComputerOutput">tip</span>, <span class="doxyComputerOutput">caution</span> or <span class="doxyComputerOutput">important</span>. In Doxygen these alerts are translated into normal Doxygen commands:</p>


<ul class="doxyList ">
<li><span class="doxyComputerOutput">&gt; [!note]</span> is translated to <a href="/web-doxygen/docs/pages/commands/#cmdnote">\note</a></li>
<li><span class="doxyComputerOutput">&gt; [!warning]</span> is translated to <a href="/web-doxygen/docs/pages/commands/#cmdwarning">\warning</a></li>
<li><span class="doxyComputerOutput">&gt; [!tip]</span> is translated to <a href="/web-doxygen/docs/pages/commands/#cmdremark">\remark</a></li>
<li><span class="doxyComputerOutput">&gt; [!caution]</span> is translated to <a href="/web-doxygen/docs/pages/commands/#cmdattention">\attention</a></li>
<li><span class="doxyComputerOutput">&gt; [!important]</span> is translated to <a href="/web-doxygen/docs/pages/commands/#cmdimportant">\important</a></li>
</ul>

<p>Example:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">&gt; [!note]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">&gt; The special text </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> the note</span></span></div>

</div>


<p>which will render as:</p>



:::info
<p>The special text for the note</p>
:::


## Debugging problems {#markdown_debug}


<p>When Doxygen parses the source code it first extracts the comments blocks, then passes these through the Markdown preprocessor. The output of the Markdown preprocessing consists of text with <a href="/web-doxygen/docs/pages/commands/#cmd_intro">special commands</a> and <a href="/web-doxygen/docs/pages/htmlcmds">HTML commands</a>. A second pass takes the output of the Markdown preprocessor and converts it into the various output formats.</p>


<p>During Markdown preprocessing no errors are produced. Anything that does not fit the Markdown syntax is simply passed on as-is. In the subsequent parsing phase this could lead to errors, which may not always be obvious as they are based on the intermediate format.</p>


<p>To see the result after Markdown processing you can run Doxygen with the <span class="doxyComputerOutput">-d Markdown</span> option. It will then print each comment block before and after Markdown processing.</p>

 
Go to the <a href="/docs/pages/lists/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
