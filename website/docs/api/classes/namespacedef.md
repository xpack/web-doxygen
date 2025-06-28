---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/namespacedef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `NamespaceDef` Class Reference

<p>An abstract interface of a namespace symbol. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class NamespaceDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/namespacedef-h">src/namespacedef.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition">Definition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The common base class of all entity definitions found in the sources. <a href="/web-doxygen/docs/api/classes/definition/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionaliasmixin">DefinitionAliasMixin&lt;Base&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedefmutable">NamespaceDefMutable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab45b155dd9bed40afe75c89ca43314">numDocMembers</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&lt; <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742c3ca27e3383a1495dd972aaf6b43b">getUsedNamespaces</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/linkedrefmap">LinkedRefMap</a>&lt; const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae894d3e60b106c127ed42266ec7d6e83">getUsedDefinitions</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36bd16cdea38963a5989a39bc8a9a776">isConstantGroup</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987a55277c2c4c9c1c3079eed406b46a">isModule</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d90bb7360567e4d376198a164e05f3">isLibrary</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69a1e5ab023bbf6017a0600c0844977">isInline</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab71f0f1f9f1dc5a1377ebfcd97759d8e">isVisibleInHierarchy</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf9627481a1469543ebac09f09af8f31">hasDetailedDescription</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00feb50dd08718e4bb7d29b86ec3daf">subGrouping</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a> (MemberListType lt) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d1b06c7331164f6562cb5f19d69c023">getMemberLists</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfeac05d3bebefde162e271a1d9e6b24">getMemberByName</a> (const QCString &amp;) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a3c112d07ba84402099c66a6bda130">countVisibleMembers</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf62c808c557f44997b866855615199">getMemberGroups</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43237a69f056b45fc87beed091688d5">getClasses</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5d69194a246277c1ac27efe392a085c">getInterfaces</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c5e7b84cb85d95090306d81ec55a676">getStructs</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf1f663e03f57dd359aaacf71c2e3be">getExceptions</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap">NamespaceLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap">ConceptLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a393d5ddac9a98c0f829b7866cce931dc">getConcepts</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac592520c3e9e8f2e633b2fae7375ccae">title</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6189830ef990cb1f6c91c8df8e4885cd">compoundTypeString</a> () const =0</td>
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

<p>An abstract interface of a namespace symbol.</p>

<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### compoundTypeString() {#a6189830ef990cb1f6c91c8df8e4885cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString NamespaceDef::compoundTypeString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a6189830ef990cb1f6c91c8df8e4885cd">compoundTypeString</a>.

Referenced by <a href="#a6189830ef990cb1f6c91c8df8e4885cd">compoundTypeString</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#acdd0830790b3ade8b139295f5e270394">NamespaceDefAliasImpl::compoundTypeString</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1d51f3aad1177695f1c4a6c1340bfa0b">MemberDefImpl::warnIfUndocumented</a>.
</div>
</div>

### countVisibleMembers() {#aa7a3c112d07ba84402099c66a6bda130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int NamespaceDef::countVisibleMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#aa7a3c112d07ba84402099c66a6bda130">countVisibleMembers</a>.

Referenced by <a href="#aa7a3c112d07ba84402099c66a6bda130">countVisibleMembers</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a9ca40f072f59d9b013f8e770ef5d1751">NamespaceDefAliasImpl::countVisibleMembers</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.
</div>
</div>

### getClasses() {#ad43237a69f056b45fc87beed091688d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassLinkedRefMap NamespaceDef::getClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the classes contained in this namespace</p>

<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#ad43237a69f056b45fc87beed091688d5">getClasses</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="#ad43237a69f056b45fc87beed091688d5">getClasses</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a45886353b1f74fbdcec6478a26041092">NamespaceDefAliasImpl::getClasses</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.
</div>
</div>

### getConcepts() {#a393d5ddac9a98c0f829b7866cce931dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ConceptLinkedRefMap NamespaceDef::getConcepts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the concepts contained in this namespace</p>

<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a393d5ddac9a98c0f829b7866cce931dc">getConcepts</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="#a393d5ddac9a98c0f829b7866cce931dc">getConcepts</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a31117c3b465c0c6a8d06e6332a3cda7b">NamespaceDefAliasImpl::getConcepts</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.
</div>
</div>

### getExceptions() {#a7cf1f663e03f57dd359aaacf71c2e3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassLinkedRefMap NamespaceDef::getExceptions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the Slice exceptions contained in this namespace</p>

<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a7cf1f663e03f57dd359aaacf71c2e3be">getExceptions</a>.

