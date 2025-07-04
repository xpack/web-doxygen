---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/crawlmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Crawlmap` Class Reference



## Declaration

<div class="doxyDeclaration">
class Crawlmap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/sitemap-h">src/sitemap.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for index generators. <a href="/web-doxygen/docs/api/classes/indexintf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78c2eb564885d3bde9d85f7aa1dcb42">Crawlmap</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4062ccd2fd1a181e83949965d04d6c6e">~Crawlmap</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07627e75c6fe9c87685b12be8ac61f5a">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad896b4b6814a6fba6e7160c83ad45f54">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc3f72d36350cd6bf558ce297b88066">incContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91611c62bf85d591111678c8217b1c2e">decContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd9ba2dc2586e4dcd08ea7da6d93b69">addContentsItem</a> (bool isDir, const QCString &amp;name, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool separateIndex, bool addToNavIndex, const Definition *def, const QCString &amp;nameAsHtml)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14459516bd2c63e2637f45b668fd676">addIndexItem</a> (const Definition *context, const MemberDef *md, const QCString &amp;sectionAnchor, const QCString &amp;title)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafc27f940e1c9768a97427452dd1f86b">addIndexFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336cb29118e9712e74cd85413b132258">addImageFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f03dbfb52659040cdc7d72380ae981e">addStyleSheetFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/crawlmap/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b40686a6238e53c3979fb36ba18a18">crawlFileName</a> = "doxygen_crawl"</td>
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


<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Crawlmap() {#ac78c2eb564885d3bde9d85f7aa1dcb42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Crawlmap::Crawlmap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>, definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac78c2eb564885d3bde9d85f7aa1dcb42">92</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ac78c2eb564885d3bde9d85f7aa1dcb42">Crawlmap::Crawlmap</a>() : <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/crawlmap/private">Private</a>&gt;()) {}</span></span></div>

</div>


<p>Reference <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>.</p>


<p>Referenced by <a href="#a4062ccd2fd1a181e83949965d04d6c6e">~Crawlmap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Crawlmap() {#a4062ccd2fd1a181e83949965d04d6c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Crawlmap::~Crawlmap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<p>Reference <a href="#ac78c2eb564885d3bde9d85f7aa1dcb42">Crawlmap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addContentsItem() {#a1dd9ba2dc2586e4dcd08ea7da6d93b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::addContentsItem (bool isDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool separateIndex, bool addToNavIndex, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; nameAsHtml)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>, definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1dd9ba2dc2586e4dcd08ea7da6d93b69">140</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1dd9ba2dc2586e4dcd08ea7da6d93b69">Crawlmap::addContentsItem</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())      </span><span class="doxyHighlightComment">// made file optional param and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightComment">// don't place links in crawl file imported</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightComment">// by tags</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (file[0]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> || file[0]==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// special markers for user defined URLs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">      link+=&amp;file[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> currFile = file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(currFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> currAnc = anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      link += currFile.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!currAnc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">        link += </span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">        link += currAnc.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.push_back(link);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### addImageFile() {#a336cb29118e9712e74cd85413b132258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::addImageFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a336cb29118e9712e74cd85413b132258">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a336cb29118e9712e74cd85413b132258">addImageFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name){}</span></span></div>

</div>

</div>
</div>

### addIndexFile() {#aafc27f940e1c9768a97427452dd1f86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::addIndexFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>, definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aafc27f940e1c9768a97427452dd1f86b">133</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aafc27f940e1c9768a97427452dd1f86b">Crawlmap::addIndexFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.push_back(fn.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### addIndexItem() {#af14459516bd2c63e2637f45b668fd676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::addIndexItem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * context, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sectionAnchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>, definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af14459516bd2c63e2637f45b668fd676">195</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af14459516bd2c63e2637f45b668fd676">Crawlmap::addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *context, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sectionAnchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context &amp;&amp; md) </span><span class="doxyHighlightComment">// member</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cfname  = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor  = !sectionAnchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? sectionAnchor : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ref     = <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>(cfname, anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.push_back(ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context) </span><span class="doxyHighlightComment">// container</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> contRef = context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ref = <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>(contRef,sectionAnchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.push_back(ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>, <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### addStyleSheetFile() {#a3f03dbfb52659040cdc7d72380ae981e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::addStyleSheetFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f03dbfb52659040cdc7d72380ae981e">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3f03dbfb52659040cdc7d72380ae981e">addStyleSheetFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name){}</span></span></div>

</div>

</div>
</div>

### decContentsDepth() {#a91611c62bf85d591111678c8217b1c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::decContentsDepth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91611c62bf85d591111678c8217b1c2e">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a91611c62bf85d591111678c8217b1c2e">decContentsDepth</a>(){}</span></span></div>

</div>

</div>
</div>

### finalize() {#ad896b4b6814a6fba6e7160c83ad45f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::finalize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>, definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad896b4b6814a6fba6e7160c83ad45f54">118</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad896b4b6814a6fba6e7160c83ad45f54">Crawlmap::finalize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  std::sort(<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.begin(),<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.erase(std::unique(<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.begin(),<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.end()),<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlLinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight"> &lt;&lt; s &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/body&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/html&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl.flush();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlFile.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>.</p>

</div>
</div>

### incContentsDepth() {#a7bc3f72d36350cd6bf558ce297b88066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::incContentsDepth ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bc3f72d36350cd6bf558ce297b88066">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7bc3f72d36350cd6bf558ce297b88066">incContentsDepth</a>(){}</span></span></div>

</div>

</div>
</div>

### initialize() {#a07627e75c6fe9c87685b12be8ac61f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Crawlmap::initialize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>, definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07627e75c6fe9c87685b12be8ac61f5a">95</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a07627e75c6fe9c87685b12be8ac61f5a">Crawlmap::initialize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> + <a href="#af7b40686a6238e53c3979fb36ba18a18">crawlFileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlFile = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlFile.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl.setStream(&amp;<a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawlFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!DOCTYPE html PUBLIC \"-//W3C//DTD XHTML 1 Transitional//EN\" \"https://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;html xmlns=\"http://www.w3.org/1999/xhtml\" lang=\""</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trISOLang() + </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;head&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;Validator / crawler helper&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;meta http-equiv=\"Content-Type\" content=\"text/xhtml;charset=UTF-8\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;meta http-equiv=\"X-UA-Compatible\" content=\"IE=11\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;meta name=\"generator\" content=\"Doxygen "</span><span class="doxyHighlight"> + getDoxygenVersion() + </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;meta name=\"viewport\" content=\"width=device-width, initial-scale=1\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/head&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>-&gt;crawl &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;body&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="#af7b40686a6238e53c3979fb36ba18a18">crawlFileName</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a960233e4b7f3e8c8f11acf1f9a8e767a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; Crawlmap::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a960233e4b7f3e8c8f11acf1f9a8e767a">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1dd9ba2dc2586e4dcd08ea7da6d93b69">addContentsItem</a>, <a href="#aafc27f940e1c9768a97427452dd1f86b">addIndexFile</a>, <a href="#af14459516bd2c63e2637f45b668fd676">addIndexItem</a>, <a href="#ac78c2eb564885d3bde9d85f7aa1dcb42">Crawlmap</a>, <a href="#ad896b4b6814a6fba6e7160c83ad45f54">finalize</a> and <a href="#a07627e75c6fe9c87685b12be8ac61f5a">initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### crawlFileName {#af7b40686a6238e53c3979fb36ba18a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString Crawlmap::crawlFileName = "doxygen_crawl"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7b40686a6238e53c3979fb36ba18a18">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af7b40686a6238e53c3979fb36ba18a18">crawlFileName</a> = </span><span class="doxyHighlightStringLiteral">"doxygen_crawl"</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a07627e75c6fe9c87685b12be8ac61f5a">initialize</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
