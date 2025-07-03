---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/layoutnaventry
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LayoutNavEntry` Struct Reference

<p>Base class for the layout of a navigation item at the top of the HTML pages. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct LayoutNavEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/layout-h">src/layout.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind { <a href="#aef36305dd829f7cde87ca203ae647c7c">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6431c54f9737e0168be5926d2d9b5e9">LayoutDocManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> (LayoutNavEntry *parent, Kind k, bool vs, const QCString &amp;bf, const QCString &amp;tl, const QCString &amp;intro)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842ec2b1a900497bae809ca674b58d81">LayoutNavEntry</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc141c39cef31bdb7af22ad64cc99187">navToString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc02648d40526f9a5675f78aac5f2773">kind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16c1e7918e22efc6c62837a0e37551d">baseFile</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fad0836fcb4498bba17120db2c84b92">id</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a006dfaa93d3dee670dd4ae22d28a1db7">title</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa298e94a9e75f9d394fd7a1121f89d84">intro</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/layout-h/#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2111e544a2355f2b2a6592819b21b232">children</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/layout-h/#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38dafcdd1828d934ac344c7c743d684c">children</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16b1f25afe49d1fbde290891414fc398">setVisible</a> (bool v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58d9ae70d4524fb21f24448acb2acab">visible</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac705591582b67407e51fbb366eab2c4d">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e311196a31dfa4d9031215cf20d1f21">insertChild</a> (size_t pos, std::unique_ptr&lt; LayoutNavEntry &gt; &amp;&amp;e)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4189efe30bb6763c42d18482d04655">appendChild</a> (std::unique_ptr&lt; LayoutNavEntry &gt; &amp;&amp;e)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509b1104c3c10f6c1da890beaa240bdd">updateVisibility</a> (LayoutNavEntry *parent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab983afb4157621ae3548364755a75002">find</a> (LayoutNavEntry::Kind k, const QCString &amp;file=QCString()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a> (LayoutNavEntry &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c394380785ec5606026ad6859e069b">m_parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/layout-h/#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a></td>
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

<p>Base class for the layout of a navigation item at the top of the HTML pages.</p>

<p>Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Kind {#aef36305dd829f7cde87ca203ae647c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LayoutNavEntry::Kind </td>
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
<td class="doxyEnumItemName">NAV_SPECIFICATIONS<a id="aef36305dd829f7cde87ca203ae647c7cac61d04c83999bd497b29972680f2218f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 193 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef36305dd829f7cde87ca203ae647c7c">193</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/layout-h/#af44a766908bd6f2e5040c265c688851e">194</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NSPEC(x,y) x y,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef36305dd829f7cde87ca203ae647c7cac61d04c83999bd497b29972680f2218f">195</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aef36305dd829f7cde87ca203ae647c7cac61d04c83999bd497b29972680f2218f">NAV_SPECIFICATIONS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef NSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### LayoutDocManager {#af6431c54f9737e0168be5926d2d9b5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6431c54f9737e0168be5926d2d9b5e9">253</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#af6431c54f9737e0168be5926d2d9b5e9">LayoutDocManager</a>;</span></span></div>

</div>


<p>Reference <a href="#af6431c54f9737e0168be5926d2d9b5e9">LayoutDocManager</a>.</p>


<p>Referenced by <a href="#af6431c54f9737e0168be5926d2d9b5e9">LayoutDocManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LayoutNavEntry() {#af57329c38d605e043016e36ec1b66c36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry::LayoutNavEntry (<a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> * parent, <a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a> k, bool vs, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; bf, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tl, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; intro)</td>
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



<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af57329c38d605e043016e36ec1b66c36">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>(<a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> *<a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>,<a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a> k,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> vs,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;bf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tl,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#aa298e94a9e75f9d394fd7a1121f89d84">intro</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>(<a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>), <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>(k), <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>(vs), <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>(bf), <a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>(tl), <a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>(<a href="#aa298e94a9e75f9d394fd7a1121f89d84">intro</a>) {}</span></span></div>

</div>


<p>References <a href="#aa298e94a9e75f9d394fd7a1121f89d84">intro</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>, <a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>, <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>, <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>, <a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>, <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a> and <a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>.</p>


<p>Referenced by <a href="#ab983afb4157621ae3548364755a75002">find</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>, <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a> and <a href="#a509b1104c3c10f6c1da890beaa240bdd">updateVisibility</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LayoutNavEntry() {#a842ec2b1a900497bae809ca674b58d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry::LayoutNavEntry ()</td>
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



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a842ec2b1a900497bae809ca674b58d81">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a842ec2b1a900497bae809ca674b58d81">LayoutNavEntry</a>() : <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>(nullptr), <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>(<a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">None</a>), <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>(true) {}</span></span></div>

</div>


<p>References <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>, <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>, <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a> and <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">None</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendChild() {#a5c4189efe30bb6763c42d18482d04655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutNavEntry::appendChild (std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> &gt; &amp;&amp; e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c4189efe30bb6763c42d18482d04655">121</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5c4189efe30bb6763c42d18482d04655">LayoutNavEntry::appendChild</a>(std::unique_ptr&lt;LayoutNavEntry&gt; &amp;&amp;e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  e-&gt;updateVisibility(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.push_back(std::move(e));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.</p>

</div>
</div>

### baseFile() {#ab16c1e7918e22efc6c62837a0e37551d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::baseFile ()</td>
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



<p>Definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab16c1e7918e22efc6c62837a0e37551d">214</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab16c1e7918e22efc6c62837a0e37551d">baseFile</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>; }</span></span></div>

</div>


<p>Reference <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>.</p>


<p>Referenced by <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a>.</p>

</div>
</div>

### children() {#a2111e544a2355f2b2a6592819b21b232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LayoutNavEntryList &amp; LayoutNavEntry::children ()</td>
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



<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2111e544a2355f2b2a6592819b21b232">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/layout-h/#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> &amp;<a href="#a2111e544a2355f2b2a6592819b21b232">children</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>; }</span></span></div>

</div>


<p>Reference <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a66c1416c41069e3b0d1952a2f05bc05d">findNavEntryRec</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a0b8f8966ef09819dbf2186a63317a5ec">mergeNavTreeNodesRec</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a191edf3c31405fc032d0277a553cea99">renderQuickLinksAsJs</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#acd16443590d430ed27faa06521ec03e4">renderQuickLinksAsTree</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab2818fb513d9fdb38f3ff8e75848f388">writeIndexHierarchy</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a>.</p>

</div>
</div>

### children() {#a38dafcdd1828d934ac344c7c743d684c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntryList &amp; LayoutNavEntry::children ()</td>
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



<p>Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38dafcdd1828d934ac344c7c743d684c">220</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/layout-h/#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> &amp;<a href="#a38dafcdd1828d934ac344c7c743d684c">children</a>()   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>; }</span></span></div>

</div>


<p>Reference <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.</p>

</div>
</div>

### clear() {#ac705591582b67407e51fbb366eab2c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutNavEntry::clear ()</td>
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



<p>Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac705591582b67407e51fbb366eab2c4d">223</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac705591582b67407e51fbb366eab2c4d">clear</a>()                     { <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.clear(); }</span></span></div>

</div>


<p>Reference <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.</p>

</div>
</div>

### find() {#ab983afb4157621ae3548364755a75002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry * LayoutNavEntry::find (<a href="#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> k, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab983afb4157621ae3548364755a75002">133</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> *<a href="#ab983afb4157621ae3548364755a75002">LayoutNavEntry::find</a>(<a href="#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> *result=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;entry : <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// depth first search, needed to find the entry furthest from the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// root in case an entry is in the tree twice</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    result = entry-&gt;<a href="#ab983afb4157621ae3548364755a75002">find</a>(<a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>,file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (entry-&gt;kind()==<a href="#abc02648d40526f9a5675f78aac5f2773">kind</a> &amp;&amp; (file==<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>() || entry-&gt;baseFile()==file))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> entry.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ab983afb4157621ae3548364755a75002">find</a>, <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> and <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.</p>


<p>Referenced by <a href="#ab983afb4157621ae3548364755a75002">find</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2508b8df6ae56345ed2dae0061d1a0df">writeClassMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aeecbfdef5946563004101a2aeffa82a3">writeFileMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a64d6048a9f49fef7b55ddef8526ac819">writeModuleMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad62d481af92d88b79731ae76f4e821b3">writeNamespaceMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.</p>

</div>
</div>

### id() {#a4fad0836fcb4498bba17120db2c84b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LayoutNavEntry::id ()</td>
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



<p>Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4fad0836fcb4498bba17120db2c84b92">215</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#a4fad0836fcb4498bba17120db2c84b92">id</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afc141c39cef31bdb7af22ad64cc99187">navToString</a>()+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+<a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>.str(); }</span></span></div>

</div>


<p>References <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a> and <a href="#afc141c39cef31bdb7af22ad64cc99187">navToString</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a66c1416c41069e3b0d1952a2f05bc05d">findNavEntryRec</a> and <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a0b8f8966ef09819dbf2186a63317a5ec">mergeNavTreeNodesRec</a>.</p>

</div>
</div>

### insertChild() {#a5e311196a31dfa4d9031215cf20d1f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutNavEntry::insertChild (size_t pos, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> &gt; &amp;&amp; e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e311196a31dfa4d9031215cf20d1f21">127</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e311196a31dfa4d9031215cf20d1f21">LayoutNavEntry::insertChild</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos,std::unique_ptr&lt;LayoutNavEntry&gt; &amp;&amp;e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  e-&gt;updateVisibility(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.insert(<a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.begin()+pos,std::move(e));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a0b8f8966ef09819dbf2186a63317a5ec">mergeNavTreeNodesRec</a>.</p>

</div>
</div>

### intro() {#aa298e94a9e75f9d394fd7a1121f89d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::intro ()</td>
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



<p>Definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa298e94a9e75f9d394fd7a1121f89d84">217</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa298e94a9e75f9d394fd7a1121f89d84">intro</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>; }</span></span></div>

</div>


<p>Reference <a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>.</p>


<p>Referenced by <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.</p>

</div>
</div>

### kind() {#abc02648d40526f9a5675f78aac5f2773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind LayoutNavEntry::kind ()</td>
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



<p>Definition at line 213 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc02648d40526f9a5675f78aac5f2773">213</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a> <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>()</span><span class="doxyHighlightKeyword"> const                </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>; }</span></span></div>

</div>


<p>Reference <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>.</p>


<p>Referenced by <a href="#ab983afb4157621ae3548364755a75002">find</a>, <a href="#afc141c39cef31bdb7af22ad64cc99187">navToString</a> and <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.</p>

</div>
</div>

### navToString() {#afc141c39cef31bdb7af22ad64cc99187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LayoutNavEntry::navToString ()</td>
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



<p>Definition at line 198 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc141c39cef31bdb7af22ad64cc99187">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#afc141c39cef31bdb7af22ad64cc99187">navToString</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define NSPEC(x,y) case x: return #x; break;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aef36305dd829f7cde87ca203ae647c7cac61d04c83999bd497b29972680f2218f">NAV_SPECIFICATIONS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef NSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// to satisfy compiler</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a> and <a href="#aef36305dd829f7cde87ca203ae647c7cac61d04c83999bd497b29972680f2218f">NAV_SPECIFICATIONS</a>.</p>


<p>Referenced by <a href="#a4fad0836fcb4498bba17120db2c84b92">id</a> and <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>.</p>

</div>
</div>

### parent() {#a61a2adf7ec0abb42e49fa07b77eb1690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry * LayoutNavEntry::parent ()</td>
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



<p>Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a61a2adf7ec0abb42e49fa07b77eb1690">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> *<a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>; }</span></span></div>

</div>


<p>References <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> and <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>.</p>


<p>Referenced by <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a> and <a href="#a509b1104c3c10f6c1da890beaa240bdd">updateVisibility</a>.</p>

</div>
</div>

### setVisible() {#a16b1f25afe49d1fbde290891414fc398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutNavEntry::setVisible (bool v)</td>
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



<p>Definition at line 221 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16b1f25afe49d1fbde290891414fc398">221</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a16b1f25afe49d1fbde290891414fc398">setVisible</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> v)          { <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a> = v; }</span></span></div>

</div>


<p>Reference <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>.</p>

</div>
</div>

### swap() {#a98b117b89cd3b4b64bfb55672eee7653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutNavEntry::swap (<a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> &amp; other)</td>
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



<p>Definition at line 228 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98b117b89cd3b4b64bfb55672eee7653">228</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>(<a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>,other.<a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>,other.<a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>,other.<a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>,other.<a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>,other.<a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>,other.<a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      std::swap(<a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>,other.<a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// reparent children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">        child-&gt;m_parent = </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>, <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>, <a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>, <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>, <a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>, <a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a> and <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>.</p>

</div>
</div>

### title() {#a006dfaa93d3dee670dd4ae22d28a1db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::title ()</td>
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



<p>Definition at line 216 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a006dfaa93d3dee670dd4ae22d28a1db7">216</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a006dfaa93d3dee670dd4ae22d28a1db7">title</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>; }</span></span></div>

</div>


<p>Reference <a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2508b8df6ae56345ed2dae0061d1a0df">writeClassMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aeecbfdef5946563004101a2aeffa82a3">writeFileMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a64d6048a9f49fef7b55ddef8526ac819">writeModuleMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad62d481af92d88b79731ae76f4e821b3">writeNamespaceMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a>.</p>

</div>
</div>

### updateVisibility() {#a509b1104c3c10f6c1da890beaa240bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutNavEntry::updateVisibility (<a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> * parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a509b1104c3c10f6c1da890beaa240bdd">116</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a509b1104c3c10f6c1da890beaa240bdd">LayoutNavEntry::updateVisibility</a>(<a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> *<a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a> = <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a> &amp;&amp; (<a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || <a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>-&gt;visible());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a> and <a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a>.</p>

</div>
</div>

### url() {#a1c873f2a034fd33d3c1ddcfcd0c2ecf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::url ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">151</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">LayoutNavEntry::url</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a> = <a href="#ab16c1e7918e22efc6c62837a0e37551d">baseFile</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>()!=LayoutNavEntry::User &amp;&amp; <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>()!=LayoutNavEntry::UserGroup) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      (<a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>()==LayoutNavEntry::UserGroup &amp;&amp; <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.startsWith(</span><span class="doxyHighlightStringLiteral">"usergroup"</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(<a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.startsWith(</span><span class="doxyHighlightStringLiteral">"@ref "</span><span class="doxyHighlight">) || <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.startsWith(</span><span class="doxyHighlightStringLiteral">"\\ref "</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> context = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parser { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>() };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> dfAst  { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>( *parser.get(), <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.mid(5).stripWhiteSpace(), context ) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> dfAstImpl = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(dfAst.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> *df = std::get_if&lt;DocRef&gt;(&amp;dfAstImpl-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || !df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      found = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>(relPath,df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a> += fn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a> += </span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight"> + df-&gt;<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"explicit link request to '{}' in layout file '{}' could not be resolved\n"</span><span class="doxyHighlight">,<a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.mid(5),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LAYOUT_FILE));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("LayoutNavEntry::url()=%s\n",qPrint(url));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">DocRef::anchor</a>, <a href="#ab16c1e7918e22efc6c62837a0e37551d">baseFile</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">DocRef::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">DocRef::ref</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.</p>


<p>Referenced by <a href="#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">url</a>.</p>

</div>
</div>

### visible() {#ad58d9ae70d4524fb21f24448acb2acab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LayoutNavEntry::visible ()</td>
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



<p>Definition at line 222 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad58d9ae70d4524fb21f24448acb2acab">222</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad58d9ae70d4524fb21f24448acb2acab">visible</a>()</span><span class="doxyHighlightKeyword"> const             </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>; }</span></span></div>

</div>


<p>Reference <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/layout-cpp/#ae5835861e8781c5f4775679657e88cdb">printNavLayout</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2508b8df6ae56345ed2dae0061d1a0df">writeClassMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aeecbfdef5946563004101a2aeffa82a3">writeFileMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a64d6048a9f49fef7b55ddef8526ac819">writeModuleMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad62d481af92d88b79731ae76f4e821b3">writeNamespaceMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_baseFile {#a8571d270987ea810865731be72feeda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::m_baseFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8571d270987ea810865731be72feeda8">249</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a8571d270987ea810865731be72feeda8">m_baseFile</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab16c1e7918e22efc6c62837a0e37551d">baseFile</a>, <a href="#a4fad0836fcb4498bba17120db2c84b92">id</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> and <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>.</p>

</div>
</div>

### m\_children {#a1ac8ba7d3423ae2cee2d68466acb86cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntryList LayoutNavEntry::m_children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">252</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/layout-h/#a9c5fd65331b31fb2296490bbff30b043">LayoutNavEntryList</a> <a href="#a1ac8ba7d3423ae2cee2d68466acb86cd">m_children</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5c4189efe30bb6763c42d18482d04655">appendChild</a>, <a href="#a38dafcdd1828d934ac344c7c743d684c">children</a>, <a href="#a2111e544a2355f2b2a6592819b21b232">children</a>, <a href="#ac705591582b67407e51fbb366eab2c4d">clear</a>, <a href="#ab983afb4157621ae3548364755a75002">find</a>, <a href="#a5e311196a31dfa4d9031215cf20d1f21">insertChild</a> and <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>.</p>

</div>
</div>

### m\_intro {#a0868a73140cbd85d9a2f50f597dc3b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::m_intro</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0868a73140cbd85d9a2f50f597dc3b06">251</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0868a73140cbd85d9a2f50f597dc3b06">m_intro</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa298e94a9e75f9d394fd7a1121f89d84">intro</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> and <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>.</p>

</div>
</div>

### m\_kind {#a8b391ae8382d6679ed4497b9b07b990c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind LayoutNavEntry::m_kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b391ae8382d6679ed4497b9b07b990c">247</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aef36305dd829f7cde87ca203ae647c7c">Kind</a> <a href="#a8b391ae8382d6679ed4497b9b07b990c">m_kind</a>;</span></span></div>

</div>


<p>Referenced by <a href="#abc02648d40526f9a5675f78aac5f2773">kind</a>, <a href="#a842ec2b1a900497bae809ca674b58d81">LayoutNavEntry</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> and <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>.</p>

</div>
</div>

### m\_parent {#af3c394380785ec5606026ad6859e069b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry* LayoutNavEntry::m_parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3c394380785ec5606026ad6859e069b">246</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a> *<a href="#af3c394380785ec5606026ad6859e069b">m_parent</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a842ec2b1a900497bae809ca674b58d81">LayoutNavEntry</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a61a2adf7ec0abb42e49fa07b77eb1690">parent</a> and <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>.</p>

</div>
</div>

### m\_title {#afb6f804300825df9a925dce9eb6768dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutNavEntry::m_title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb6f804300825df9a925dce9eb6768dd">250</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#afb6f804300825df9a925dce9eb6768dd">m_title</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a> and <a href="#a006dfaa93d3dee670dd4ae22d28a1db7">title</a>.</p>

</div>
</div>

### m\_visible {#a0c12a3f992aa3c0727310e1a686332e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LayoutNavEntry::m_visible</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c12a3f992aa3c0727310e1a686332e3">248</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0c12a3f992aa3c0727310e1a686332e3">m_visible</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a842ec2b1a900497bae809ca674b58d81">LayoutNavEntry</a>, <a href="#af57329c38d605e043016e36ec1b66c36">LayoutNavEntry</a>, <a href="#a16b1f25afe49d1fbde290891414fc398">setVisible</a>, <a href="#a98b117b89cd3b4b64bfb55672eee7653">swap</a>, <a href="#a509b1104c3c10f6c1da890beaa240bdd">updateVisibility</a> and <a href="#ad58d9ae70d4524fb21f24448acb2acab">visible</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
