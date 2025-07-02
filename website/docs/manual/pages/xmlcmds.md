---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /pages/xmlcmds
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - page
toc_max_heading_level: 4

---

<div class="doxyPage">

# XML Commands




Doxygen supports most of the XML commands that are typically used in C# code comments. The XML tags are defined in Appendix D of the <a href="https://ecma-international.org/publications-and-standards/standards/ecma-334/">ECMA-334</a> standard, which defines the C# language. Unfortunately, the specification is not very precise and a number of the examples given are of poor quality.

Here is the list of tags supported by Doxygen:

<table class="doxyTable">
<tr>
<th align="left">XML Command</th>
<th align="left">Description</th>
</tr>
<tr>
<td valign="top"><a id="xmltag_c"></a> <span class="doxyComputerOutput"> &lt;c&gt;</span></td>
<td valign="top">Identifies inline text that should be rendered as a piece of code. Similar to using <span class="doxyComputerOutput">&lt;tt&gt;</span>text<span class="doxyComputerOutput">&lt;/tt&gt;</span>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_code"></a> <span class="doxyComputerOutput"> &lt;code&gt;</span></td>
<td valign="top">Set one or more lines of source code or program output. Note that this command behaves like <a href="/web-doxygen/docs/pages/commands/#cmdcode">\code</a> ... <a href="/web-doxygen/docs/pages/commands/#cmdendcode">\endcode</a> for C# code, but it behaves like the HTML equivalent <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_CODE">&lt;CODE&gt;</a>...<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endCODE">&lt;/CODE&gt;</a> for other languages.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_description"></a> <span class="doxyComputerOutput"> &lt;description&gt;</span></td>
<td valign="top">Part of a <a href="#xmltag_list">&lt;list&gt;</a> command, describes an item.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_example"></a> <span class="doxyComputerOutput"> &lt;example&gt;</span></td>
<td valign="top">Marks a block of text as an example, ignored by Doxygen.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_exception"></a> <span class="doxyComputerOutput"> &lt;exception cref="member"&gt;</span></td>
<td valign="top">Identifies the exception a method can throw.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_include"></a> <span class="doxyComputerOutput"> &lt;include&gt;</span></td>
<td valign="top">Can be used to import a piece of XML from an external file. Ignored by Doxygen at the moment.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_inheritdoc"></a> <span class="doxyComputerOutput"> &lt;inheritdoc&gt;</span></td>
<td valign="top">Can be used to insert the documentation of a member of a base class into the documentation of a member of a derived class that reimplements it.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_item"></a> <span class="doxyComputerOutput"> &lt;item&gt;</span></td>
<td valign="top">List item. Can only be used inside a <a href="#xmltag_list">&lt;list&gt;</a> context.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_list"></a> <span class="doxyComputerOutput"> &lt;list type="type"&gt;</span></td>
<td valign="top">Starts a list, supported types are <span class="doxyComputerOutput">bullet</span> or <span class="doxyComputerOutput">number</span> and <span class="doxyComputerOutput">table</span>. A list consists of a number of <span class="doxyComputerOutput">&lt;item&gt;</span> tags. A list of type table, is a two column table which can have a header.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_listheader"></a> <span class="doxyComputerOutput"> &lt;listheader&gt;</span></td>
<td valign="top">Starts the header of a list of type "table".</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_para"></a> <span class="doxyComputerOutput"> &lt;para&gt;</span></td>
<td valign="top">Identifies a paragraph of text.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_param"></a> <span class="doxyComputerOutput"> &lt;param name="paramName"&gt;</span></td>
<td valign="top">Marks a piece of text as the documentation for parameter "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdparam">\param</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_paramref"></a> <span class="doxyComputerOutput"> &lt;paramref name="paramName"&gt;</span></td>
<td valign="top">Refers to a parameter with name "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmda">\a</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_permission"></a> <span class="doxyComputerOutput"> &lt;permission&gt;</span></td>
<td valign="top">Identifies the security accessibility of a member. Ignored by Doxygen.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_remarks"></a> <span class="doxyComputerOutput"> &lt;remarks&gt;</span></td>
<td valign="top">Identifies the detailed description.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_returns"></a> <span class="doxyComputerOutput"> &lt;returns&gt;</span></td>
<td valign="top">Marks a piece of text as the return value of a function or method. Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdreturn">\return</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_see"></a> <span class="doxyComputerOutput"> &lt;see cref="member"&gt;</span></td>
<td valign="top">Refers to a member. Similar to <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_seealso"></a> <span class="doxyComputerOutput"> &lt;seealso cref="member"&gt;</span></td>
<td valign="top">Starts a "See also" section referring to "member". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdsa">\sa</a> member.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_summary"></a> <span class="doxyComputerOutput"> &lt;summary&gt;</span></td>
<td valign="top">In case this tag is used outside a <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_DETAILS">&lt;DETAILS&gt;</a> tag this tag identifies the brief description. Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdbrief">\brief</a>. In case this tag is used inside a <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_DETAILS">&lt;DETAILS&gt;</a> tag this tag identifies the heading of the <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_DETAILS">&lt;DETAILS&gt;</a> tag.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_term"></a> <span class="doxyComputerOutput"> &lt;term&gt;</span></td>
<td valign="top">Part of a <a href="#xmltag_list">&lt;list&gt;</a> command.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_typeparam"></a> <span class="doxyComputerOutput"> &lt;typeparam name="paramName"&gt;</span></td>
<td valign="top">Marks a piece of text as the documentation for type parameter "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdparam">\param</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_typeparamref"></a> <span class="doxyComputerOutput">&lt;typeparamref name="paramName"&gt;</span></td>
<td valign="top">Refers to a parameter with name "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmda">\a</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_value"></a> <span class="doxyComputerOutput"> &lt;value&gt;</span></td>
<td valign="top">Identifies a property. Ignored by Doxygen.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_CDATA"></a> <span class="doxyComputerOutput"> &lt;![CDATA[...]]&gt;</span></td>
<td valign="top">The text inside this tag (on the ...) is handled as normal Doxygen comment except for the XML special characters <span class="doxyComputerOutput">&lt;</span>, <span class="doxyComputerOutput">&gt;</span> and <span class="doxyComputerOutput">&amp;</span> that are used as if they were escaped.</td>
</tr>
</table>

Here is an example of a typical piece of code using some of the above commands:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// &lt;summary&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// A search engine.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">/// &lt;/summary&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight">Engine</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// &lt;summary&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// The Search method takes a series of parameters to specify the search criterion</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// and returns a dataset containing the result set.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// &lt;/summary&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// &lt;param name="connectionString"&gt;the connection string to connect to the</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// database holding the content to search&lt;/param&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// &lt;param name="maxRows"&gt;The maximum number of rows to</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// return in the result set&lt;/param&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// &lt;param name="searchString"&gt;The text that we are searching for&lt;/param&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// &lt;returns&gt;A DataSet instance containing the matching rows. It contains a maximum</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightComment">  /// number of rows specified by the maxRows parameter&lt;/returns&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">public</span><span class="doxyHighlight"> DataSet Search(</span><span class="doxyHighlightKeywordType">string</span><span class="doxyHighlight"> connectionString, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxRows, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> searchString)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    DataSet ds = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> DataSet();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ds;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

 
Go to the <a href="/docs/pages/emojisup/">next</a> section or return to the
 <a href="/docs/">index</a>.


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
