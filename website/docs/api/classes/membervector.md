---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/membervector
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `MemberVector` Class Reference

<p>A vector of <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class MemberVector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/memberlist-h">src/memberlist.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> objects as shown in documentation sections. <a href="/web-doxygen/docs/api/classes/memberlist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a> = <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228e1d26a11b0a1beeb2067a4e9d8b4f">Vec</a> = std::vector&lt; <a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6c8979ac8c7291618bf70793a2d6700">value_type</a> = Vec::value_type</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9146e6a3490c80b75b5050597f0c3583">allocator_type</a> = Vec::allocator_type</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a> = Vec::size_type</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053e7d32211052df98f4c63b78ef8ea7">difference_type</a> = Vec::difference_type</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdccb511e90a5c1a443670e242647681">reference</a> = Vec::reference</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a> = Vec::const_reference</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> = Vec::iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a> = Vec::const_iterator</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afdccb511e90a5c1a443670e242647681">reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28443026f8177a5278881da7fd50b9fe">operator[]</a> (size_type pos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03825cfb70a8e20c3a152ad73396a800">operator[]</a> (size_type pos) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8265ec4f4b9b33ae0ddc0341f84433f">push_back</a> (const T &amp;value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c83cd62526fa63b86e060265edb404c">push_back</a> (T &amp;&amp;value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f404f074e0385b8339dd91e1a0a3ab">erase</a> (iterator pos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19de3fc7a07a0a08ef4000971c22211e">erase</a> (const_iterator pos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59b75a387fce804f30cbf31ea9c3297">begin</a> () noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0f65d6767771d9f7503a24d1078045">begin</a> () const noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51414ef16b6467930e5e6ea6865177b">end</a> () noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db04a2ba94299e2da714c4f6d98dcfc">end</a> () const noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add7e9c83dbcc4a504337d0b2f95f702d">size</a> () const noexcept</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8211803ee32d3deef9aafca1cc061101">empty</a> () const noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afdccb511e90a5c1a443670e242647681">reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602285c1987a5e4f223507c54df96443">front</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded22301293f615d2f20a038d7554129">front</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afdccb511e90a5c1a443670e242647681">reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23b51526926e872b05428496285f43d3">back</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c5e9f1a0cdb5fc6161342954f2a19fc">back</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4391e4cb58c64ccf2325d67a8933e85f">sort</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac628512e0013609863af231ece9fed50">inSort</a> (MemberDef *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c36ea0755042a20f9eb4537b9f0d10b">remove</a> (const MemberDef *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb2660f6e0049ba5ac4a53e4a5b0d0df">contains</a> (const MemberDef *md) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af97b42c8dd7d1e220bd86ec9d5a44867">find</a> (const QCString &amp;name)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a228e1d26a11b0a1beeb2067a4e9d8b4f">Vec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bc8544d134138efb4a3aaf8518c32f">lessThan</a> (const MemberDef *md1, const MemberDef *md2)</td>
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

<p>A vector of <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> object.</p>

<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxySectionDef">

## Public Member Typedefs

### allocator&#95;type {#a9146e6a3490c80b75b5050597f0c3583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::allocator_type =  Vec::allocator_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00040">40</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9146e6a3490c80b75b5050597f0c3583">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9146e6a3490c80b75b5050597f0c3583">allocator_type</a>   = Vec::allocator_type;</span></span></div>

</div>

</div>
</div>

### const&#95;iterator {#af1ccea866bff121d95fc2992fc7aca1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::const_iterator =  Vec::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1ccea866bff121d95fc2992fc7aca1a">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a>   = Vec::const_iterator;</span></span></div>

</div>

</div>
</div>

### const&#95;reference {#afe4abafaf8212402875ddb98bb485ab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::const_reference =  Vec::const_reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe4abafaf8212402875ddb98bb485ab6">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a>  = Vec::const_reference;</span></span></div>

</div>

</div>
</div>

### difference&#95;type {#a053e7d32211052df98f4c63b78ef8ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::difference_type =  Vec::difference_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00042">42</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a053e7d32211052df98f4c63b78ef8ea7">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a053e7d32211052df98f4c63b78ef8ea7">difference_type</a>  = Vec::difference_type;</span></span></div>

</div>

</div>
</div>

### iterator {#af600b93343a96eef5fee8f631a6b2d46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::iterator =  Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00045">45</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af600b93343a96eef5fee8f631a6b2d46">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a>         = Vec::iterator;</span></span></div>

</div>

</div>
</div>

### reference {#afdccb511e90a5c1a443670e242647681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::reference =  Vec::reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00043">43</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afdccb511e90a5c1a443670e242647681">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#afdccb511e90a5c1a443670e242647681">reference</a>        = Vec::reference;</span></span></div>

</div>

</div>
</div>

### size&#95;type {#a50361ae2e3c9cdc4d28f47a65b2d264a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::size_type =  Vec::size_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00041">41</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a>        = Vec::size_type;</span></span></div>

</div>

</div>
</div>

### T {#a9a8fb1498502d4146281d030c5fba9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::T =  MemberDef*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00037">37</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a8fb1498502d4146281d030c5fba9a4">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a>                = <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*;</span></span></div>

</div>

</div>
</div>

### value&#95;type {#ac6c8979ac8c7291618bf70793a2d6700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::value_type =  Vec::value_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00039">39</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6c8979ac8c7291618bf70793a2d6700">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ac6c8979ac8c7291618bf70793a2d6700">value_type</a>       = Vec::value_type;</span></span></div>

</div>

</div>
</div>

### Vec {#a228e1d26a11b0a1beeb2067a4e9d8b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using MemberVector::Vec =  std::vector&lt;T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00038">38</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a228e1d26a11b0a1beeb2067a4e9d8b4f">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a228e1d26a11b0a1beeb2067a4e9d8b4f">Vec</a>              = std::vector&lt;T&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&#91;&#93;() {#a28443026f8177a5278881da7fd50b9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference MemberVector::operator[] (<a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a> pos)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00068">68</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28443026f8177a5278881da7fd50b9fe">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afdccb511e90a5c1a443670e242647681">reference</a> <a href="#a28443026f8177a5278881da7fd50b9fe">operator[]</a>( <a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a> pos )       { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.operator[](pos); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### operator&#91;&#93;() {#a03825cfb70a8e20c3a152ad73396a800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference MemberVector::operator[] (<a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a> pos)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00069">69</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03825cfb70a8e20c3a152ad73396a800">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a> <a href="#a03825cfb70a8e20c3a152ad73396a800">operator[]</a>( <a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a> pos )</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.operator[](pos); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#a23b51526926e872b05428496285f43d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference MemberVector::back ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00065">65</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23b51526926e872b05428496285f43d3">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afdccb511e90a5c1a443670e242647681">reference</a> <a href="#a23b51526926e872b05428496285f43d3">back</a>()                  { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.back();  }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### back() {#a6c5e9f1a0cdb5fc6161342954f2a19fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference MemberVector::back ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00066">66</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c5e9f1a0cdb5fc6161342954f2a19fc">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a> <a href="#a6c5e9f1a0cdb5fc6161342954f2a19fc">back</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.back();  }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### begin() {#ae59b75a387fce804f30cbf31ea9c3297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberVector::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae59b75a387fce804f30cbf31ea9c3297">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> <a href="#ae59b75a387fce804f30cbf31ea9c3297">begin</a>()       noexcept   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::&#95;writeReimplementedBy</a> and <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ae91eb6342041a59b5b4f4fc916d6ffe5">refMapToVector</a>.
</div>
</div>

### begin() {#a9e0f65d6767771d9f7503a24d1078045}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator MemberVector::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e0f65d6767771d9f7503a24d1078045">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a> <a href="#a9e0f65d6767771d9f7503a24d1078045">begin</a>() const noexcept   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### contains() {#abb2660f6e0049ba5ac4a53e4a5b0d0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemberVector::contains (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00089">89</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb2660f6e0049ba5ac4a53e4a5b0d0df">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abb2660f6e0049ba5ac4a53e4a5b0d0df">contains</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::find(<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(),<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end(),md)!=<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a6c89498ad2de8fa4026db0ac73167608">FileDefImpl::insertMember</a>.
</div>
</div>

### empty() {#a8211803ee32d3deef9aafca1cc061101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemberVector::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00060">60</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8211803ee32d3deef9aafca1cc061101">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8211803ee32d3deef9aafca1cc061101">empty</a>()     const noexcept         { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.empty(); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a2cc4fd1745dd5af379937db46ac15761">DotGroupCollaboration::addMemberList</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a008f3c41fee6631ee72278082f3d1a2d">generateDEFClassSection</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#adc602caedeaab8d348c752b53368cdc9">generateDEFSection</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae515e3c5baf8a9c7b818a3f492d576a1">writeMemberToIndex</a>.
</div>
</div>

### end() {#ab51414ef16b6467930e5e6ea6865177b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberVector::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00056">56</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab51414ef16b6467930e5e6ea6865177b">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> <a href="#ab51414ef16b6467930e5e6ea6865177b">end</a>()         noexcept   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end();   }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::&#95;writeReimplementedBy</a> and <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ae91eb6342041a59b5b4f4fc916d6ffe5">refMapToVector</a>.
</div>
</div>

### end() {#a7db04a2ba94299e2da714c4f6d98dcfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator MemberVector::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00057">57</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7db04a2ba94299e2da714c4f6d98dcfc">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a> <a href="#a7db04a2ba94299e2da714c4f6d98dcfc">end</a>()   const noexcept   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end();   }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### erase() {#ab5f404f074e0385b8339dd91e1a0a3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberVector::erase (<a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> pos)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00051">51</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5f404f074e0385b8339dd91e1a0a3ab">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> <a href="#ab5f404f074e0385b8339dd91e1a0a3ab">erase</a>( <a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> pos )          { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.erase(pos); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="#a2c36ea0755042a20f9eb4537b9f0d10b">remove</a>.
</div>
</div>

### erase() {#a19de3fc7a07a0a08ef4000971c22211e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator MemberVector::erase (<a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a> pos)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19de3fc7a07a0a08ef4000971c22211e">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af600b93343a96eef5fee8f631a6b2d46">iterator</a> <a href="#a19de3fc7a07a0a08ef4000971c22211e">erase</a>( <a href="#af1ccea866bff121d95fc2992fc7aca1a">const_iterator</a> pos )    { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.erase(pos); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### find() {#af97b42c8dd7d1e220bd86ec9d5a44867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberDef * MemberVector::find (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00093">93</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af97b42c8dd7d1e220bd86ec9d5a44867">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#af97b42c8dd7d1e220bd86ec9d5a44867">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find_if(<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(),<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end(),[name=name](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;el) { return el-&gt;name()==name; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a>.
</div>
</div>

### front() {#a602285c1987a5e4f223507c54df96443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference MemberVector::front ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00062">62</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a602285c1987a5e4f223507c54df96443">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afdccb511e90a5c1a443670e242647681">reference</a> <a href="#a602285c1987a5e4f223507c54df96443">front</a>()                 { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.front(); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### front() {#aded22301293f615d2f20a038d7554129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference MemberVector::front ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00063">63</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aded22301293f615d2f20a038d7554129">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afe4abafaf8212402875ddb98bb485ab6">const_reference</a> <a href="#aded22301293f615d2f20a038d7554129">front</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.front(); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### inSort() {#ac628512e0013609863af231ece9fed50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberVector::inSort (<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00080">80</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac628512e0013609863af231ece9fed50">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac628512e0013609863af231ece9fed50">inSort</a>(<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.insert( std::upper_bound( <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(), <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end(), md, <a href="#a55bc8544d134138efb4a3aaf8518c32f">lessThan</a>), md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a55bc8544d134138efb4a3aaf8518c32f">lessThan</a> and <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### push&#95;back() {#ae8265ec4f4b9b33ae0ddc0341f84433f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberVector::push_back (const <a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a> &amp; value)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00048">48</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8265ec4f4b9b33ae0ddc0341f84433f">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae8265ec4f4b9b33ae0ddc0341f84433f">push_back</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a>&amp; value )        { <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.push_back(value); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/membergroup/#a298db4223e61135eb6da36ade9c00c02">MemberGroup::addGroupedInheritedMembers</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a6c89498ad2de8fa4026db0ac73167608">FileDefImpl::insertMember</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>.
</div>
</div>

### push&#95;back() {#a9c83cd62526fa63b86e060265edb404c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberVector::push_back (<a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a> &amp;&amp; value)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00049">49</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c83cd62526fa63b86e060265edb404c">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9c83cd62526fa63b86e060265edb404c">push_back</a>( <a href="#a9a8fb1498502d4146281d030c5fba9a4">T</a>&amp;&amp; value )             { <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.push_back(std::move(value)); }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### remove() {#a2c36ea0755042a20f9eb4537b9f0d10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberVector::remove (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00084">84</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c36ea0755042a20f9eb4537b9f0d10b">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2c36ea0755042a20f9eb4537b9f0d10b">remove</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find(<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(),<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end()) <a href="#ab5f404f074e0385b8339dd91e1a0a3ab">erase</a>(it);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ab5f404f074e0385b8339dd91e1a0a3ab">erase</a> and <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a997cd374af0007f7a3b1f3026d62c2be">FileDefImpl::removeMemberFromList</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a180bb92685e13838d5bacc59a4dc9648">GroupDefImpl::removeMemberFromList</a>.
</div>
</div>

### size() {#add7e9c83dbcc4a504337d0b2f95f702d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type MemberVector::size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add7e9c83dbcc4a504337d0b2f95f702d">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a50361ae2e3c9cdc4d28f47a65b2d264a">size_type</a> <a href="#add7e9c83dbcc4a504337d0b2f95f702d">size</a>() const noexcept         { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.size();  }</span></span></div>

</div>


Reference <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.
</div>
</div>

### sort() {#a4391e4cb58c64ccf2325d67a8933e85f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberVector::sort ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00076">76</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4391e4cb58c64ccf2325d67a8933e85f">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4391e4cb58c64ccf2325d67a8933e85f">sort</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      std::stable_sort(<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.begin(),<a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>.end(),<a href="#a55bc8544d134138efb4a3aaf8518c32f">lessThan</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a55bc8544d134138efb4a3aaf8518c32f">lessThan</a> and <a href="#ab42304afbcf068af52820567fbc74fd4">m&#95;members</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a38dfbb5daa66a820f49167beecae6e90">FileDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### m&#95;members {#ab42304afbcf068af52820567fbc74fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vec MemberVector::m_members</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00104">104</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab42304afbcf068af52820567fbc74fd4">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a228e1d26a11b0a1beeb2067a4e9d8b4f">Vec</a> <a href="#ab42304afbcf068af52820567fbc74fd4">m_members</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="#a23b51526926e872b05428496285f43d3">back</a>, <a href="#a6c5e9f1a0cdb5fc6161342954f2a19fc">back</a>, <a href="#a9e0f65d6767771d9f7503a24d1078045">begin</a>, <a href="#ae59b75a387fce804f30cbf31ea9c3297">begin</a>, <a href="#abb2660f6e0049ba5ac4a53e4a5b0d0df">contains</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af3acf88514cd3851185e73b8c386741a">MemberList::countDecMembers</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#abca221290e11d876fe4eade22711b9e5">MemberList::countDocMembers</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a20350e5803a50856a69419c6473dd5a1">MemberList::countEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a70f473313b44a7d39bd284595f3e9639">MemberList::countInheritableMembers</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af3e9802567a6e2df20e4714a7aed3807">MemberList::declVisible</a>, <a href="#a8211803ee32d3deef9aafca1cc061101">empty</a>, <a href="#a7db04a2ba94299e2da714c4f6d98dcfc">end</a>, <a href="#ab51414ef16b6467930e5e6ea6865177b">end</a>, <a href="#a19de3fc7a07a0a08ef4000971c22211e">erase</a>, <a href="#ab5f404f074e0385b8339dd91e1a0a3ab">erase</a>, <a href="#af97b42c8dd7d1e220bd86ec9d5a44867">find</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ad095317a533d0e4d883e286a5599746d">MemberList::findSectionsInDocumentation</a>, <a href="#a602285c1987a5e4f223507c54df96443">front</a>, <a href="#aded22301293f615d2f20a038d7554129">front</a>, <a href="#ac628512e0013609863af231ece9fed50">inSort</a>, <a href="#a28443026f8177a5278881da7fd50b9fe">operator&#91;&#93;</a>, <a href="#a03825cfb70a8e20c3a152ad73396a800">operator&#91;&#93;</a>, <a href="#ae8265ec4f4b9b33ae0ddc0341f84433f">push&#95;back</a>, <a href="#a9c83cd62526fa63b86e060265edb404c">push&#95;back</a>, <a href="#a2c36ea0755042a20f9eb4537b9f0d10b">remove</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ae626c9e633e5efcf3476b1c7c847d06b">MemberList::setAnchors</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a663e4dedf84ec20ab0b682c0c762647e">MemberList::setAnonymousEnumType</a>, <a href="#add7e9c83dbcc4a504337d0b2f95f702d">size</a>, <a href="#a4391e4cb58c64ccf2325d67a8933e85f">sort</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### lessThan() {#a55bc8544d134138efb4a3aaf8518c32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemberVector::lessThan (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md1, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/memberlist-h/#l00072">72</a> of file <a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55bc8544d134138efb4a3aaf8518c32f">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a55bc8544d134138efb4a3aaf8518c32f">lessThan</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/memberlist-h/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>(md1,md2)&lt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/memberlist-h/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>.

Referenced by <a href="#ac628512e0013609863af231ece9fed50">inSort</a> and <a href="#a4391e4cb58c64ccf2325d67a8933e85f">sort</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
