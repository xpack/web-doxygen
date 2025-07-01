---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/layoutdocentrysection
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LayoutDocEntrySection` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct LayoutDocEntrySection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/layout-h">src/layout.h</a>&gt;
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutdocentrysimple">LayoutDocEntrySimple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Represents of a piece of a documentation page without configurable parts. <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e7ece581ed0d7b1ac41d3f39a3059bc">LayoutDocEntrySection</a> (Kind k, const std::string &amp;id, const QCString &amp;tl, bool v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a363185aa61931f8aa77b4a6c71b6c62b">title</a> (SrcLangExt lang) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42d4e63b77f0b73e7160d499604047e">m_title</a></td>
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


Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.

<div class="doxySectionDef">

## Public Constructors

### LayoutDocEntrySection() {#a5e7ece581ed0d7b1ac41d3f39a3059bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutDocEntrySection::LayoutDocEntrySection (<a href="/web-doxygen/docs/api/structs/layoutdocentry/#a89dcbe762ed7e7f7790d8c034cf8ea01">Kind</a> k, const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tl, bool v)</td>
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



Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e7ece581ed0d7b1ac41d3f39a3059bc">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5e7ece581ed0d7b1ac41d3f39a3059bc">LayoutDocEntrySection</a>(<a href="/web-doxygen/docs/api/structs/layoutdocentry/#a89dcbe762ed7e7f7790d8c034cf8ea01">Kind</a> k,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> v) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a98ca4f55e9b69d4c8f241ae4c601dc6d">LayoutDocEntrySimple</a>(k,<a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a9b4f3a2bcdbe43a1017ef1ffd43ec735">id</a>,v), <a href="#ae42d4e63b77f0b73e7160d499604047e">m_title</a>(tl) {}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a9b4f3a2bcdbe43a1017ef1ffd43ec735">LayoutDocEntrySimple::id</a>, <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a98ca4f55e9b69d4c8f241ae4c601dc6d">LayoutDocEntrySimple::LayoutDocEntrySimple</a> and <a href="#ae42d4e63b77f0b73e7160d499604047e">m\_title</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### title() {#a363185aa61931f8aa77b4a6c71b6c62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutDocEntrySection::title (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 105 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>, definition at line 1779 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a363185aa61931f8aa77b4a6c71b6c62b">1779</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a363185aa61931f8aa77b4a6c71b6c62b">LayoutDocEntrySection::title</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/layout-cpp/#af079449c7fca1ffd687c7b964cceb15c">extractLanguageSpecificTitle</a>(<a href="#ae42d4e63b77f0b73e7160d499604047e">m_title</a>,lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#af079449c7fca1ffd687c7b964cceb15c">extractLanguageSpecificTitle</a> and <a href="#ae42d4e63b77f0b73e7160d499604047e">m\_title</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a65a60aa7cc7048c9f3b39312b4aba21d">ConceptDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae849568cb2c125f1d3a89a41e3ded5d7">ClassDefImpl::writeDocumentationContents</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_title {#ae42d4e63b77f0b73e7160d499604047e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutDocEntrySection::m_title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae42d4e63b77f0b73e7160d499604047e">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae42d4e63b77f0b73e7160d499604047e">m_title</a>;</span></span></div>

</div>


Referenced by <a href="#a5e7ece581ed0d7b1ac41d3f39a3059bc">LayoutDocEntrySection</a> and <a href="#a363185aa61931f8aa77b4a6c71b6c62b">title</a>.
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
