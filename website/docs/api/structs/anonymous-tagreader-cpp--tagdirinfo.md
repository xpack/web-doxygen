---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anonymous-tagreader-cpp-/tagdirinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TagDirInfo` Struct Reference

<p>Container for directory specific info that can be read from a tagfile. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{tagreader.cpp}::TagDirInfo { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc9abe1c86f41a084f57c364ad56dda">path</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c65e15ae8672ee0c41439891fc6055">subdirList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949b238cd7c7927e08818bfc1100b20b">fileList</a></td>
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

<p>Container for directory specific info that can be read from a tagfile.</p>

<p>Definition at line 203 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### fileList {#a949b238cd7c7927e08818bfc1100b20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector anonymous_namespace{tagreader.cpp}::TagDirInfo::fileList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a949b238cd7c7927e08818bfc1100b20b">207</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> <a href="#a949b238cd7c7927e08818bfc1100b20b">fileList</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aafd3846f78cc76b992152366c99f7d74">anonymous_namespace{tagreader.cpp}::TagFileParser::dump</a> and <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a34e5a973da1491d711704a2ee6ee8ae0">anonymous_namespace{tagreader.cpp}::TagFileParser::endFile</a>.</p>

</div>
</div>

### path {#a4cc9abe1c86f41a084f57c364ad56dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous_namespace{tagreader.cpp}::TagDirInfo::path</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cc9abe1c86f41a084f57c364ad56dda">205</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4cc9abe1c86f41a084f57c364ad56dda">path</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aafd3846f78cc76b992152366c99f7d74">anonymous_namespace{tagreader.cpp}::TagFileParser::dump</a> and <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a8020f9f5e883fd98854ac72e4e6e776d">anonymous_namespace{tagreader.cpp}::TagFileParser::endPath</a>.</p>

</div>
</div>

### subdirList {#a54c65e15ae8672ee0c41439891fc6055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector anonymous_namespace{tagreader.cpp}::TagDirInfo::subdirList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54c65e15ae8672ee0c41439891fc6055">206</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> <a href="#a54c65e15ae8672ee0c41439891fc6055">subdirList</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aafd3846f78cc76b992152366c99f7d74">anonymous_namespace{tagreader.cpp}::TagFileParser::dump</a> and <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#af120fd7d4ed4df2d800e4a531152728d">anonymous_namespace{tagreader.cpp}::TagFileParser::endDir</a>.</p>

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
