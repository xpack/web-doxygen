---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/memberdef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `MemberDef` Class Reference

A model of a class/file/namespace member symbol. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class MemberDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/memberdef-h">src/memberdef.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9b10308c1c2590cbb82f2eff52d5ce5">deepCopy</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff323c90bda3ac08cae467b51061cdb">moveTo</a> (Definition *)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8366efce20df1bf0f096d6296189e474">resolveAlias</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f15f4ba2a99554f061c8091414d05b">resolveAlias</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1003f3dd9b61ac1d8e115600f8ffaa06">declaration</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc15da1d36aef0514a095c9ff485618">definition</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0032c6e040cdec6d9c52dc75a790a884">typeString</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfae3b8f49644ba27669daa9412e14a3">argsString</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ca4dbd8b0975ce3bf393a52a15e435">extraTypeChars</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed70a711fa3e8b02bcc7d5ae34fb92a">initializerLines</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3e5d2e532ebe2a0f45fe1a945fb4269">getMemberSpecifiers</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab001f5a231830270bac7da746201c02e">getSectionList</a> (const Definition *container) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a655ea55d777fb3ae96319be96f56323d">displayDefinition</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5036fd8ee16b186925236105029ee823">getFileDef</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ea166eb6883ec29aedb1d58eb5dc59">getFileDef</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ff70edee6691aacaeecf40a1146995">getClassDef</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbdd0e17187a9512364eeb42782df6a">getClassDef</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ef0d32e09ba0696f74c4651839ad73">getNamespaceDef</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3b6809f49a66d7d3f99f4b40ae6d47">getModuleDef</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e35fd33e87d41ebfe413d9ec63a44b">accessorClass</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d7b70952b14c1f6af79a16f122a6c9">getReadAccessor</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7638dcb798738c331ba2c2567118ceb6">getWriteAccessor</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ef09743c900283a46b2e0ecd81e486">getGroupDef</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/grouping/#a9f0ec5ab376b083ebe3274ea79fd2d70">Grouping::GroupPri_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9da3d6b3e2f3e8102ee9a3380c0746">getGroupFileName</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3b273949bc92e2b88e981aebc789bd">getGroupStartLine</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7228a0cbd28108dfab580c17d3f2751">objCMethodName</a> (bool localLink, bool showStatic) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab266b88c02dd8d5089b29d501b412c5d">protection</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae450a2be776cc5d05726bab8354f6d62">virtualness</a> (int count=0) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41">MemberType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbdaf88716807e7ff82ed7502cde51fc">memberType</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca314e25245ec3b08f1a55068c2fbeff">memberTypeName</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d2e041a0c3a89c0968b20869aa1981">isSignal</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db9f074e1f02c5dbf901d120fd433aa">isSlot</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b6f788b487058e9e6ac65b092479b9">isVariable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1ed0ba61a371a22b21dbd4d538e06c">isEnumValue</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f97f032bc09463bf950820e6431fdc5">isSequence</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b92d5888d4ff0b4ef5acc80d9ac76c7">isDictionary</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e6ace25ee464a601e1b3f2b8016ddad">isFunction</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9795a9ed4f86eca5ce5d39e88d21d36e">isFunctionPtr</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9a34fe614f8c55edc60deaf0143f47">isDefine</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a22a7e9394cf6e49ab6156274461d3">isFriend</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada93aac0fade61cc0018d94967e2a8e0">isDCOP</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4a6cd84468b885049120e767b017fc">isProperty</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b37ee8d3c1b7b10c2f38a6b8ca165f">isEvent</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a273e3f09760e57d718ee9d3c66f73eaa">isRelated</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b388162e65708a87857b9605cb63591">isForeign</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73354ecea5b876ab8d59724b080189b4">isStatic</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509e150708bb48d4bafaa1146cf1eadc">isInline</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa8429875443e986e04e34624c5c0c8">isExplicit</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af448f46a30d6337ef678db352dd244e3">isMutable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4783c1fa6a84a2beb2b4dad7000616">isGettable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594fe47b12073b186b7f1e4d8e2b1d56">isPrivateGettable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69883d56b1adfe457130d7c96873ba7">isProtectedGettable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b6a11c61d72073dcfc17d85a303ac5">isSettable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787020ca6fc65ea0cc13f5721d166420">isPrivateSettable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa51dd090dc6e2d111145cc04e9e3f7fe">isProtectedSettable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0cad08f28ef0b4e73fd13baefa56a8">isReadable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a562a056cb102eb78ad78fffe455a2db9">isWritable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496b02cff3e89cc59eab5139a9211475">isAddable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebd90ccb692199c14ef91526df6d534">isRemovable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0e45a5885e55221f756a8e3153fb8a">isRaisable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0c62b7d85f8eff11657f9a7e3f87f4">isFinal</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1601490373728611996a958bbfc38d3">isAbstract</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a02263fa1b55949b87c237f452d081c">isOverride</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a894331323ad650cd3b748ce9d604b">isInitonly</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41ecacc3c433253d893d6baded01de0">isOptional</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62549140ec2a398af9b6a72c63aad7d5">isRequired</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8981c87afa75a323943f727919c2669c">isNonAtomic</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6548961c5a9f2003ec5425bea0249ad2">isCopy</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09bc44df807bfe787766e6268b991732">isAssign</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4902c8d45c53057b6b421a22821d999b">isRetain</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14124f33e6513789346a840f5e49385">isWeak</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbdbd0e3d3630af579a02e97e162a328">isStrong</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30da3b2d7800741fb6c09a37069d6372">isEnumStruct</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8123dc4361300613c03c9d5a5e8883">isUnretained</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ceb921ed3647329a26b0c9ce434658d">isNew</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3f4fc396e748b60fd3f4057f0bba21">isSealed</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cec965870198c96a14371c694b2027">isImplementation</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a3294a87e2a6e2ff4a2d52bfd3187a">isExternal</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebab5c76a587caadf8f3079729625fd">isTypeAlias</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2693c2e5c943567acd971d7e15dc4304">isDefault</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21681601f9f6a421ca2a174d17841d06">isDelete</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ea035c8de361f0ba253fc45e3303f0">isNoExcept</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62780d0d926b1c17801dbba81921336a">isAttribute</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4cae75d9163036f5bc9a232dc880812">isUNOProperty</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8679a7213fda9304814aa989c731a4a9">isReadonly</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bb29ff5f9e049343bdb990b08ff9a3">isBound</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a42e55d42df534c9da463015872d41">isConstrained</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb531645493ceda329fc922748401be">isTransient</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b343dd677e74a1ecb5723fbb746395">isMaybeVoid</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735ac6b44a83924b761bdac676eb4184">isMaybeDefault</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581d0d2acf3c99191e1a5f3cb5f95ce6">isMaybeAmbiguous</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b07d194b0db97594df0116577e9fbf">isPublished</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784f1e1160f33e552720b3e90638811c">isTemplateSpecialization</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae943a44f4314a00a9572d0fa5e364e7">isObjCProperty</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fb7997900b202912af886e2ccc8381">isCSharpProperty</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196a099fba755a0586625635e40e9c58">isConstructor</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0807e7d46f56761eb33db77778289c11">isDestructor</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7bcaaff6e07e660a124d779a1300218">hasOneLineInitializer</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0edc949c11ffd04ae0f79b8850b1586">hasMultiLineInitializer</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af589ca13a0dec56fb92038c9b2488208">isCallable</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b99e725308ea15248722f69611844aa">isStrongEnumValue</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746d9cacb5bd7eed7e99697ad6c8314b">livesInsideEnum</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2109d4aac7f6350a75dadc71ddc55f1">isSliceLocal</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c5790de4e5ac8861bc89bd0a76c7a3">isConstExpr</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0268c2546b2d46b5ef741b91306ace53">isConstEval</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28140ddb3c4306995afe94d972cf7674">isConstInit</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fda10e3128c3e735e5b24132037033">isNoDiscard</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23dc837ee131aa1642a61efd24764032">numberOfFlowKeyWords</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88104421cb961405baa312d0bd1f009f">isFriendToHide</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a677f4f48e4bf01762fc024a230092">isNotFriend</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd18512439916b8cb1fc1f7a43ebc6b5">isFunctionOrSignalSlot</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd3ac8d3848d07104ad3e3e35590f3a">isRelatedOrFriend</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf88b64d5de77c0fc51c4a0c57003f7">isDeleted</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1902fdf699e7983c0dfc20a0e8192da">isBriefSectionVisible</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af860d239096a51aeec8ff95d5ac0b0dd">isDetailedSectionVisible</a> (MemberListContainer container) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a091d243bd31c95a34233e364dfdd9f5d">hasDetailedDescription</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48614022a9d54e68ca09db0cafbf2c2">isFriendClass</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2766e32f6704305ce66b9cf6766d4e5b">isDocumentedFriendClass</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a735862f449c091668f1fc86004aab3a2">reimplements</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdaf0953a164c3e6d7831a39c072e71">reimplementedBy</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88908e0048f8220fea8ce3a116adc415">isReimplementedBy</a> (const ClassDef *cd) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00728f58f71b2b8baf6f9913c7651ae">relatedAlso</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152281092758c092ff3aa7954ab94f23">hasDocumentedEnumValues</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020685b10037e71388d08925716ffdd5">getAnonymousEnumType</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842ff86c34c3ae387d995e2597be8118">isDocsForDefinition</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99e46c3a8716075dfcb6debf428e44f">getEnumScope</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df0bef52b6d1d15a4b12a187c8a90ca">enumFieldList</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e08adab7ea5d97208e8662165d89995">enumBaseType</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1decd0941a5f9a2cc919a811be9e7d56">hasExamples</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/examplelist">ExampleList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11ea2d4093d08b9ca4147b6e10b1c7b">getExamples</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa756b712f45e7800617808f708c2876">isPrototype</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515503656a6cffb2d27f60e93c3c780e">argumentList</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d0461390544ad385a962aefd88c313">declArgumentList</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409da33c248938e57ba2135777a38628">templateArguments</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad43afec960b7c0d7e76a1b7eec3d0e3a">definitionTemplateParameterLists</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaddfdfb06c2122a283d4afc01bd78a8">formalTemplateArguments</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b67777af87af494e32dfec9d881da5d">getMemberGroupId</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/membergroup">MemberGroup</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80cdb3bd4361d8b5d8dd91c0d7cfc083">getMemberGroup</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b1e297724aaf4e8bca3424d72ae9129">fromAnonymousScope</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485884aca7071b99f7e0c8af2781a126">fromAnonymousMember</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f8eeb9656c15d74956b893e5cef255d">hasCallGraph</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0b1dcd40b111eea088027193c2e411">hasCallerGraph</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aedaf487c755d4749b10fa95729a2af">hasReferencesRelation</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc1862f5e87a67541a4c40403a95fd81">hasReferencedByRelation</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779bcddb2e508d5bf7300d17376caf04">hasInlineSource</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870e7856099eb3a263255703c14b65ad">hasEnumValues</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64c6a04cf0c6d2ebf56ed6959ce1f89d">sourceRefName</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1f125e42e876b4e552f71a4748b42f">templateMaster</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68246f42d892a0cd4e1b5248d8f8f947">getScopeString</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90092536a05578d258ca1381e3176c88">getClassDefOfAnonymousType</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f317162cd72dbfd6829ee85aec91170">isTypedefValCached</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d86b14ef7e0bae448c4ab6cb0e0bedc">getCachedTypedefVal</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799ea114bacbfab8f6b8eb4e63564484">getCachedTypedefTemplSpec</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101fb5ed20d2c97e877e0f7b8ef07740">getCachedResolvedTypedef</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2500af3692e4b00d42868603d2da26e9">inheritsDocsFrom</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347b09058c4ebdded074d8030ad53bb1">getGroupAlias</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d88b32a0ffb15971a56e67dd0fbf21b">category</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea0734fcbde2539f921faf4461fd1833">categoryRelation</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f41851957c71761afa7afe4faf4a476">getDeclType</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4402807338308bd8d09e8e11592159d">getLabels</a> (const Definition *container) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ea63aa23ada7ecd6d8c59163c3dadf">getQualifiers</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa01306dc1e488d40d7b3b600091e4ec9">typeConstraints</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a3159272913d2f0f441761a28ee674">requiresClause</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f47ca16628b42880b0aaa0a684c4a47">fieldType</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fcd7ce509544c84675118e28d7f6c8c">getDeclFileName</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8d6ea6270c9f8a0e5250a3408014c1">getDeclLine</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73180115a82af3a943f4bb34b1cc0df3">getDeclColumn</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb144dad9c39430ac79b10a7ac18d9c">createTemplateInstanceMember</a> (const ArgumentList &amp;formalArgs, const std::unique_ptr&lt; ArgumentList &gt; &amp;actualArgs) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21917a4770d64cc6a97a6b2c81c45312">writeDeclaration</a> (OutputList &amp;ol, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *md, bool inGroup, int indentLevel=0, const ClassDef *inheritFrom=nullptr, const QCString &amp;inheritId=QCString()) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19bbaeceb1a5834827c03aaf6cac4e3f">writeEnumDeclaration</a> (OutputList &amp;typeDecl, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *mod) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb488146339ce401624a13e908c95ab">writeLink</a> (OutputList &amp;ol, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *md, bool onlyText=FALSE) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae191114ab6407a74711b5dad045a20c9">detectUndocumentedParams</a> (bool hasParamCommand, bool hasReturnCommand) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1212af3d2b7edf710bbda655097a8a7b">warnIfUndocumented</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af292c658cf6cf0f6ac800f520818f7b6">warnIfUndocumentedParams</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a341567c872ef0f346b59c1dd84c49a57">visibleInIndex</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa605daa08e85f7261890848ad923cbd9">setMemberGroup</a> (MemberGroup *grp)=0</td>
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

