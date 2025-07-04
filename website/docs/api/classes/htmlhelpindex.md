---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/htmlhelpindex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HtmlHelpIndex` Class Reference

<p>A helper class for <a href="/web-doxygen/docs/api/classes/htmlhelp">HtmlHelp</a> that manages a two level index in alphabetical order. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class HtmlHelpIndex { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41b0639266dc74951a9a77732749e56">HtmlHelpIndex</a> (HtmlHelpRecoder &amp;recoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b68b2ca104803c3a6dc76a18aa05f13">~HtmlHelpIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d9d3885e2b3e6a8587e6c59e02afa0">addItem</a> (const QCString &amp;first, const QCString &amp;second, const QCString &amp;url, const QCString &amp;anchor, bool hasLink, bool reversed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90f49f18773a8f5949d7908575996e71">writeFields</a> (std::ostream &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8b9fea4dc8f00945e141c0621fa6b1">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap</a>&lt; <a href="/web-doxygen/docs/api/structs/indexfield">IndexField</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlhelprecoder">HtmlHelpRecoder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper class for <a href="/web-doxygen/docs/api/classes/htmlhelp">HtmlHelp</a> that manages a two level index in alphabetical order.</p>

<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HtmlHelpIndex() {#aa41b0639266dc74951a9a77732749e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelpIndex::HtmlHelpIndex (<a href="/web-doxygen/docs/api/classes/htmlhelprecoder">HtmlHelpRecoder</a> &amp; recoder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Constructs a new <a href="/web-doxygen/docs/api/classes/htmlhelp">HtmlHelp</a> index</p>


<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa41b0639266dc74951a9a77732749e56">130</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa41b0639266dc74951a9a77732749e56">HtmlHelpIndex::HtmlHelpIndex</a>(<a href="/web-doxygen/docs/api/classes/htmlhelprecoder">HtmlHelpRecoder</a> &amp;recoder) : <a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>(recoder)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>.</p>


<p>Referenced by <a href="#a0b68b2ca104803c3a6dc76a18aa05f13">~HtmlHelpIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~HtmlHelpIndex() {#a0b68b2ca104803c3a6dc76a18aa05f13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelpIndex::~HtmlHelpIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Destroys the <a href="/web-doxygen/docs/api/classes/htmlhelp">HtmlHelp</a> index</p>


<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<p>Reference <a href="#aa41b0639266dc74951a9a77732749e56">HtmlHelpIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addItem() {#a70d9d3885e2b3e6a8587e6c59e02afa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelpIndex::addItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; level1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; level2, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; url, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool hasLink, bool reversed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Stores an item in the index if it is not already present. Items are stored in alphabetical order, by sorting on the concatenation of <em>level1</em> and <em>level2</em> (if present).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">level1</td>
<td class="doxyParamItemDescription"><p>the string at level 1 in the index.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">level2</td>
<td class="doxyParamItemDescription"><p>the string at level 2 in the index (or 0 if not applicable).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">url</td>
<td class="doxyParamItemDescription"><p>the url of the documentation (without .html extension).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">anchor</td>
<td class="doxyParamItemDescription"><p>the anchor of the documentation within the page.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">hasLink</td>
<td class="doxyParamItemDescription"><p>if true, the url (without anchor) can be used in the level1 item, when writing the header of a list of level2 items.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">reversed</td>
<td class="doxyParamItemDescription"><p>TRUE if level1 is the member name and level2 the compound name.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70d9d3885e2b3e6a8587e6c59e02afa0">151</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a70d9d3885e2b3e6a8587e6c59e02afa0">HtmlHelpIndex::addItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;level1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;level2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;url,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasLink,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> reversed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(R</span><span class="doxyHighlightStringLiteral">"(@\d+)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  std::string key = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(level1,</span><span class="doxyHighlightStringLiteral">"?"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quest;"</span><span class="doxyHighlight">).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!level2.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) key+= std::string(</span><span class="doxyHighlightStringLiteral">"?"</span><span class="doxyHighlight">) + <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(level2,</span><span class="doxyHighlightStringLiteral">"?"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"&amp;quest;"</span><span class="doxyHighlight">).<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(key,re)) </span><span class="doxyHighlightComment">// skip anonymous stuff</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string key_anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    key_anchor = key+anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    key_anchor = key;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>.add(key_anchor.c_str(),key.c_str(),url,anchor,hasLink,reversed);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>

</div>
</div>

### size() {#a0d8b9fea4dc8f00945e141c0621fa6b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t HtmlHelpIndex::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d8b9fea4dc8f00945e141c0621fa6b1">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a0d8b9fea4dc8f00945e141c0621fa6b1">size</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>.size(); }</span></span></div>

</div>


<p>Reference <a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>.</p>

</div>
</div>

### writeFields() {#a90f49f18773a8f5949d7908575996e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelpIndex::writeFields (std::ostream &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Writes the sorted list of index items into a html like list.</p>


<p>An list of calls with <span class="doxyComputerOutput">name = level1,level2</span> as follows:</p>



<pre><code>  a1,b1
  a1,b2
  a2,b1
  a2,b2
  a3
  a4,b1
</code></pre>


<p>Will result in the following list:</p>



<pre><code>  a1       -&gt; link to url if hasLink==TRUE
    b1     -&gt; link to url#anchor
    b2     -&gt; link to url#anchor
  a2       -&gt; link to url if hasLink==TRUE
    b1     -&gt; link to url#anchor
    b2     -&gt; link to url#anchor
  a3       -&gt; link to url if hasLink==TRUE
  a4       -&gt; link to url if hasLink==TRUE
    b1     -&gt; link to url#anchor
</code></pre>


<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90f49f18773a8f5949d7908575996e71">238</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>(std::ostream &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  std::stable_sort(std::begin(<a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">            std::end(<a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">            [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e2) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(e1-&gt;name,e2-&gt;name)&lt;0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> prevLevel1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> level2Started=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::begin(<a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>); it!=std::end(<a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>); ++it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;f = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> level1,level2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = f-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      level1 = f-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      level2 = f-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(f-&gt;name.length()-i-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      level1  = f-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// finish old list at level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level2Started) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      level2Started=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// &lt;Antony&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Added this code so that an item with only one subitem is written</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// without any subitem.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// For example:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//   a1, b1 -&gt; will create only a1, not separate subitem for b1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//   a2, b2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//   a2, b3</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nextLevel1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it_next = std::next(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it_next!=std::end(<a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fnext = *it_next;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = fnext-&gt;name.find(</span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&lt;0) j=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">        nextLevel1 = fnext-&gt;name.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(level1 == prevLevel1 || level1 == nextLevel1))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">        level2 = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      prevLevel1 = level1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// &lt;/Antony&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level2.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;LI&gt;&lt;OBJECT type=\"text/sitemap\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Local\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#aa9dc1225d5dff26cbdf7521f3d2d5ebe">field2URL</a>(f.get(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Name\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>(<a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>.recode(level1)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f-&gt;link)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;LI&gt;&lt;OBJECT type=\"text/sitemap\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Local\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#aa9dc1225d5dff26cbdf7521f3d2d5ebe">field2URL</a>(f.get(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Name\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>(<a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>.recode(level1)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;LI&gt;&lt;OBJECT type=\"text/sitemap\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"See Also\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>.recode(level1)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Name\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>(<a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>.recode(level1)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!level2Started &amp;&amp; !level2.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// start new list at level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      level2Started=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level2Started &amp;&amp; level2.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// end list at level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">      level2Started=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level2Started)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;LI&gt;&lt;OBJECT type=\"text/sitemap\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Local\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#aa9dc1225d5dff26cbdf7521f3d2d5ebe">field2URL</a>(f.get(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Name\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>(<a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>.recode(level2)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level2Started) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#a360a61caf065b5b140e9275aa2253a8b">convertToHtmlAndTruncate</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp/#aa9dc1225d5dff26cbdf7521f3d2d5ebe">field2URL</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>, <a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_map {#ab8f0ee0b1ceeaecd88427d7416f3f7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkedMap&lt;IndexField&gt; HtmlHelpIndex::m_map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap&lt;IndexField&gt;</a> <a href="#ab8f0ee0b1ceeaecd88427d7416f3f7d2">m_map</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a70d9d3885e2b3e6a8587e6c59e02afa0">addItem</a>, <a href="#a0d8b9fea4dc8f00945e141c0621fa6b1">size</a> and <a href="#a90f49f18773a8f5949d7908575996e71">writeFields</a>.</p>

</div>
</div>

### m\_recoder {#a628c35fd57a70fd8325d8fcac8f65103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelpRecoder&amp; HtmlHelpIndex::m_recoder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a628c35fd57a70fd8325d8fcac8f65103">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/htmlhelprecoder">HtmlHelpRecoder</a> &amp;<a href="#a628c35fd57a70fd8325d8fcac8f65103">m_recoder</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa41b0639266dc74951a9a77732749e56">HtmlHelpIndex</a> and <a href="#a90f49f18773a8f5949d7908575996e71">writeFields</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
