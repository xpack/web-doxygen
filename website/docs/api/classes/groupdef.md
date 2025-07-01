---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/groupdef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `GroupDef` Class Reference

A model of a group of symbols. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class GroupDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/groupdef-h">src/groupdef.h</a>&gt;
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition">Definition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The common base class of all entity definitions found in the sources. <a href="/web-doxygen/docs/api/classes/definition/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionmixin">DefinitionMixin&lt;Base&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeab8894628309c44392b37392f9c095a">setGroupTitle</a> (const QCString &amp;newtitle)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18c28c4c9018a99b6d78cf5ac93bf55">hasGroupTitle</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac55e299141c3066682afe93cb8c2793f">addFile</a> (FileDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645821da41c9e9e22e0f9e4e114c2087">containsFile</a> (const FileDef *def) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a80bd0b7430a7adaf6403f01821becd">addClass</a> (ClassDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e35a187293d00cdccc7da69e3e86a0">addConcept</a> (ConceptDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530747d47eb188ab2997190dcd78b8bb">addModule</a> (ModuleDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69045b40b7deb5217d45b0bf1e183d7f">addNamespace</a> (NamespaceDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5e0a4e1a5c815563de6e3ea235da420">addGroup</a> (GroupDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c5d805ca23c87783db6d27f231ba8ab">addPage</a> (PageDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7a8ae65f303cde09e95f68d1960e08">addExample</a> (PageDef *def)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cefe14a8b4f2004a76bbcca39e5aada">addDir</a> (DirDef *dd)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7c161ee9febb2cb5ea6ed3dc74176e">insertMember</a> (MemberDef *def, bool docOnly=FALSE)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62090524551868d7e7016245b3800d1b">removeMember</a> (MemberDef *md)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcaaf2e683208c173158a73d512edd0">findGroup</a> (const GroupDef *def) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e661711fbab648ce59579dc94618538">writeDocumentation</a> (OutputList &amp;ol)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e54ab530ac3ca3c1495031770de8b4e">writeMemberPages</a> (OutputList &amp;ol, int hierarchyLevel)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8761743f1171297d79ea2b7074ec63">writeTagFile</a> (TextStream &amp;)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003f32b442427eb1abe49a67982e6888">numDocMembers</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b57d9fa463708a660dc4b96f8ccde3">isVisibleInHierarchy</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa351dc6bcfe739a61ddb66e6a65892da">isASubGroup</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63dbf389eb8b78455fca974006ffa73e">computeAnchors</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12209686dee1aa61c48d34e82cd31017">countMembers</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08ac5e49287a2209e29bf2519bab006">addMembersToMemberGroup</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728afd28f6ecf14455cf243f5efc84ec">distributeMemberGroupDocumentation</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631d5c5c83b5a2edd35f4d3b1cd86d3a">findSectionsInDocumentation</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774f8df6fd6a6ff9a45831a94a42fc42">addListReferences</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850d73569a0f852d2ac855dd173db834">sortMemberLists</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6b08e19187d1332f355ab93a421480">subGrouping</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d699953c84daa0aae69f0988ea3bf12">setGroupScope</a> (Definition *d)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a38c58fe6be5aba2e6dac9c41be9e1">getGroupScope</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a> (MemberListType lt) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberlists">MemberLists</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d174d39f8e75953f384736d3effaad8">getMemberLists</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a9fe05d4375b4571d822141ba498bf2">getMemberGroups</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filelist">FileList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc93620cc6002b6e7919565cb32b29ed">getClasses</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap">ConceptLinkedRefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927445c6f77b990c4b7ea29e93a7837e">getConcepts</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/modulelinkedrefmap">ModuleLinkedRefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae9211266248f6c26c5fabf1c4415b0">getModules</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap">NamespaceLinkedRefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/grouplist">GroupList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29954976b38072020da6c0c0dbde6520">getSubGroups</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/pagelinkedrefmap">PageLinkedRefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d9ddba395f4c011a01966dc7a61568">getPages</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dirlist">DirList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25362a91e571718de606e663975c6a1b">getDirs</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/pagelinkedrefmap">PageLinkedRefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b690ed7965596387ea0a2d1d958027c">getExamples</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cd7e2bebfc139c65a6ff4835868fc01">hasDetailedDescription</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504ee747b49968786514ec580fa5218c">sortSubGroups</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a5552b2d14d9da2535d12dd323e1af6">hasGroupGraph</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a476ffd1f00512dcb6f2f724bf23124">overrideGroupGraph</a> (bool e)=0</td>
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

A model of a group of symbols.

Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### addClass() {#a4a80bd0b7430a7adaf6403f01821becd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::addClass (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a4a80bd0b7430a7adaf6403f01821becd">addClass</a>.

Referenced by <a href="#a4a80bd0b7430a7adaf6403f01821becd">addClass</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a133ed5d7ef56cd0de5d89dcfead564e7">addClassToGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a21cfa81a6854b108ab53153e9db19d3c">distributeClassGroupRelations</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a>.
</div>
</div>

### addConcept() {#ae0e35a187293d00cdccc7da69e3e86a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::addConcept (<a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#ae0e35a187293d00cdccc7da69e3e86a0">addConcept</a>.

Referenced by <a href="#ae0e35a187293d00cdccc7da69e3e86a0">addConcept</a> and <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a>.
</div>
</div>

### addDir() {#a1cefe14a8b4f2004a76bbcca39e5aada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addDir (<a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a1cefe14a8b4f2004a76bbcca39e5aada">addDir</a>.

Referenced by <a href="#a1cefe14a8b4f2004a76bbcca39e5aada">addDir</a> and <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a378ec2ef3e841a44602739461386c1f9">addDirToGroups</a>.
</div>
</div>

### addExample() {#a1f7a8ae65f303cde09e95f68d1960e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addExample (<a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a1f7a8ae65f303cde09e95f68d1960e08">addExample</a>.

Referenced by <a href="#a1f7a8ae65f303cde09e95f68d1960e08">addExample</a> and <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#af777f735af0317cec08f59bd101c0825">addExampleToGroups</a>.
</div>
</div>

### addFile() {#ac55e299141c3066682afe93cb8c2793f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addFile (<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#ac55e299141c3066682afe93cb8c2793f">addFile</a>.

Referenced by <a href="#ac55e299141c3066682afe93cb8c2793f">addFile</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>.
</div>
</div>

### addGroup() {#aa5e0a4e1a5c815563de6e3ea235da420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addGroup (<a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#aa5e0a4e1a5c815563de6e3ea235da420">addGroup</a>.

Referenced by <a href="#aa5e0a4e1a5c815563de6e3ea235da420">addGroup</a> and <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a>.
</div>
</div>

### addListReferences() {#a774f8df6fd6a6ff9a45831a94a42fc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addListReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a774f8df6fd6a6ff9a45831a94a42fc42">addListReferences</a>.

Referenced by <a href="#a774f8df6fd6a6ff9a45831a94a42fc42">addListReferences</a>.
</div>
</div>

### addMembersToMemberGroup() {#af08ac5e49287a2209e29bf2519bab006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addMembersToMemberGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#af08ac5e49287a2209e29bf2519bab006">addMembersToMemberGroup</a>.

Referenced by <a href="#af08ac5e49287a2209e29bf2519bab006">addMembersToMemberGroup</a>.
</div>
</div>

### addModule() {#a530747d47eb188ab2997190dcd78b8bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::addModule (<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a530747d47eb188ab2997190dcd78b8bb">addModule</a>.

Referenced by <a href="#a530747d47eb188ab2997190dcd78b8bb">addModule</a> and <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>.
</div>
</div>

### addNamespace() {#a69045b40b7deb5217d45b0bf1e183d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::addNamespace (<a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a69045b40b7deb5217d45b0bf1e183d7f">addNamespace</a>.

Referenced by <a href="#a69045b40b7deb5217d45b0bf1e183d7f">addNamespace</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a035458fc750e2a32abad901b719f8392">addNamespaceToGroups</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>.
</div>
</div>

### addPage() {#a5c5d805ca23c87783db6d27f231ba8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::addPage (<a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a5c5d805ca23c87783db6d27f231ba8ab">addPage</a>.

Referenced by <a href="#a5c5d805ca23c87783db6d27f231ba8ab">addPage</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>.
</div>
</div>

### computeAnchors() {#a63dbf389eb8b78455fca974006ffa73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::computeAnchors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a63dbf389eb8b78455fca974006ffa73e">computeAnchors</a>.

Referenced by <a href="#a63dbf389eb8b78455fca974006ffa73e">computeAnchors</a>.
</div>
</div>

### containsFile() {#a645821da41c9e9e22e0f9e4e114c2087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::containsFile (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a645821da41c9e9e22e0f9e4e114c2087">containsFile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a> and <a href="#a645821da41c9e9e22e0f9e4e114c2087">containsFile</a>.
</div>
</div>

### countMembers() {#a12209686dee1aa61c48d34e82cd31017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::countMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a12209686dee1aa61c48d34e82cd31017">countMembers</a>.

Referenced by <a href="#a12209686dee1aa61c48d34e82cd31017">countMembers</a>.
</div>
</div>

### distributeMemberGroupDocumentation() {#a728afd28f6ecf14455cf243f5efc84ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::distributeMemberGroupDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a728afd28f6ecf14455cf243f5efc84ec">distributeMemberGroupDocumentation</a>.

Referenced by <a href="#a728afd28f6ecf14455cf243f5efc84ec">distributeMemberGroupDocumentation</a>.
</div>
</div>

### findGroup() {#abbcaaf2e683208c173158a73d512edd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::findGroup (const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * def)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#abbcaaf2e683208c173158a73d512edd0">findGroup</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a0b501f4e23a2e8465946abfdfe294c4c">addGroupToGroups</a> and <a href="#abbcaaf2e683208c173158a73d512edd0">findGroup</a>.
</div>
</div>

### findSectionsInDocumentation() {#a631d5c5c83b5a2edd35f4d3b1cd86d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::findSectionsInDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a631d5c5c83b5a2edd35f4d3b1cd86d3a">findSectionsInDocumentation</a>.

Referenced by <a href="#a631d5c5c83b5a2edd35f4d3b1cd86d3a">findSectionsInDocumentation</a>.
</div>
</div>

### getClasses() {#adc93620cc6002b6e7919565cb32b29ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassLinkedRefMap &amp; GroupDef::getClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#adc93620cc6002b6e7919565cb32b29ed">getClasses</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#adc93620cc6002b6e7919565cb32b29ed">getClasses</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getConcepts() {#a927445c6f77b990c4b7ea29e93a7837e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ConceptLinkedRefMap &amp; GroupDef::getConcepts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a927445c6f77b990c4b7ea29e93a7837e">getConcepts</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a927445c6f77b990c4b7ea29e93a7837e">getConcepts</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getDirs() {#a25362a91e571718de606e663975c6a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const DirList &amp; GroupDef::getDirs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a25362a91e571718de606e663975c6a1b">getDirs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="#a25362a91e571718de606e663975c6a1b">getDirs</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getExamples() {#a5b690ed7965596387ea0a2d1d958027c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const PageLinkedRefMap &amp; GroupDef::getExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a5b690ed7965596387ea0a2d1d958027c">getExamples</a>.

Referenced by <a href="#a5b690ed7965596387ea0a2d1d958027c">getExamples</a>.
</div>
</div>

### getFiles() {#a2cb0a3622503ad4232eabc2b7ff86753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const FileList &amp; GroupDef::getFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getGroupScope() {#ac8a38c58fe6be5aba2e6dac9c41be9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Definition * GroupDef::getGroupScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#ac8a38c58fe6be5aba2e6dac9c41be9e1">getGroupScope</a>.

Referenced by <a href="#ac8a38c58fe6be5aba2e6dac9c41be9e1">getGroupScope</a>.
</div>
</div>

### getMemberGroups() {#a8a9fe05d4375b4571d822141ba498bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberGroupList &amp; GroupDef::getMemberGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a8a9fe05d4375b4571d822141ba498bf2">getMemberGroups</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a> and <a href="#a8a9fe05d4375b4571d822141ba498bf2">getMemberGroups</a>.
</div>
</div>

### getMemberList() {#ae1e55ed1172103ac1072cde37b3fd578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberList * GroupDef::getMemberList (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getMemberLists() {#a2d174d39f8e75953f384736d3effaad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberLists &amp; GroupDef::getMemberLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a2d174d39f8e75953f384736d3effaad8">getMemberLists</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a2d174d39f8e75953f384736d3effaad8">getMemberLists</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getModules() {#afae9211266248f6c26c5fabf1c4415b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ModuleLinkedRefMap &amp; GroupDef::getModules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#afae9211266248f6c26c5fabf1c4415b0">getModules</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a> and <a href="#afae9211266248f6c26c5fabf1c4415b0">getModules</a>.
</div>
</div>

### getNamespaces() {#a9ac892052b696a7c561f7dfa7be68f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const NamespaceLinkedRefMap &amp; GroupDef::getNamespaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getPages() {#a97d9ddba395f4c011a01966dc7a61568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const PageLinkedRefMap &amp; GroupDef::getPages ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a97d9ddba395f4c011a01966dc7a61568">getPages</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a97d9ddba395f4c011a01966dc7a61568">getPages</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### getSubGroups() {#a29954976b38072020da6c0c0dbde6520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const GroupList &amp; GroupDef::getSubGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#ae378b5ab8e781335e10e32435ae70ded">hasNonReferenceNestedGroupRec</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### groupTitle() {#a2caedefd187d92eb8c4afe01d403456e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString GroupDef::groupTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration::DotGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a44a2f9f4ba14ceb381c325b3438febd8">generateSqlite3ForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#af8538fc61fb952e7681b9804247edc13">DefinitionImpl::pathFragment</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#adcacedbd41c269a155cadcb46deda856">SearchIndexExternal::setCurrentDoc</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### hasDetailedDescription() {#a1cd7e2bebfc139c65a6ff4835868fc01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::hasDetailedDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a1cd7e2bebfc139c65a6ff4835868fc01">hasDetailedDescription</a>.

Referenced by <a href="#a1cd7e2bebfc139c65a6ff4835868fc01">hasDetailedDescription</a>.
</div>
</div>

### hasGroupGraph() {#a2a5552b2d14d9da2535d12dd323e1af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::hasGroupGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a2a5552b2d14d9da2535d12dd323e1af6">hasGroupGraph</a>.

Referenced by <a href="#a2a5552b2d14d9da2535d12dd323e1af6">hasGroupGraph</a>.
</div>
</div>

### hasGroupTitle() {#af18c28c4c9018a99b6d78cf5ac93bf55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::hasGroupTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#af18c28c4c9018a99b6d78cf5ac93bf55">hasGroupTitle</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a> and <a href="#af18c28c4c9018a99b6d78cf5ac93bf55">hasGroupTitle</a>.
</div>
</div>

### insertMember() {#aae7c161ee9febb2cb5ea6ed3dc74176e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::insertMember (<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * def, bool docOnly=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#aae7c161ee9febb2cb5ea6ed3dc74176e">insertMember</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="#aae7c161ee9febb2cb5ea6ed3dc74176e">insertMember</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a>.
</div>
</div>

### isASubGroup() {#aa351dc6bcfe739a61ddb66e6a65892da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::isASubGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#aa351dc6bcfe739a61ddb66e6a65892da">isASubGroup</a>.

Referenced by <a href="#aa351dc6bcfe739a61ddb66e6a65892da">isASubGroup</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### isVisibleInHierarchy() {#ad9b57d9fa463708a660dc4b96f8ccde3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::isVisibleInHierarchy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#ad9b57d9fa463708a660dc4b96f8ccde3">isVisibleInHierarchy</a>.

Referenced by <a href="#ad9b57d9fa463708a660dc4b96f8ccde3">isVisibleInHierarchy</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>.
</div>
</div>

### numDocMembers() {#a003f32b442427eb1abe49a67982e6888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual size_t GroupDef::numDocMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a003f32b442427eb1abe49a67982e6888">numDocMembers</a>.

Referenced by <a href="#a003f32b442427eb1abe49a67982e6888">numDocMembers</a>.
</div>
</div>

### overrideGroupGraph() {#a4a476ffd1f00512dcb6f2f724bf23124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::overrideGroupGraph (bool e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 112 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

References <a href="/web-doxygen/docs/api/files/src/groupdef-h/#ad6183f79a16993a6ee06e93ae0357bbe">createGroupDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a4a476ffd1f00512dcb6f2f724bf23124">overrideGroupGraph</a> and <a href="/web-doxygen/docs/api/files/src/groupdef-h/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a> and <a href="#a4a476ffd1f00512dcb6f2f724bf23124">overrideGroupGraph</a>.
</div>
</div>

### removeMember() {#a62090524551868d7e7016245b3800d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::removeMember (<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a62090524551868d7e7016245b3800d1b">removeMember</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a> and <a href="#a62090524551868d7e7016245b3800d1b">removeMember</a>.
</div>
</div>

### setGroupScope() {#a6d699953c84daa0aae69f0988ea3bf12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::setGroupScope (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a6d699953c84daa0aae69f0988ea3bf12">setGroupScope</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5799cbe90654271460f7384c5c6f1a69">findGroupScope</a> and <a href="#a6d699953c84daa0aae69f0988ea3bf12">setGroupScope</a>.
</div>
</div>

### setGroupTitle() {#aeab8894628309c44392b37392f9c095a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::setGroupTitle (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; newtitle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#aeab8894628309c44392b37392f9c095a">setGroupTitle</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a> and <a href="#aeab8894628309c44392b37392f9c095a">setGroupTitle</a>.
</div>
</div>

### sortMemberLists() {#a850d73569a0f852d2ac855dd173db834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::sortMemberLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a850d73569a0f852d2ac855dd173db834">sortMemberLists</a>.

Referenced by <a href="#a850d73569a0f852d2ac855dd173db834">sortMemberLists</a>.
</div>
</div>

### sortSubGroups() {#a504ee747b49968786514ec580fa5218c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::sortSubGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a504ee747b49968786514ec580fa5218c">sortSubGroups</a>.

Referenced by <a href="#a504ee747b49968786514ec580fa5218c">sortSubGroups</a>.
</div>
</div>

### subGrouping() {#a9c6b08e19187d1332f355ab93a421480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool GroupDef::subGrouping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a9c6b08e19187d1332f355ab93a421480">subGrouping</a>.

Referenced by <a href="#a9c6b08e19187d1332f355ab93a421480">subGrouping</a>.
</div>
</div>

### writeDocumentation() {#a6e661711fbab648ce59579dc94618538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a6e661711fbab648ce59579dc94618538">writeDocumentation</a>.

Referenced by <a href="#a6e661711fbab648ce59579dc94618538">writeDocumentation</a>.
</div>
</div>

### writeMemberPages() {#a1e54ab530ac3ca3c1495031770de8b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::writeMemberPages (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, int hierarchyLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a1e54ab530ac3ca3c1495031770de8b4e">writeMemberPages</a>.

Referenced by <a href="#a1e54ab530ac3ca3c1495031770de8b4e">writeMemberPages</a>.
</div>
</div>

### writeTagFile() {#a0f8761743f1171297d79ea2b7074ec63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void GroupDef::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>.

Reference <a href="#a0f8761743f1171297d79ea2b7074ec63">writeTagFile</a>.

Referenced by <a href="#a0f8761743f1171297d79ea2b7074ec63">writeTagFile</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