A model of a class/file/namespace member symbol.

Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### accessorClass() {#a19e35fd33e87d41ebfe413d9ec63a44b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassDef * MemberDef::accessorClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a19e35fd33e87d41ebfe413d9ec63a44b">accessorClass</a>.

Referenced by <a href="#a19e35fd33e87d41ebfe413d9ec63a44b">accessorClass</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a72d1ae7f30aa8073a2790546df7771be">MemberDefAliasImpl::accessorClass</a>.
</div>
</div>

### argsString() {#adfae3b8f49644ba27669daa9412e14a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::argsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#adfae3b8f49644ba27669daa9412e14a3">argsString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlhelp/#a247f8e8a9f527f64cbd47875876ee62b">HtmlHelp::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/qhp/#afdd0e586dc670e184d23bf80c880f0cf">Qhp::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="#adfae3b8f49644ba27669daa9412e14a3">argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a08d9e1d8330ee820835e987f3b98962e">MemberDefAliasImpl::argsString</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a76fe2943fccabc70c52ad3b6e31f4fa5">VhdlDocGen::writeTagFile</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### argumentList() {#a515503656a6cffb2d27f60e93c3c780e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentList &amp; MemberDef::argumentList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 224 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a92f40ce21a3c575393ba368299fd58c3">MemberDefAliasImpl::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a803ce79833ba42275ae6a45c695fe24c">ClassDefImpl::containsOverload</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ada5b9e6fb75b1e07ba0602b2b40229db">MemberDefImpl::copyArgumentNames</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acbd23ce837bcb562fbf5909c28e3ee06">MemberDefImpl::resolveUnnamedParameters</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#add91dbbc9b0c632da7f20c52ca03e6c8">setParameterList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a76fe2943fccabc70c52ad3b6e31f4fa5">VhdlDocGen::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### bitfieldString() {#a79b45e3c4c595bebe2c1e65e965c6d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::bitfieldString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a>.

Referenced by <a href="#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac1e54f5fb27478d640a2154263307537">MemberDefAliasImpl::bitfieldString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>.
</div>
</div>

### category() {#a4d88b32a0ffb15971a56e67dd0fbf21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassDef * MemberDef::category ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 264 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4d88b32a0ffb15971a56e67dd0fbf21b">category</a>.

Referenced by <a href="#a4d88b32a0ffb15971a56e67dd0fbf21b">category</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aefe87e3b1995f22580baef73bc18ae87">MemberDefAliasImpl::category</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### categoryRelation() {#aea0734fcbde2539f921faf4461fd1833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::categoryRelation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aea0734fcbde2539f921faf4461fd1833">categoryRelation</a>.

Referenced by <a href="#aea0734fcbde2539f921faf4461fd1833">categoryRelation</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab8cb3810e35cf002b88959976940bd3e">MemberDefAliasImpl::categoryRelation</a>.
</div>
</div>

### createTemplateInstanceMember() {#a9cb144dad9c39430ac79b10a7ac18d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; MemberDef &gt; MemberDef::createTemplateInstanceMember (const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; formalArgs, const std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &gt; &amp; actualArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 281 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a9cb144dad9c39430ac79b10a7ac18d9c">createTemplateInstanceMember</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="#a9cb144dad9c39430ac79b10a7ac18d9c">createTemplateInstanceMember</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8eca027c06effdb42b1430454b23ea3e">MemberDefAliasImpl::createTemplateInstanceMember</a>.
</div>
</div>

### declaration() {#a1003f3dd9b61ac1d8e115600f8ffaa06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::declaration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1003f3dd9b61ac1d8e115600f8ffaa06">declaration</a>.

Referenced by <a href="#a1003f3dd9b61ac1d8e115600f8ffaa06">declaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a5e914a4e75e59e36cf75c30fe30327ec">MemberDefAliasImpl::declaration</a> and <a href="/web-doxygen/docs/api/classes/tooltipmanager/#a9fabdb64f4fd1b5a5fded9d7dac90c3b">TooltipManager::writeTooltips</a>.
</div>
</div>

### declArgumentList() {#af0d0461390544ad385a962aefd88c313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentList &amp; MemberDef::declArgumentList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af0d0461390544ad385a962aefd88c313">declArgumentList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ada5b9e6fb75b1e07ba0602b2b40229db">MemberDefImpl::copyArgumentNames</a>, <a href="#af0d0461390544ad385a962aefd88c313">declArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7cff2146a8053a3738816b623393b1b8">MemberDefAliasImpl::declArgumentList</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acbd23ce837bcb562fbf5909c28e3ee06">MemberDefImpl::resolveUnnamedParameters</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### deepCopy() {#ac9b10308c1c2590cbb82f2eff52d5ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; MemberDef &gt; MemberDef::deepCopy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ac9b10308c1c2590cbb82f2eff52d5ce5">deepCopy</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7a05059f489e3c94d51aa47127ccdfed">ClassDefImpl::deepCopy</a> and <a href="#ac9b10308c1c2590cbb82f2eff52d5ce5">deepCopy</a>.
</div>
</div>

### definition() {#a1bc15da1d36aef0514a095c9ff485618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::definition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1bc15da1d36aef0514a095c9ff485618">definition</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="#a1bc15da1d36aef0514a095c9ff485618">definition</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac0fd29713adf9549df9a34b6a2967580">MemberDefAliasImpl::definition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>.
</div>
</div>

### definitionTemplateParameterLists() {#ad43afec960b7c0d7e76a1b7eec3d0e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentLists &amp; MemberDef::definitionTemplateParameterLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ad43afec960b7c0d7e76a1b7eec3d0e3a">definitionTemplateParameterLists</a>.

Referenced by <a href="#ad43afec960b7c0d7e76a1b7eec3d0e3a">definitionTemplateParameterLists</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a39b927ee978d3883e8ed5fc2bf38f2f2">MemberDefAliasImpl::definitionTemplateParameterLists</a>.
</div>
</div>

### detectUndocumentedParams() {#ae191114ab6407a74711b5dad045a20c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::detectUndocumentedParams (bool hasParamCommand, bool hasReturnCommand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 291 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ae191114ab6407a74711b5dad045a20c9">detectUndocumentedParams</a>.

Referenced by <a href="#ae191114ab6407a74711b5dad045a20c9">detectUndocumentedParams</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>.
</div>
</div>

### displayDefinition() {#a655ea55d777fb3ae96319be96f56323d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::displayDefinition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a655ea55d777fb3ae96319be96f56323d">displayDefinition</a>.

Referenced by <a href="#a655ea55d777fb3ae96319be96f56323d">displayDefinition</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa0c005ebaf14fa477a5d390f7a847ad6">MemberDefAliasImpl::displayDefinition</a>.
</div>
</div>

### enumBaseType() {#a1e08adab7ea5d97208e8662165d89995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::enumBaseType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1e08adab7ea5d97208e8662165d89995">enumBaseType</a>.

Referenced by <a href="#a1e08adab7ea5d97208e8662165d89995">enumBaseType</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a13268b641bd88ab5c4b0c2383ba0ee96">MemberDefAliasImpl::enumBaseType</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>.
</div>
</div>

### enumFieldList() {#a4df0bef52b6d1d15a4b12a187c8a90ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberVector &amp; MemberDef::enumFieldList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 216 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4df0bef52b6d1d15a4b12a187c8a90ca">enumFieldList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="#a4df0bef52b6d1d15a4b12a187c8a90ca">enumFieldList</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a75727879881005eede9e7704dec38eda">MemberDefAliasImpl::enumFieldList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e11a9d8c5f3fc3b78bc02ebe04380c">findDEV</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae515e3c5baf8a9c7b818a3f492d576a1">writeMemberToIndex</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

### excpString() {#a2f94a19fd2121d155de4865cf7c2fa81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::excpString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7ff2e26cbc7fff4007003e80bbd2b1e4">MemberDefAliasImpl::excpString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a158781f51faf723e59ca681487e4da1a">writeExceptionList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>.
</div>
</div>

### extraTypeChars() {#a53ca4dbd8b0975ce3bf393a52a15e435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::extraTypeChars ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a53ca4dbd8b0975ce3bf393a52a15e435">extraTypeChars</a>.

Referenced by <a href="#a53ca4dbd8b0975ce3bf393a52a15e435">extraTypeChars</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a9154aea0867b94b58ee1697ae34e9ff6">MemberDefAliasImpl::extraTypeChars</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### fieldType() {#a2f47ca16628b42880b0aaa0a684c4a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::fieldType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 275 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2f47ca16628b42880b0aaa0a684c4a47">fieldType</a>.

Referenced by <a href="#a2f47ca16628b42880b0aaa0a684c4a47">fieldType</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#adb081738161e6790884541dd1c7ad02e">MemberDefAliasImpl::fieldType</a>.
</div>
</div>

### formalTemplateArguments() {#aaaddfdfb06c2122a283d4afc01bd78a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; ArgumentList &gt; MemberDef::formalTemplateArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 228 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aaaddfdfb06c2122a283d4afc01bd78a8">formalTemplateArguments</a>.

Referenced by <a href="#aaaddfdfb06c2122a283d4afc01bd78a8">formalTemplateArguments</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#addb17b4c5f207a2f1a16e13a700e6b13">MemberDefAliasImpl::formalTemplateArguments</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>.
</div>
</div>

### fromAnonymousMember() {#a485884aca7071b99f7e0c8af2781a126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberDef * MemberDef::fromAnonymousMember ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a485884aca7071b99f7e0c8af2781a126">fromAnonymousMember</a>.

Referenced by <a href="#a485884aca7071b99f7e0c8af2781a126">fromAnonymousMember</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad37f141fe0e429548fbf39c2bc666963">MemberDefAliasImpl::fromAnonymousMember</a>.
</div>
</div>

### fromAnonymousScope() {#a2b1e297724aaf4e8bca3424d72ae9129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::fromAnonymousScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2b1e297724aaf4e8bca3424d72ae9129">fromAnonymousScope</a>.

Referenced by <a href="#a2b1e297724aaf4e8bca3424d72ae9129">fromAnonymousScope</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8969ab606ff87df184d152b53d88b0ed">MemberDefAliasImpl::fromAnonymousScope</a>.
</div>
</div>

