---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/classdef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ClassDef` Class Reference

<p>A abstract class representing of a compound symbol. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ClassDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/classdef-h">src/classdef.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CompoundType { <a href="#ae70cf86d35fe954a94c566fbcfc87939">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The various compound types. <a href="#ae70cf86d35fe954a94c566fbcfc87939">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98feeeb839e90eea9c64ba2f2fabfb8">deepCopy</a> (const QCString &amp;name) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9efadd9727924f524013b3b46238c980">moveTo</a> (Definition *)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8476d860cfdada4916c4dc722f0bea07">getInstanceOutputFileBase</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b24aeece30ae83930ed2a3ca0621fec">isLocal</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this is a local class definition, see EXTRACT_LOCAL_CLASSES. <a href="#a6b24aeece30ae83930ed2a3ca0621fec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb64dc8f57c5d07f1b1d55bc560a7004">getClasses</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the classes nested into this class <a href="#aeb64dc8f57c5d07f1b1d55bc560a7004">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd0e2c039c6d81ffa25579184568e87">hasDetailedDescription</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns TRUE if this class has a non-empty detailed description <a href="#a1fd0e2c039c6d81ffa25579184568e87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe7312465f1dfe18360ed5effbf7c32">collaborationGraphFileName</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the file name to use for the collaboration graph <a href="#aabe7312465f1dfe18360ed5effbf7c32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4feb0d6c2afb9ab04ba7faec2becf27e">inheritanceGraphFileName</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the file name to use for the inheritance graph <a href="#a4feb0d6c2afb9ab04ba7faec2becf27e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae70cf86d35fe954a94c566fbcfc87939">CompoundType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of compound this is, i.e. <a href="#ae8ba915e00984129bcbbaa4efff48b00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239fe977638806153345cd2411c28062">compoundTypeString</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of compound as a string. <a href="#a239fe977638806153345cd2411c28062">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38001a11a297629e363c0db5b1968ab3">baseClasses</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of base classes from which this class directly inherits. <a href="#a38001a11a297629e363c0db5b1968ab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a053f323d6b837a81cd86a82ce3c4d4a4">updateBaseClasses</a> (const BaseClassList &amp;bcd)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the list of base classes to the one passed. <a href="#a053f323d6b837a81cd86a82ce3c4d4a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of sub classes that directly derive from this class. <a href="#afdeec11149bf831c4c6dd297f7c4e34d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6916d56bb83637aa0be3054cb0f46ac1">updateSubClasses</a> (const BaseClassList &amp;bcd)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the list of sub classes to the one passed. <a href="#a6916d56bb83637aa0be3054cb0f46ac1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membernameinfolinkedmap">MemberNameInfoLinkedMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f58a78e8196768f3ddd17e645cf7f9">memberNameInfoLinkedMap</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a dictionary of all members. <a href="#ac8f58a78e8196768f3ddd17e645cf7f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759c68ae0af03a49aff1a86d383af68d">protection</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the protection level (Public,Protected,Private) in which this compound was found. <a href="#a759c68ae0af03a49aff1a86d383af68d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3067e647412a923d7743258c89eabe75">isVisibleInHierarchy</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>the class is visible in a class diagram, or class hierarchy <a href="#a3067e647412a923d7743258c89eabe75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a79f778ae2201c52ee19c048763d4fa">visibleInParentsDeclList</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>show this class in the declaration section of its parent? <a href="#a1a79f778ae2201c52ee19c048763d4fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the template arguments of this class. <a href="#a201b8f24043f9b7c7cc59d55282f6d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4a0864e51e5a3ac616f6c8e10f56c6">getFileDef</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the namespace this compound is in, or 0 if it has a global scope. <a href="#aed4a0864e51e5a3ac616f6c8e10f56c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109769b1e6eb23eb36e23530e667703e">getModuleDef</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the C++20 module in which this compound's definition can be found. <a href="#a109769b1e6eb23eb36e23530e667703e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bec35936216530bf2385a8dfd2ab0e5">getMemberByName</a> (const QCString &amp;) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the member with the given name. <a href="#a3bec35936216530bf2385a8dfd2ab0e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e118df515565a29662b41396ee66579">isBaseClass</a> (const ClassDef *bcd, bool followInstances, const QCString &amp;templSpec=QCString()) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE iff <em>bcd</em> is a direct or indirect base class of this class. <a href="#a3e118df515565a29662b41396ee66579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4c36f29d33a44a6b7460e89a7cd741">isSubClass</a> (ClassDef *bcd, int level=0) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE iff <em>bcd</em> is a direct or indirect sub class of this class. <a href="#a9a4c36f29d33a44a6b7460e89a7cd741">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f8aa899e9bf12dacd3442c9647bac4">isAccessibleMember</a> (const MemberDef *md) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns TRUE iff <em>md</em> is a member of this class or of the the public/protected members of a base class <a href="#aa4f8aa899e9bf12dacd3442c9647bac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#ac6ced1c572e645da3d141b20bad3aeb4">TemplateInstanceList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ceb3e484b62599117b5eb424c10fd10">getTemplateInstances</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a sorted dictionary with all template instances found for this template class. <a href="#a3ceb3e484b62599117b5eb424c10fd10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae587759f556ea0d641b92a30e923a7c9">templateMaster</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the template master of which this class is an instance. <a href="#ae587759f556ea0d641b92a30e923a7c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f19d5b8fb17b204b9e41d19b2ca49f">isTemplate</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is a template. <a href="#a30f19d5b8fb17b204b9e41d19b2ca49f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c57a31c5cbef35d12de99e88745f66">includeInfo</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/usesclasslist">UsesClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a15dff9d9567c126433228fff77837b">usedImplementationClasses</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/usesclasslist">UsesClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade6f41d07606c61673264a5d50e95c61">usedByImplementationClasses</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/constraintclasslist">ConstraintClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8e27ea299fea8b7d180608bfb1326b">templateTypeConstraints</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eabb427f58a6631c73f76c6856694a7">isTemplateArgument</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e4fb6ebed35075ecee567872abbe20">getTemplateParameterLists</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the template parameter lists that form the template declaration of this class. <a href="#a43e4fb6ebed35075ecee567872abbe20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad488bfd3800b79d9984bb2e11aadde2f">qualifiedNameWithTemplateParameters</a> (const ArgumentLists *actualParams=nullptr, uint32_t *actualParamIndex=nullptr) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12dd6a6b0ac63233a82327a8b2d2d9f2">isAbstract</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if there is at least one pure virtual member in this class. <a href="#a12dd6a6b0ac63233a82327a8b2d2d9f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9613dc45d98c8cd04a6fcf6a4f21ee">isObjectiveC</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is implemented in Objective-C. <a href="#a4d9613dc45d98c8cd04a6fcf6a4f21ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f184cac0ea4de2d27b0c0957ab9b77">isFortran</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is implemented in Fortran. <a href="#a25f184cac0ea4de2d27b0c0957ab9b77">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bfbc9a9cc5af4db69a0b5a796a28d38">isCSharp</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is implemented in C#. <a href="#a8bfbc9a9cc5af4db69a0b5a796a28d38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c81095d49e7a4e05820d9928deaa45">isFinal</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is marked as final. <a href="#a18c81095d49e7a4e05820d9928deaa45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcc0025ce9b44d8617da2abaf0eb978">isSealed</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is marked as sealed. <a href="#a3bcc0025ce9b44d8617da2abaf0eb978">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab61c051bbda755836c90d7be3d63e4f2">isPublished</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class is marked as published. <a href="#ab61c051bbda755836c90d7be3d63e4f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a066b13127c13f73ae916af7d883ea1">isExtension</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class represents an Objective-C 2.0 extension (nameless category) <a href="#a8a066b13127c13f73ae916af7d883ea1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c23670661fa0360c44d3352b16135b4">isForwardDeclared</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class represents a forward declaration of a template class. <a href="#a8c23670661fa0360c44d3352b16135b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebcf69f2e74678dc5e62f1b528c9b902">isInterface</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if this class represents an interface. <a href="#aebcf69f2e74678dc5e62f1b528c9b902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81969b4626cb26cd6061f6c54d051827">categoryOf</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the class of which this is a category (Objective-C only) <a href="#a81969b4626cb26cd6061f6c54d051827">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bdad1ebef918dac2ae32233c26ef723">className</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of the class including outer classes, but not including namespaces. <a href="#a2bdad1ebef918dac2ae32233c26ef723">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a> (MemberListType lt) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the members in the list identified by <em>lt</em>. <a href="#a7d2f9d08207ecf5b227c11f8b4ea6d9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberlists">MemberLists</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283e841b3eb34d0ba2e0e106a4e3ad59">getMemberLists</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list containing the list of members sorted per type. <a href="#a283e841b3eb34d0ba2e0e106a4e3ad59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2c3b56273ce664bbaeb0ce1c8f420c">getMemberGroups</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the member groups defined for this class. <a href="#add2c3b56273ce664bbaeb0ce1c8f420c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a52c06547a303385be1dc01559096a3d9">TemplateNameMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3dc7118f6d91b7bc741e29f45215b1">getTemplateBaseClassNames</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee08a2576eb4d2888560c89ab2e1614">isUsedOnly</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac86d2e29cb6233d073aa4c9b5ea726af">isEmbeddedInOuterScope</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7396ab268485c570718f3274105b3f48">isSimple</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4e443b14553fba6f95e3462b531149">tagLessReference</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88fd3d3f7762f2a3c7b3634b554ce579">isSmartPointer</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3699b6766321cef5a194b6fa1a9d2c">isJavaEnum</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb51998523ff484408b2a96fd4f3fced">title</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc67c6c1096d9c72d3daa092c0f480a">generatedFromFiles</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6ba54124ee74df07036e2473579264d">usedFiles</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c4caac2adb12c3207df5936ba2c90b">typeConstraints</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980a867140493e4cf4fd9ded7ee75e55">getExamples</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da7081ddd605c4b0f972d4aeadaf1a0">hasExamples</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac620ac7f22f673e84410b1ceca0af3be">getMemberListFileName</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2ce9f8d0cb3b6f1ba0317ca8dbb714">subGrouping</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9ae30aa6558cef5fd9bda03c1bb569">isSliceLocal</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bfa7122b5f501c389a13c2d55219f44">hasNonReferenceSuperClass</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af404e73b14943149542cf4202bc0ab6d">requiresClause</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570d8dcfdd144e17226ca785e58b15b7">getQualifiers</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91329b7bf621cc29f18774301b923ad">containsOverload</a> (const MemberDef *md) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03b3f6196640021e3c44d7b1eb9e924">isImplicitTemplateInstance</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08a21c84b7e1718d8f2701bc3af6291">countMembersIncludingGrouped</a> (MemberListType lt, const ClassDef *inheritedFrom, bool additional) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e4ba15784fceaf76a6a630a18448095">countMemberDeclarations</a> (MemberListType lt, const ClassDef *inheritedFrom, MemberListType lt2, bool invert, bool showAlways, ClassDefSet &amp;visitedClasses) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd75a76f95d8eacddd4afbb7dc8693a2">writeDeclarationLink</a> (OutputList &amp;ol, bool &amp;found, const QCString &amp;header, bool localNames) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283ca4e39a593316c8c6c83085088900">writeDocumentation</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd404f2052b5c688bf0815741a290842">writeDocumentationForInnerClasses</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e64cf1626ca35924f114aaadac8009">writeMemberPages</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30391896721a6454f35d69ef5457080b">writeMemberList</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcf16726b8d952b1c76d43adfbef197">writeDeclaration</a> (OutputList &amp;ol, const MemberDef *md, bool inGroup, int indentLevel, const ClassDef *inheritedFrom, const QCString &amp;inheritId) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f85844c1b5d67ca6110b3c48053bc77">writeQuickMemberLinks</a> (OutputList &amp;ol, const MemberDef *md) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4c88be7cbea1cd3c46833f69843612">writeSummaryLinks</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8188a9157bac12e715b2a94372a5b59d">writePageNavigation</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59b44de9052b4e62482853fdb7a514a">writeInlineDocumentation</a> (OutputList &amp;ol) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5fb9d775ecdb41ff87abcc2eb44f105">writeTagFile</a> (TextStream &amp;) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac598c1ecb31cdb19524cc60cfe312667">writeMemberDeclarations</a> (OutputList &amp;ol, ClassDefSet &amp;visitedClasses, MemberListType lt, const QCString &amp;title, const QCString &amp;subTitle=QCString(), bool showInline=FALSE, const ClassDef *inheritedFrom=nullptr, MemberListType lt2=MemberListType::Invalid(), bool invert=FALSE, bool showAlways=FALSE) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ed300bfb36eefd34b5ba9f165ff880">addGroupedInheritedMembers</a> (OutputList &amp;ol, MemberListType lt, const ClassDef *inheritedFrom, const QCString &amp;inheritId) const =0</td>
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

<p>A abstract class representing of a compound symbol.</p>


<p>A compound can be a class, struct, union, interface, service, singleton, or exception.</p>

<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### CompoundType {#ae70cf86d35fe954a94c566fbcfc87939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ClassDef::CompoundType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>The various compound types.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Class<a id="ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Struct<a id="ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Union<a id="ae70cf86d35fe954a94c566fbcfc87939a07fb8df6b10c0140665c0421b6f64c09"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Interface<a id="ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Protocol<a id="ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Category<a id="ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exception<a id="ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Service<a id="ae70cf86d35fe954a94c566fbcfc87939aaf2c9d4d2eaa6e6a614d7bd164a29c0e"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Singleton<a id="ae70cf86d35fe954a94c566fbcfc87939a34f6a5dd42307d62a5fe3038b245a667"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00109">109</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">    enum <a href="#ae70cf86d35fe954a94c566fbcfc87939">CompoundType</a> { <a href="#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">Class</a>,     </span><span class="doxyHighlightComment">//=Entry::CLASS_SEC,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939adbed80de6b389027e03afb5abb06f2c9">Struct</a>,    </span><span class="doxyHighlightComment">//=Entry::STRUCT_SEC,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939a07fb8df6b10c0140665c0421b6f64c09">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939a07fb8df6b10c0140665c0421b6f64c09">Union</a>,     </span><span class="doxyHighlightComment">//=Entry::UNION_SEC,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">112</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939a6ff6e3b1bbf7e59a752826880e148528">Interface</a>, </span><span class="doxyHighlightComment">//=Entry::INTERFACE_SEC,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939a16feb88dead0850cea552a51ad9d26b5">Protocol</a>,  </span><span class="doxyHighlightComment">//=Entry::PROTOCOL_SEC,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939a937d0378cd8fb4b49efe215cc6c00469">Category</a>,  </span><span class="doxyHighlightComment">//=Entry::CATEGORY_SEC,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939ad14369c9a6f5e3977c0e02714a4beba8">Exception</a>, </span><span class="doxyHighlightComment">//=Entry::EXCEPTION_SEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939aaf2c9d4d2eaa6e6a614d7bd164a29c0e">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939aaf2c9d4d2eaa6e6a614d7bd164a29c0e">Service</a>,   </span><span class="doxyHighlightComment">//=Entry::CLASS_SEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae70cf86d35fe954a94c566fbcfc87939a34f6a5dd42307d62a5fe3038b245a667">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#ae70cf86d35fe954a94c566fbcfc87939a34f6a5dd42307d62a5fe3038b245a667">Singleton</a>, </span><span class="doxyHighlightComment">//=Entry::CLASS_SEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">                      };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGroupedInheritedMembers() {#ac8ed300bfb36eefd34b5ba9f165ff880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::addGroupedInheritedMembers (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00368">368</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a83b0c4ffd68fcb029528f950303a1ca0">ClassDefAliasImpl::addGroupedInheritedMembers</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>.
</div>
</div>

### baseClasses() {#a38001a11a297629e363c0db5b1968ab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const BaseClassList &amp; ClassDef::baseClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the list of base classes from which this class directly inherits.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00153">153</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#acc3618423ef6577a41a35c61be91a330">ClassDefAliasImpl::baseClasses</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#af0c88e52d4d7424c0840a23a522dc330">classHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a15f807d04ca6a15d183d7c05396bae30">trimBaseClassScope</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.
</div>
</div>

### categoryOf() {#a81969b4626cb26cd6061f6c54d051827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassDef * ClassDef::categoryOf ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the class of which this is a category (Objective-C only)</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00286">286</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::&#95;writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aada67d5160e3ae9c3f0dedadf267d894">ClassDefAliasImpl::categoryOf</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ad1c7d957765b81dbe423423b2f5e5b48">classInheritedProtectionLevel</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a649670159a00e0a1c323df1b40bf01e6">minClassDistance</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.
</div>
</div>

### className() {#a2bdad1ebef918dac2ae32233c26ef723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::className ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the name of the class including outer classes, but not including namespaces.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00291">291</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a9eb13d241236d480b0d37a8c9a918a09">ClassDefAliasImpl::className</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9e5659d6cb4369b41809c279d006b44c">VhdlDocGen::findAllArchitectures</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad4c47fcf278c5cb6b23e82b584413ee8">DefinitionImpl::navigationPathAsString</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a38dfbb5daa66a820f49167beecae6e90">FileDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a2a3b6387c4b99adde50e0751493d4990">GroupDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a16de9b0536cf33e6b6380cf55ecb3ca5">ModuleDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ade0ababe591c242aa32049874d07e298">NamespaceDefImpl::sortMemberLists</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>.
</div>
</div>

### collaborationGraphFileName() {#aabe7312465f1dfe18360ed5effbf7c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::collaborationGraphFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns the file name to use for the collaboration graph</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00139">139</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ab1ea1a5681a32c3199ce2e4cd5bfc443">ClassDefAliasImpl::collaborationGraphFileName</a> and <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a53601818c690d945d05a971b506bb5df">DotClassGraph::DotClassGraph</a>.
</div>
</div>

### compoundType() {#ae8ba915e00984129bcbbaa4efff48b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual CompoundType ClassDef::compoundType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the type of compound this is, i.e.</p>


<p>class/struct/union/..</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00145">145</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::&#95;writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb157ec5dd9aa56ca80abcf1fd5099f7">buildInterfaceAndServiceList</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a7db9cd15a920c0bfc3b396a6a1fa1584">compoundIcon</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ab4defbdd48f1c76760c3cdbaefb26982">ClassDefAliasImpl::compoundType</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#adfe5e615942afd900cff9f219424d5a5">generateLink</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a4aec37ad5da49941a8993835db185ab8">FileDefImpl::insertClass</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a37dc5ed59ff43edea5cae22046984986">NamespaceDefImpl::insertClass</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>.
</div>
</div>

### compoundTypeString() {#a239fe977638806153345cd2411c28062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::compoundTypeString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the type of compound as a string.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00148">148</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a998350d1371352749b27cbe3e955f9c5">ClassDefAliasImpl::compoundTypeString</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1d51f3aad1177695f1c4a6c1340bfa0b">MemberDefImpl::warnIfUndocumented</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### containsOverload() {#ae91329b7bf621cc29f18774301b923ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::containsOverload (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00333">333</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a74c2a1be234252613efc34fee89e3bac">ClassDefAliasImpl::containsOverload</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>.
</div>
</div>

### countMemberDeclarations() {#a0e4ba15784fceaf76a6a630a18448095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int ClassDef::countMemberDeclarations (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt2, bool invert, bool showAlways, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp; visitedClasses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00343">343</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a8635f06556c6af82953ab2e0797db8a6">ClassDefImpl::countInheritedDecMembers</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a0a1f62fe6c0c1994a7e054e57b393719">ClassDefAliasImpl::countMemberDeclarations</a>.
</div>
</div>

### countMembersIncludingGrouped() {#aa08a21c84b7e1718d8f2701bc3af6291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int ClassDef::countMembersIncludingGrouped (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, bool additional)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00341">341</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a8038034311942e74e24735bd87c3601f">ClassDefAliasImpl::countMembersIncludingGrouped</a>.
</div>
</div>

### deepCopy() {#ad98feeeb839e90eea9c64ba2f2fabfb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; ClassDef &gt; ClassDef::deepCopy (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00120">120</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Reference <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>.
</div>
</div>

### generatedFromFiles() {#a8dc67c6c1096d9c72d3daa092c0f480a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::generatedFromFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00318">318</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ac95ed07819450425cc542c6fe110fc65">ClassDefAliasImpl::generatedFromFiles</a>.
</div>
</div>

### getClasses() {#aeb64dc8f57c5d07f1b1d55bc560a7004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ClassLinkedRefMap ClassDef::getClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns the classes nested into this class</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00133">133</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a83afd139000520327a795c8c39f2cd8a">addClassAndNestedClasses</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a97d3881f19cc6d4afb3d7a7376ec222b">ClassDefImpl::addMembersToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a90bc9ccd867058973acec037b08218a6">findTagLessClasses</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ad6d03ddc7d64482fe61594f39760eec6">ClassDefAliasImpl::getClasses</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>.
</div>
</div>

### getExamples() {#a980a867140493e4cf4fd9ded7ee75e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ExampleList &amp; ClassDef::getExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00322">322</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a46cadea07d5df790e78b20f7f3385c17">ClassDefAliasImpl::getExamples</a>.
</div>
</div>

### getFileDef() {#aed4a0864e51e5a3ac616f6c8e10f56c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual FileDef * ClassDef::getFileDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the namespace this compound is in, or 0 if it has a global scope.</p>


<p>Returns the file in which this compound's definition can be found. Should not return 0 (but it might be a good idea to check anyway).</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00193">193</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8e0a72feb96a836fa1650fe1b9f1e39a">findClassWithinClassContext</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a67d97db3c717b89b9a6211ae48e9273b">findModuleDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a858094677f40ed5783d6fa0e478d1436">ClassDefAliasImpl::getFileDef</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6f19768de5264715ae39c70e66c20997">writeTemplateList</a>.
</div>
</div>

### getInstanceOutputFileBase() {#a8476d860cfdada4916c4dc722f0bea07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::getInstanceOutputFileBase ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00127">127</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aa5cc8426c3d589ef6b9f8f515381c1a8">ClassDefAliasImpl::getInstanceOutputFileBase</a>.
</div>
</div>

### getMemberByName() {#a3bec35936216530bf2385a8dfd2ab0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * ClassDef::getMemberByName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the member with the given name.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00200">200</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aab0947e93a77169efff48326518717ab">SymbolResolver::Private::followPath</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa723e85238b66b5916c25989013e52b8">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ae517db2634ad080c8525e2372e357846">ClassDefAliasImpl::getMemberByName</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>.
</div>
</div>

### getMemberGroups() {#add2c3b56273ce664bbaeb0ce1c8f420c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberGroupList &amp; ClassDef::getMemberGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the member groups defined for this class.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00300">300</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a7bf05103ee29cfb5044803f807b4ffc3">ClassDefAliasImpl::getMemberGroups</a>.
</div>
</div>

### getMemberList() {#a7d2f9d08207ecf5b227c11f8b4ea6d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberList * ClassDef::getMemberList (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the members in the list identified by <em>lt</em>.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00294">294</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a765683cbd1cf5a8e7374b64a9ac37d98">VhdlDocGen::findFunction</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aad904b7993ef051b6141cb1726547c2b">ClassDefAliasImpl::getMemberList</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>.
</div>
</div>

### getMemberListFileName() {#ac620ac7f22f673e84410b1ceca0af3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::getMemberListFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00324">324</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a8757c279d4e5c9045031aee25c803a8e">ClassDefAliasImpl::getMemberListFileName</a>.
</div>
</div>

### getMemberLists() {#a283e841b3eb34d0ba2e0e106a4e3ad59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberLists &amp; ClassDef::getMemberLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the list containing the list of members sorted per type.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00297">297</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aaba9f5d25cf840f83a761fac5366004d">ClassDefAliasImpl::getMemberLists</a>.
</div>
</div>

### getModuleDef() {#a109769b1e6eb23eb36e23530e667703e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ModuleDef * ClassDef::getModuleDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the C++20 module in which this compound's definition can be found.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00197">197</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a1a32242add36cd5333c0bf797891a656">ClassDefAliasImpl::getModuleDef</a>.
</div>
</div>

### getQualifiers() {#a570d8dcfdd144e17226ca785e58b15b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringVector ClassDef::getQualifiers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00331">331</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a2925368285d630431e824f40245df057">ClassDefAliasImpl::getQualifiers</a>.
</div>
</div>

### getTemplateBaseClassNames() {#aaf3dc7118f6d91b7bc741e29f45215b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TemplateNameMap &amp; ClassDef::getTemplateBaseClassNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00302">302</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aba326b765f7af4f942eda8ed49db9063">ClassDefAliasImpl::getTemplateBaseClassNames</a>.
</div>
</div>

### getTemplateInstances() {#a3ceb3e484b62599117b5eb424c10fd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TemplateInstanceList &amp; ClassDef::getTemplateInstances ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns a sorted dictionary with all template instances found for this template class.</p>


<p>Returns 0 if not a template or no instances.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00221">221</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a96c36f33834fe7c00c5cc237e2a84f15">ClassDefAliasImpl::getTemplateInstances</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>.
</div>
</div>

### getTemplateParameterLists() {#a43e4fb6ebed35075ecee567872abbe20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArgumentLists ClassDef::getTemplateParameterLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the template parameter lists that form the template declaration of this class.</p>


<p><a href="/web-doxygen/docs/api/structs/example">Example</a>: <span class="doxyComputerOutput">template&lt;class T&gt; class TC {} = 0;</span> will return a list with one <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> containing one argument with type="class" and name="T".</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00248">248</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a85e4b2162a44896395d809a098420c2d">ClassDefAliasImpl::getTemplateParameterLists</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### hasDetailedDescription() {#a1fd0e2c039c6d81ffa25579184568e87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::hasDetailedDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns TRUE if this class has a non-empty detailed description</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00136">136</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a17cd90b59ffb3350b65ee8ea591c00bf">ClassDefAliasImpl::hasDetailedDescription</a>.
</div>
</div>

### hasExamples() {#a4da7081ddd605c4b0f972d4aeadaf1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::hasExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00323">323</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ae099a548e89bc8fe025a23956302c941">ClassDefAliasImpl::hasExamples</a>.
</div>
</div>

### hasNonReferenceSuperClass() {#a8bfa7122b5f501c389a13c2d55219f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::hasNonReferenceSuperClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00328">328</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a87dbe574a9382a77997d537e765a91dc">ClassDefAliasImpl::hasNonReferenceSuperClass</a>.
</div>
</div>

### includeInfo() {#af0c57a31c5cbef35d12de99e88745f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const IncludeInfo * ClassDef::includeInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00231">231</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a5d42a0caefc7e005ea3c631060e99b67">ClassDefAliasImpl::includeInfo</a>.
</div>
</div>

### inheritanceGraphFileName() {#a4feb0d6c2afb9ab04ba7faec2becf27e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::inheritanceGraphFileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns the file name to use for the inheritance graph</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00142">142</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a53601818c690d945d05a971b506bb5df">DotClassGraph::DotClassGraph</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a92ae76c1dfc81b0c710c81ef51f26b49">ClassDefAliasImpl::inheritanceGraphFileName</a>.
</div>
</div>

### isAbstract() {#a12dd6a6b0ac63233a82327a8b2d2d9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isAbstract ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if there is at least one pure virtual member in this class.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00256">256</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#adaae961f8756744ea5dda669438bb72e">ClassDefAliasImpl::isAbstract</a>.
</div>
</div>

### isAccessibleMember() {#aa4f8aa899e9bf12dacd3442c9647bac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isAccessibleMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns TRUE iff <em>md</em> is a member of this class or of the the public/protected members of a base class</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00216">216</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a645b16eec442e33bc9e1ec74d905ae7e">ClassDefAliasImpl::isAccessibleMember</a>.
</div>
</div>

### isBaseClass() {#a3e118df515565a29662b41396ee66579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int ClassDef::isBaseClass (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * bcd, bool followInstances, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; templSpec=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE iff <em>bcd</em> is a direct or indirect base class of this class.</p>


<p>This function will recursively traverse all branches of the inheritance tree.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00206">206</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a7f39d12e122ea5b3b193bbcebf0d4ffa">ClassDefAliasImpl::isBaseClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad65dc2d081e8048a924cd1402e4399ef">ClassDefImpl::isBaseClass</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a738d45232dc0fca703f9e9042acae9c0">MemberDefImpl::isReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>.
</div>
</div>

### isCSharp() {#a8bfbc9a9cc5af4db69a0b5a796a28d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isCSharp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is implemented in C#.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00265">265</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a79e5f3bb598a5c4e7d7da910b94346a7">ClassDefAliasImpl::isCSharp</a>.
</div>
</div>

### isEmbeddedInOuterScope() {#ac86d2e29cb6233d073aa4c9b5ea726af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isEmbeddedInOuterScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00306">306</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a83afd139000520327a795c8c39f2cd8a">addClassAndNestedClasses</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a7c79bfd6caa7a9f75b579efc5e6c8d21">ClassDefAliasImpl::isEmbeddedInOuterScope</a>.
</div>
</div>

### isExtension() {#a8a066b13127c13f73ae916af7d883ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isExtension ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class represents an Objective-C 2.0 extension (nameless category)</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00277">277</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ad58aee30483201711f9c22c4a7a76f37">ClassDefAliasImpl::isExtension</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>.
</div>
</div>

### isFinal() {#a18c81095d49e7a4e05820d9928deaa45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isFinal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is marked as final.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00268">268</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a3b5f214b1d0ca22e9cca64ceff86fad8">ClassDefAliasImpl::isFinal</a>.
</div>
</div>

### isFortran() {#a25f184cac0ea4de2d27b0c0957ab9b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isFortran ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is implemented in Fortran.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00262">262</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a00c035549072771ff77d41853d1dcb85">ClassDefAliasImpl::isFortran</a>.
</div>
</div>

### isForwardDeclared() {#a8c23670661fa0360c44d3352b16135b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isForwardDeclared ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class represents a forward declaration of a template class.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00280">280</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a57c5f72005a5274806e9c313008fe20c">ClassDefAliasImpl::isForwardDeclared</a>.
</div>
</div>

### isImplicitTemplateInstance() {#ad03b3f6196640021e3c44d7b1eb9e924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isImplicitTemplateInstance ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00335">335</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a83afd139000520327a795c8c39f2cd8a">addClassAndNestedClasses</a>, <a href="/web-doxygen/docs/api/classes/index/#a1153de637b2551bc2ae88578ec6e295f">Index::addClassMemberNameToIndex</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a04f8dba009adb568081909d56c207bc3">addMemberToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a3983c632458a22f0a08586f8cecd5a3f">ClassDefAliasImpl::isImplicitTemplateInstance</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>.
</div>
</div>

### isInterface() {#aebcf69f2e74678dc5e62f1b528c9b902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isInterface ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class represents an interface.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00283">283</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ad8ef9734df70fb412b8448263a6710cc">ClassDefAliasImpl::isInterface</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>.
</div>
</div>

### isJavaEnum() {#a9a3699b6766321cef5a194b6fa1a9d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isJavaEnum ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00314">314</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a8f5e61e688959db751fdd0f4c348bff0">ClassDefAliasImpl::isJavaEnum</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a>.
</div>
</div>

### isLocal() {#a6b24aeece30ae83930ed2a3ca0621fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isLocal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this is a local class definition, see EXTRACT_LOCAL_CLASSES.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00130">130</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aa0182439370e6edec85940f146165a6c">ClassDefAliasImpl::isLocal</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>.
</div>
</div>

### isObjectiveC() {#a4d9613dc45d98c8cd04a6fcf6a4f21ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isObjectiveC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is implemented in Objective-C.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00259">259</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#af999602a0c50fba3fc8e8e9a6099117b">ClassDefAliasImpl::isObjectiveC</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>.
</div>
</div>

### isPublished() {#ab61c051bbda755836c90d7be3d63e4f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isPublished ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is marked as published.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00274">274</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a33f513d25096ffbdd609f8a8b8d90eaa">ClassDefAliasImpl::isPublished</a>.
</div>
</div>

### isSealed() {#a3bcc0025ce9b44d8617da2abaf0eb978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isSealed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is marked as sealed.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00271">271</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a845e9d5013f50f4cc3b993f9c25e19bc">ClassDefAliasImpl::isSealed</a>.
</div>
</div>

### isSimple() {#a7396ab268485c570718f3274105b3f48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isSimple ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00308">308</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ab3b02c051abc4e2dc28d7abb654cf1e9">MemberDefImpl::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a08141c981655c1db838d76cd0044df0c">MemberDefImpl::isDetailedSectionVisible</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a009dcf17da2c27f28a96b4853d86a1b2">ClassDefAliasImpl::isSimple</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>.
</div>
</div>

### isSliceLocal() {#a0e9ae30aa6558cef5fd9bda03c1bb569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isSliceLocal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00327">327</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#af586f33895a2216917c713a592650c93">ClassDefAliasImpl::isSliceLocal</a>.
</div>
</div>

### isSmartPointer() {#a88fd3d3f7762f2a3c7b3634b554ce579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberDef * ClassDef::isSmartPointer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00312">312</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#af8842bc054a73e6f2afde250689769c5">ClassDefAliasImpl::isSmartPointer</a>.
</div>
</div>

### isSubClass() {#a9a4c36f29d33a44a6b7460e89a7cd741}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isSubClass (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * bcd, int level=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE iff <em>bcd</em> is a direct or indirect sub class of this class.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00211">211</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a0f71e5d60cca54183d1065a41c1a0f44">ClassDefAliasImpl::isSubClass</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a00883ff38c8750298ceb59e13823e52b">ClassDefImpl::isSubClass</a>.
</div>
</div>

### isTemplate() {#a30f19d5b8fb17b204b9e41d19b2ca49f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isTemplate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns TRUE if this class is a template.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00229">229</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a082d23658541704d3493a7a881583d55">flushCachedTemplateRelations</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#af13b5351fc7fd510363e990fa879f98f">ClassDefAliasImpl::isTemplate</a> and <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>.
</div>
</div>

### isTemplateArgument() {#a9eabb427f58a6631c73f76c6856694a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isTemplateArgument ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00239">239</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#aef9c4245c6f445e282a59005f1f6ca5a">SymbolResolver::Private::getResolvedType</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a4ad1e6b4087d769162b741416eb71aad">ClassDefAliasImpl::isTemplateArgument</a>.
</div>
</div>

### isUsedOnly() {#afee08a2576eb4d2888560c89ab2e1614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isUsedOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00304">304</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#af649a11e97e72bb215cbf6b63bc6dec8">ClassDefAliasImpl::isUsedOnly</a>.
</div>
</div>

### isVisibleInHierarchy() {#a3067e647412a923d7743258c89eabe75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::isVisibleInHierarchy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>the class is visible in a class diagram, or class hierarchy</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00176">176</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aba6e058bd7da92eb4d1035ab15c51cf6">ClassDefImpl::countInheritedByNodes</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a944f11401da9c071a468c2462842aad7">ClassDefImpl::countInheritsNodes</a>, <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a2dec55de26c5156f759c5e74f541a3c9">ClassDefAliasImpl::isVisibleInHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### memberNameInfoLinkedMap() {#ac8f58a78e8196768f3ddd17e645cf7f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberNameInfoLinkedMap &amp; ClassDef::memberNameInfoLinkedMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns a dictionary of all members.</p>


<p>This includes any inherited members. Members are sorted alphabetically.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00168">168</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a81142c12bb2ef7638500997115bf2f43">PerlModGenerator::addListOfAllMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a97d3881f19cc6d4afb3d7a7376ec222b">ClassDefImpl::addMembersToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a92be09d6ea0ae352da3d441abed04f30">associateAllClassMembers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7c714f2eedf0d52d8428bbcdd06b6975">ClassDefImpl::hideDerivedVariablesInPython</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a352f59ecd49f57e3672483e74a3f28fb">ClassDefAliasImpl::memberNameInfoLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a361dd0c822c454f8b1fe78d762c9d872">writeListOfAllMembers</a>.
</div>
</div>

### moveTo() {#a9efadd9727924f524013b3b46238c980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::moveTo (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00121">121</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a1db2f74ea53f449c9f3ad06cead61f7a">findUsingDeclImports</a>.
</div>
</div>

### protection() {#a759c68ae0af03a49aff1a86d383af68d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Protection ClassDef::protection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Return the protection level (Public,Protected,Private) in which this compound was found.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00173">173</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a83afd139000520327a795c8c39f2cd8a">addClassAndNestedClasses</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a0cf2ae6bf35f920987bb1804a5fed8b7">generateMemLink</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a4ddceeda3319a2ba878acc54cca4e70e">ClassDefImpl::insertSubClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a7961a65064ffd08298daa974dbf22f62">ClassDefAliasImpl::protection</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### qualifiedNameWithTemplateParameters() {#ad488bfd3800b79d9984bb2e11aadde2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::qualifiedNameWithTemplateParameters (const <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> * actualParams=nullptr, uint32_t * actualParamIndex=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00250">250</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>.
</div>
</div>

### requiresClause() {#af404e73b14943149542cf4202bc0ab6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::requiresClause ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00330">330</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a01f7627552da826d1fc811a1cb7745be">ClassDefAliasImpl::requiresClause</a>.
</div>
</div>

### subClasses() {#afdeec11149bf831c4c6dd297f7c4e34d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const BaseClassList &amp; ClassDef::subClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the list of sub classes that directly derive from this class.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00160">160</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#af0c88e52d4d7424c0840a23a522dc330">classHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a3dbc9c08f8cf61bdd6a98fce028ae320">generateDEFForClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>, <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a8da844453583bd41555356e618e421d3">ClassDefAliasImpl::subClasses</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>.
</div>
</div>

### subGrouping() {#a1e2ce9f8d0cb3b6f1ba0317ca8dbb714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::subGrouping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00325">325</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a751ea04eced6b1babc036079c65442b3">ClassDefAliasImpl::subGrouping</a>.
</div>
</div>

### tagLessReference() {#a7b4e443b14553fba6f95e3462b531149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassDef * ClassDef::tagLessReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00310">310</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ad2fdbc08bbbbc42580f6cc5dcedd6bef">ClassDefAliasImpl::tagLessReference</a>.
</div>
</div>

### templateArguments() {#a201b8f24043f9b7c7cc59d55282f6d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentList &amp; ClassDef::templateArguments ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the template arguments of this class.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00183">183</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a97d3881f19cc6d4afb3d7a7376ec222b">ClassDefImpl::addMembersToTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad59851d3155ba565dfe74bbb919435cc">ClassDefMutable::addMembersToTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#a8839c9270bdf7c9779b0bcf221608f0f">ClassDefMutable::addMemberToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae13abaf328534f92b57bb6af8208f31d">findBaseClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aa2b4c58062de6e3075936abc6c29dd7e">getTemplateArgumentsFromName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a28c7c96ebabd6ec7cf5c81f01288d1e3">resolveTemplateInstanceInType</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a77a2605db1e0eb2e8de6af646aa7e3fa">ClassDefAliasImpl::templateArguments</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a751d93630bc7cb9fa396ce5322fc9aab">writeTemplateList</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6f19768de5264715ae39c70e66c20997">writeTemplateList</a>.
</div>
</div>

### templateMaster() {#ae587759f556ea0d641b92a30e923a7c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassDef * ClassDef::templateMaster ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns the template master of which this class is an instance.</p>


<p>Returns 0 if not applicable.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00226">226</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad65dc2d081e8048a924cd1402e4399ef">ClassDefImpl::isBaseClass</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a015321aa6ad5077eaefabeced13bfd4e">makeTemplateInstanceRelation</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aec00fde6dc30bb24809fee577bb09815">ClassDefAliasImpl::templateMaster</a>.
</div>
</div>

### templateTypeConstraints() {#acd8e27ea299fea8b7d180608bfb1326b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ConstraintClassList &amp; ClassDef::templateTypeConstraints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00237">237</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ad805eac8641d4d75315d8385315cd117">ClassDefAliasImpl::templateTypeConstraints</a>.
</div>
</div>

### title() {#afb51998523ff484408b2a96fd4f3fced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ClassDef::title ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00316">316</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a358d46451cf46a373a32d0c5658b0936">ClassDefAliasImpl::title</a> and <a href="#ac598c1ecb31cdb19524cc60cfe312667">writeMemberDeclarations</a>.
</div>
</div>

### typeConstraints() {#aa4c4caac2adb12c3207df5936ba2c90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ArgumentList &amp; ClassDef::typeConstraints ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00321">321</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a5850425ae3d9bfdb3892661066d8bd9f">ClassDefAliasImpl::typeConstraints</a>.
</div>
</div>

### updateBaseClasses() {#a053f323d6b837a81cd86a82ce3c4d4a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::updateBaseClasses (const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp; bcd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Update the list of base classes to the one passed.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00156">156</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>.
</div>
</div>

### updateSubClasses() {#a6916d56bb83637aa0be3054cb0f46ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::updateSubClasses (const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp; bcd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Update the list of sub classes to the one passed.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00163">163</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>
</div>
</div>

### usedByImplementationClasses() {#ade6f41d07606c61673264a5d50e95c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const UsesClassList &amp; ClassDef::usedByImplementationClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00235">235</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a16cff2ab73c4abbd38d29b5a12e8021c">ClassDefAliasImpl::usedByImplementationClasses</a>.
</div>
</div>

### usedFiles() {#ab6ba54124ee74df07036e2473579264d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const FileList &amp; ClassDef::usedFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00319">319</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a39a5532e4d59a5a5adcad9e5d7ec4cab">ClassDefAliasImpl::usedFiles</a>.
</div>
</div>

### usedImplementationClasses() {#a4a15dff9d9567c126433228fff77837b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const UsesClassList &amp; ClassDef::usedImplementationClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00233">233</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a257058fa8508a33ca9dbbfc8715838e4">ClassDefAliasImpl::usedImplementationClasses</a>.
</div>
</div>

### visibleInParentsDeclList() {#a1a79f778ae2201c52ee19c048763d4fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ClassDef::visibleInParentsDeclList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>show this class in the declaration section of its parent?</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00179">179</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ae4d8df5b0e45883b18308263d215200f">ClassDefAliasImpl::visibleInParentsDeclList</a>.
</div>
</div>

### writeDeclaration() {#acfcf16726b8d952b1c76d43adfbef197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeDeclaration (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, bool inGroup, int indentLevel, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00356">356</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a6effa63252fa897e5521fd8034bb19a9">ClassDefAliasImpl::writeDeclaration</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### writeDeclarationLink() {#acd75a76f95d8eacddd4afbb7dc8693a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeDeclarationLink (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, bool &amp; found, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header, bool localNames)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00350">350</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#abcfb957d1b34d6e323a5ae8f8f7c0da3">ClassDefAliasImpl::writeDeclarationLink</a>.
</div>
</div>

### writeDocumentation() {#a283ca4e39a593316c8c6c83085088900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00352">352</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a61b713e61e238a458b7a64ef221973a4">generateNamespaceClassDocs</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a236a08389de317adcab69a7ab6e9a37a">ClassDefAliasImpl::writeDocumentation</a>.
</div>
</div>

### writeDocumentationForInnerClasses() {#afd404f2052b5c688bf0815741a290842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeDocumentationForInnerClasses (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00353">353</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a61b713e61e238a458b7a64ef221973a4">generateNamespaceClassDocs</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#aa63ae9765c16beef2b4a889b0f5d321b">ClassDefAliasImpl::writeDocumentationForInnerClasses</a>.
</div>
</div>

### writeInlineDocumentation() {#af59b44de9052b4e62482853fdb7a514a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeInlineDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00361">361</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a8c919b56012472db7a02ccb01316ccab">ClassDefAliasImpl::writeInlineDocumentation</a>.
</div>
</div>

### writeMemberDeclarations() {#ac598c1ecb31cdb19524cc60cfe312667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeMemberDeclarations (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp; visitedClasses, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; subTitle=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool showInline=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom=nullptr, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt2=<a href="/web-doxygen/docs/api/classes/memberlisttype/#a6bba5f5f3ba3a36e97d8d7106001480d">MemberListType::Invalid</a>(), bool invert=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, bool showAlways=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00363">363</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#a6bba5f5f3ba3a36e97d8d7106001480d">MemberListType::Invalid</a> and <a href="#afb51998523ff484408b2a96fd4f3fced">title</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fb5141ea8877090d564026636d81a14">ClassDefImpl::writeInheritedMemberDeclarations</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ab287ccfb0386977fce96aa616e9be50e">ClassDefAliasImpl::writeMemberDeclarations</a>.
</div>
</div>

### writeMemberList() {#a30391896721a6454f35d69ef5457080b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeMemberList (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00355">355</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a61b713e61e238a458b7a64ef221973a4">generateNamespaceClassDocs</a> and <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#afcedf72f74d9a02cd4e29852c1e07ebe">ClassDefAliasImpl::writeMemberList</a>.
</div>
</div>

### writeMemberPages() {#a21e64cf1626ca35924f114aaadac8009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeMemberPages (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00354">354</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a672214abd88e36416d36b390728fc0f4">ClassDefAliasImpl::writeMemberPages</a>.
</div>
</div>

### writePageNavigation() {#a8188a9157bac12e715b2a94372a5b59d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writePageNavigation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00360">360</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a190101033114f81cf21225e28525d833">ClassDefAliasImpl::writePageNavigation</a>.
</div>
</div>

### writeQuickMemberLinks() {#a6f85844c1b5d67ca6110b3c48053bc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeQuickMemberLinks (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00358">358</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a70e4e875c4a4b14689d58f1114ead623">ClassDefAliasImpl::writeQuickMemberLinks</a>.
</div>
</div>

### writeSummaryLinks() {#a1e4c88be7cbea1cd3c46833f69843612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeSummaryLinks (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00359">359</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a2bcc1c98274b691e8709551d753b0a18">ClassDefAliasImpl::writeSummaryLinks</a>.
</div>
</div>

### writeTagFile() {#af5fb9d775ecdb41ff87abcc2eb44f105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ClassDef::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/classdef-h/#l00362">362</a> of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a076783e77d8c5731d465d196336416fb">ClassDefAliasImpl::writeTagFile</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
