---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/findfilecacheelem
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `FindFileCacheElem` Struct Reference

<p><a href="/web-doxygen/docs/api/classes/cache">Cache</a> element for the file name to <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> mapping cache. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct FindFileCacheElem { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe37384216a36e8e4e225ebb8b487dd7">FindFileCacheElem</a> (FileDef *fd, bool ambig)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ee6985f0ee3593ee2d8d0b9e0f5006">fileDef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380e1879b7462592ef5eb5c7289f5714">isAmbig</a></td>
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

<p><a href="/web-doxygen/docs/api/classes/cache">Cache</a> element for the file name to <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> mapping cache.</p>

<p>Definition at line 3405 of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### FindFileCacheElem() {#abe37384216a36e8e4e225ebb8b487dd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FindFileCacheElem::FindFileCacheElem (<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, bool ambig)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/util-cpp/#l03407">3407</a> of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe37384216a36e8e4e225ebb8b487dd7">3407</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abe37384216a36e8e4e225ebb8b487dd7">FindFileCacheElem</a>(<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig) : <a href="#a39ee6985f0ee3593ee2d8d0b9e0f5006">fileDef</a>(fd), <a href="#a380e1879b7462592ef5eb5c7289f5714">isAmbig</a>(ambig) {}</span></span></div>

</div>


References <a href="#a39ee6985f0ee3593ee2d8d0b9e0f5006">fileDef</a> and <a href="#a380e1879b7462592ef5eb5c7289f5714">isAmbig</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fileDef {#a39ee6985f0ee3593ee2d8d0b9e0f5006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileDef* FindFileCacheElem::fileDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/util-cpp/#l03408">3408</a> of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39ee6985f0ee3593ee2d8d0b9e0f5006">3408</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#a39ee6985f0ee3593ee2d8d0b9e0f5006">fileDef</a>;</span></span></div>

</div>


Referenced by <a href="#abe37384216a36e8e4e225ebb8b487dd7">FindFileCacheElem</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>.
</div>
</div>

### isAmbig {#a380e1879b7462592ef5eb5c7289f5714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FindFileCacheElem::isAmbig</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/util-cpp/#l03409">3409</a> of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a380e1879b7462592ef5eb5c7289f5714">3409</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a380e1879b7462592ef5eb5c7289f5714">isAmbig</a>;</span></span></div>

</div>


Referenced by <a href="#abe37384216a36e8e4e225ebb8b487dd7">FindFileCacheElem</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