### getAnonymousEnumType() {#a020685b10037e71388d08925716ffdd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::getAnonymousEnumType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 213 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a020685b10037e71388d08925716ffdd5">getAnonymousEnumType</a>.

Referenced by <a href="#a020685b10037e71388d08925716ffdd5">getAnonymousEnumType</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ae8d8e0492f0a91e2925423f6a633a110">MemberDefAliasImpl::getAnonymousEnumType</a>.
</div>
</div>

### getCachedResolvedTypedef() {#a101fb5ed20d2c97e877e0f7b8ef07740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getCachedResolvedTypedef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 257 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a101fb5ed20d2c97e877e0f7b8ef07740">getCachedResolvedTypedef</a>.

Referenced by <a href="#a101fb5ed20d2c97e877e0f7b8ef07740">getCachedResolvedTypedef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3f5720971a6dee2e968ac2983afc141a">MemberDefAliasImpl::getCachedResolvedTypedef</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>.
</div>
</div>

### getCachedTypedefTemplSpec() {#a799ea114bacbfab8f6b8eb4e63564484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getCachedTypedefTemplSpec ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 256 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a799ea114bacbfab8f6b8eb4e63564484">getCachedTypedefTemplSpec</a>.

Referenced by <a href="#a799ea114bacbfab8f6b8eb4e63564484">getCachedTypedefTemplSpec</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a6e0309dc66ff64486a0000ae6167e00d">MemberDefAliasImpl::getCachedTypedefTemplSpec</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>.
</div>
</div>

### getCachedTypedefVal() {#a2d86b14ef7e0bae448c4ab6cb0e0bedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassDef * MemberDef::getCachedTypedefVal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 255 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2d86b14ef7e0bae448c4ab6cb0e0bedc">getCachedTypedefVal</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a082d23658541704d3493a7a881583d55">flushCachedTemplateRelations</a>, <a href="#a2d86b14ef7e0bae448c4ab6cb0e0bedc">getCachedTypedefVal</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a01fffd763b95e60cae965442fdb7514f">MemberDefAliasImpl::getCachedTypedefVal</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>.
</div>
</div>

### getClassDef() {#a33ff70edee6691aacaeecf40a1146995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassDef * MemberDef::getClassDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0860f5779a240d32f68e1f86a1863a01">MemberDefImpl::\_isReimplements</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::\_writeReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::\_writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a81142c12bb2ef7638500997115bf2f43">PerlModGenerator::addListOfAllMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>, <a href="#a3dbdd0e17187a9512364eeb42782df6a">getClassDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a0e9cbc6be94f72a334915a282cc08fb7">MemberDefAliasImpl::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab8eea721f3aa95df70f1043e7faf6eed">MemberDefAliasImpl::getClassDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a6c89498ad2de8fa4026db0ac73167608">FileDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af93f11710bda96d773cf74795ae210e8">ClassDefImpl::isAccessibleMember</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a47a707dff2d9bbe606da2f4201dd1725">MemberGroup::memberContainer</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab1ec5ab1220e68ad6313166e9ac79378">writeClassLinkForMember</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6afc0eddf054d70eebc855c3a8608fcd">writeMemberTemplateLists</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fc4c3be9e48561ac4ee240aad2ef9d7">ClassDefImpl::writeQuickMemberLinks</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>.
</div>
</div>

### getClassDef() {#a3dbdd0e17187a9512364eeb42782df6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassDef * MemberDef::getClassDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>.
</div>
</div>

### getClassDefOfAnonymousType() {#a90092536a05578d258ca1381e3176c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassDef * MemberDef::getClassDefOfAnonymousType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a90092536a05578d258ca1381e3176c88">getClassDefOfAnonymousType</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="#a90092536a05578d258ca1381e3176c88">getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3e0a738dbdd23f3d5cfee1d062445957">MemberDefAliasImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### getDeclColumn() {#a73180115a82af3a943f4bb34b1cc0df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int MemberDef::getDeclColumn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a73180115a82af3a943f4bb34b1cc0df3">getDeclColumn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a73180115a82af3a943f4bb34b1cc0df3">getDeclColumn</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7c5ecf31b6fd716d944cafe5b53979e1">MemberDefAliasImpl::getDeclColumn</a>.
</div>
</div>

### getDeclFileName() {#a9fcd7ce509544c84675118e28d7f6c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getDeclFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a9fcd7ce509544c84675118e28d7f6c8c">getDeclFileName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a9fcd7ce509544c84675118e28d7f6c8c">getDeclFileName</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a07931b122f9dd393677ffda5602bc6ed">MemberDefAliasImpl::getDeclFileName</a>.
</div>
</div>

### getDeclLine() {#a6d8d6ea6270c9f8a0e5250a3408014c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int MemberDef::getDeclLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 278 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a6d8d6ea6270c9f8a0e5250a3408014c1">getDeclLine</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a6d8d6ea6270c9f8a0e5250a3408014c1">getDeclLine</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a61c55530f12aea9c3e08d04e3eadd6d2">MemberDefAliasImpl::getDeclLine</a>.
</div>
</div>

### getDeclType() {#a6f41851957c71761afa7afe4faf4a476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getDeclType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a6f41851957c71761afa7afe4faf4a476">getDeclType</a>.

Referenced by <a href="#a6f41851957c71761afa7afe4faf4a476">getDeclType</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a804bd46b5a52c8575481fb624b8547d1">MemberDefAliasImpl::getDeclType</a>.
</div>
</div>

### getEnumScope() {#af99e46c3a8716075dfcb6debf428e44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::getEnumScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af99e46c3a8716075dfcb6debf428e44f">getEnumScope</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="#af99e46c3a8716075dfcb6debf428e44f">getEnumScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab999a273e404ddf9b8b632abb5529f92">MemberDefAliasImpl::getEnumScope</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>.
</div>
</div>

### getExamples() {#af11ea2d4093d08b9ca4147b6e10b1c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ExampleList &amp; MemberDef::getExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af11ea2d4093d08b9ca4147b6e10b1c7b">getExamples</a>.

Referenced by <a href="#af11ea2d4093d08b9ca4147b6e10b1c7b">getExamples</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a596a17921233981cd696d63d02ccc699">MemberDefAliasImpl::getExamples</a>.
</div>
</div>

### getFileDef() {#a5036fd8ee16b186925236105029ee823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const FileDef * MemberDef::getFileDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5036fd8ee16b186925236105029ee823">getFileDef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a803ce79833ba42275ae6a45c695fe24c">ClassDefImpl::containsOverload</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2de08afddfa24b4a037c36ac329185ff">VhdlDocGen::createFlowChart</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="#a5036fd8ee16b186925236105029ee823">getFileDef</a>, <a href="#ae4ea166eb6883ec29aedb1d58eb5dc59">getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ada88b8880faa38132256facd594e93ce">MemberDefAliasImpl::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3db8f23e821810a68d5862a4edb2e1a7">MemberDefAliasImpl::getFileDef</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac8b51a59c563eeb4756d181947a53260">haveEqualFileNames</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a47a707dff2d9bbe606da2f4201dd1725">MemberGroup::memberContainer</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a720a2761163764ce53aff1186ad9bfb3">writeFileLinkForMember</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6afc0eddf054d70eebc855c3a8608fcd">writeMemberTemplateLists</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>.
</div>
</div>

### getFileDef() {#ae4ea166eb6883ec29aedb1d58eb5dc59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual FileDef * MemberDef::getFileDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5036fd8ee16b186925236105029ee823">getFileDef</a>.
</div>
</div>

### getGroupAlias() {#a347b09058c4ebdded074d8030ad53bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::getGroupAlias ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a347b09058c4ebdded074d8030ad53bb1">getGroupAlias</a>.

Referenced by <a href="#a347b09058c4ebdded074d8030ad53bb1">getGroupAlias</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a292ff53c2fa2152fc4fa42d4770d9f78">MemberDefAliasImpl::getGroupAlias</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>.
</div>
</div>

### getGroupDef() {#a43566d882fc7994385bbdaf7fe927e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual GroupDef * MemberDef::getGroupDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a568741e989fcbe6cd20c1295cf9c7aed">buildTypedefList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="#a43ef09743c900283a46b2e0ecd81e486">getGroupDef</a>, <a href="#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a87103a76bfb3ee34f2f5c794deb57218">MemberDefAliasImpl::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a06196ddb8d78a9b3b0be360d4c5f6040">MemberDefAliasImpl::getGroupDef</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af3d5f8078a92e94865d17a273751c128">isEntryInGroupOfMember</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aab98b3020d2d9bfaa85ca3d81fd6b6f6">MemberDefImpl::setEnumScope</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae515e3c5baf8a9c7b818a3f492d576a1">writeMemberToIndex</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### getGroupDef() {#a43ef09743c900283a46b2e0ecd81e486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const GroupDef * MemberDef::getGroupDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>.
</div>
</div>

### getGroupFileName() {#acb9da3d6b3e2f3e8102ee9a3380c0746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getGroupFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#acb9da3d6b3e2f3e8102ee9a3380c0746">getGroupFileName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="#acb9da3d6b3e2f3e8102ee9a3380c0746">getGroupFileName</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a909fc518eb5f236c31b795bdbe83f504">MemberDefAliasImpl::getGroupFileName</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aab98b3020d2d9bfaa85ca3d81fd6b6f6">MemberDefImpl::setEnumScope</a>.
</div>
</div>

### getGroupHasDocs() {#a01cb4b118d46ca86b9475e1d243560b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::getGroupHasDocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="#a01cb4b118d46ca86b9475e1d243560b1">getGroupHasDocs</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a0e95c9ab5e53215fe88a0bdb955e2057">MemberDefAliasImpl::getGroupHasDocs</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aab98b3020d2d9bfaa85ca3d81fd6b6f6">MemberDefImpl::setEnumScope</a>.
</div>
</div>

### getGroupPri() {#a9ed95e7cef3948c6a978540c0d48bca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Grouping::GroupPri_t MemberDef::getGroupPri ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="#a9ed95e7cef3948c6a978540c0d48bca7">getGroupPri</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a70392e3c846970ae8998fc73ce7c651c">MemberDefAliasImpl::getGroupPri</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aab98b3020d2d9bfaa85ca3d81fd6b6f6">MemberDefImpl::setEnumScope</a>.
</div>
</div>

### getGroupStartLine() {#a5d3b273949bc92e2b88e981aebc789bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int MemberDef::getGroupStartLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5d3b273949bc92e2b88e981aebc789bd">getGroupStartLine</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="#a5d3b273949bc92e2b88e981aebc789bd">getGroupStartLine</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a2f43ab6d4c849233c196d13f2587f862">MemberDefAliasImpl::getGroupStartLine</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aab98b3020d2d9bfaa85ca3d81fd6b6f6">MemberDefImpl::setEnumScope</a>.
</div>
</div>

### getLabels() {#ad4402807338308bd8d09e8e11592159d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringVector MemberDef::getLabels (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 268 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ad4402807338308bd8d09e8e11592159d">getLabels</a>.

Referenced by <a href="#ad4402807338308bd8d09e8e11592159d">getLabels</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8db83ee6d1d2710a78503e41d396507c">MemberDefAliasImpl::getLabels</a>.
</div>
</div>

### getMemberGroup() {#a80cdb3bd4361d8b5d8dd91c0d7cfc083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberGroup * MemberDef::getMemberGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a80cdb3bd4361d8b5d8dd91c0d7cfc083">getMemberGroup</a>.

Referenced by <a href="#a80cdb3bd4361d8b5d8dd91c0d7cfc083">getMemberGroup</a>.
</div>
</div>

### getMemberGroupId() {#a6b67777af87af494e32dfec9d881da5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int MemberDef::getMemberGroupId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a6b67777af87af494e32dfec9d881da5d">getMemberGroupId</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="#a6b67777af87af494e32dfec9d881da5d">getMemberGroupId</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a53f3e7c45fa9a19cf606d647fca28c59">MemberDefAliasImpl::getMemberGroupId</a>.
</div>
</div>

