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
<td valign="top"><a id="xmltag_c"></a> <code> &lt;c&gt;</code></td>
<td valign="top">Identifies inline text that should be rendered as a piece of code. Similar to using <code>&lt;tt&gt;</code>text<code>&lt;/tt&gt;</code>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_code"></a> <code> &lt;code&gt;</code></td>
<td valign="top">Set one or more lines of source code or program output. Note that this command behaves like <a href="/web-doxygen/docs/pages/commands/#cmdcode">\code</a> ... <a href="/web-doxygen/docs/pages/commands/#cmdendcode">\endcode</a> for C# code, but it behaves like the HTML equivalent <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_CODE">&lt;CODE&gt;</a>...<a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_endCODE">&lt;/CODE&gt;</a> for other languages.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_description"></a> <code> &lt;description&gt;</code></td>
<td valign="top">Part of a <a href="#xmltag_list">&lt;list&gt;</a> command, describes an item.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_example"></a> <code> &lt;example&gt;</code></td>
<td valign="top">Marks a block of text as an example, ignored by Doxygen.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_exception"></a> <code> &lt;exception cref="member"&gt;</code></td>
<td valign="top">Identifies the exception a method can throw.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_include"></a> <code> &lt;include&gt;</code></td>
<td valign="top">Can be used to import a piece of XML from an external file. Ignored by Doxygen at the moment.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_inheritdoc"></a> <code> &lt;inheritdoc&gt;</code></td>
<td valign="top">Can be used to insert the documentation of a member of a base class into the documentation of a member of a derived class that reimplements it.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_item"></a> <code> &lt;item&gt;</code></td>
<td valign="top">List item. Can only be used inside a <a href="#xmltag_list">&lt;list&gt;</a> context.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_list"></a> <code> &lt;list type="type"&gt;</code></td>
<td valign="top">Starts a list, supported types are <code>bullet</code> or <code>number</code> and <code>table</code>. A list consists of a number of <code>&lt;item&gt;</code> tags. A list of type table, is a two column table which can have a header.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_listheader"></a> <code> &lt;listheader&gt;</code></td>
<td valign="top">Starts the header of a list of type "table".</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_para"></a> <code> &lt;para&gt;</code></td>
<td valign="top">Identifies a paragraph of text.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_param"></a> <code> &lt;param name="paramName"&gt;</code></td>
<td valign="top">Marks a piece of text as the documentation for parameter "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdparam">\param</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_paramref"></a> <code> &lt;paramref name="paramName"&gt;</code></td>
<td valign="top">Refers to a parameter with name "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmda">\a</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_permission"></a> <code> &lt;permission&gt;</code></td>
<td valign="top">Identifies the security accessibility of a member. Ignored by Doxygen.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_remarks"></a> <code> &lt;remarks&gt;</code></td>
<td valign="top">Identifies the detailed description.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_returns"></a> <code> &lt;returns&gt;</code></td>
<td valign="top">Marks a piece of text as the return value of a function or method. Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdreturn">\return</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_see"></a> <code> &lt;see cref="member"&gt;</code></td>
<td valign="top">Refers to a member. Similar to <a href="/web-doxygen/docs/pages/commands/#cmdref">\ref</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_seealso"></a> <code> &lt;seealso cref="member"&gt;</code></td>
<td valign="top">Starts a "See also" section referring to "member". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdsa">\sa</a> member.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_summary"></a> <code> &lt;summary&gt;</code></td>
<td valign="top">In case this tag is used outside a <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_DETAILS">&lt;DETAILS&gt;</a> tag this tag identifies the brief description. Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdbrief">\brief</a>. In case this tag is used inside a <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_DETAILS">&lt;DETAILS&gt;</a> tag this tag identifies the heading of the <a href="/web-doxygen/docs/pages/htmlcmds/#htmltag_DETAILS">&lt;DETAILS&gt;</a> tag.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_term"></a> <code> &lt;term&gt;</code></td>
<td valign="top">Part of a <a href="#xmltag_list">&lt;list&gt;</a> command.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_typeparam"></a> <code> &lt;typeparam name="paramName"&gt;</code></td>
<td valign="top">Marks a piece of text as the documentation for type parameter "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmdparam">\param</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_typeparamref"></a> <code>&lt;typeparamref name="paramName"&gt;</code></td>
<td valign="top">Refers to a parameter with name "paramName". Similar to using <a href="/web-doxygen/docs/pages/commands/#cmda">\a</a>.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_value"></a> <code> &lt;value&gt;</code></td>
<td valign="top">Identifies a property. Ignored by Doxygen.</td>
</tr>
<tr>
<td valign="top"><a id="xmltag_CDATA"></a> <code> &lt;![CDATA[...]]&gt;</code></td>
<td valign="top">The text inside this tag (on the ...) is handled as normal Doxygen comment except for the XML special characters <code>&lt;</code>, <code>&gt;</code> and <code>&amp;</code> that are used as if they were escaped.</td>
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