Referenced by <a href="#a7cf1f663e03f57dd359aaacf71c2e3be">getExceptions</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a1fa88b18ae9b86334d933ba175a2fd52">NamespaceDefAliasImpl::getExceptions</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>.
</div>
</div>

### getInterfaces() {#ae5d69194a246277c1ac27efe392a085c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassLinkedRefMap NamespaceDef::getInterfaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the Slice interfaces contained in this namespace</p>

<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#ae5d69194a246277c1ac27efe392a085c">getInterfaces</a>.

Referenced by <a href="#ae5d69194a246277c1ac27efe392a085c">getInterfaces</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a077d79523e5fbede6237ec022af237f4">NamespaceDefAliasImpl::getInterfaces</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>.
</div>
</div>

### getMemberByName() {#abfeac05d3bebefde162e271a1d9e6b24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * NamespaceDef::getMemberByName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#abfeac05d3bebefde162e271a1d9e6b24">getMemberByName</a>.

Referenced by <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="#abfeac05d3bebefde162e271a1d9e6b24">getMemberByName</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a21b0ea6a1dcb7167b6a625fd1b26f47e">NamespaceDefAliasImpl::getMemberByName</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>.
</div>
</div>

### getMemberGroups() {#aedf62c808c557f44997b866855615199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberGroupList &amp; NamespaceDef::getMemberGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the user defined member groups</p>

<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#aedf62c808c557f44997b866855615199">getMemberGroups</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="#aedf62c808c557f44997b866855615199">getMemberGroups</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a86082636b09077cb1280285678e08438">NamespaceDefAliasImpl::getMemberGroups</a>.
</div>
</div>

### getMemberList() {#a2a67c423c453ef9275729a7e9b5b4b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberList * NamespaceDef::getMemberList (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#af7618d7d3aeddf3aae435cd00b9293e9">generateDEFForNamespace</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a>, <a href="#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ac4301785a516040bcf0c15927a4e1c42">NamespaceDefAliasImpl::getMemberList</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a56fd407208531785588bf3482ac098b9">writeNamespaceMembers</a>.
</div>
</div>

### getMemberLists() {#a8d1b06c7331164f6562cb5f19d69c023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberLists &amp; NamespaceDef::getMemberLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a8d1b06c7331164f6562cb5f19d69c023">getMemberLists</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="#a8d1b06c7331164f6562cb5f19d69c023">getMemberLists</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#aecb3ff5ed5682451aa92a143b76934e4">NamespaceDefAliasImpl::getMemberLists</a>.
</div>
</div>

### getNamespaces() {#a948889b7a35fb82ebcdf2598a63e1d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual NamespaceLinkedRefMap NamespaceDef::getNamespaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the namespaces contained in this namespace</p>

<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ad1a0e44c6927b35bd8f268e29cb468c9">NamespaceDefAliasImpl::getNamespaces</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#abd70ea7f48a1498038b7b1426813401c">hasNonReferenceNestedNamespaceRec</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#af84e6fea0b6f07072eab35b1569fd357">namespaceHasNestedConcept</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a061ac5e55a8b63f2c06e1f4e272cb011">namespaceHasNestedNamespace</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.
</div>
</div>

### getStructs() {#a5c5e7b84cb85d95090306d81ec55a676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassLinkedRefMap NamespaceDef::getStructs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Returns the Slice structs contained in this namespace</p>

<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a5c5e7b84cb85d95090306d81ec55a676">getStructs</a>.

Referenced by <a href="#a5c5e7b84cb85d95090306d81ec55a676">getStructs</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a304b7989f19c9fefd6eac47b731ff6ee">NamespaceDefAliasImpl::getStructs</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a3d15fcf5c959d5ce9db005cba5692094">namespaceHasNestedClass</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>.
</div>
</div>

### getUsedDefinitions() {#ae894d3e60b106c127ed42266ec7d6e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const LinkedRefMap&lt; const Definition &gt; &amp; NamespaceDef::getUsedDefinitions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#ae894d3e60b106c127ed42266ec7d6e83">getUsedDefinitions</a>.

Referenced by <a href="#ae894d3e60b106c127ed42266ec7d6e83">getUsedDefinitions</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a88f2c51032a15c826827e87c0be4061d">NamespaceDefAliasImpl::getUsedDefinitions</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>.
</div>
</div>