### getMemberSpecifiers() {#ab3e5d2e532ebe2a0f45fe1a945fb4269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual TypeSpecifier MemberDef::getMemberSpecifiers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab3e5d2e532ebe2a0f45fe1a945fb4269">getMemberSpecifiers</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="#ab3e5d2e532ebe2a0f45fe1a945fb4269">getMemberSpecifiers</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a687d7ece548efc0a6e72a19a42007f69">MemberDefAliasImpl::getMemberSpecifiers</a>.
</div>
</div>

### getModuleDef() {#a8c3b6809f49a66d7d3f99f4b40ae6d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ModuleDef * MemberDef::getModuleDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a8c3b6809f49a66d7d3f99f4b40ae6d47">getModuleDef</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="#a8c3b6809f49a66d7d3f99f4b40ae6d47">getModuleDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad1fb19b6d2781949ca12e1bcaa2ed6db">MemberDefAliasImpl::getModuleDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac6b9d1199e7d38e674f28253098abc0e">writeModuleLinkForMember</a>.
</div>
</div>

### getNamespaceDef() {#a900cace4959b6cad9e6aa58e8283195f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const NamespaceDef * MemberDef::getNamespaceDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>, <a href="#ad1ef0d32e09ba0696f74c4651839ad73">getNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a046459b2b68cc6f96813987348f9204e">MemberDefAliasImpl::getNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a0328c146fc737528b93513f308edda07">MemberDefAliasImpl::getNamespaceDef</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a47a707dff2d9bbe606da2f4201dd1725">MemberGroup::memberContainer</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a87820cde653197fc9c4de838999c3104">memberVisible</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae515e3c5baf8a9c7b818a3f492d576a1">writeMemberToIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c10dc89e478b9f6f343c8def01c5238">writeNamespaceLinkForMember</a>.
</div>
</div>

### getNamespaceDef() {#ad1ef0d32e09ba0696f74c4651839ad73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual NamespaceDef * MemberDef::getNamespaceDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a900cace4959b6cad9e6aa58e8283195f">getNamespaceDef</a>.
</div>
</div>

### getQualifiers() {#a78ea63aa23ada7ecd6d8c59163c3dadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringVector MemberDef::getQualifiers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a78ea63aa23ada7ecd6d8c59163c3dadf">getQualifiers</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a78ea63aa23ada7ecd6d8c59163c3dadf">getQualifiers</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#afe7f40e5bd1f8834db5aaa1e279fbaac">MemberDefAliasImpl::getQualifiers</a>.
</div>
</div>

### getReadAccessor() {#ab8d7b70952b14c1f6af79a16f122a6c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getReadAccessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab8d7b70952b14c1f6af79a16f122a6c9">getReadAccessor</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#ab8d7b70952b14c1f6af79a16f122a6c9">getReadAccessor</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a2ea6cf823c8913af0fd5eb3ecfa2820c">MemberDefAliasImpl::getReadAccessor</a>.
</div>
</div>

### getScopeString() {#a68246f42d892a0cd4e1b5248d8f8f947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getScopeString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 250 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a68246f42d892a0cd4e1b5248d8f8f947">getScopeString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#a68246f42d892a0cd4e1b5248d8f8f947">getScopeString</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a9039f553e11e28d05033b4c01cfb21cb">MemberDefAliasImpl::getScopeString</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a52015628829279296a6334d955676868">writeMemberReference</a>.
</div>
</div>

### getSectionList() {#ab001f5a231830270bac7da746201c02e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberList * MemberDef::getSectionList (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab001f5a231830270bac7da746201c02e">getSectionList</a>.

Referenced by <a href="#ab001f5a231830270bac7da746201c02e">getSectionList</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ace20f8697f19e6cea5b9e44a680e7a5b">MemberDefAliasImpl::getSectionList</a> and <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a>.
</div>
</div>

### getVhdlSpecifiers() {#a5cd379d53915c1fafe22420d04d26aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual VhdlSpecifier MemberDef::getVhdlSpecifiers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab171a05efe0ae922f1e24062abd22fec">MemberDefAliasImpl::getVhdlSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#af13dd5eb831c1df008b0fd41928f4b7c">VhdlDocGen::isAlias</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0281ffc4e374d27d703419ae289e3b8c">VhdlDocGen::isArchitecture</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2dc9e668acc7c79f211709e2a0eeccad">VhdlDocGen::isAttribute</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad3fdc795bf951ef11221894512b8bc6c">VhdlDocGen::isComponent</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a57efdf5bddd0b36667c8aa21256ebac7">VhdlDocGen::isConfig</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c3cdcd27394531385ccd8c56257edc1">VhdlDocGen::isConstant</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#adb04cd03e2039ecab3a0a8f31ee4c890">VhdlDocGen::isConstraint</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a65218023c4970a90f3bce70938a99781">VhdlDocGen::isEntity</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a7ac9c26b1b0fb7402cc58acaf569df89">VhdlDocGen::isFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae3c19429669d382581ba37aee5f39278">VhdlDocGen::isGeneric</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a069c8ad206be372bd948cc8e964218ed">VhdlDocGen::isGroup</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a3f582b69841bae3ec6f1281604b6f0c8">VhdlDocGen::isLibrary</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a55ef68e914c38033a48b6fdac2907689">VhdlDocGen::isMisc</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aca017e059b8a2972c2cad968800c0564">VhdlDocGen::isPackage</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab6e9aff43352b39d31806d0616e2c7af">VhdlDocGen::isPackageBody</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a73186f5d1ba5e6c11c6f006708da79a6">VhdlDocGen::isPort</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a212ea7da7de8f22c3ca1dd14a38a67ef">VhdlDocGen::isProcess</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac0634a061165ad22c27eef2ac12057d0">VhdlDocGen::isRecord</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a07199651d2f493ee3afe42975df77efb">VhdlDocGen::isSignal</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a7fb01b11d2a225ee8d8c43a56862be8b">VhdlDocGen::isSignals</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab57f7d02afdd7034f78894b20e6ff4aa">VhdlDocGen::isSubType</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4861484cc952d96afcfe277cf958aff0">VhdlDocGen::isUnit</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a877e8a81695500e7ad5ed8d76fdbaffc">VhdlDocGen::isVariable</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a8ab98ceef0a36aea7a15c548ec9aa455">VhdlDocGen::isVType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### getWriteAccessor() {#a7638dcb798738c331ba2c2567118ceb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::getWriteAccessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a7638dcb798738c331ba2c2567118ceb6">getWriteAccessor</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a7638dcb798738c331ba2c2567118ceb6">getWriteAccessor</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac17beff31ab5ad4fa465a6678c8b33af">MemberDefAliasImpl::getWriteAccessor</a>.
</div>
</div>

### hasCallerGraph() {#a9e0b1dcd40b111eea088027193c2e411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasCallerGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a9e0b1dcd40b111eea088027193c2e411">hasCallerGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="#a9e0b1dcd40b111eea088027193c2e411">hasCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a13111733c39026d50bd3d9e77ac91de7">MemberDefAliasImpl::hasCallerGraph</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a>.
</div>
</div>

### hasCallGraph() {#a4f8eeb9656c15d74956b893e5cef255d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasCallGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4f8eeb9656c15d74956b893e5cef255d">hasCallGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="#a4f8eeb9656c15d74956b893e5cef255d">hasCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a5fc46db1625f76cf8a476464cd977346">MemberDefAliasImpl::hasCallGraph</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a>.
</div>
</div>

### hasDetailedDescription() {#a091d243bd31c95a34233e364dfdd9f5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasDetailedDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a091d243bd31c95a34233e364dfdd9f5d">hasDetailedDescription</a>.

Referenced by <a href="#a091d243bd31c95a34233e364dfdd9f5d">hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7e1cbf70cc0a3f5d4ede4c201f703f46">MemberDefAliasImpl::hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### hasDocumentedEnumValues() {#a152281092758c092ff3aa7954ab94f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasDocumentedEnumValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a152281092758c092ff3aa7954ab94f23">hasDocumentedEnumValues</a>.

Referenced by <a href="#a152281092758c092ff3aa7954ab94f23">hasDocumentedEnumValues</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a887ae58010826340b5a8baa90dac5399">MemberDefAliasImpl::hasDocumentedEnumValues</a>.
</div>
</div>

### hasEnumValues() {#a870e7856099eb3a263255703c14b65ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasEnumValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a870e7856099eb3a263255703c14b65ad">hasEnumValues</a>.

Referenced by <a href="#a870e7856099eb3a263255703c14b65ad">hasEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a008e1603baccff8ed237b5e2f7f48187">MemberDefAliasImpl::hasEnumValues</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a>.
</div>
</div>

### hasExamples() {#a1decd0941a5f9a2cc919a811be9e7d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1decd0941a5f9a2cc919a811be9e7d56">hasExamples</a>.

Referenced by <a href="#a1decd0941a5f9a2cc919a811be9e7d56">hasExamples</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a050b6bbc860537476077acf0ddd41607">MemberDefAliasImpl::hasExamples</a>.
</div>
</div>

### hasInlineSource() {#a779bcddb2e508d5bf7300d17376caf04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasInlineSource ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a779bcddb2e508d5bf7300d17376caf04">hasInlineSource</a>.

Referenced by <a href="#a779bcddb2e508d5bf7300d17376caf04">hasInlineSource</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aef54d46cb50db54bec407b7a7971f916">MemberDefAliasImpl::hasInlineSource</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>.
</div>
</div>

### hasMultiLineInitializer() {#ab0edc949c11ffd04ae0f79b8850b1586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasMultiLineInitializer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 181 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab0edc949c11ffd04ae0f79b8850b1586">hasMultiLineInitializer</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#ab0edc949c11ffd04ae0f79b8850b1586">hasMultiLineInitializer</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a6dfba642cd34a8030c01902314b04d4c">MemberDefAliasImpl::hasMultiLineInitializer</a>.
</div>
</div>

### hasOneLineInitializer() {#aa7bcaaff6e07e660a124d779a1300218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasOneLineInitializer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa7bcaaff6e07e660a124d779a1300218">hasOneLineInitializer</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#aa7bcaaff6e07e660a124d779a1300218">hasOneLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a5b3cf21d00cb08db4605f096ea5ae4be">MemberDefAliasImpl::hasOneLineInitializer</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>.
</div>
</div>

### hasReferencedByRelation() {#abc1862f5e87a67541a4c40403a95fd81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasReferencedByRelation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#abc1862f5e87a67541a4c40403a95fd81">hasReferencedByRelation</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="#abc1862f5e87a67541a4c40403a95fd81">hasReferencedByRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aec509883bb7a11931e92c2ee82ab6825">MemberDefAliasImpl::hasReferencedByRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>.
</div>
</div>

### hasReferencesRelation() {#a3aedaf487c755d4749b10fa95729a2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::hasReferencesRelation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 241 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a3aedaf487c755d4749b10fa95729a2af">hasReferencesRelation</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="#a3aedaf487c755d4749b10fa95729a2af">hasReferencesRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa2a8260106f48a674532b6674e1f9298">MemberDefAliasImpl::hasReferencesRelation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aaeb66f0aa57917b9aff55be8d61cc8c2">mergeMemberOverrideOptions</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>.
</div>
</div>

### inheritsDocsFrom() {#a2500af3692e4b00d42868603d2da26e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::inheritsDocsFrom ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2500af3692e4b00d42868603d2da26e9">inheritsDocsFrom</a>.

Referenced by <a href="#a2500af3692e4b00d42868603d2da26e9">inheritsDocsFrom</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a12381afac14d7c04e46df5cd22448b55">MemberDefAliasImpl::inheritsDocsFrom</a>.
</div>
</div>

### initializer() {#afe9302d711e627fdd4e9eb7c393ceeb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const QCString &amp; MemberDef::initializer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a65c251bb0f5de24cc7f782ed613d4a8d">MemberDefAliasImpl::initializer</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>.
</div>
</div>

