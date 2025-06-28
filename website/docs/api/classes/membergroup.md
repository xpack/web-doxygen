---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/membergroup
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `MemberGroup` Class Reference

<p>A class representing a group of members. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class MemberGroup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/membergroup-h">src/membergroup.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a> (const Definition *container, int id, const QCString &amp;header, const QCString &amp;docs, const QCString &amp;docFile, int docLine, MemberListContainer con)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918bd808efb147a24b25c5246425d5bf">header</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d5f6dce1695c96eaddefd8b54fce43">groupId</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">insertMember</a> (MemberDef *md)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325068f062701fe19500cfe9f88e9ef2">setAnchors</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac126af1f687acb4c1067eb3307e733da">writePlainDeclarations</a> (OutputList &amp;ol, bool inGroup, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *mod, int indentLevel, const ClassDef *inheritedFrom, const QCString &amp;inheritId) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340fc8ac627f2f84ae3110d5f42480a1">writeDeclarations</a> (OutputList &amp;ol, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *mod, bool showInline=FALSE) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e87b521c1766f9bfe0be171213660ea">writeDocumentation</a> (OutputList &amp;ol, const QCString &amp;scopeName, const Definition *container, bool showEnumValues, bool showInline) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55915e6ca60ab6cd13d6d257bd916d60">writeDocumentationPage</a> (OutputList &amp;ol, const QCString &amp;scopeName, const DefinitionMutable *container) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c72b6c09af02d25cfeca6a1779bf47d">writeTagFile</a> (TextStream &amp;, bool qualifiedName=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a298db4223e61135eb6da36ade9c00c02">addGroupedInheritedMembers</a> (OutputList &amp;ol, const ClassDef *cd, MemberListType lt, const ClassDef *inheritedFrom, const QCString &amp;inheritId) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50c108b2749aff03ea41820f78f48f7">setAnonymousEnumType</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9bfe64caa099a821c650b927e4ac514">documentation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e54a4524c532b3893ea2f810fbdbeb5">allMembersInSameSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc30e752b0c36ee2be1716ff8d83856">addToDeclarationSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8087668389d7c351fe4574060f5c710d">countDecMembers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f32d80074cdb79883017c7670146e98">countDocMembers</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9134204269c78e233a4160a10653a04f">countGroupedInheritedMembers</a> (MemberListType lt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7814e5796402b44a7ee813a2bd5c23eb">distributeMemberGroupDocumentation</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2718e48c3a7d884ef429b93487b7f83e">findSectionsInDocumentation</a> (const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df8307d8e3bad5587972fe4feff8541">numDecMembers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269280874f15bb88828ded24882ca4fe">numDecEnumValues</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cc7a88c6cd63de9c9e67fbfb619a29">numDocMembers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff78ad78777dce2bb18a5f8723c2580">numDocEnumValues</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e680180c8170971bda95c445f9e8fd9">container</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47a707dff2d9bbe606da2f4201dd1725">memberContainer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348cb6acf20ae8fcd79c9794e6531166">countInheritableMembers</a> (const ClassDef *inheritedFrom) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847857b04f0977eef02f896db366f18b">addListReferences</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64fc6bdd80d5cce30b106284d4649543">setRefItems</a> (const RefItemVector &amp;sli)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d6f9905934dcecd96a6f47036c00900">members</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac917d697ac387e35c72253fe6afec7b9">docFile</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acddbf4e98852c63461077bb29e80e00e">docLine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8679d2fc948fed9ee833c1fb5545f9">grpId</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c340c8bf8ddc9fb599875b972206ed6">fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a> = true</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m_docFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18983b9ac8859ed852f2376c8e95b447">m_docLine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af118cd2ec3faa65375b364f1a01ce256">m_xrefListItems</a></td>
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

<p>A class representing a group of members.</p>

<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### MemberGroup() {#a17798ab21bdf69de04afe3294c7005ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberGroup::MemberGroup (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * container, int id, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docs, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docFile, int docLine, <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449d">MemberListContainer</a> con)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00032">32</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17798ab21bdf69de04afe3294c7005ca">32</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup::MemberGroup</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;hdr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;d,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#ac917d697ac387e35c72253fe6afec7b9">docFile</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acddbf4e98852c63461077bb29e80e00e">docLine</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449d">MemberListContainer</a> con)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>(<a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a>&gt;(<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a>::<a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>(),con)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9d8679d2fc948fed9ee833c1fb5545f9">grpId</a>(id), <a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a>(hdr), <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>(d), <a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m_docFile</a>(<a href="#ac917d697ac387e35c72253fe6afec7b9">docFile</a>), <a href="#a18983b9ac8859ed852f2376c8e95b447">m_docLine</a>(<a href="#acddbf4e98852c63461077bb29e80e00e">docLine</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("New member group id=%d header=%s desc=%s\n",id,hdr,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;setNeedsSorting(<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SORT_BRIEF_DOCS)); </span><span class="doxyHighlightComment">// detailed sections are already sorted elsewhere.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Member group docs='%s'\n",qPrint(doc));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>, <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>, <a href="#ac917d697ac387e35c72253fe6afec7b9">docFile</a>, <a href="#acddbf4e98852c63461077bb29e80e00e">docLine</a>, <a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a>, <a href="#a9d8679d2fc948fed9ee833c1fb5545f9">grpId</a>, <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m&#95;container</a>, <a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m&#95;docFile</a>, <a href="#a18983b9ac8859ed852f2376c8e95b447">m&#95;docLine</a>, <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.

Referenced by <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGroupedInheritedMembers() {#a298db4223e61135eb6da36ade9c00c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::addGroupedInheritedMembers (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00063">63</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00121">121</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a298db4223e61135eb6da36ade9c00c02">121</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a298db4223e61135eb6da36ade9c00c02">MemberGroup::addGroupedInheritedMembers</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("** addGroupedInheritedMembers()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("matching %d == %d\n",lt,md-&gt;getSectionList()-&gt;listType());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml = md-&gt;getSectionList(<a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml &amp;&amp; lt==ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> mml(lt,<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da9bd81329febf6efe22788e03ddeaf0af">MemberListContainer::Class</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      mml.<a href="/web-doxygen/docs/api/classes/membervector/#ae8265ec4f4b9b33ae0ddc0341f84433f">push_back</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">      mml.<a href="/web-doxygen/docs/api/classes/memberlist/#ab3cff28cc4778300689c569599582b9b">countDecMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">      mml.<a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">writePlainDeclarations</a>(ol,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,cd,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,0,inheritedFrom,inheritId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449da9bd81329febf6efe22788e03ddeaf0af">Class</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#ab3cff28cc4778300689c569599582b9b">MemberList::countDecMembers</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m&#95;container</a>, <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>, <a href="/web-doxygen/docs/api/classes/membervector/#ae8265ec4f4b9b33ae0ddc0341f84433f">MemberVector::push&#95;back</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>.
</div>
</div>

### addListReferences() {#a847857b04f0977eef02f896db366f18b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::addListReferences (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00084">84</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00267">267</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a847857b04f0977eef02f896db366f18b">267</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a847857b04f0977eef02f896db366f18b">MemberGroup::addListReferences</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;addListReferences(def);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### addToDeclarationSection() {#a1dc30e752b0c36ee2be1716ff8d83856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::addToDeclarationSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Add this group as a subsection of the declaration section, instead of rendering it in its own section</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00070">70</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00160">160</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1dc30e752b0c36ee2be1716ff8d83856">160</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1dc30e752b0c36ee2be1716ff8d83856">MemberGroup::addToDeclarationSection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Adding group %p to list %p (type=%d) memberList=%p\n",this,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//                             inDeclSection,inDeclSection-&gt;listType(),memberList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a>-&gt;addMemberGroup(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a>.
</div>
</div>

### allMembersInSameSection() {#a5e54a4524c532b3893ea2f810fbdbeb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemberGroup::allMembersInSameSection ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00069">69</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e54a4524c532b3893ea2f810fbdbeb5">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5e54a4524c532b3893ea2f810fbdbeb5">allMembersInSameSection</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a>; }</span></span></div>

</div>


Reference <a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a>.
</div>
</div>

### container() {#a1e680180c8170971bda95c445f9e8fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * MemberGroup::container ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00080">80</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00180">180</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e680180c8170971bda95c445f9e8fd9">180</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a1e680180c8170971bda95c445f9e8fd9">MemberGroup::container</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m&#95;container</a>.

Referenced by <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>, <a href="#a4e87b521c1766f9bfe0be171213660ea">writeDocumentation</a> and <a href="#a55915e6ca60ab6cd13d6d257bd916d60">writeDocumentationPage</a>.
</div>
</div>

### countDecMembers() {#a8087668389d7c351fe4574060f5c710d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::countDecMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00071">71</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00170">170</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8087668389d7c351fe4574060f5c710d">170</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8087668389d7c351fe4574060f5c710d">MemberGroup::countDecMembers</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;countDecMembers();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### countDocMembers() {#a9f32d80074cdb79883017c7670146e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::countDocMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00072">72</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00175">175</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f32d80074cdb79883017c7670146e98">175</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9f32d80074cdb79883017c7670146e98">MemberGroup::countDocMembers</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;countDocMembers();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### countGroupedInheritedMembers() {#a9134204269c78e233a4160a10653a04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::countGroupedInheritedMembers (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00073">73</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00140">140</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9134204269c78e233a4160a10653a04f">140</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a9134204269c78e233a4160a10653a04f">MemberGroup::countGroupedInheritedMembers</a>(<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("** countGroupedInheritedMembers()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("matching %d == %d\n",lt,md-&gt;getSectionList()-&gt;listType());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml = md-&gt;getSectionList(<a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml &amp;&amp; lt==ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">      count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m&#95;container</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### countInheritableMembers() {#a348cb6acf20ae8fcd79c9794e6531166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::countInheritableMembers (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00083">83</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00202">202</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a348cb6acf20ae8fcd79c9794e6531166">202</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a348cb6acf20ae8fcd79c9794e6531166">MemberGroup::countInheritableMembers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;countInheritableMembers(inheritedFrom);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### distributeMemberGroupDocumentation() {#a7814e5796402b44a7ee813a2bd5c23eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::distributeMemberGroupDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00074">74</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00208">208</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7814e5796402b44a7ee813a2bd5c23eb">208</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7814e5796402b44a7ee813a2bd5c23eb">MemberGroup::distributeMemberGroupDocumentation</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("MemberGroup::distributeMemberGroupDocumentation() %s\n",qPrint(grpHeader));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;smd : *<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("checking md=%s\n",qPrint(md-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// find the first member of the group with documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!smd-&gt;documentation().isEmpty()       ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">        !smd-&gt;briefDescription().isEmpty()    ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">        !smd-&gt;inbodyDocumentation().isEmpty()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("found it!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      md = smd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md) </span><span class="doxyHighlightComment">// distribute docs of md to other members of the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Member %s has documentation!\n",qPrint(md-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;iomd : *<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *omd = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(iomd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (omd &amp;&amp; md!=omd &amp;&amp; omd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">                            omd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">                            omd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Copying documentation to member %s\n",qPrint(omd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">        omd-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">setBriefDescription</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">briefFile</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">briefLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">        omd-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">setDocumentation</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">        omd-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a8a4d82f0315802612dcd9732369eaa8a">setInbodyDocumentation</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">inbodyDocumentation</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af6fd6ee64e4e2599c1cb7cba93897aa7">inbodyFile</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a74cb27736839a0e602ef5fa9bbb9deab">inbodyLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">Definition::briefFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">Definition::briefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#af59473951772c62b9db328e342fc2198">Definition::inbodyDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#af6fd6ee64e4e2599c1cb7cba93897aa7">Definition::inbodyFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a74cb27736839a0e602ef5fa9bbb9deab">Definition::inbodyLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">DefinitionMutable::setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">DefinitionMutable::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a8a4d82f0315802612dcd9732369eaa8a">DefinitionMutable::setInbodyDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>.
</div>
</div>

### docFile() {#ac917d697ac387e35c72253fe6afec7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberGroup::docFile ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00088">88</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac917d697ac387e35c72253fe6afec7b9">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac917d697ac387e35c72253fe6afec7b9">docFile</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m_docFile</a>; }</span></span></div>

</div>


Reference <a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m&#95;docFile</a>.

Referenced by <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

### docLine() {#acddbf4e98852c63461077bb29e80e00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::docLine ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00089">89</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acddbf4e98852c63461077bb29e80e00e">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acddbf4e98852c63461077bb29e80e00e">docLine</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a18983b9ac8859ed852f2376c8e95b447">m_docLine</a>; }</span></span></div>

</div>


Reference <a href="#a18983b9ac8859ed852f2376c8e95b447">m&#95;docLine</a>.

Referenced by <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

### documentation() {#ae9bfe64caa099a821c650b927e4ac514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString &amp; MemberGroup::documentation ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00068">68</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9bfe64caa099a821c650b927e4ac514">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#ae9bfe64caa099a821c650b927e4ac514">documentation</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>; }</span></span></div>

</div>


Reference <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>.
</div>
</div>

### findSectionsInDocumentation() {#a2718e48c3a7d884ef429b93487b7f83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::findSectionsInDocumentation (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00075">75</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00272">272</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2718e48c3a7d884ef429b93487b7f83e">272</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2718e48c3a7d884ef429b93487b7f83e">MemberGroup::findSectionsInDocumentation</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a0fc0d3e4ca95dd0dc254d0efb1fd045a">docFindSections</a>(<a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>,d,<a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m_docFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;findSectionsInDocumentation(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a0fc0d3e4ca95dd0dc254d0efb1fd045a">docFindSections</a>, <a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m&#95;docFile</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### groupId() {#a25d5f6dce1695c96eaddefd8b54fce43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::groupId ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00049">49</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25d5f6dce1695c96eaddefd8b54fce43">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a25d5f6dce1695c96eaddefd8b54fce43">groupId</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9d8679d2fc948fed9ee833c1fb5545f9">grpId</a>; }</span></span></div>

</div>


Reference <a href="#a9d8679d2fc948fed9ee833c1fb5545f9">grpId</a>.
</div>
</div>

### header() {#a918bd808efb147a24b25c5246425d5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberGroup::header ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00048">48</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a918bd808efb147a24b25c5246425d5bf">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a918bd808efb147a24b25c5246425d5bf">header</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a>; }</span></span></div>

</div>


Reference <a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a>.
</div>
</div>

### insertMember() {#ad7b02bac5d0ed254d5c979b19cf4ae1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::insertMember (<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00050">50</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">44</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a>(<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("MemberGroup::insertMember(%s) inSameSection=%d md-&gt;getSectionList()=%s\n",qPrint(md-&gt;name()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    inSameSection,qPrint(md-&gt;getSectionList(m_container)-&gt;listType().to_string()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *firstMd = <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;empty() ? nullptr : <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a> &amp;&amp; firstMd &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      firstMd-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab001f5a231830270bac7da746201c02e">getSectionList</a>(<a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>)!=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab001f5a231830270bac7da746201c02e">getSectionList</a>(<a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("inSameSection=FALSE\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a>==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a> = </span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab001f5a231830270bac7da746201c02e">getSectionList</a>(<a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("inDeclSection=%p type=%d\n",inDeclSection,inDeclSection-&gt;listType());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;push_back(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// copy the group of the first member in the memberGroup</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (firstMd &amp;&amp; !firstMd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac64bb0cde04aa2eed0e2a439d0a17c8e">isAlias</a>() &amp;&amp; (gd=firstMd-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      mdm-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">setGroupDef</a>(gd, firstMd-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">                       firstMd-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#acb9da3d6b3e2f3e8102ee9a3380c0746">getGroupFileName</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">                       firstMd-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5d3b273949bc92e2b88e981aebc789bd">getGroupStartLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">                       firstMd-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#aae7c161ee9febb2cb5ea6ed3dc74176e">insertMember</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">MemberDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#acb9da3d6b3e2f3e8102ee9a3380c0746">MemberDef::getGroupFileName</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a01cb4b118d46ca86b9475e1d243560b1">MemberDef::getGroupHasDocs</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a9ed95e7cef3948c6a978540c0d48bca7">MemberDef::getGroupPri</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5d3b273949bc92e2b88e981aebc789bd">MemberDef::getGroupStartLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab001f5a231830270bac7da746201c02e">MemberDef::getSectionList</a>, <a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a>, <a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#aae7c161ee9febb2cb5ea6ed3dc74176e">GroupDef::insertMember</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac64bb0cde04aa2eed0e2a439d0a17c8e">Definition::isAlias</a>, <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m&#95;container</a>, <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#ac1ea8d9adeeef3466a0b36b20aa8ca8e">MemberDefMutable::setGroupDef</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a>.
</div>
</div>

### memberContainer() {#a47a707dff2d9bbe606da2f4201dd1725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * MemberGroup::memberContainer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00081">81</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00185">185</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47a707dff2d9bbe606da2f4201dd1725">185</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a47a707dff2d9bbe606da2f4201dd1725">MemberGroup::memberContainer</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// return the container for the first member.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Note this can be different from container() in case</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// the member is rendered as part of a file but the members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// are actually of a namespace.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a> &amp;&amp; !<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    ctx = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) ctx = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) ctx = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ctx==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> ? <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a> : ctx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a900cace4959b6cad9e6aa58e8283195f">MemberDef::getNamespaceDef</a>, <a href="#ae8bd9cbfeab2545946c46eef9ba53400">m&#95;container</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### members() {#a2d6f9905934dcecd96a6f47036c00900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberList &amp; MemberGroup::members ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00086">86</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d6f9905934dcecd96a6f47036c00900">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> &amp;<a href="#a2d6f9905934dcecd96a6f47036c00900">members</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.get(); }</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### numDecEnumValues() {#a269280874f15bb88828ded24882ca4fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::numDecEnumValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00077">77</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00252">252</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a269280874f15bb88828ded24882ca4fe">252</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a269280874f15bb88828ded24882ca4fe">MemberGroup::numDecEnumValues</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;numDecEnumValues();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### numDecMembers() {#a1df8307d8e3bad5587972fe4feff8541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::numDecMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00076">76</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00247">247</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1df8307d8e3bad5587972fe4feff8541">247</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a1df8307d8e3bad5587972fe4feff8541">MemberGroup::numDecMembers</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;numDecMembers();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### numDocEnumValues() {#a9ff78ad78777dce2bb18a5f8723c2580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::numDocEnumValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00079">79</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00262">262</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ff78ad78777dce2bb18a5f8723c2580">262</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a9ff78ad78777dce2bb18a5f8723c2580">MemberGroup::numDocEnumValues</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;numDocEnumValues();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### numDocMembers() {#a58cc7a88c6cd63de9c9e67fbfb619a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::numDocMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00257">257</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a58cc7a88c6cd63de9c9e67fbfb619a29">257</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a58cc7a88c6cd63de9c9e67fbfb619a29">MemberGroup::numDocMembers</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;numDocMembers();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### setAnchors() {#a325068f062701fe19500cfe9f88e9ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::setAnchors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00051">51</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00080">80</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a325068f062701fe19500cfe9f88e9ef2">80</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a325068f062701fe19500cfe9f88e9ef2">MemberGroup::setAnchors</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;setAnchors();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### setAnonymousEnumType() {#ae50c108b2749aff03ea41820f78f48f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::setAnonymousEnumType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00066">66</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00116">116</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae50c108b2749aff03ea41820f78f48f7">116</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae50c108b2749aff03ea41820f78f48f7">MemberGroup::setAnonymousEnumType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;setAnonymousEnumType();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### setRefItems() {#a64fc6bdd80d5cce30b106284d4649543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::setRefItems (const <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> &amp; sli)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00085">85</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00278">278</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64fc6bdd80d5cce30b106284d4649543">278</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64fc6bdd80d5cce30b106284d4649543">MemberGroup::setRefItems</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> &amp;sli)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af118cd2ec3faa65375b364f1a01ce256">m_xrefListItems</a>.insert(<a href="#af118cd2ec3faa65375b364f1a01ce256">m_xrefListItems</a>.end(), sli.cbegin(), sli.cend());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af118cd2ec3faa65375b364f1a01ce256">m&#95;xrefListItems</a>.
</div>
</div>

### writeDeclarations() {#a340fc8ac627f2f84ae3110d5f42480a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::writeDeclarations (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod, bool showInline=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00085">85</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a340fc8ac627f2f84ae3110d5f42480a1">85</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a340fc8ac627f2f84ae3110d5f42480a1">MemberGroup::writeDeclarations</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showInline)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("MemberGroup::writeDeclarations() %s\n",qPrint(grpHeader));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ldoc = <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;writeDeclarations(ol,cd,nd,fd,gd,mod,<a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a>,ldoc,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,showInline);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### writeDocumentation() {#a4e87b521c1766f9bfe0be171213660ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * container, bool showEnumValues, bool showInline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00103">103</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e87b521c1766f9bfe0be171213660ea">103</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4e87b521c1766f9bfe0be171213660ea">MemberGroup::writeDocumentation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showEnumValues,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showInline)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("MemberGroup::writeDocumentation() %s\n",qPrint(grpHeader));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;writeDocumentation(ol,scopeName,<a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;listType().toLabel(),showEnumValues,showInline);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1e680180c8170971bda95c445f9e8fd9">container</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### writeDocumentationPage() {#a55915e6ca60ab6cd13d6d257bd916d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::writeDocumentationPage (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00060">60</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00110">110</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55915e6ca60ab6cd13d6d257bd916d60">110</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a55915e6ca60ab6cd13d6d257bd916d60">MemberGroup::writeDocumentationPage</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *<a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;writeDocumentationPage(ol,scopeName,<a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1e680180c8170971bda95c445f9e8fd9">container</a> and <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### writePlainDeclarations() {#ac126af1f687acb4c1067eb3307e733da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::writePlainDeclarations (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, bool inGroup, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod, int indentLevel, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00094">94</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac126af1f687acb4c1067eb3307e733da">94</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac126af1f687acb4c1067eb3307e733da">MemberGroup::writePlainDeclarations</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inGroup,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indentLevel,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("MemberGroup::writePlainDeclarations() memberList-&gt;count()=%d\n",memberList-&gt;count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;writePlainDeclarations(ol,inGroup,cd,nd,fd,gd,mod,indentLevel,inheritedFrom,inheritId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

### writeTagFile() {#a8c72b6c09af02d25cfeca6a1779bf47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemberGroup::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; tagFile, bool qualifiedName=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00062">62</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-cpp/#l00283">283</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c72b6c09af02d25cfeca6a1779bf47d">283</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c72b6c09af02d25cfeca6a1779bf47d">MemberGroup::writeTagFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;tagFile,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> qualifiedName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>-&gt;writeTagFile(tagFile,qualifiedName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### doc {#ad47e2e80677fc1d17a849b4b4c8c308a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberGroup::doc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00098">98</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad47e2e80677fc1d17a849b4b4c8c308a">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad47e2e80677fc1d17a849b4b4c8c308a">doc</a>;</span></span></div>

</div>


Referenced by <a href="#ae9bfe64caa099a821c650b927e4ac514">documentation</a>, <a href="#a2718e48c3a7d884ef429b93487b7f83e">findSectionsInDocumentation</a>, <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a> and <a href="#a340fc8ac627f2f84ae3110d5f42480a1">writeDeclarations</a>.
</div>
</div>

### fileName {#a7c340c8bf8ddc9fb599875b972206ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberGroup::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00097">97</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c340c8bf8ddc9fb599875b972206ed6">97</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7c340c8bf8ddc9fb599875b972206ed6">fileName</a>;           </span><span class="doxyHighlightComment">// base name of the generated file</span></span></div>

</div>

</div>
</div>

### grpHeader {#afc95ff9392193c0e867ec5e1a15332d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberGroup::grpHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00096">96</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc95ff9392193c0e867ec5e1a15332d4">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#afc95ff9392193c0e867ec5e1a15332d4">grpHeader</a>;</span></span></div>

</div>


Referenced by <a href="#a918bd808efb147a24b25c5246425d5bf">header</a>, <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a> and <a href="#a340fc8ac627f2f84ae3110d5f42480a1">writeDeclarations</a>.
</div>
</div>

### grpId {#a9d8679d2fc948fed9ee833c1fb5545f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::grpId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00095">95</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9d8679d2fc948fed9ee833c1fb5545f9">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a9d8679d2fc948fed9ee833c1fb5545f9">grpId</a> = 0;</span></span></div>

</div>


Referenced by <a href="#a25d5f6dce1695c96eaddefd8b54fce43">groupId</a> and <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

### inDeclSection {#afb3c989e974138d44fab79ce1a321971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberList* MemberGroup::inDeclSection = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00094">94</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb3c989e974138d44fab79ce1a321971">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *<a href="#afb3c989e974138d44fab79ce1a321971">inDeclSection</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a1dc30e752b0c36ee2be1716ff8d83856">addToDeclarationSection</a> and <a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">insertMember</a>.
</div>
</div>

### inSameSection {#a0b7d8f05fe65b9d4a87b3e95cbe498ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemberGroup::inSameSection = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00099">99</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0b7d8f05fe65b9d4a87b3e95cbe498ea">inSameSection</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a5e54a4524c532b3893ea2f810fbdbeb5">allMembersInSameSection</a> and <a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">insertMember</a>.
</div>
</div>

### m&#95;container {#ae8bd9cbfeab2545946c46eef9ba53400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* MemberGroup::m_container</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00092">92</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8bd9cbfeab2545946c46eef9ba53400">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#ae8bd9cbfeab2545946c46eef9ba53400">m_container</a>;</span></span></div>

</div>


Referenced by <a href="#a298db4223e61135eb6da36ade9c00c02">addGroupedInheritedMembers</a>, <a href="#a1e680180c8170971bda95c445f9e8fd9">container</a>, <a href="#a9134204269c78e233a4160a10653a04f">countGroupedInheritedMembers</a>, <a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">insertMember</a>, <a href="#a47a707dff2d9bbe606da2f4201dd1725">memberContainer</a> and <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

### m&#95;docFile {#ae49f7e0dd66e5fd58e52d2e216a0f798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString MemberGroup::m_docFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00100">100</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae49f7e0dd66e5fd58e52d2e216a0f798">m_docFile</a>;</span></span></div>

</div>


Referenced by <a href="#ac917d697ac387e35c72253fe6afec7b9">docFile</a>, <a href="#a2718e48c3a7d884ef429b93487b7f83e">findSectionsInDocumentation</a> and <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

### m&#95;docLine {#a18983b9ac8859ed852f2376c8e95b447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int MemberGroup::m_docLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00101">101</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18983b9ac8859ed852f2376c8e95b447">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a18983b9ac8859ed852f2376c8e95b447">m_docLine</a>;</span></span></div>

</div>


Referenced by <a href="#acddbf4e98852c63461077bb29e80e00e">docLine</a> and <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>.
</div>
</div>

### m&#95;xrefListItems {#af118cd2ec3faa65375b364f1a01ce256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefItemVector MemberGroup::m_xrefListItems</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00102">102</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af118cd2ec3faa65375b364f1a01ce256">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a> <a href="#af118cd2ec3faa65375b364f1a01ce256">m_xrefListItems</a>;</span></span></div>

</div>


Referenced by <a href="#a64fc6bdd80d5cce30b106284d4649543">setRefItems</a>.
</div>
</div>

### memberList {#af5136254d93ca9a6fd5021ec2ea8f849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemberList&gt; MemberGroup::memberList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/membergroup-h/#l00093">93</a> of file <a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5136254d93ca9a6fd5021ec2ea8f849">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;MemberList&gt; <a href="#af5136254d93ca9a6fd5021ec2ea8f849">memberList</a>;      </span><span class="doxyHighlightComment">// list of all members in the group</span></span></div>

</div>


Referenced by <a href="#a298db4223e61135eb6da36ade9c00c02">addGroupedInheritedMembers</a>, <a href="#a847857b04f0977eef02f896db366f18b">addListReferences</a>, <a href="#a8087668389d7c351fe4574060f5c710d">countDecMembers</a>, <a href="#a9f32d80074cdb79883017c7670146e98">countDocMembers</a>, <a href="#a9134204269c78e233a4160a10653a04f">countGroupedInheritedMembers</a>, <a href="#a348cb6acf20ae8fcd79c9794e6531166">countInheritableMembers</a>, <a href="#a7814e5796402b44a7ee813a2bd5c23eb">distributeMemberGroupDocumentation</a>, <a href="#a2718e48c3a7d884ef429b93487b7f83e">findSectionsInDocumentation</a>, <a href="#ad7b02bac5d0ed254d5c979b19cf4ae1e">insertMember</a>, <a href="#a47a707dff2d9bbe606da2f4201dd1725">memberContainer</a>, <a href="#a17798ab21bdf69de04afe3294c7005ca">MemberGroup</a>, <a href="#a2d6f9905934dcecd96a6f47036c00900">members</a>, <a href="#a269280874f15bb88828ded24882ca4fe">numDecEnumValues</a>, <a href="#a1df8307d8e3bad5587972fe4feff8541">numDecMembers</a>, <a href="#a9ff78ad78777dce2bb18a5f8723c2580">numDocEnumValues</a>, <a href="#a58cc7a88c6cd63de9c9e67fbfb619a29">numDocMembers</a>, <a href="#a325068f062701fe19500cfe9f88e9ef2">setAnchors</a>, <a href="#ae50c108b2749aff03ea41820f78f48f7">setAnonymousEnumType</a>, <a href="#a340fc8ac627f2f84ae3110d5f42480a1">writeDeclarations</a>, <a href="#a4e87b521c1766f9bfe0be171213660ea">writeDocumentation</a>, <a href="#a55915e6ca60ab6cd13d6d257bd916d60">writeDocumentationPage</a>, <a href="#ac126af1f687acb4c1067eb3307e733da">writePlainDeclarations</a> and <a href="#a8c72b6c09af02d25cfeca6a1779bf47d">writeTagFile</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/membergroup-cpp">membergroup.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
