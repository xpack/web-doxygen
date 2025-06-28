---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/membergroup-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `membergroup.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;map&gt;
#include &lt;memory&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/membergroup">MemberGroup</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A class representing a group of members. <a href="/web-doxygen/docs/api/classes/membergroup/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/membergroupreflist">MemberGroupRefList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/membergroupinfo">MemberGroupInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data collected for a member group. <a href="/web-doxygen/docs/api/structs/membergroupinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e45b7986d21b8425baf0e1d59e2443b">MemberGroupInfoMap</a> = std::unordered_map&lt; int, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/membergroupinfo">MemberGroupInfo</a> &gt; &gt;</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>&nbsp;&nbsp;&nbsp;-1</td>
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


<div class="doxySectionDef">

## Typedefs

### MemberGroupInfoMap {#a6e45b7986d21b8425baf0e1d59e2443b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberGroupInfoMap =  std::unordered_map&lt; int,std::unique_ptr&lt;MemberGroupInfo&gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00125">125</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e45b7986d21b8425baf0e1d59e2443b">125</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a6e45b7986d21b8425baf0e1d59e2443b">MemberGroupInfoMap</a> = std::unordered_map&lt; int,std::unique_ptr&lt;MemberGroupInfo&gt; &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DOX&#95;NOGROUP {#af4a5ed4e8eab2424cd34974b84562093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DOX_NOGROUP&nbsp;&nbsp;&nbsp;-1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00026">26</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af4a5ed4e8eab2424cd34974b84562093">26</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DOX_NOGROUP -1</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docgroup/#a7610569d96adb6bd19ed159a5f53a26c">DocGroup::close</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4867a5cabf355b71e9540e4316ba17dd">distributeConceptGroups</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#ae49d781442d3cbceed9b62859b3d4b89">DocGroup::enterCompound</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#af3ca5770267b6242e2b95d15c47a0db9">DocGroup::enterFile</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#aa6a996a17a2a292dd6f0a2936a1d9910">DocGroup::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a14c0151b77e31de76f50ea2cb9d3e5cb">DocGroup::leaveCompound</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a15c99d30cd779d86716ffb2f341db5e1">DocGroup::leaveFile</a> and <a href="/web-doxygen/docs/api/classes/docgroup/#a9cb5ab2169da2f5bf14816e9c10e8290">DocGroup::open</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