### initializerLines() {#aeed70a711fa3e8b02bcc7d5ae34fb92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int MemberDef::initializerLines ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aeed70a711fa3e8b02bcc7d5ae34fb92a">initializerLines</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="#aeed70a711fa3e8b02bcc7d5ae34fb92a">initializerLines</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a4fba2943f72c2c0dfc84f5e3cb03d0ef">MemberDefAliasImpl::initializerLines</a>.
</div>
</div>

### isAbstract() {#af1601490373728611996a958bbfc38d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isAbstract ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af1601490373728611996a958bbfc38d3">isAbstract</a>.

Referenced by <a href="#af1601490373728611996a958bbfc38d3">isAbstract</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa5ad593619ebd10a3006621a00019d6f">MemberDefAliasImpl::isAbstract</a>.
</div>
</div>

### isAddable() {#a496b02cff3e89cc59eab5139a9211475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isAddable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a496b02cff3e89cc59eab5139a9211475">isAddable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a496b02cff3e89cc59eab5139a9211475">isAddable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8f182e36e119dff587236b3a871ab455">MemberDefAliasImpl::isAddable</a>.
</div>
</div>

### isAssign() {#a09bc44df807bfe787766e6268b991732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isAssign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a09bc44df807bfe787766e6268b991732">isAssign</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a09bc44df807bfe787766e6268b991732">isAssign</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a2bdd15518a7ee43e74f1853d70954738">MemberDefAliasImpl::isAssign</a>.
</div>
</div>

### isAttribute() {#a62780d0d926b1c17801dbba81921336a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a62780d0d926b1c17801dbba81921336a">isAttribute</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a62780d0d926b1c17801dbba81921336a">isAttribute</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a9b26a58c44485f3b143e1875608df3b7">MemberDefAliasImpl::isAttribute</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isBound() {#a86bb29ff5f9e049343bdb990b08ff9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isBound ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a86bb29ff5f9e049343bdb990b08ff9a3">isBound</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a86bb29ff5f9e049343bdb990b08ff9a3">isBound</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a88bfd21b61e03473699ad4b5910bba12">MemberDefAliasImpl::isBound</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isBriefSectionVisible() {#ad1902fdf699e7983c0dfc20a0e8192da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isBriefSectionVisible ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ad1902fdf699e7983c0dfc20a0e8192da">isBriefSectionVisible</a>.

Referenced by <a href="#ad1902fdf699e7983c0dfc20a0e8192da">isBriefSectionVisible</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#afc0c264f685f863503df65d73f95ae35">MemberDefAliasImpl::isBriefSectionVisible</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>.
</div>
</div>

### isCallable() {#af589ca13a0dec56fb92038c9b2488208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isCallable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af589ca13a0dec56fb92038c9b2488208">isCallable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="#af589ca13a0dec56fb92038c9b2488208">isCallable</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7d662b1a73e920faeed40353f04df636">MemberDefAliasImpl::isCallable</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>.
</div>
</div>

### isConstEval() {#a0268c2546b2d46b5ef741b91306ace53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isConstEval ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a0268c2546b2d46b5ef741b91306ace53">isConstEval</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a0268c2546b2d46b5ef741b91306ace53">isConstEval</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a0136ee914c222e758546b392fafcbf0d">MemberDefAliasImpl::isConstEval</a>.
</div>
</div>

### isConstExpr() {#a01c5790de4e5ac8861bc89bd0a76c7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isConstExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a01c5790de4e5ac8861bc89bd0a76c7a3">isConstExpr</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a01c5790de4e5ac8861bc89bd0a76c7a3">isConstExpr</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a4f2752fc11a291bf8fdfe6f7b8692741">MemberDefAliasImpl::isConstExpr</a>.
</div>
</div>

### isConstInit() {#a28140ddb3c4306995afe94d972cf7674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isConstInit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a28140ddb3c4306995afe94d972cf7674">isConstInit</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a28140ddb3c4306995afe94d972cf7674">isConstInit</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a1399569b43dfd1c393e7f6e77e57f889">MemberDefAliasImpl::isConstInit</a>.
</div>
</div>

### isConstrained() {#a80a42e55d42df534c9da463015872d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isConstrained ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a80a42e55d42df534c9da463015872d41">isConstrained</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a80a42e55d42df534c9da463015872d41">isConstrained</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a0b8adddde5852864b2d575efa0a032c3">MemberDefAliasImpl::isConstrained</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isConstructor() {#a196a099fba755a0586625635e40e9c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isConstructor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a196a099fba755a0586625635e40e9c58">isConstructor</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a196a099fba755a0586625635e40e9c58">isConstructor</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad62cf94641abcd059fa096dd3d6ad3a2">MemberDefAliasImpl::isConstructor</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a8390a828ac301fcfe39d600bfa242297">isStandardFunc</a>.
</div>
</div>

### isCopy() {#a6548961c5a9f2003ec5425bea0249ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isCopy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a6548961c5a9f2003ec5425bea0249ad2">isCopy</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a6548961c5a9f2003ec5425bea0249ad2">isCopy</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a5ff4f04f25516d058fd30376c09a5bac">MemberDefAliasImpl::isCopy</a>.
</div>
</div>

### isCSharpProperty() {#a48fb7997900b202912af886e2ccc8381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isCSharpProperty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a48fb7997900b202912af886e2ccc8381">isCSharpProperty</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="#a48fb7997900b202912af886e2ccc8381">isCSharpProperty</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aeeef328c05231823ac28da16ba60f4ce">MemberDefAliasImpl::isCSharpProperty</a>.
</div>
</div>

### isDCOP() {#ada93aac0fade61cc0018d94967e2a8e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDCOP ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ada93aac0fade61cc0018d94967e2a8e0">isDCOP</a>.

Referenced by <a href="#ada93aac0fade61cc0018d94967e2a8e0">isDCOP</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac5bd4be3b80929b82985af9f0edc1694">MemberDefAliasImpl::isDCOP</a>.
</div>
</div>

### isDefault() {#a2693c2e5c943567acd971d7e15dc4304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDefault ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2693c2e5c943567acd971d7e15dc4304">isDefault</a>.

Referenced by <a href="#a2693c2e5c943567acd971d7e15dc4304">isDefault</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a97c729c512f427963bb13faf683b55fb">MemberDefAliasImpl::isDefault</a>.
</div>
</div>

### isDefine() {#a8c9a34fe614f8c55edc60deaf0143f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDefine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a8c9a34fe614f8c55edc60deaf0143f47">isDefine</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#afce5972b6b52acbb18c0d79b1f0d4433">codeFolding</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="#a8c9a34fe614f8c55edc60deaf0143f47">isDefine</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7db1617b509719669ee0fb56528d0fb3">MemberDefAliasImpl::isDefine</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### isDelete() {#a21681601f9f6a421ca2a174d17841d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDelete ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a21681601f9f6a421ca2a174d17841d06">isDelete</a>.

Referenced by <a href="#a21681601f9f6a421ca2a174d17841d06">isDelete</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#abbce9968be6df80c888df12102bd6506">MemberDefAliasImpl::isDelete</a>.
</div>
</div>

### isDeleted() {#a2cf88b64d5de77c0fc51c4a0c57003f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDeleted ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2cf88b64d5de77c0fc51c4a0c57003f7">isDeleted</a>.

Referenced by <a href="#a2cf88b64d5de77c0fc51c4a0c57003f7">isDeleted</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a25888f22b6d1bff3a673037227bdd3ca">MemberDefAliasImpl::isDeleted</a>.
</div>
</div>

### isDestructor() {#a0807e7d46f56761eb33db77778289c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDestructor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a0807e7d46f56761eb33db77778289c11">isDestructor</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a0807e7d46f56761eb33db77778289c11">isDestructor</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a87c0c2413e48cb7c7a77eda21ed09926">MemberDefAliasImpl::isDestructor</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a8390a828ac301fcfe39d600bfa242297">isStandardFunc</a>.
</div>
</div>

### isDetailedSectionVisible() {#af860d239096a51aeec8ff95d5ac0b0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDetailedSectionVisible (<a href="/web-doxygen/docs/api/files/src/types-h/#a6dc2e6c0ceaaa530cb9859af8d37449d">MemberListContainer</a> container)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af860d239096a51aeec8ff95d5ac0b0dd">isDetailedSectionVisible</a>.

Referenced by <a href="#af860d239096a51aeec8ff95d5ac0b0dd">isDetailedSectionVisible</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#acc4219b5317f63f91f9cee316579270b">MemberDefAliasImpl::isDetailedSectionVisible</a>.
</div>
</div>

### isDictionary() {#a6b92d5888d4ff0b4ef5acc80d9ac76c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDictionary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a6b92d5888d4ff0b4ef5acc80d9ac76c7">isDictionary</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="#a6b92d5888d4ff0b4ef5acc80d9ac76c7">isDictionary</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3ce1cd28cfbd15ff7468935f84234bd8">MemberDefAliasImpl::isDictionary</a>.
</div>
</div>

### isDocsForDefinition() {#a842ff86c34c3ae387d995e2597be8118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDocsForDefinition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a842ff86c34c3ae387d995e2597be8118">isDocsForDefinition</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad23f7d576fcba6cc66edf702842a9d3">inheritDocumentation</a>, <a href="#a842ff86c34c3ae387d995e2597be8118">isDocsForDefinition</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7020e05a62880c040e10562dc615171d">MemberDefAliasImpl::isDocsForDefinition</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### isDocumentedFriendClass() {#a2766e32f6704305ce66b9cf6766d4e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isDocumentedFriendClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2766e32f6704305ce66b9cf6766d4e5b">isDocumentedFriendClass</a>.

Referenced by <a href="#a2766e32f6704305ce66b9cf6766d4e5b">isDocumentedFriendClass</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a4c0be8aef27f0c52dd50512aaced7c18">MemberDefAliasImpl::isDocumentedFriendClass</a>.
</div>
</div>

### isEnumerate() {#ab99e728441f3ce7d5784ad6fb6df18f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isEnumerate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e11a9d8c5f3fc3b78bc02ebe04380c">findDEV</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="#ab99e728441f3ce7d5784ad6fb6df18f2">isEnumerate</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a62405f8dbaeb86c640d3722258012d7a">MemberDefAliasImpl::isEnumerate</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae515e3c5baf8a9c7b818a3f492d576a1">writeMemberToIndex</a>.
</div>
</div>

### isEnumStruct() {#a30da3b2d7800741fb6c09a37069d6372}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isEnumStruct ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a30da3b2d7800741fb6c09a37069d6372">isEnumStruct</a>.

Referenced by <a href="#a30da3b2d7800741fb6c09a37069d6372">isEnumStruct</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#afa5b0e54433dba91af71b7ccb6e3a4ff">MemberDefAliasImpl::isEnumStruct</a>.
</div>
</div>

### isEnumValue() {#afa1ed0ba61a371a22b21dbd4d538e06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isEnumValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#afa1ed0ba61a371a22b21dbd4d538e06c">isEnumValue</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="#afa1ed0ba61a371a22b21dbd4d538e06c">isEnumValue</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ae6151a1b1d568af457f7238b614d2558">MemberDefAliasImpl::isEnumValue</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fc4c3be9e48561ac4ee240aad2ef9d7">ClassDefImpl::writeQuickMemberLinks</a>.
</div>
</div>

### isEvent() {#a50b37ee8d3c1b7b10c2f38a6b8ca165f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isEvent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a50b37ee8d3c1b7b10c2f38a6b8ca165f">isEvent</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="#a50b37ee8d3c1b7b10c2f38a6b8ca165f">isEvent</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#abf5953e094eb4634e00f620dd761aa11">MemberDefAliasImpl::isEvent</a>.
</div>
</div>

