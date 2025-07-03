---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/docgroup-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `docgroup.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;atomic&gt;
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::atomic_int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d0ccc0d7aaedbd3ae467c5d1479658">g_groupId</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a></td>
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

## Variables

### g\_groupId {#a05d0ccc0d7aaedbd3ae467c5d1479658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic_int g_groupId</td>
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



<p>Definition at line 23 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05d0ccc0d7aaedbd3ae467c5d1479658">23</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::atomic_int <a href="#a05d0ccc0d7aaedbd3ae467c5d1479658">g_groupId</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docgroup/#a75ac79ba2e9fa9b9feeaadf6f8567931">DocGroup::findExistingGroup</a>.</p>

</div>
</div>

### g\_memberGroupInfoMapMutex {#a83c0259d4567db59783728e348688ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_memberGroupInfoMapMutex</td>
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



<p>Definition at line 24 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83c0259d4567db59783728e348688ab3">24</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docgroup/#a9b79815ce3108572e1405da479f34e3d">DocGroup::addDocs</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a7610569d96adb6bd19ed159a5f53a26c">DocGroup::close</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a75ac79ba2e9fa9b9feeaadf6f8567931">DocGroup::findExistingGroup</a> and <a href="/web-doxygen/docs/api/classes/docgroup/#a9cb5ab2169da2f5bf14816e9c10e8290">DocGroup::open</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