### getUsedNamespaces() {#a742c3ca27e3383a1495dd972aaf6b43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const LinkedRefMap&lt; NamespaceDef &gt; &amp; NamespaceDef::getUsedNamespaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a742c3ca27e3383a1495dd972aaf6b43b">getUsedNamespaces</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="#a742c3ca27e3383a1495dd972aaf6b43b">getUsedNamespaces</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ad4138e1c20e5c0bde1e3f7ce79f07381">NamespaceDefAliasImpl::getUsedNamespaces</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>.
</div>
</div>

### hasDetailedDescription() {#aaf9627481a1469543ebac09f09af8f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::hasDetailedDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#aaf9627481a1469543ebac09f09af8f31">hasDetailedDescription</a>.

Referenced by <a href="#aaf9627481a1469543ebac09f09af8f31">hasDetailedDescription</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ac1287ef8f39810abb59b45998b43011a">NamespaceDefAliasImpl::hasDetailedDescription</a>.
</div>
</div>

### isConstantGroup() {#a36bd16cdea38963a5989a39bc8a9a776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::isConstantGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a36bd16cdea38963a5989a39bc8a9a776">isConstantGroup</a>.

Referenced by <a href="#a36bd16cdea38963a5989a39bc8a9a776">isConstantGroup</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#af4e92fc2fdb6572e50fd93bd492e3884">NamespaceDefAliasImpl::isConstantGroup</a>.
</div>
</div>

### isInline() {#ab69a1e5ab023bbf6017a0600c0844977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::isInline ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#ab69a1e5ab023bbf6017a0600c0844977">isInline</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="#ab69a1e5ab023bbf6017a0600c0844977">isInline</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ace55b80d09d93f88a247ea51577567b4">NamespaceDefAliasImpl::isInline</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a> and <a href="/web-doxygen/docs/api/classes/namespacedefmutable/#ab41129b22b4eac9adde902522bcca6c2">NamespaceDefMutable::setInline</a>.
</div>
</div>

### isLibrary() {#a27d90bb7360567e4d376198a164e05f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::isLibrary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a27d90bb7360567e4d376198a164e05f3">isLibrary</a>.

Referenced by <a href="#a27d90bb7360567e4d376198a164e05f3">isLibrary</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ac0dd979289f75812099f1982e1a860aa">NamespaceDefAliasImpl::isLibrary</a>.
</div>
</div>

### isModule() {#a987a55277c2c4c9c1c3079eed406b46a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::isModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#a987a55277c2c4c9c1c3079eed406b46a">isModule</a>.

Referenced by <a href="#a987a55277c2c4c9c1c3079eed406b46a">isModule</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#acd2f8b1c562b8399379593fe3f7c5478">NamespaceDefAliasImpl::isModule</a>.
</div>
</div>

### isVisibleInHierarchy() {#ab71f0f1f9f1dc5a1377ebfcd97759d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::isVisibleInHierarchy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#ab71f0f1f9f1dc5a1377ebfcd97759d8e">isVisibleInHierarchy</a>.

Referenced by <a href="#ab71f0f1f9f1dc5a1377ebfcd97759d8e">isVisibleInHierarchy</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#ac2d05724ca7618644365d49b32acfee7">NamespaceDefAliasImpl::isVisibleInHierarchy</a>.
</div>
</div>

### numDocMembers() {#aaab45b155dd9bed40afe75c89ca43314}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int NamespaceDef::numDocMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#aaab45b155dd9bed40afe75c89ca43314">numDocMembers</a>.

Referenced by <a href="#aaab45b155dd9bed40afe75c89ca43314">numDocMembers</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a8064863d62950847194fb6bf9e0b8e1f">NamespaceDefAliasImpl::numDocMembers</a>.
</div>
</div>

### subGrouping() {#aa00feb50dd08718e4bb7d29b86ec3daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool NamespaceDef::subGrouping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#aa00feb50dd08718e4bb7d29b86ec3daf">subGrouping</a>.

Referenced by <a href="#aa00feb50dd08718e4bb7d29b86ec3daf">subGrouping</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a134d46b504ba3d3c9c3318d302627494">NamespaceDefAliasImpl::subGrouping</a>.
</div>
</div>

### title() {#ac592520c3e9e8f2e633b2fae7375ccae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString NamespaceDef::title ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>.</p>

Reference <a href="#ac592520c3e9e8f2e633b2fae7375ccae">title</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ad5597180db00f8bb26d51d9b3b409241">generateSqlite3ForNamespace</a>, <a href="#ac592520c3e9e8f2e633b2fae7375ccae">title</a> and <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a621e8fd95932df699d95999b32c6fcb7">NamespaceDefAliasImpl::title</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