### isExplicit() {#a0aa8429875443e986e04e34624c5c0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isExplicit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a0aa8429875443e986e04e34624c5c0c8">isExplicit</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a0aa8429875443e986e04e34624c5c0c8">isExplicit</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad208e902d32a2755051c5c0dfca0e31c">MemberDefAliasImpl::isExplicit</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isExternal() {#a62a3294a87e2a6e2ff4a2d52bfd3187a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isExternal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a62a3294a87e2a6e2ff4a2d52bfd3187a">isExternal</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a62a3294a87e2a6e2ff4a2d52bfd3187a">isExternal</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a4652266d30b41d8e8439bc3b84a12807">MemberDefAliasImpl::isExternal</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>.
</div>
</div>

### isFinal() {#aef0c62b7d85f8eff11657f9a7e3f87f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFinal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aef0c62b7d85f8eff11657f9a7e3f87f4">isFinal</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#aef0c62b7d85f8eff11657f9a7e3f87f4">isFinal</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a1458a2afb0c7cb635888bf082417f148">MemberDefAliasImpl::isFinal</a>.
</div>
</div>

### isForeign() {#a1b388162e65708a87857b9605cb63591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isForeign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1b388162e65708a87857b9605cb63591">isForeign</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="#a1b388162e65708a87857b9605cb63591">isForeign</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aad36172f74a65417d266c070a692b8df">MemberDefAliasImpl::isForeign</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>.
</div>
</div>

### isFriend() {#a19a22a7e9394cf6e49ab6156274461d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFriend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a19a22a7e9394cf6e49ab6156274461d3">isFriend</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a19a22a7e9394cf6e49ab6156274461d3">isFriend</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad77c9110cef6649a2da3ee4b8d969ca8">MemberDefAliasImpl::isFriend</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isFriendClass() {#af48614022a9d54e68ca09db0cafbf2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFriendClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 203 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af48614022a9d54e68ca09db0cafbf2c2">isFriendClass</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#af48614022a9d54e68ca09db0cafbf2c2">isFriendClass</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a28fb4c6f314f7562e7020884f8a98158">MemberDefAliasImpl::isFriendClass</a>.
</div>
</div>

### isFriendToHide() {#a88104421cb961405baa312d0bd1f009f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFriendToHide ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 193 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a88104421cb961405baa312d0bd1f009f">isFriendToHide</a>.

Referenced by <a href="#a88104421cb961405baa312d0bd1f009f">isFriendToHide</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7e246b28429a866b93cc5cba2efa9c06">MemberDefAliasImpl::isFriendToHide</a>.
</div>
</div>

### isFunction() {#a5e6ace25ee464a601e1b3f2b8016ddad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5e6ace25ee464a601e1b3f2b8016ddad">isFunction</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a5e6ace25ee464a601e1b3f2b8016ddad">isFunction</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#af0747f22d1735bdc8ff1826e3373a1b5">MemberDefAliasImpl::isFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isFunctionOrSignalSlot() {#abd18512439916b8cb1fc1f7a43ebc6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFunctionOrSignalSlot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#abd18512439916b8cb1fc1f7a43ebc6b5">isFunctionOrSignalSlot</a>.

Referenced by <a href="#abd18512439916b8cb1fc1f7a43ebc6b5">isFunctionOrSignalSlot</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a970d9105d969a974966f986e2b4f7348">MemberDefAliasImpl::isFunctionOrSignalSlot</a>.
</div>
</div>

### isFunctionPtr() {#a9795a9ed4f86eca5ce5d39e88d21d36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isFunctionPtr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a9795a9ed4f86eca5ce5d39e88d21d36e">isFunctionPtr</a>.

Referenced by <a href="#a9795a9ed4f86eca5ce5d39e88d21d36e">isFunctionPtr</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8d25384df617106167b8219d0a903bc9">MemberDefAliasImpl::isFunctionPtr</a>.
</div>
</div>

### isGettable() {#aba4783c1fa6a84a2beb2b4dad7000616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isGettable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aba4783c1fa6a84a2beb2b4dad7000616">isGettable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#aba4783c1fa6a84a2beb2b4dad7000616">isGettable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a755c0ff5a72f45da656e7c128729b5ef">MemberDefAliasImpl::isGettable</a>.
</div>
</div>

### isImplementation() {#aa5cec965870198c96a14371c694b2027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isImplementation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa5cec965870198c96a14371c694b2027">isImplementation</a>.

Referenced by <a href="#aa5cec965870198c96a14371c694b2027">isImplementation</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aaf2c3cd1c5be7ca69a96953266571502">MemberDefAliasImpl::isImplementation</a>.
</div>
</div>

### isInitonly() {#a02a894331323ad650cd3b748ce9d604b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isInitonly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a02a894331323ad650cd3b748ce9d604b">isInitonly</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a02a894331323ad650cd3b748ce9d604b">isInitonly</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a589d384c25ad38975d3a3d1cd75e0133">MemberDefAliasImpl::isInitonly</a>.
</div>
</div>

### isInline() {#a509e150708bb48d4bafaa1146cf1eadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isInline ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a509e150708bb48d4bafaa1146cf1eadc">isInline</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a509e150708bb48d4bafaa1146cf1eadc">isInline</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa1f1d51208383f2c81fd4c4d5a0fc478">MemberDefAliasImpl::isInline</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isMaybeAmbiguous() {#a581d0d2acf3c99191e1a5f3cb5f95ce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isMaybeAmbiguous ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a581d0d2acf3c99191e1a5f3cb5f95ce6">isMaybeAmbiguous</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a581d0d2acf3c99191e1a5f3cb5f95ce6">isMaybeAmbiguous</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aec44aaf8241ba26741e2fea6e2966a41">MemberDefAliasImpl::isMaybeAmbiguous</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isMaybeDefault() {#a735ac6b44a83924b761bdac676eb4184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isMaybeDefault ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 171 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a735ac6b44a83924b761bdac676eb4184">isMaybeDefault</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a735ac6b44a83924b761bdac676eb4184">isMaybeDefault</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab320224993c7aa32f199213aae3a13db">MemberDefAliasImpl::isMaybeDefault</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isMaybeVoid() {#a18b343dd677e74a1ecb5723fbb746395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isMaybeVoid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a18b343dd677e74a1ecb5723fbb746395">isMaybeVoid</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a18b343dd677e74a1ecb5723fbb746395">isMaybeVoid</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a507a2e8f5189db220046ec9eba425b0d">MemberDefAliasImpl::isMaybeVoid</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isMutable() {#af448f46a30d6337ef678db352dd244e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isMutable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af448f46a30d6337ef678db352dd244e3">isMutable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#af448f46a30d6337ef678db352dd244e3">isMutable</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad7d3f80b8d2a91e9b94dda4fce12e189">MemberDefAliasImpl::isMutable</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isNew() {#a0ceb921ed3647329a26b0c9ce434658d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isNew ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a0ceb921ed3647329a26b0c9ce434658d">isNew</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a0ceb921ed3647329a26b0c9ce434658d">isNew</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ae6912fde0d29f2ec38854eddf40e4028">MemberDefAliasImpl::isNew</a>.
</div>
</div>

### isNoDiscard() {#ac2fda10e3128c3e735e5b24132037033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isNoDiscard ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 189 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ac2fda10e3128c3e735e5b24132037033">isNoDiscard</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#ac2fda10e3128c3e735e5b24132037033">isNoDiscard</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8802beb0983afad477fe8448f09a1836">MemberDefAliasImpl::isNoDiscard</a>.
</div>
</div>

### isNoExcept() {#a06ea035c8de361f0ba253fc45e3303f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isNoExcept ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a06ea035c8de361f0ba253fc45e3303f0">isNoExcept</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a06ea035c8de361f0ba253fc45e3303f0">isNoExcept</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa03b6d02d98fd30acc7df09ba5893bea">MemberDefAliasImpl::isNoExcept</a>.
</div>
</div>

### isNonAtomic() {#a8981c87afa75a323943f727919c2669c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isNonAtomic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a8981c87afa75a323943f727919c2669c">isNonAtomic</a>.

Referenced by <a href="#a8981c87afa75a323943f727919c2669c">isNonAtomic</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac11dede9f1d533589bcc263b838a776e">MemberDefAliasImpl::isNonAtomic</a>.
</div>
</div>

### isNotFriend() {#ad8a677f4f48e4bf01762fc024a230092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isNotFriend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ad8a677f4f48e4bf01762fc024a230092">isNotFriend</a>.

Referenced by <a href="#ad8a677f4f48e4bf01762fc024a230092">isNotFriend</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ace019d70ff0c8254bef4aa56ceb3a0fc">MemberDefAliasImpl::isNotFriend</a>.
</div>
</div>

### isObjCMethod() {#a146e2a27f8eee953b076a03e42ecf2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isObjCMethod ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="#a146e2a27f8eee953b076a03e42ecf2b4">isObjCMethod</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa42b95dd3caf3e01a2be33f9f759ed77">MemberDefAliasImpl::isObjCMethod</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isObjCProperty() {#aae943a44f4314a00a9572d0fa5e364e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isObjCProperty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 176 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aae943a44f4314a00a9572d0fa5e364e7">isObjCProperty</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="#aae943a44f4314a00a9572d0fa5e364e7">isObjCProperty</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a77456de8cef37bf10fa93b498fc9a1b8">MemberDefAliasImpl::isObjCProperty</a>.
</div>
</div>

### isOptional() {#ab41ecacc3c433253d893d6baded01de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isOptional ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab41ecacc3c433253d893d6baded01de0">isOptional</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#ab41ecacc3c433253d893d6baded01de0">isOptional</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a1cbaad4c6e93b2b64b8c0a6bc6ae39cd">MemberDefAliasImpl::isOptional</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isOverride() {#a3a02263fa1b55949b87c237f452d081c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isOverride ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a3a02263fa1b55949b87c237f452d081c">isOverride</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a3a02263fa1b55949b87c237f452d081c">isOverride</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aabc01d50cd14e53abba3a296f8be58d1">MemberDefAliasImpl::isOverride</a>.
</div>
</div>

### isPrivateGettable() {#a594fe47b12073b186b7f1e4d8e2b1d56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isPrivateGettable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a594fe47b12073b186b7f1e4d8e2b1d56">isPrivateGettable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a594fe47b12073b186b7f1e4d8e2b1d56">isPrivateGettable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a25bc5921a289bee18e0565da07a9d0d6">MemberDefAliasImpl::isPrivateGettable</a>.
</div>
</div>

### isPrivateSettable() {#a787020ca6fc65ea0cc13f5721d166420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isPrivateSettable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a787020ca6fc65ea0cc13f5721d166420">isPrivateSettable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a787020ca6fc65ea0cc13f5721d166420">isPrivateSettable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa95344595e0dcd6ba9d02cde3b3a03a4">MemberDefAliasImpl::isPrivateSettable</a>.
</div>
</div>

### isProperty() {#afd4a6cd84468b885049120e767b017fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isProperty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#afd4a6cd84468b885049120e767b017fc">isProperty</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="#afd4a6cd84468b885049120e767b017fc">isProperty</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a4ac81474a1ebc01260b7491390ee4128">MemberDefAliasImpl::isProperty</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### isProtectedGettable() {#aa69883d56b1adfe457130d7c96873ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isProtectedGettable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa69883d56b1adfe457130d7c96873ba7">isProtectedGettable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#aa69883d56b1adfe457130d7c96873ba7">isProtectedGettable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a5ba255038b64148283080b54d1d5fb2f">MemberDefAliasImpl::isProtectedGettable</a>.
</div>
</div>

### isProtectedSettable() {#aa51dd090dc6e2d111145cc04e9e3f7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isProtectedSettable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa51dd090dc6e2d111145cc04e9e3f7fe">isProtectedSettable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#aa51dd090dc6e2d111145cc04e9e3f7fe">isProtectedSettable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab66e2650f487bc524f5141f5a0813077">MemberDefAliasImpl::isProtectedSettable</a>.
</div>
</div>

### isPrototype() {#afa756b712f45e7800617808f708c2876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isPrototype ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 221 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#afa756b712f45e7800617808f708c2876">isPrototype</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="#afa756b712f45e7800617808f708c2876">isPrototype</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a9a3eb9ee7d26eaf24573549b9aefecf4">MemberDefAliasImpl::isPrototype</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>.
</div>
</div>

