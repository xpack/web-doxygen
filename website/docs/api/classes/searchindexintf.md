---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/searchindexintf
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `SearchIndexIntf` Class Reference

<p>Abstract proxy interface for non-javascript based search indices. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class SearchIndexIntf { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/searchindex-h">src/searchindex.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3cf24c21e3eb2a27011711a7040e6c2">SearchIndexVariant</a> = std::variant&lt; std::monostate, <a href="/web-doxygen/docs/api/classes/searchindex">SearchIndex</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal">SearchIndexExternal</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09bb6fc7de0cb12011dbaad5645eb00f">SearchIndexIntf</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ba48887ebb27a765bc9f36d4339c77">enabled</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa7df3f4440a0b3adf710fd312195e5">setCurrentDoc</a> (const Definition *ctx, const QCString &amp;anchor, bool isSourceFile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c73d699dbfbee68fb730a3246965c1">addWord</a> (const QCString &amp;word, bool hiPriority)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e841df6d6d7f85bec747ab0aedb038">write</a> (const QCString &amp;file)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5dc87e5ce9c0a92c53fc3978f6ef31e">setKind</a> (Kind k)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc55c10e28715c334a3e51fb5003c08">kind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad3cf24c21e3eb2a27011711a7040e6c2">SearchIndexVariant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a></td>
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

<p>Abstract proxy interface for non-javascript based search indices.</p>


<p>It forwards calls to either <a href="/web-doxygen/docs/api/classes/searchindex">SearchIndex</a> or <a href="/web-doxygen/docs/api/classes/searchindexexternal">SearchIndexExternal</a> depending on the <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a> passed during construction.</p>

<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxySectionDef">

## Public Member Typedefs

### SearchIndexVariant {#ad3cf24c21e3eb2a27011711a7040e6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SearchIndexIntf::SearchIndexVariant =  std::variant&lt;std::monostate,SearchIndex,SearchIndexExternal&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00143">143</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3cf24c21e3eb2a27011711a7040e6c2">143</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad3cf24c21e3eb2a27011711a7040e6c2">SearchIndexVariant</a> = std::variant&lt;std::monostate,SearchIndex,SearchIndexExternal&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Kind {#ade3dd4c1f8bc6487f0f3dccba5c6f9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum SearchIndexIntf::Kind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Disabled<a id="ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Internal<a id="ade3dd4c1f8bc6487f0f3dccba5c6f9eaa4e9f47fa9f92dd54889f2e95261a1041"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">External<a id="ade3dd4c1f8bc6487f0f3dccba5c6f9eaa507071eac5d8808e1e91570d8c20523b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00144">144</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a> { <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a>, <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa4e9f47fa9f92dd54889f2e95261a1041">Internal</a>, <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa507071eac5d8808e1e91570d8c20523b">External</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SearchIndexIntf() {#a09bb6fc7de0cb12011dbaad5645eb00f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchIndexIntf::SearchIndexIntf ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00145">145</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09bb6fc7de0cb12011dbaad5645eb00f">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a09bb6fc7de0cb12011dbaad5645eb00f">SearchIndexIntf</a>() : <a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a>(<a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a>) {}</span></span></div>

</div>


References <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a> and <a href="#ab3bc6742416b3472eebee53632757df2">m&#95;kind</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addWord() {#a40c73d699dbfbee68fb730a3246965c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndexIntf::addWord (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; word, bool hiPriority)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00159">159</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40c73d699dbfbee68fb730a3246965c1">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a40c73d699dbfbee68fb730a3246965c1">addWord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;word,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hiPriority)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;SearchIndex&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get&lt;SearchIndex&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>).addWord(word,hiPriority);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;SearchIndexExternal&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get&lt;SearchIndexExternal&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>).addWord(word,hiPriority);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a950d158c195ac3eef237b9a6ae7a5265">m&#95;variant</a>.
</div>
</div>

### enabled() {#a99ba48887ebb27a765bc9f36d4339c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SearchIndexIntf::enabled ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00146">146</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99ba48887ebb27a765bc9f36d4339c77">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a99ba48887ebb27a765bc9f36d4339c77">enabled</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a>!=<a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a>; }</span></span></div>

</div>


References <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a> and <a href="#ab3bc6742416b3472eebee53632757df2">m&#95;kind</a>.
</div>
</div>

### kind() {#a7cc55c10e28715c334a3e51fb5003c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind SearchIndexIntf::kind ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00190">190</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cc55c10e28715c334a3e51fb5003c08">190</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a> <a href="#a7cc55c10e28715c334a3e51fb5003c08">kind</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a>; }</span></span></div>

</div>


Reference <a href="#ab3bc6742416b3472eebee53632757df2">m&#95;kind</a>.
</div>
</div>

### setCurrentDoc() {#a5aa7df3f4440a0b3adf710fd312195e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndexIntf::setCurrentDoc (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool isSourceFile)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00148">148</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa7df3f4440a0b3adf710fd312195e5">148</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5aa7df3f4440a0b3adf710fd312195e5">setCurrentDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isSourceFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;SearchIndex&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get&lt;SearchIndex&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>).setCurrentDoc(ctx,anchor,isSourceFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;SearchIndexExternal&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get&lt;SearchIndexExternal&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>).setCurrentDoc(ctx,anchor,isSourceFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a950d158c195ac3eef237b9a6ae7a5265">m&#95;variant</a>.
</div>
</div>

### setKind() {#aa5dc87e5ce9c0a92c53fc3978f6ef31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndexIntf::setKind (<a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a> k)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00181">181</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5dc87e5ce9c0a92c53fc3978f6ef31e">181</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa5dc87e5ce9c0a92c53fc3978f6ef31e">setKind</a>(<a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a> k) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a>=k;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a>: <a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a> = std::monostate();      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa4e9f47fa9f92dd54889f2e95261a1041">Internal</a>: <a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a> = <a href="/web-doxygen/docs/api/classes/searchindex">SearchIndex</a>();         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa507071eac5d8808e1e91570d8c20523b">External</a>: <a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a> = <a href="/web-doxygen/docs/api/classes/searchindexexternal">SearchIndexExternal</a>(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa18319e2d242c98414b3a334f4d04215d">Disabled</a>, <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa507071eac5d8808e1e91570d8c20523b">External</a>, <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9eaa4e9f47fa9f92dd54889f2e95261a1041">Internal</a>, <a href="#ab3bc6742416b3472eebee53632757df2">m&#95;kind</a> and <a href="#a950d158c195ac3eef237b9a6ae7a5265">m&#95;variant</a>.
</div>
</div>

### write() {#ae9e841df6d6d7f85bec747ab0aedb038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndexIntf::write (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00170">170</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9e841df6d6d7f85bec747ab0aedb038">170</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae9e841df6d6d7f85bec747ab0aedb038">write</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;SearchIndex&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get&lt;SearchIndex&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>).write(file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;SearchIndexExternal&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get&lt;SearchIndexExternal&gt;(<a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>).write(file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a950d158c195ac3eef237b9a6ae7a5265">m&#95;variant</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;kind {#ab3bc6742416b3472eebee53632757df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind SearchIndexIntf::m_kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00192">192</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3bc6742416b3472eebee53632757df2">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ade3dd4c1f8bc6487f0f3dccba5c6f9ea">Kind</a> <a href="#ab3bc6742416b3472eebee53632757df2">m_kind</a>;</span></span></div>

</div>


Referenced by <a href="#a99ba48887ebb27a765bc9f36d4339c77">enabled</a>, <a href="#a7cc55c10e28715c334a3e51fb5003c08">kind</a>, <a href="#a09bb6fc7de0cb12011dbaad5645eb00f">SearchIndexIntf</a> and <a href="#aa5dc87e5ce9c0a92c53fc3978f6ef31e">setKind</a>.
</div>
</div>

### m&#95;variant {#a950d158c195ac3eef237b9a6ae7a5265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchIndexVariant SearchIndexIntf::m_variant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/searchindex-h/#l00193">193</a> of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a950d158c195ac3eef237b9a6ae7a5265">193</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad3cf24c21e3eb2a27011711a7040e6c2">SearchIndexVariant</a> <a href="#a950d158c195ac3eef237b9a6ae7a5265">m_variant</a>;</span></span></div>

</div>


Referenced by <a href="#a40c73d699dbfbee68fb730a3246965c1">addWord</a>, <a href="#a5aa7df3f4440a0b3adf710fd312195e5">setCurrentDoc</a>, <a href="#aa5dc87e5ce9c0a92c53fc3978f6ef31e">setKind</a> and <a href="#ae9e841df6d6d7f85bec747ab0aedb038">write</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
