---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fmhlinfo
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `FmhlInfo` Struct Reference

<p>Helper class representing a file member in the navigation menu. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct FmhlInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad54e7439cbbbea228c915d2d787efc9">FmhlInfo</a> (const char *fn, const QCString &amp;t)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af139ff6dcd5a3078dd119860da575ef5">fname</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd88c71ff2562f6d67b07845e300f224">title</a></td>
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

<p>Helper class representing a file member in the navigation menu.</p>

<p>Definition at line 3263 of file <a href="/web-doxygen/docs/api/files/src/index-cpp">index.cpp</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### FmhlInfo() {#aad54e7439cbbbea228c915d2d787efc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FmhlInfo::FmhlInfo (const char * fn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; t)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/index-cpp/#l03265">3265</a> of file <a href="/web-doxygen/docs/api/files/src/index-cpp">index.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad54e7439cbbbea228c915d2d787efc9">3265</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aad54e7439cbbbea228c915d2d787efc9">FmhlInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fn,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;t) : <a href="#af139ff6dcd5a3078dd119860da575ef5">fname</a>(fn), <a href="#afd88c71ff2562f6d67b07845e300f224">title</a>(t) {}</span></span></div>

</div>


References <a href="#af139ff6dcd5a3078dd119860da575ef5">fname</a> and <a href="#afd88c71ff2562f6d67b07845e300f224">title</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fname {#af139ff6dcd5a3078dd119860da575ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* FmhlInfo::fname</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/index-cpp/#l03266">3266</a> of file <a href="/web-doxygen/docs/api/files/src/index-cpp">index.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af139ff6dcd5a3078dd119860da575ef5">3266</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#af139ff6dcd5a3078dd119860da575ef5">fname</a>;</span></span></div>

</div>


Referenced by <a href="#aad54e7439cbbbea228c915d2d787efc9">FmhlInfo</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>.
</div>
</div>

### title {#afd88c71ff2562f6d67b07845e300f224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString FmhlInfo::title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/index-cpp/#l03267">3267</a> of file <a href="/web-doxygen/docs/api/files/src/index-cpp">index.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afd88c71ff2562f6d67b07845e300f224">3267</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#afd88c71ff2562f6d67b07845e300f224">title</a>;</span></span></div>

</div>


Referenced by <a href="#aad54e7439cbbbea228c915d2d787efc9">FmhlInfo</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/index-cpp">index.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