### isPublished() {#a92b07d194b0db97594df0116577e9fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isPublished ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a92b07d194b0db97594df0116577e9fbf">isPublished</a>.

Referenced by <a href="#a92b07d194b0db97594df0116577e9fbf">isPublished</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3a7c437c3828695f29752a5f31248658">MemberDefAliasImpl::isPublished</a>.
</div>
</div>

### isRaisable() {#a7e0e45a5885e55221f756a8e3153fb8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isRaisable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a7e0e45a5885e55221f756a8e3153fb8a">isRaisable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a7e0e45a5885e55221f756a8e3153fb8a">isRaisable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a7402786b99b7f04456f80573da94f025">MemberDefAliasImpl::isRaisable</a>.
</div>
</div>

### isReadable() {#abf0cad08f28ef0b4e73fd13baefa56a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isReadable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#abf0cad08f28ef0b4e73fd13baefa56a8">isReadable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#abf0cad08f28ef0b4e73fd13baefa56a8">isReadable</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#abd6af4902118a2b7ff610312e416b399">MemberDefAliasImpl::isReadable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab67c7ae917805e8f25cef32df3cc48ff">MemberDefAliasImpl::isReadonly</a>.
</div>
</div>

### isReadonly() {#a8679a7213fda9304814aa989c731a4a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isReadonly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a8679a7213fda9304814aa989c731a4a9">isReadonly</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a8679a7213fda9304814aa989c731a4a9">isReadonly</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isReimplementedBy() {#a88908e0048f8220fea8ce3a116adc415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isReimplementedBy (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a88908e0048f8220fea8ce3a116adc415">isReimplementedBy</a>.

Referenced by <a href="#a88908e0048f8220fea8ce3a116adc415">isReimplementedBy</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac58e88197be888fa19664ae1e77850f1">MemberDefAliasImpl::isReimplementedBy</a>.
</div>
</div>

### isRelated() {#a273e3f09760e57d718ee9d3c66f73eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isRelated ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a273e3f09760e57d718ee9d3c66f73eaa">isRelated</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a273e3f09760e57d718ee9d3c66f73eaa">isRelated</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aab165191f96c1133cdb92eb7d5e4b1db">MemberDefAliasImpl::isRelated</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isRelatedOrFriend() {#a2dd3ac8d3848d07104ad3e3e35590f3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isRelatedOrFriend ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2dd3ac8d3848d07104ad3e3e35590f3a">isRelatedOrFriend</a>.

Referenced by <a href="#a2dd3ac8d3848d07104ad3e3e35590f3a">isRelatedOrFriend</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa202b519e1e4762ee11142ddbc393364">MemberDefAliasImpl::isRelatedOrFriend</a>.
</div>
</div>

### isRemovable() {#a7ebd90ccb692199c14ef91526df6d534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isRemovable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a7ebd90ccb692199c14ef91526df6d534">isRemovable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a7ebd90ccb692199c14ef91526df6d534">isRemovable</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a206cd0c0eb498fbfa66bdc2a207e2bf2">MemberDefAliasImpl::isRemovable</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isRequired() {#a62549140ec2a398af9b6a72c63aad7d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isRequired ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a62549140ec2a398af9b6a72c63aad7d5">isRequired</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a62549140ec2a398af9b6a72c63aad7d5">isRequired</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a1fd086462901b0dfc2eb04c94965d68b">MemberDefAliasImpl::isRequired</a>.
</div>
</div>

### isRetain() {#a4902c8d45c53057b6b421a22821d999b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isRetain ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4902c8d45c53057b6b421a22821d999b">isRetain</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a4902c8d45c53057b6b421a22821d999b">isRetain</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#afa154f7b3999d8f1cd8ed1b29beb4b8d">MemberDefAliasImpl::isRetain</a>.
</div>
</div>

### isSealed() {#a1b3f4fc396e748b60fd3f4057f0bba21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isSealed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1b3f4fc396e748b60fd3f4057f0bba21">isSealed</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a1b3f4fc396e748b60fd3f4057f0bba21">isSealed</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa9967681dec57fe3e0f083ea236aeebc">MemberDefAliasImpl::isSealed</a>.
</div>
</div>

### isSequence() {#a2f97f032bc09463bf950820e6431fdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a2f97f032bc09463bf950820e6431fdc5">isSequence</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="#a2f97f032bc09463bf950820e6431fdc5">isSequence</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3c80869d42d2f59a9ad001f85b7df8d4">MemberDefAliasImpl::isSequence</a>.
</div>
</div>

### isSettable() {#a44b6a11c61d72073dcfc17d85a303ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isSettable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a44b6a11c61d72073dcfc17d85a303ac5">isSettable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a44b6a11c61d72073dcfc17d85a303ac5">isSettable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a0abefa5c2e8fe6ce87ec8516c7c0f0ed">MemberDefAliasImpl::isSettable</a>.
</div>
</div>

### isSignal() {#a02d2e041a0c3a89c0968b20869aa1981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isSignal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a02d2e041a0c3a89c0968b20869aa1981">isSignal</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="#a02d2e041a0c3a89c0968b20869aa1981">isSignal</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a26320cf7689c4d20e74be1da6d8f80c9">MemberDefAliasImpl::isSignal</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isSliceLocal() {#ae2109d4aac7f6350a75dadc71ddc55f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isSliceLocal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ae2109d4aac7f6350a75dadc71ddc55f1">isSliceLocal</a>.

Referenced by <a href="#ae2109d4aac7f6350a75dadc71ddc55f1">isSliceLocal</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a39377a7a9eeafa5b719a32611bc55b0c">MemberDefAliasImpl::isSliceLocal</a>.
</div>
</div>

### isSlot() {#a4db9f074e1f02c5dbf901d120fd433aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isSlot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4db9f074e1f02c5dbf901d120fd433aa">isSlot</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="#a4db9f074e1f02c5dbf901d120fd433aa">isSlot</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aba9933110de3e136262dd61e6378fd2d">MemberDefAliasImpl::isSlot</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isStatic() {#a73354ecea5b876ab8d59724b080189b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isStatic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a73354ecea5b876ab8d59724b080189b4">isStatic</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a73354ecea5b876ab8d59724b080189b4">isStatic</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa8100dfae56865b75c0b8f2bdcf36cb4">MemberDefAliasImpl::isStatic</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isStrong() {#adbdbd0e3d3630af579a02e97e162a328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isStrong ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#adbdbd0e3d3630af579a02e97e162a328">isStrong</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="#adbdbd0e3d3630af579a02e97e162a328">isStrong</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aa3114a7bc21087a094c223464902f7de">MemberDefAliasImpl::isStrong</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

### isStrongEnumValue() {#a5b99e725308ea15248722f69611844aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isStrongEnumValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5b99e725308ea15248722f69611844aa">isStrongEnumValue</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="#a5b99e725308ea15248722f69611844aa">isStrongEnumValue</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a2969ee1363bb112bfb9482eedf8e2a01">MemberDefAliasImpl::isStrongEnumValue</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>.
</div>
</div>

### isTemplateSpecialization() {#a784f1e1160f33e552720b3e90638811c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isTemplateSpecialization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a784f1e1160f33e552720b3e90638811c">isTemplateSpecialization</a>.

Referenced by <a href="#a784f1e1160f33e552720b3e90638811c">isTemplateSpecialization</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ace8d6b166d0994f5971774ecf7f914da">MemberDefAliasImpl::isTemplateSpecialization</a>.
</div>
</div>

### isTransient() {#aafb531645493ceda329fc922748401be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isTransient ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aafb531645493ceda329fc922748401be">isTransient</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#aafb531645493ceda329fc922748401be">isTransient</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad668b3f180e3fbddbd1a7cbff94d9b5b">MemberDefAliasImpl::isTransient</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isTypeAlias() {#a6ebab5c76a587caadf8f3079729625fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isTypeAlias ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a6ebab5c76a587caadf8f3079729625fd">isTypeAlias</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a6ebab5c76a587caadf8f3079729625fd">isTypeAlias</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a1f85ea333f42181b416753f52439afcf">MemberDefAliasImpl::isTypeAlias</a>.
</div>
</div>

### isTypedef() {#a4bd8f9b14007a57f53918a21258c284e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isTypedef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4ca7796c0d1fc682a180bc156f3a3514">checkIfTypedef</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#a4bd8f9b14007a57f53918a21258c284e">isTypedef</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a9e5c7b14984d6b058605c47bd467a888">MemberDefAliasImpl::isTypedef</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isTypedefValCached() {#a7f317162cd72dbfd6829ee85aec91170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isTypedefValCached ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 254 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a7f317162cd72dbfd6829ee85aec91170">isTypedefValCached</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a082d23658541704d3493a7a881583d55">flushCachedTemplateRelations</a>, <a href="#a7f317162cd72dbfd6829ee85aec91170">isTypedefValCached</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a709a9fa50b5fbd6c976118306f35694a">MemberDefAliasImpl::isTypedefValCached</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>.
</div>
</div>

### isUNOProperty() {#ae4cae75d9163036f5bc9a232dc880812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isUNOProperty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ae4cae75d9163036f5bc9a232dc880812">isUNOProperty</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#ae4cae75d9163036f5bc9a232dc880812">isUNOProperty</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a30ecc7761226752f24e6d492af6d6f8b">MemberDefAliasImpl::isUNOProperty</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isUnretained() {#aca8123dc4361300613c03c9d5a5e8883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isUnretained ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aca8123dc4361300613c03c9d5a5e8883">isUnretained</a>.

Referenced by <a href="#aca8123dc4361300613c03c9d5a5e8883">isUnretained</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a750ddf88331742ad530fae31b78f9096">MemberDefAliasImpl::isUnretained</a>.
</div>
</div>

### isVariable() {#ad7b6f788b487058e9e6ac65b092479b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isVariable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 112 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ad7b6f788b487058e9e6ac65b092479b9">isVariable</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a79a8496dde56d56eadf905399ec62dcf">Index::addFileMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/classes/index/#a638834a45c0d08559e4b0fc8bdb19b8b">Index::addNamespaceMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#ae15cbb19e2f84dafe98f527902c3e2d9">definitionToName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#ad7b6f788b487058e9e6ac65b092479b9">isVariable</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a3d7922bda533b87314d09283b9d5dcc8">MemberDefAliasImpl::isVariable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4ee52c8be189a58fdf71cac6164f6be1">transferFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5234f1896d9c47e7836c34e3b03a36b0">transferStaticInstanceInitializers</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### isWeak() {#ac14124f33e6513789346a840f5e49385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isWeak ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ac14124f33e6513789346a840f5e49385">isWeak</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#ac14124f33e6513789346a840f5e49385">isWeak</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad7c4fcca4a0164a66ceb4c0b55ecbaf6">MemberDefAliasImpl::isWeak</a>.
</div>
</div>

### isWritable() {#a562a056cb102eb78ad78fffe455a2db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::isWritable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a562a056cb102eb78ad78fffe455a2db9">isWritable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a562a056cb102eb78ad78fffe455a2db9">isWritable</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a4bc49cdab0c9376d6e4e9d8d29b839a3">MemberDefAliasImpl::isWritable</a>.
</div>
</div>

### livesInsideEnum() {#a746d9cacb5bd7eed7e99697ad6c8314b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::livesInsideEnum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 184 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a746d9cacb5bd7eed7e99697ad6c8314b">livesInsideEnum</a>.

Referenced by <a href="#a746d9cacb5bd7eed7e99697ad6c8314b">livesInsideEnum</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a5ce6334345bc14e98b2f83c128af6660">MemberDefAliasImpl::livesInsideEnum</a> and <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a516a3565cbd64716f4dccc6a8e00bf86">MemberDefMutable::setEnumScope</a>.
</div>
</div>

