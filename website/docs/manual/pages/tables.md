---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/tables
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - page

---

<div class="doxyPage">

# Including tables




<p>Doxygen supports two ways to put tables in the documentation.</p>


<p>The easiest is to use the Markdown format as shown in <a href="/web-doxygen/docs/pages/markdown/#markdown_extra">Markdown Extensions</a> section <a href="/web-doxygen/docs/pages/markdown/#md_tables">Tables</a>.</p>


<p>Although this format is easy to use and read, it is also rather limited. It supports only a simple grid of cells, while each cell is a single line of plain text.</p>


<p>For more complex tables the HTML syntax can be used. Doxygen will process such tables and translate them to the various output formats (at least for the formats that do support tables such as HTML and <code>{\LaTeX}</code>).</p>


<p>Note a table should at least contain 1 row (<span class="doxyComputerOutput">&lt;tr&gt;</span>) and in case a <span class="doxyComputerOutput">&lt;caption&gt;</span> is used the <span class="doxyComputerOutput">&lt;caption&gt;</span> should precede the first row.</p>


<p>Here is an example of a complex table:</p>



<pre><code>&lt;table&gt;
&lt;caption id="multi_row"&gt;Complex table&lt;/caption&gt;
&lt;tr&gt;&lt;th&gt;Column 1                      &lt;th&gt;Column 2        &lt;th&gt;Column 3
&lt;tr&gt;&lt;td rowspan="2"&gt;cell row=1+2,col=1&lt;td&gt;cell row=1,col=2&lt;td&gt;cell row=1,col=3
&lt;tr&gt;&lt;td rowspan="2"&gt;cell row=2+3,col=2                    &lt;td&gt;cell row=2,col=3
&lt;tr&gt;&lt;td&gt;cell row=3,col=1                                  &lt;td rowspan="2"&gt;cell row=3+4,col=3
&lt;tr&gt;&lt;td colspan="2"&gt;cell row=4,col=1+2
&lt;tr&gt;&lt;td&gt;cell row=5,col=1              &lt;td colspan="2"&gt;cell row=5,col=2+3
&lt;tr&gt;&lt;td colspan="2" rowspan="2"&gt;cell row=6+7,col=1+2      &lt;td&gt;cell row=6,col=3
&lt;tr&gt;                                                      &lt;td&gt;cell row=7,col=3
&lt;tr&gt;&lt;td&gt;cell row=8,col=1              &lt;td&gt;cell row=8,col=2\n
  &lt;table&gt;
    &lt;tr&gt;&lt;td&gt;Inner cell row=1,col=1&lt;td&gt;Inner cell row=1,col=2
    &lt;tr&gt;&lt;td&gt;Inner cell row=2,col=1&lt;td&gt;Inner cell row=2,col=2
  &lt;/table&gt;
  &lt;td&gt;cell row=8,col=3
  &lt;ul&gt;
    &lt;li&gt;Item 1
    &lt;li&gt;Item 2
  &lt;/ul&gt;
&lt;/table&gt;
</code></pre>


<p>It has a caption, table heading, various row and column spans, a nested table as one of the cells, and a item list in another cell.</p>


<p>Note that the end tags (like <span class="doxyComputerOutput">&lt;/td&gt;</span>) are left out in the example above. This is allowed, and in the HTML output Doxygen will add the end tags again.</p>


<p>The output will look as follows:</p>


<table class="doxyTable">
<caption id="tables_1multi_row">Complex table</caption>
<tr>
<th>Column 1</th>
<th>Column 2</th>
<th>Column 3</th>
</tr>
<tr>
<td rowspan="2">cell row=1+2,col=1</td>
<td>cell row=1,col=2</td>
<td>cell row=1,col=3</td>
</tr>
<tr>
<td rowspan="2">cell row=2+3,col=2</td>
<td>cell row=2,col=3</td>
</tr>
<tr>
<td>cell row=3,col=1</td>
<td rowspan="2">cell row=3+4,col=3</td>
</tr>
<tr>
<td colspan="2">cell row=4,col=1+2</td>
</tr>
<tr>
<td>cell row=5,col=1</td>
<td colspan="2">cell row=5,col=2+3</td>
</tr>
<tr>
<td colspan="2" rowspan="2">cell row=6+7,col=1+2</td>
<td>cell row=6,col=3</td>
</tr>
<tr>
<td>cell row=7,col=3</td>
</tr>
<tr>
<td>cell row=8,col=1</td>
<td>cell row=8,col=2
<br/>

<table class="doxyTable">
<tr>
<td>Inner cell row=1,col=1</td>
<td>Inner cell row=1,col=2</td>
</tr>
<tr>
<td>Inner cell row=2,col=1</td>
<td>Inner cell row=2,col=2</td>
</tr>
</table></td>
<td>cell row=8,col=3

<ul class="doxyList ">
<li>Item 1</li>
<li>Item 2</li>
</ul></td>
</tr>
</table>

<p>One can refer to the caption of the table using <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a> using the caption's id as the label.</p>

 
Go to the <a href="/docs/pages/diagrams/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
