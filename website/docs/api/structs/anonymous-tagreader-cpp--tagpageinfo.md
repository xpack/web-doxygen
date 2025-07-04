---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anonymous-tagreader-cpp-/tagpageinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TagPageInfo` Struct Reference

<p>Container for page specific info that can be read from a tagfile. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{tagreader.cpp}::TagPageInfo { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for all compound types. <a href="/web-doxygen/docs/api/structs/anonymous-tagreader-cpp-/tagcompoundinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251988254871e25f8b2a3f041ab0a0d1">title</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac15a5ec4694c2839b96398815b523ad7">subpages</a></td>
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

<p>Container for page specific info that can be read from a tagfile.</p>

<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### subpages {#ac15a5ec4694c2839b96398815b523ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector anonymous_namespace{tagreader.cpp}::TagPageInfo::subpages</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac15a5ec4694c2839b96398815b523ad7">197</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> <a href="#ac15a5ec4694c2839b96398815b523ad7">subpages</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous_namespace{tagreader.cpp}::TagFileParser::buildLists</a> and <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a6fd29da85de1ed3faf625ee0d27122ae">anonymous_namespace{tagreader.cpp}::TagFileParser::endSubpage</a>.</p>

</div>
</div>

### title {#a251988254871e25f8b2a3f041ab0a0d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous_namespace{tagreader.cpp}::TagPageInfo::title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a251988254871e25f8b2a3f041ab0a0d1">196</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a251988254871e25f8b2a3f041ab0a0d1">title</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous_namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aafd3846f78cc76b992152366c99f7d74">anonymous_namespace{tagreader.cpp}::TagFileParser::dump</a> and <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aa6e06a88bac03298d1b7b1d960786089">anonymous_namespace{tagreader.cpp}::TagFileParser::endTitle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