### memberDeclaration() {#a160b1eb96684b652bd0611e78d8fe831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberDef * MemberDef::memberDeclaration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 260 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="#a160b1eb96684b652bd0611e78d8fe831">memberDeclaration</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a26b742f8a11431dcdb61d8d0841a23b8">MemberDefAliasImpl::memberDeclaration</a>.
</div>
</div>

### memberDefinition() {#a0b88c6841076c450863bc9b57e5068d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberDef * MemberDef::memberDefinition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp/#a8162981adf82bd139a6f62da022783bf">getUniqueId</a>, <a href="#a0b88c6841076c450863bc9b57e5068d1">memberDefinition</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a9ce42bf45bd30e09601a09b23e6e13bb">MemberDefAliasImpl::memberDefinition</a>.
</div>
</div>

### memberType() {#abbdaf88716807e7ff82ed7502cde51fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberType MemberDef::memberType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a332043aa0d664d063e7fcc0614acbeea">MemberList::addListReferences</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a589e3e52c7dc0599e7342171a7531064">findDefineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a6c89498ad2de8fa4026db0ac73167608">FileDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab3e12b6cb50e36955c0e0362f4d45648">MemberDefAliasImpl::memberType</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a617f35b436f3dd412c26d8ae5c8e0c38">FileDefImpl::removeMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a37a6a44c9519e80b8331cacf2f883bb3">GroupDefImpl::removeMember</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

### memberTypeName() {#aca314e25245ec3b08f1a55068c2fbeff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::memberTypeName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aca314e25245ec3b08f1a55068c2fbeff">memberTypeName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad1c6c890ed8e8ebcfe057f3de5db4fcb">NamespaceDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#aca314e25245ec3b08f1a55068c2fbeff">memberTypeName</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a8e41d8cfbade9b6a17d48c823dc11cd5">MemberDefAliasImpl::memberTypeName</a>.
</div>
</div>

### moveTo() {#a4ff323c90bda3ac08cae467b51061cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::moveTo (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a4ff323c90bda3ac08cae467b51061cdb">moveTo</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a> and <a href="#a4ff323c90bda3ac08cae467b51061cdb">moveTo</a>.
</div>
</div>

### numberOfFlowKeyWords() {#a23dc837ee131aa1642a61efd24764032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int MemberDef::numberOfFlowKeyWords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 190 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a23dc837ee131aa1642a61efd24764032">numberOfFlowKeyWords</a>.

Referenced by <a href="#a23dc837ee131aa1642a61efd24764032">numberOfFlowKeyWords</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad75c8fefd89d01096facb351c34e31ef">MemberDefAliasImpl::numberOfFlowKeyWords</a>.
</div>
</div>

### objCMethodName() {#aa7228a0cbd28108dfab580c17d3f2751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::objCMethodName (bool localLink, bool showStatic)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa7228a0cbd28108dfab580c17d3f2751">objCMethodName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="#aa7228a0cbd28108dfab580c17d3f2751">objCMethodName</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a855d6a793487f48c561e3b2bf01ec07d">MemberDefAliasImpl::objCMethodName</a>.
</div>
</div>

### protection() {#ab266b88c02dd8d5089b29d501b412c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Protection MemberDef::protection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ab266b88c02dd8d5089b29d501b412c5d">protection</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae11c2fb2e5b6cbe3dcd1a1b594406e93">addMemberSpecialization</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a85a426e31ddcde4eb6a417cc0a939d6a">ClassDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="#ab266b88c02dd8d5089b29d501b412c5d">protection</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#aba0c7bf5ac1c402b002393ec5321f391">MemberDefAliasImpl::protection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a37a6a44c9519e80b8331cacf2f883bb3">GroupDefImpl::removeMember</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### reimplementedBy() {#a5cdaf0953a164c3e6d7831a39c072e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberVector &amp; MemberDef::reimplementedBy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a5cdaf0953a164c3e6d7831a39c072e71">reimplementedBy</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a5cdaf0953a164c3e6d7831a39c072e71">reimplementedBy</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ab14ffecb13ba23fe06ee22a858ff083b">MemberDefAliasImpl::reimplementedBy</a>.
</div>
</div>

### reimplements() {#a735862f449c091668f1fc86004aab3a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::reimplements ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a735862f449c091668f1fc86004aab3a2">reimplements</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0eecb8116d4410392244f76fb8c209e6">DocPara::handleInheritDoc</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad23f7d576fcba6cc66edf702842a9d3">inheritDocumentation</a>, <a href="#a735862f449c091668f1fc86004aab3a2">reimplements</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a1623c7801402bbcdc4dc0a1912d20c03">MemberDefAliasImpl::reimplements</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a4d2df8a849eaf8f463153085bdbb395e">MemberDefImpl::virtualness</a>.
</div>
</div>

### relatedAlso() {#ad00728f58f71b2b8baf6f9913c7651ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassDef * MemberDef::relatedAlso ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 210 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ad00728f58f71b2b8baf6f9913c7651ae">relatedAlso</a>.

Referenced by <a href="#ad00728f58f71b2b8baf6f9913c7651ae">relatedAlso</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#af9821d9750e9656468d1ae8e4ad1c175">MemberDefAliasImpl::relatedAlso</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>.
</div>
</div>

### requiresClause() {#a07a3159272913d2f0f441761a28ee674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::requiresClause ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a07a3159272913d2f0f441761a28ee674">requiresClause</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a07a3159272913d2f0f441761a28ee674">requiresClause</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ad7d83acc0b3a60293cd0977280388285">MemberDefAliasImpl::requiresClause</a>.
</div>
</div>

### resolveAlias() {#a8366efce20df1bf0f096d6296189e474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberDef * MemberDef::resolveAlias ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a8366efce20df1bf0f096d6296189e474">resolveAlias</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="#a20f15f4ba2a99554f061c8091414d05b">resolveAlias</a>, <a href="#a8366efce20df1bf0f096d6296189e474">resolveAlias</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>.
</div>
</div>

### resolveAlias() {#a20f15f4ba2a99554f061c8091414d05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::resolveAlias ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a8366efce20df1bf0f096d6296189e474">resolveAlias</a>.
</div>
</div>

### setMemberGroup() {#aa605daa08e85f7261890848ad923cbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::setMemberGroup (<a href="/web-doxygen/docs/api/classes/membergroup">MemberGroup</a> * grp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa605daa08e85f7261890848ad923cbd9">setMemberGroup</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a> and <a href="#aa605daa08e85f7261890848ad923cbd9">setMemberGroup</a>.
</div>
</div>

### sourceRefName() {#a64c6a04cf0c6d2ebf56ed6959ce1f89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::sourceRefName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a64c6a04cf0c6d2ebf56ed6959ce1f89d">sourceRefName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a91959a7c929a76adaaa2d342fea73126">addDocCrossReference</a>, <a href="#a64c6a04cf0c6d2ebf56ed6959ce1f89d">sourceRefName</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#af778660d0ae437277f50370242772766">MemberDefAliasImpl::sourceRefName</a>.
</div>
</div>

### templateArguments() {#a409da33c248938e57ba2135777a38628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentList &amp; MemberDef::templateArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a409da33c248938e57ba2135777a38628">templateArguments</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="#a409da33c248938e57ba2135777a38628">templateArguments</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#afdd265b9ac0946266fa37ff7e857bf57">MemberDefAliasImpl::templateArguments</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#adbab9cdf5d958b7f7ac7b736428974dd">writeMemberTemplateLists</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6afc0eddf054d70eebc855c3a8608fcd">writeMemberTemplateLists</a>.
</div>
</div>

### templateMaster() {#aaa1f125e42e876b4e552f71a4748b42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * MemberDef::templateMaster ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aaa1f125e42e876b4e552f71a4748b42f">templateMaster</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="#aaa1f125e42e876b4e552f71a4748b42f">templateMaster</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a413f31e4d616a724c917698ac8c8c1a3">MemberDefAliasImpl::templateMaster</a>.
</div>
</div>

### typeConstraints() {#aa01306dc1e488d40d7b3b600091e4ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentList &amp; MemberDef::typeConstraints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 271 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#aa01306dc1e488d40d7b3b600091e4ec9">typeConstraints</a>.

Referenced by <a href="#aa01306dc1e488d40d7b3b600091e4ec9">typeConstraints</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a959f313af181818940511b0fd4bdc09e">MemberDefAliasImpl::typeConstraints</a>.
</div>
</div>

### typeString() {#a0032c6e040cdec6d9c52dc75a790a884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString MemberDef::typeString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1ba016192f46b348d5dbc66f8f574380">createUsingMemberImportForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7970104534296194ccd535117234a682">resolveTypeDef</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a>, <a href="#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ace92d8d5ef32aaaa9f2db11acc7f6175">MemberDefAliasImpl::typeString</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a8da5e564ca5debbb07a26fb91c0fc3d6">updateCallContextForSmartPointer</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a76fe2943fccabc70c52ad3b6e31f4fa5">VhdlDocGen::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### virtualness() {#ae450a2be776cc5d05726bab8354f6d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Specifier MemberDef::virtualness (int count=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::\_writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a81142c12bb2ef7638500997115bf2f43">PerlModGenerator::addListOfAllMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#affa42bdf0b91c838fe0215b4e6afb7b5">associateMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a95a1eb3d3f08bcdfcf8e69053003eeb5">MemberDefAliasImpl::virtualness</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a4d2df8a849eaf8f463153085bdbb395e">MemberDefImpl::virtualness</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a361dd0c822c454f8b1fe78d762c9d872">writeListOfAllMembers</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### visibleInIndex() {#a341567c872ef0f346b59c1dd84c49a57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool MemberDef::visibleInIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 294 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a341567c872ef0f346b59c1dd84c49a57">visibleInIndex</a>.

Referenced by <a href="#a341567c872ef0f346b59c1dd84c49a57">visibleInIndex</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#af6090bc5e816e9d9183b770c853ff4ad">MemberDefAliasImpl::visibleInIndex</a>.
</div>
</div>

### warnIfUndocumented() {#a1212af3d2b7edf710bbda655097a8a7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::warnIfUndocumented ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 292 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a1212af3d2b7edf710bbda655097a8a7b">warnIfUndocumented</a>.

Referenced by <a href="#a1212af3d2b7edf710bbda655097a8a7b">warnIfUndocumented</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### warnIfUndocumentedParams() {#af292c658cf6cf0f6ac800f520818f7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::warnIfUndocumentedParams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 293 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#af292c658cf6cf0f6ac800f520818f7b6">warnIfUndocumentedParams</a>.

Referenced by <a href="#af292c658cf6cf0f6ac800f520818f7b6">warnIfUndocumentedParams</a>.
</div>
</div>

### writeDeclaration() {#a21917a4770d64cc6a97a6b2c81c45312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::writeDeclaration (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * md, bool inGroup, int indentLevel=0, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritFrom=nullptr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 283 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a21917a4770d64cc6a97a6b2c81c45312">writeDeclaration</a>.

Referenced by <a href="#a21917a4770d64cc6a97a6b2c81c45312">writeDeclaration</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ace02aaabe60838f7e8cd349bc4d132c0">MemberDefAliasImpl::writeDeclaration</a>.
</div>
</div>

### writeEnumDeclaration() {#a19bbaeceb1a5834827c03aaf6cac4e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::writeEnumDeclaration (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; typeDecl, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

Reference <a href="#a19bbaeceb1a5834827c03aaf6cac4e3f">writeEnumDeclaration</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="#a19bbaeceb1a5834827c03aaf6cac4e3f">writeEnumDeclaration</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#ac9d1ca230c04570fdb23923c0b2a421b">MemberDefAliasImpl::writeEnumDeclaration</a>.
</div>
</div>

### writeLink() {#acbb488146339ce401624a13e908c95ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void MemberDef::writeLink (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * md, bool onlyText=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 288 of file <a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>.

References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#acbb488146339ce401624a13e908c95ab">writeLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="#acbb488146339ce401624a13e908c95ab">writeLink</a> and <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a631a6b4069c839eeb964ceaba0c012ed">MemberDefAliasImpl::writeLink</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
