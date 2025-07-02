---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/classdefaliasimpl
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ClassDefAliasImpl` Class Reference



## Declaration

<div class="doxyDeclaration">
class ClassDefAliasImpl { ... }
</div>

## Base class

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a11e5ccd30b61bd7f5b7df76ce29b39">ClassDefAliasImpl</a> (const Definition *newScope, const ClassDef *cd)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a966ac38c57f6055e29fff995d5728900">~ClassDefAliasImpl</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8e">DefType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73a350dc8861ac4793054fa67d339b4">definitionType</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4744c5dd6e3339cf4de2b8d2b50717">deepCopy</a> (const QCString &amp;name) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48c89c5ecd68496abd8b1ac56530110c">moveTo</a> (Definition *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2aee50bed9fd30164137abd6827ae9">codeSymbolType</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4a6db56da1eb406e31ab4e93e970e49">getOutputFileBase</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cc8426c3d589ef6b9f8f515381c1a8">getInstanceOutputFileBase</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670ee0af2bc87b10113a41a76c4a84c8">getSourceFileBase</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db9cf4aacb7a843ee0be85684ca3ce0">getReference</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a640308f08565df3c59d2e6e6fd346f">isReference</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0182439370e6edec85940f146165a6c">isLocal</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this is a local class definition, see EXTRACT\_LOCAL\_CLASSES. <a href="#aa0182439370e6edec85940f146165a6c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d03ddc7d64482fe61594f39760eec6">getClasses</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns the classes nested into this class <a href="#ad6d03ddc7d64482fe61594f39760eec6">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a855edd664ad46a701a511306ceb4dfad">hasDocumentation</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17cd90b59ffb3350b65ee8ea591c00bf">hasDetailedDescription</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns TRUE if this class has a non-empty detailed description <a href="#a17cd90b59ffb3350b65ee8ea591c00bf">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ea1a5681a32c3199ce2e4cd5bfc443">collaborationGraphFileName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns the file name to use for the collaboration graph <a href="#ab1ea1a5681a32c3199ce2e4cd5bfc443">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ae76c1dfc81b0c710c81ef51f26b49">inheritanceGraphFileName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns the file name to use for the inheritance graph <a href="#a92ae76c1dfc81b0c710c81ef51f26b49">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0a300a44e814de013db11434e9568c">displayName</a> (bool includeScope=TRUE) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">CompoundType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4defbdd48f1c76760c3cdbaefb26982">compoundType</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the type of compound this is, i.e. <a href="#ab4defbdd48f1c76760c3cdbaefb26982">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998350d1371352749b27cbe3e955f9c5">compoundTypeString</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the type of compound as a string. <a href="#a998350d1371352749b27cbe3e955f9c5">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3618423ef6577a41a35c61be91a330">baseClasses</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the list of base classes from which this class directly inherits. <a href="#acc3618423ef6577a41a35c61be91a330">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8da844453583bd41555356e618e421d3">subClasses</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the list of sub classes that directly derive from this class. <a href="#a8da844453583bd41555356e618e421d3">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membernameinfolinkedmap">MemberNameInfoLinkedMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352f59ecd49f57e3672483e74a3f28fb">memberNameInfoLinkedMap</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a dictionary of all members. <a href="#a352f59ecd49f57e3672483e74a3f28fb">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7961a65064ffd08298daa974dbf22f62">protection</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Return the protection level (Public,Protected,Private) in which this compound was found. <a href="#a7961a65064ffd08298daa974dbf22f62">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf9b733ce1e3dd0b66576d7a936cce6">isLinkableInProject</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb73f5827e37675b97aea0a28f152f42">isLinkable</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dec55de26c5156f759c5e74f541a3c9">isVisibleInHierarchy</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
the class is visible in a class diagram, or class hierarchy <a href="#a2dec55de26c5156f759c5e74f541a3c9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4d8df5b0e45883b18308263d215200f">visibleInParentsDeclList</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
show this class in the declaration section of its parent? <a href="#ae4d8df5b0e45883b18308263d215200f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a2605db1e0eb2e8de6af646aa7e3fa">templateArguments</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the template arguments of this class. <a href="#a77a2605db1e0eb2e8de6af646aa7e3fa">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858094677f40ed5783d6fa0e478d1436">getFileDef</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the namespace this compound is in, or 0 if it has a global scope. <a href="#a858094677f40ed5783d6fa0e478d1436">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a32242add36cd5333c0bf797891a656">getModuleDef</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the C++20 module in which this compound's definition can be found. <a href="#a1a32242add36cd5333c0bf797891a656">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae517db2634ad080c8525e2372e357846">getMemberByName</a> (const QCString &amp;s) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the member with the given name. <a href="#ae517db2634ad080c8525e2372e357846">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f39d12e122ea5b3b193bbcebf0d4ffa">isBaseClass</a> (const ClassDef *bcd, bool followInstances, const QCString &amp;templSpec) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE iff <em>bcd</em> is a direct or indirect base class of this class. <a href="#a7f39d12e122ea5b3b193bbcebf0d4ffa">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f71e5d60cca54183d1065a41c1a0f44">isSubClass</a> (ClassDef *bcd, int level=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE iff <em>bcd</em> is a direct or indirect sub class of this class. <a href="#a0f71e5d60cca54183d1065a41c1a0f44">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645b16eec442e33bc9e1ec74d905ae7e">isAccessibleMember</a> (const MemberDef *md) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns TRUE iff <em>md</em> is a member of this class or of the the public/protected members of a base class <a href="#a645b16eec442e33bc9e1ec74d905ae7e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#ac6ced1c572e645da3d141b20bad3aeb4">TemplateInstanceList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c36f33834fe7c00c5cc237e2a84f15">getTemplateInstances</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a sorted dictionary with all template instances found for this template class. <a href="#a96c36f33834fe7c00c5cc237e2a84f15">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec00fde6dc30bb24809fee577bb09815">templateMaster</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the template master of which this class is an instance. <a href="#aec00fde6dc30bb24809fee577bb09815">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13b5351fc7fd510363e990fa879f98f">isTemplate</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is a template. <a href="#af13b5351fc7fd510363e990fa879f98f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d42a0caefc7e005ea3c631060e99b67">includeInfo</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257058fa8508a33ca9dbbfc8715838e4">usedImplementationClasses</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16cff2ab73c4abbd38d29b5a12e8021c">usedByImplementationClasses</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad805eac8641d4d75315d8385315cd117">templateTypeConstraints</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad1e6b4087d769162b741416eb71aad">isTemplateArgument</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd39ec0ae0a30540f9bce713d88b845">findInnerCompound</a> (const QCString &amp;name) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e4b2162a44896395d809a098420c2d">getTemplateParameterLists</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the template parameter lists that form the template declaration of this class. <a href="#a85e4b2162a44896395d809a098420c2d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7190f6e1928c0e8d70d6cc013cc401">qualifiedNameWithTemplateParameters</a> (const ArgumentLists *actualParams=nullptr, uint32_t *actualParamIndex=nullptr) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaae961f8756744ea5dda669438bb72e">isAbstract</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if there is at least one pure virtual member in this class. <a href="#adaae961f8756744ea5dda669438bb72e">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af999602a0c50fba3fc8e8e9a6099117b">isObjectiveC</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is implemented in Objective-C. <a href="#af999602a0c50fba3fc8e8e9a6099117b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c035549072771ff77d41853d1dcb85">isFortran</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is implemented in Fortran. <a href="#a00c035549072771ff77d41853d1dcb85">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e5f3bb598a5c4e7d7da910b94346a7">isCSharp</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is implemented in C#. <a href="#a79e5f3bb598a5c4e7d7da910b94346a7">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5f214b1d0ca22e9cca64ceff86fad8">isFinal</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is marked as final. <a href="#a3b5f214b1d0ca22e9cca64ceff86fad8">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845e9d5013f50f4cc3b993f9c25e19bc">isSealed</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is marked as sealed. <a href="#a845e9d5013f50f4cc3b993f9c25e19bc">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f513d25096ffbdd609f8a8b8d90eaa">isPublished</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class is marked as published. <a href="#a33f513d25096ffbdd609f8a8b8d90eaa">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad58aee30483201711f9c22c4a7a76f37">isExtension</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class represents an Objective-C 2.0 extension (nameless category) <a href="#ad58aee30483201711f9c22c4a7a76f37">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c5f72005a5274806e9c313008fe20c">isForwardDeclared</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class represents a forward declaration of a template class. <a href="#a57c5f72005a5274806e9c313008fe20c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ef9734df70fb412b8448263a6710cc">isInterface</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if this class represents an interface. <a href="#ad8ef9734df70fb412b8448263a6710cc">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aada67d5160e3ae9c3f0dedadf267d894">categoryOf</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the class of which this is a category (Objective-C only) <a href="#aada67d5160e3ae9c3f0dedadf267d894">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eb13d241236d480b0d37a8c9a918a09">className</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the name of the class including outer classes, but not including namespaces. <a href="#a9eb13d241236d480b0d37a8c9a918a09">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad904b7993ef051b6141cb1726547c2b">getMemberList</a> (MemberListType lt) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the members in the list identified by <em>lt</em>. <a href="#aad904b7993ef051b6141cb1726547c2b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/memberlists">MemberLists</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba9f5d25cf840f83a761fac5366004d">getMemberLists</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the list containing the list of members sorted per type. <a href="#aaba9f5d25cf840f83a761fac5366004d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf05103ee29cfb5044803f807b4ffc3">getMemberGroups</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the member groups defined for this class. <a href="#a7bf05103ee29cfb5044803f807b4ffc3">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a52c06547a303385be1dc01559096a3d9">TemplateNameMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba326b765f7af4f942eda8ed49db9063">getTemplateBaseClassNames</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af649a11e97e72bb215cbf6b63bc6dec8">isUsedOnly</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3548997640a2675bd68c2310de2fcf43">anchor</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c79bfd6caa7a9f75b579efc5e6c8d21">isEmbeddedInOuterScope</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009dcf17da2c27f28a96b4853d86a1b2">isSimple</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fdbc08bbbbc42580f6cc5dcedd6bef">tagLessReference</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8842bc054a73e6f2afde250689769c5">isSmartPointer</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f5e61e688959db751fdd0f4c348bff0">isJavaEnum</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358d46451cf46a373a32d0c5658b0936">title</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac95ed07819450425cc542c6fe110fc65">generatedFromFiles</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a5532e4d59a5a5adcad9e5d7ec4cab">usedFiles</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5850425ae3d9bfdb3892661066d8bd9f">typeConstraints</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46cadea07d5df790e78b20f7f3385c17">getExamples</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae099a548e89bc8fe025a23956302c941">hasExamples</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8757c279d4e5c9045031aee25c803a8e">getMemberListFileName</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751ea04eced6b1babc036079c65442b3">subGrouping</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af586f33895a2216917c713a592650c93">isSliceLocal</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87dbe574a9382a77997d537e765a91dc">hasNonReferenceSuperClass</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f7627552da826d1fc811a1cb7745be">requiresClause</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2925368285d630431e824f40245df057">getQualifiers</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c2a1be234252613efc34fee89e3bac">containsOverload</a> (const MemberDef *md) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8038034311942e74e24735bd87c3601f">countMembersIncludingGrouped</a> (MemberListType lt, const ClassDef *inheritedFrom, bool additional) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1f62fe6c0c1994a7e054e57b393719">countMemberDeclarations</a> (MemberListType lt, const ClassDef *inheritedFrom, MemberListType lt2, bool invert, bool showAlways, ClassDefSet &amp;visitedClasses) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcfb957d1b34d6e323a5ae8f8f7c0da3">writeDeclarationLink</a> (OutputList &amp;ol, bool &amp;found, const QCString &amp;header, bool localNames) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3983c632458a22f0a08586f8cecd5a3f">isImplicitTemplateInstance</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236a08389de317adcab69a7ab6e9a37a">writeDocumentation</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63ae9765c16beef2b4a889b0f5d321b">writeDocumentationForInnerClasses</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a672214abd88e36416d36b390728fc0f4">writeMemberPages</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcedf72f74d9a02cd4e29852c1e07ebe">writeMemberList</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6effa63252fa897e5521fd8034bb19a9">writeDeclaration</a> (OutputList &amp;ol, const MemberDef *md, bool inGroup, int indentLevel, const ClassDef *inheritedFrom, const QCString &amp;inheritId) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70e4e875c4a4b14689d58f1114ead623">writeQuickMemberLinks</a> (OutputList &amp;ol, const MemberDef *md) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bcc1c98274b691e8709551d753b0a18">writeSummaryLinks</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190101033114f81cf21225e28525d833">writePageNavigation</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c919b56012472db7a02ccb01316ccab">writeInlineDocumentation</a> (OutputList &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076783e77d8c5731d465d196336416fb">writeTagFile</a> (TextStream &amp;ol) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab287ccfb0386977fce96aa616e9be50e">writeMemberDeclarations</a> (OutputList &amp;ol, ClassDefSet &amp;visitedClasses, MemberListType lt, const QCString &amp;title, const QCString &amp;subTitle=QCString(), bool showInline=FALSE, const ClassDef *inheritedFrom=nullptr, MemberListType lt2=MemberListType::Invalid(), bool invert=FALSE, bool showAlways=FALSE) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83b0c4ffd68fcb029528f950303a1ca0">addGroupedInheritedMembers</a> (OutputList &amp;ol, MemberListType lt, const ClassDef *inheritedFrom, const QCString &amp;inheritId) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742f87acdae8e420b133af8dbfc92ee7">updateBaseClasses</a> (const BaseClassList &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Update the list of base classes to the one passed. <a href="#a742f87acdae8e420b133af8dbfc92ee7">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502bc75feea6d219fea06fd859fdae8b">updateSubClasses</a> (const BaseClassList &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Update the list of sub classes to the one passed. <a href="#a502bc75feea6d219fea06fd859fdae8b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


Definition at line 569 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxySectionDef">

## Public Constructors

### ClassDefAliasImpl() {#a6a11e5ccd30b61bd7f5b7df76ce29b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDefAliasImpl::ClassDefAliasImpl (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * newScope, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



Definition at line 572 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a11e5ccd30b61bd7f5b7df76ce29b39">572</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6a11e5ccd30b61bd7f5b7df76ce29b39">ClassDefAliasImpl</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#afd1a5da7bbbbc6825f6697fab75eb8e8">DefinitionAliasMixin</a>(newScope,cd) { <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#addb92cda4aaedc984532ef5e0f71d600">init</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#afd1a5da7bbbbc6825f6697fab75eb8e8">DefinitionAliasMixin&lt; ClassDef &gt;::DefinitionAliasMixin</a> and <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#addb92cda4aaedc984532ef5e0f71d600">DefinitionAliasMixin&lt; ClassDef &gt;::init</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ClassDefAliasImpl() {#a966ac38c57f6055e29fff995d5728900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDefAliasImpl::~ClassDefAliasImpl ()</td>
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



Definition at line 574 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a966ac38c57f6055e29fff995d5728900">574</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#a966ac38c57f6055e29fff995d5728900">~ClassDefAliasImpl</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a42da11d9a116f204cf848b3bceb1608f">deinit</a>(); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a42da11d9a116f204cf848b3bceb1608f">DefinitionAliasMixin&lt; ClassDef &gt;::deinit</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addGroupedInheritedMembers() {#a83b0c4ffd68fcb029528f950303a1ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::addGroupedInheritedMembers (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 780 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83b0c4ffd68fcb029528f950303a1ca0">780</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a83b0c4ffd68fcb029528f950303a1ca0">addGroupedInheritedMembers</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac8ed300bfb36eefd34b5ba9f165ff880">addGroupedInheritedMembers</a>(ol,lt,inheritedFrom,inheritId); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#ac8ed300bfb36eefd34b5ba9f165ff880">ClassDef::addGroupedInheritedMembers</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### anchor() {#a3548997640a2675bd68c2310de2fcf43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns the anchor within a page where this item can be found

Definition at line 702 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3548997640a2675bd68c2310de2fcf43">702</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3548997640a2675bd68c2310de2fcf43">anchor</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### baseClasses() {#acc3618423ef6577a41a35c61be91a330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BaseClassList &amp; ClassDefAliasImpl::baseClasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the list of base classes from which this class directly inherits.

Definition at line 615 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc3618423ef6577a41a35c61be91a330">615</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;<a href="#acc3618423ef6577a41a35c61be91a330">baseClasses</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### categoryOf() {#aada67d5160e3ae9c3f0dedadf267d894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * ClassDefAliasImpl::categoryOf ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the class of which this is a category (Objective-C only)

Definition at line 688 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aada67d5160e3ae9c3f0dedadf267d894">688</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#aada67d5160e3ae9c3f0dedadf267d894">categoryOf</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">categoryOf</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a81969b4626cb26cd6061f6c54d051827">ClassDef::categoryOf</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### className() {#a9eb13d241236d480b0d37a8c9a918a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::className ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the name of the class including outer classes, but not including namespaces.

Definition at line 690 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9eb13d241236d480b0d37a8c9a918a09">690</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9eb13d241236d480b0d37a8c9a918a09">className</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">className</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">ClassDef::className</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### codeSymbolType() {#a3a2aee50bed9fd30164137abd6827ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeSymbolType ClassDefAliasImpl::codeSymbolType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Used for syntax highlighting symbol class

Definition at line 585 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a2aee50bed9fd30164137abd6827ae9">585</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> <a href="#a3a2aee50bed9fd30164137abd6827ae9">codeSymbolType</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac94212137110d5ca75eabad07e8ebed6">codeSymbolType</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#ac94212137110d5ca75eabad07e8ebed6">Definition::codeSymbolType</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### collaborationGraphFileName() {#ab1ea1a5681a32c3199ce2e4cd5bfc443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::collaborationGraphFileName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns the file name to use for the collaboration graph

Definition at line 605 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1ea1a5681a32c3199ce2e4cd5bfc443">605</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab1ea1a5681a32c3199ce2e4cd5bfc443">collaborationGraphFileName</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aabe7312465f1dfe18360ed5effbf7c32">collaborationGraphFileName</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#aabe7312465f1dfe18360ed5effbf7c32">ClassDef::collaborationGraphFileName</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### compoundType() {#ab4defbdd48f1c76760c3cdbaefb26982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompoundType ClassDefAliasImpl::compoundType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the type of compound this is, i.e.


class/struct/union/..

Definition at line 611 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4defbdd48f1c76760c3cdbaefb26982">611</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">CompoundType</a> <a href="#ab4defbdd48f1c76760c3cdbaefb26982">compoundType</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">compoundType</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#ae8ba915e00984129bcbbaa4efff48b00">ClassDef::compoundType</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### compoundTypeString() {#a998350d1371352749b27cbe3e955f9c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::compoundTypeString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the type of compound as a string.

Definition at line 613 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a998350d1371352749b27cbe3e955f9c5">613</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a998350d1371352749b27cbe3e955f9c5">compoundTypeString</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">compoundTypeString</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">ClassDef::compoundTypeString</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### containsOverload() {#a74c2a1be234252613efc34fee89e3bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::containsOverload (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 738 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74c2a1be234252613efc34fee89e3bac">738</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a74c2a1be234252613efc34fee89e3bac">containsOverload</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae91329b7bf621cc29f18774301b923ad">containsOverload</a>(md); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#ae91329b7bf621cc29f18774301b923ad">ClassDef::containsOverload</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### countMemberDeclarations() {#a0a1f62fe6c0c1994a7e054e57b393719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ClassDefAliasImpl::countMemberDeclarations (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt2, bool invert, bool showAlways, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp; visitedClasses)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 743 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a1f62fe6c0c1994a7e054e57b393719">743</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a0a1f62fe6c0c1994a7e054e57b393719">countMemberDeclarations</a>(<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt2,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> invert,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showAlways,<a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp;visitedClasses)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a0e4ba15784fceaf76a6a630a18448095">countMemberDeclarations</a>(lt,inheritedFrom,lt2,invert,showAlways,visitedClasses); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a0e4ba15784fceaf76a6a630a18448095">ClassDef::countMemberDeclarations</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### countMembersIncludingGrouped() {#a8038034311942e74e24735bd87c3601f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ClassDefAliasImpl::countMembersIncludingGrouped (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, bool additional)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 741 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8038034311942e74e24735bd87c3601f">741</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8038034311942e74e24735bd87c3601f">countMembersIncludingGrouped</a>(<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> additional)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aa08a21c84b7e1718d8f2701bc3af6291">countMembersIncludingGrouped</a>(lt,inheritedFrom,additional); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#aa08a21c84b7e1718d8f2701bc3af6291">ClassDef::countMembersIncludingGrouped</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### deepCopy() {#ada4744c5dd6e3339cf4de2b8d2b50717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ClassDef &gt; ClassDefAliasImpl::deepCopy (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 580 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada4744c5dd6e3339cf4de2b8d2b50717">580</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;ClassDef&gt; <a href="#ada4744c5dd6e3339cf4de2b8d2b50717">deepCopy</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a00c58ec375d3017160c860d290133c5e">name</a>)</span><span class="doxyHighlightKeyword"> const override  </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9e5773d03b68726ad9d01bb1c7dc5f0e">createClassDefAlias</a>(<a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a9fa006e6df908d4b1a998f48e06ffd14">getScope</a>(),<a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a9e5773d03b68726ad9d01bb1c7dc5f0e">createClassDefAlias</a>, <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>, <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a9fa006e6df908d4b1a998f48e06ffd14">DefinitionAliasMixin&lt; ClassDef &gt;::getScope</a> and <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a00c58ec375d3017160c860d290133c5e">DefinitionAliasMixin&lt; ClassDef &gt;::name</a>.
</div>
</div>

### definitionType() {#ac73a350dc8861ac4793054fa67d339b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefType ClassDefAliasImpl::definitionType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Use this for dynamic inspection of the type of the derived class

Definition at line 577 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac73a350dc8861ac4793054fa67d339b4">577</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8e">DefType</a> <a href="#ac73a350dc8861ac4793054fa67d339b4">definitionType</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">TypeClass</a>; }</span></span></div>

</div>


References <a href="#ac73a350dc8861ac4793054fa67d339b4">definitionType</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>.

Referenced by <a href="#ac73a350dc8861ac4793054fa67d339b4">definitionType</a>.
</div>
</div>

### displayName() {#a9e0a300a44e814de013db11434e9568c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::displayName (bool includeScope=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns the name of the definition as it appears in the output

Definition at line 609 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e0a300a44e814de013db11434e9568c">609</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9e0a300a44e814de013db11434e9568c">displayName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> includeScope=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,includeScope); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### findInnerCompound() {#abfd39ec0ae0a30540f9bce713d88b845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition * ClassDefAliasImpl::findInnerCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 661 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abfd39ec0ae0a30540f9bce713d88b845">661</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#abfd39ec0ae0a30540f9bce713d88b845">findInnerCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a00c58ec375d3017160c860d290133c5e">name</a>)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a99240810ee50ab17c2cb21b56651cf09">findInnerCompound</a>(<a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a00c58ec375d3017160c860d290133c5e">name</a>); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a99240810ee50ab17c2cb21b56651cf09">Definition::findInnerCompound</a>, <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a00c58ec375d3017160c860d290133c5e">DefinitionAliasMixin&lt; ClassDef &gt;::name</a>.
</div>
</div>

### generatedFromFiles() {#ac95ed07819450425cc542c6fe110fc65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::generatedFromFiles ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 716 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac95ed07819450425cc542c6fe110fc65">716</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac95ed07819450425cc542c6fe110fc65">generatedFromFiles</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8dc67c6c1096d9c72d3daa092c0f480a">generatedFromFiles</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a8dc67c6c1096d9c72d3daa092c0f480a">ClassDef::generatedFromFiles</a> and <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>.
</div>
</div>

### getCdAlias() {#ab1366e62ee0c1a0e917952eb62b3fcab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * ClassDefAliasImpl::getCdAlias ()</td>
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



Definition at line 579 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1366e62ee0c1a0e917952eb62b3fcab">579</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(<a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a69970921105b4e7d6aebca0b297a9393">getAlias</a>()); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#a69970921105b4e7d6aebca0b297a9393">DefinitionAliasMixin&lt; ClassDef &gt;::getAlias</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>.

Referenced by <a href="#a83b0c4ffd68fcb029528f950303a1ca0">addGroupedInheritedMembers</a>, <a href="#a3548997640a2675bd68c2310de2fcf43">anchor</a>, <a href="#acc3618423ef6577a41a35c61be91a330">baseClasses</a>, <a href="#aada67d5160e3ae9c3f0dedadf267d894">categoryOf</a>, <a href="#a9eb13d241236d480b0d37a8c9a918a09">className</a>, <a href="#a3a2aee50bed9fd30164137abd6827ae9">codeSymbolType</a>, <a href="#ab1ea1a5681a32c3199ce2e4cd5bfc443">collaborationGraphFileName</a>, <a href="#ab4defbdd48f1c76760c3cdbaefb26982">compoundType</a>, <a href="#a998350d1371352749b27cbe3e955f9c5">compoundTypeString</a>, <a href="#a74c2a1be234252613efc34fee89e3bac">containsOverload</a>, <a href="#a0a1f62fe6c0c1994a7e054e57b393719">countMemberDeclarations</a>, <a href="#a8038034311942e74e24735bd87c3601f">countMembersIncludingGrouped</a>, <a href="#ada4744c5dd6e3339cf4de2b8d2b50717">deepCopy</a>, <a href="#abfd39ec0ae0a30540f9bce713d88b845">findInnerCompound</a>, <a href="#ac95ed07819450425cc542c6fe110fc65">generatedFromFiles</a>, <a href="#ad6d03ddc7d64482fe61594f39760eec6">getClasses</a>, <a href="#a46cadea07d5df790e78b20f7f3385c17">getExamples</a>, <a href="#a858094677f40ed5783d6fa0e478d1436">getFileDef</a>, <a href="#aa5cc8426c3d589ef6b9f8f515381c1a8">getInstanceOutputFileBase</a>, <a href="#ae517db2634ad080c8525e2372e357846">getMemberByName</a>, <a href="#a7bf05103ee29cfb5044803f807b4ffc3">getMemberGroups</a>, <a href="#aad904b7993ef051b6141cb1726547c2b">getMemberList</a>, <a href="#a8757c279d4e5c9045031aee25c803a8e">getMemberListFileName</a>, <a href="#aaba9f5d25cf840f83a761fac5366004d">getMemberLists</a>, <a href="#a1a32242add36cd5333c0bf797891a656">getModuleDef</a>, <a href="#ab4a6db56da1eb406e31ab4e93e970e49">getOutputFileBase</a>, <a href="#a2925368285d630431e824f40245df057">getQualifiers</a>, <a href="#a7db9cf4aacb7a843ee0be85684ca3ce0">getReference</a>, <a href="#a670ee0af2bc87b10113a41a76c4a84c8">getSourceFileBase</a>, <a href="#aba326b765f7af4f942eda8ed49db9063">getTemplateBaseClassNames</a>, <a href="#a96c36f33834fe7c00c5cc237e2a84f15">getTemplateInstances</a>, <a href="#a85e4b2162a44896395d809a098420c2d">getTemplateParameterLists</a>, <a href="#a17cd90b59ffb3350b65ee8ea591c00bf">hasDetailedDescription</a>, <a href="#a855edd664ad46a701a511306ceb4dfad">hasDocumentation</a>, <a href="#ae099a548e89bc8fe025a23956302c941">hasExamples</a>, <a href="#a87dbe574a9382a77997d537e765a91dc">hasNonReferenceSuperClass</a>, <a href="#a5d42a0caefc7e005ea3c631060e99b67">includeInfo</a>, <a href="#a92ae76c1dfc81b0c710c81ef51f26b49">inheritanceGraphFileName</a>, <a href="#adaae961f8756744ea5dda669438bb72e">isAbstract</a>, <a href="#a645b16eec442e33bc9e1ec74d905ae7e">isAccessibleMember</a>, <a href="#a7f39d12e122ea5b3b193bbcebf0d4ffa">isBaseClass</a>, <a href="#a79e5f3bb598a5c4e7d7da910b94346a7">isCSharp</a>, <a href="#a7c79bfd6caa7a9f75b579efc5e6c8d21">isEmbeddedInOuterScope</a>, <a href="#ad58aee30483201711f9c22c4a7a76f37">isExtension</a>, <a href="#a3b5f214b1d0ca22e9cca64ceff86fad8">isFinal</a>, <a href="#a00c035549072771ff77d41853d1dcb85">isFortran</a>, <a href="#a57c5f72005a5274806e9c313008fe20c">isForwardDeclared</a>, <a href="#a3983c632458a22f0a08586f8cecd5a3f">isImplicitTemplateInstance</a>, <a href="#ad8ef9734df70fb412b8448263a6710cc">isInterface</a>, <a href="#a8f5e61e688959db751fdd0f4c348bff0">isJavaEnum</a>, <a href="#acb73f5827e37675b97aea0a28f152f42">isLinkable</a>, <a href="#a9cf9b733ce1e3dd0b66576d7a936cce6">isLinkableInProject</a>, <a href="#aa0182439370e6edec85940f146165a6c">isLocal</a>, <a href="#af999602a0c50fba3fc8e8e9a6099117b">isObjectiveC</a>, <a href="#a33f513d25096ffbdd609f8a8b8d90eaa">isPublished</a>, <a href="#a4a640308f08565df3c59d2e6e6fd346f">isReference</a>, <a href="#a845e9d5013f50f4cc3b993f9c25e19bc">isSealed</a>, <a href="#a009dcf17da2c27f28a96b4853d86a1b2">isSimple</a>, <a href="#af586f33895a2216917c713a592650c93">isSliceLocal</a>, <a href="#af8842bc054a73e6f2afde250689769c5">isSmartPointer</a>, <a href="#a0f71e5d60cca54183d1065a41c1a0f44">isSubClass</a>, <a href="#af13b5351fc7fd510363e990fa879f98f">isTemplate</a>, <a href="#a4ad1e6b4087d769162b741416eb71aad">isTemplateArgument</a>, <a href="#af649a11e97e72bb215cbf6b63bc6dec8">isUsedOnly</a>, <a href="#a2dec55de26c5156f759c5e74f541a3c9">isVisibleInHierarchy</a>, <a href="#a352f59ecd49f57e3672483e74a3f28fb">memberNameInfoLinkedMap</a>, <a href="#a7961a65064ffd08298daa974dbf22f62">protection</a>, <a href="#a01f7627552da826d1fc811a1cb7745be">requiresClause</a>, <a href="#a8da844453583bd41555356e618e421d3">subClasses</a>, <a href="#a751ea04eced6b1babc036079c65442b3">subGrouping</a>, <a href="#ad2fdbc08bbbbc42580f6cc5dcedd6bef">tagLessReference</a>, <a href="#a77a2605db1e0eb2e8de6af646aa7e3fa">templateArguments</a>, <a href="#aec00fde6dc30bb24809fee577bb09815">templateMaster</a>, <a href="#ad805eac8641d4d75315d8385315cd117">templateTypeConstraints</a>, <a href="#a358d46451cf46a373a32d0c5658b0936">title</a>, <a href="#a5850425ae3d9bfdb3892661066d8bd9f">typeConstraints</a>, <a href="#a16cff2ab73c4abbd38d29b5a12e8021c">usedByImplementationClasses</a>, <a href="#a39a5532e4d59a5a5adcad9e5d7ec4cab">usedFiles</a>, <a href="#a257058fa8508a33ca9dbbfc8715838e4">usedImplementationClasses</a>, <a href="#ae4d8df5b0e45883b18308263d215200f">visibleInParentsDeclList</a>, <a href="#a6effa63252fa897e5521fd8034bb19a9">writeDeclaration</a>, <a href="#abcfb957d1b34d6e323a5ae8f8f7c0da3">writeDeclarationLink</a>, <a href="#a236a08389de317adcab69a7ab6e9a37a">writeDocumentation</a>, <a href="#aa63ae9765c16beef2b4a889b0f5d321b">writeDocumentationForInnerClasses</a>, <a href="#a8c919b56012472db7a02ccb01316ccab">writeInlineDocumentation</a>, <a href="#ab287ccfb0386977fce96aa616e9be50e">writeMemberDeclarations</a>, <a href="#afcedf72f74d9a02cd4e29852c1e07ebe">writeMemberList</a>, <a href="#a672214abd88e36416d36b390728fc0f4">writeMemberPages</a>, <a href="#a190101033114f81cf21225e28525d833">writePageNavigation</a>, <a href="#a70e4e875c4a4b14689d58f1114ead623">writeQuickMemberLinks</a>, <a href="#a2bcc1c98274b691e8709551d753b0a18">writeSummaryLinks</a> and <a href="#a076783e77d8c5731d465d196336416fb">writeTagFile</a>.
</div>
</div>

### getClasses() {#ad6d03ddc7d64482fe61594f39760eec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassLinkedRefMap ClassDefAliasImpl::getClasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns the classes nested into this class

Definition at line 599 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6d03ddc7d64482fe61594f39760eec6">599</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classlinkedrefmap">ClassLinkedRefMap</a> <a href="#ad6d03ddc7d64482fe61594f39760eec6">getClasses</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aeb64dc8f57c5d07f1b1d55bc560a7004">getClasses</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#aeb64dc8f57c5d07f1b1d55bc560a7004">ClassDef::getClasses</a>.
</div>
</div>

### getExamples() {#a46cadea07d5df790e78b20f7f3385c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ExampleList &amp; ClassDefAliasImpl::getExamples ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 722 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46cadea07d5df790e78b20f7f3385c17">722</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/examplelist">ExampleList</a> &amp;<a href="#a46cadea07d5df790e78b20f7f3385c17">getExamples</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a980a867140493e4cf4fd9ded7ee75e55">getExamples</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a980a867140493e4cf4fd9ded7ee75e55">ClassDef::getExamples</a>.
</div>
</div>

### getFileDef() {#a858094677f40ed5783d6fa0e478d1436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileDef * ClassDefAliasImpl::getFileDef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the namespace this compound is in, or 0 if it has a global scope.


Returns the file in which this compound's definition can be found. Should not return 0 (but it might be a good idea to check anyway).

Definition at line 633 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a858094677f40ed5783d6fa0e478d1436">633</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#a858094677f40ed5783d6fa0e478d1436">getFileDef</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">getFileDef</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#aed4a0864e51e5a3ac616f6c8e10f56c6">ClassDef::getFileDef</a>.
</div>
</div>

### getInstanceOutputFileBase() {#aa5cc8426c3d589ef6b9f8f515381c1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::getInstanceOutputFileBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 589 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5cc8426c3d589ef6b9f8f515381c1a8">589</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa5cc8426c3d589ef6b9f8f515381c1a8">getInstanceOutputFileBase</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8476d860cfdada4916c4dc722f0bea07">getInstanceOutputFileBase</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a8476d860cfdada4916c4dc722f0bea07">ClassDef::getInstanceOutputFileBase</a>.
</div>
</div>

### getMemberByName() {#ae517db2634ad080c8525e2372e357846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * ClassDefAliasImpl::getMemberByName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the member with the given name.

Definition at line 637 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae517db2634ad080c8525e2372e357846">637</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#ae517db2634ad080c8525e2372e357846">getMemberByName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3bec35936216530bf2385a8dfd2ab0e5">getMemberByName</a>(s); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a3bec35936216530bf2385a8dfd2ab0e5">ClassDef::getMemberByName</a>.
</div>
</div>

### getMemberGroups() {#a7bf05103ee29cfb5044803f807b4ffc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberGroupList &amp; ClassDefAliasImpl::getMemberGroups ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the member groups defined for this class.

Definition at line 696 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bf05103ee29cfb5044803f807b4ffc3">696</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a> &amp;<a href="#a7bf05103ee29cfb5044803f807b4ffc3">getMemberGroups</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#add2c3b56273ce664bbaeb0ce1c8f420c">getMemberGroups</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#add2c3b56273ce664bbaeb0ce1c8f420c">ClassDef::getMemberGroups</a>.
</div>
</div>

### getMemberList() {#aad904b7993ef051b6141cb1726547c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberList * ClassDefAliasImpl::getMemberList (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the members in the list identified by <em>lt</em>.

Definition at line 692 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad904b7993ef051b6141cb1726547c2b">692</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *<a href="#aad904b7993ef051b6141cb1726547c2b">getMemberList</a>(<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(lt); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">ClassDef::getMemberList</a>.
</div>
</div>

### getMemberListFileName() {#a8757c279d4e5c9045031aee25c803a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::getMemberListFileName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8757c279d4e5c9045031aee25c803a8e">726</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a8757c279d4e5c9045031aee25c803a8e">getMemberListFileName</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac620ac7f22f673e84410b1ceca0af3be">getMemberListFileName</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ac620ac7f22f673e84410b1ceca0af3be">ClassDef::getMemberListFileName</a>.
</div>
</div>

### getMemberLists() {#aaba9f5d25cf840f83a761fac5366004d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberLists &amp; ClassDefAliasImpl::getMemberLists ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the list containing the list of members sorted per type.

Definition at line 694 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaba9f5d25cf840f83a761fac5366004d">694</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlists">MemberLists</a> &amp;<a href="#aaba9f5d25cf840f83a761fac5366004d">getMemberLists</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a283e841b3eb34d0ba2e0e106a4e3ad59">getMemberLists</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a283e841b3eb34d0ba2e0e106a4e3ad59">ClassDef::getMemberLists</a>.
</div>
</div>

### getModuleDef() {#a1a32242add36cd5333c0bf797891a656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleDef * ClassDefAliasImpl::getModuleDef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the C++20 module in which this compound's definition can be found.

Definition at line 635 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a32242add36cd5333c0bf797891a656">635</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *<a href="#a1a32242add36cd5333c0bf797891a656">getModuleDef</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a109769b1e6eb23eb36e23530e667703e">getModuleDef</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a109769b1e6eb23eb36e23530e667703e">ClassDef::getModuleDef</a>.
</div>
</div>

### getOutputFileBase() {#ab4a6db56da1eb406e31ab4e93e970e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::getOutputFileBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns the base file name (without extension) of this definition. as it is referenced to/written to disk.

Definition at line 587 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4a6db56da1eb406e31ab4e93e970e49">587</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab4a6db56da1eb406e31ab4e93e970e49">getOutputFileBase</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>.
</div>
</div>

### getQualifiers() {#a2925368285d630431e824f40245df057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector ClassDefAliasImpl::getQualifiers ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 736 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2925368285d630431e824f40245df057">736</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> <a href="#a2925368285d630431e824f40245df057">getQualifiers</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a570d8dcfdd144e17226ca785e58b15b7">getQualifiers</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a570d8dcfdd144e17226ca785e58b15b7">ClassDef::getQualifiers</a>.
</div>
</div>

### getReference() {#a7db9cf4aacb7a843ee0be85684ca3ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::getReference ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




If this definition was imported via a tag file, this function returns the tagfile for the external project. This can be translated into an external link target via Doxygen::tagDestinationDict

Definition at line 593 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7db9cf4aacb7a843ee0be85684ca3ce0">593</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7db9cf4aacb7a843ee0be85684ca3ce0">getReference</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>.
</div>
</div>

### getSourceFileBase() {#a670ee0af2bc87b10113a41a76c4a84c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::getSourceFileBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns the name of the source listing of this definition.

Definition at line 591 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a670ee0af2bc87b10113a41a76c4a84c8">591</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a670ee0af2bc87b10113a41a76c4a84c8">getSourceFileBase</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ab7ecf3e26ca026ed20af225f332e5fe7">getSourceFileBase</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#ab7ecf3e26ca026ed20af225f332e5fe7">Definition::getSourceFileBase</a>.
</div>
</div>

### getTemplateBaseClassNames() {#aba326b765f7af4f942eda8ed49db9063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TemplateNameMap &amp; ClassDefAliasImpl::getTemplateBaseClassNames ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 698 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba326b765f7af4f942eda8ed49db9063">698</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#a52c06547a303385be1dc01559096a3d9">TemplateNameMap</a> &amp;<a href="#aba326b765f7af4f942eda8ed49db9063">getTemplateBaseClassNames</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aaf3dc7118f6d91b7bc741e29f45215b1">getTemplateBaseClassNames</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#aaf3dc7118f6d91b7bc741e29f45215b1">ClassDef::getTemplateBaseClassNames</a>.
</div>
</div>

### getTemplateInstances() {#a96c36f33834fe7c00c5cc237e2a84f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TemplateInstanceList &amp; ClassDefAliasImpl::getTemplateInstances ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns a sorted dictionary with all template instances found for this template class.


Returns 0 if not a template or no instances.

Definition at line 645 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96c36f33834fe7c00c5cc237e2a84f15">645</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#ac6ced1c572e645da3d141b20bad3aeb4">TemplateInstanceList</a> &amp;<a href="#a96c36f33834fe7c00c5cc237e2a84f15">getTemplateInstances</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3ceb3e484b62599117b5eb424c10fd10">getTemplateInstances</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a3ceb3e484b62599117b5eb424c10fd10">ClassDef::getTemplateInstances</a>.
</div>
</div>

### getTemplateParameterLists() {#a85e4b2162a44896395d809a098420c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgumentLists ClassDefAliasImpl::getTemplateParameterLists ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the template parameter lists that form the template declaration of this class.


<a href="/web-doxygen/docs/api/structs/example">Example</a>: <code>template&lt;class T&gt; class TC {} = 0;</code> will return a list with one <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> containing one argument with type="class" and name="T".

Definition at line 663 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85e4b2162a44896395d809a098420c2d">663</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> <a href="#a85e4b2162a44896395d809a098420c2d">getTemplateParameterLists</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a43e4fb6ebed35075ecee567872abbe20">getTemplateParameterLists</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a43e4fb6ebed35075ecee567872abbe20">ClassDef::getTemplateParameterLists</a>.
</div>
</div>

### hasDetailedDescription() {#a17cd90b59ffb3350b65ee8ea591c00bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::hasDetailedDescription ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns TRUE if this class has a non-empty detailed description

Definition at line 603 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17cd90b59ffb3350b65ee8ea591c00bf">603</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a17cd90b59ffb3350b65ee8ea591c00bf">hasDetailedDescription</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a1fd0e2c039c6d81ffa25579184568e87">hasDetailedDescription</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a1fd0e2c039c6d81ffa25579184568e87">ClassDef::hasDetailedDescription</a>.
</div>
</div>

### hasDocumentation() {#a855edd664ad46a701a511306ceb4dfad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::hasDocumentation ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns TRUE iff the definition is documented (which could be generated documentation)

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#adb03d1aad0f7f7b77c1fe0a8ab43d282">hasUserDocumentation()</a>
</dd>
</dl>


Definition at line 601 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a855edd664ad46a701a511306ceb4dfad">601</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a855edd664ad46a701a511306ceb4dfad">hasDocumentation</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a81f5c355e27d6e159e1598be748aa4de">hasDocumentation</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#a81f5c355e27d6e159e1598be748aa4de">Definition::hasDocumentation</a>.
</div>
</div>

### hasExamples() {#ae099a548e89bc8fe025a23956302c941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::hasExamples ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 724 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae099a548e89bc8fe025a23956302c941">724</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae099a548e89bc8fe025a23956302c941">hasExamples</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a4da7081ddd605c4b0f972d4aeadaf1a0">hasExamples</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a4da7081ddd605c4b0f972d4aeadaf1a0">ClassDef::hasExamples</a>.
</div>
</div>

### hasNonReferenceSuperClass() {#a87dbe574a9382a77997d537e765a91dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::hasNonReferenceSuperClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 732 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87dbe574a9382a77997d537e765a91dc">732</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a87dbe574a9382a77997d537e765a91dc">hasNonReferenceSuperClass</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8bfa7122b5f501c389a13c2d55219f44">hasNonReferenceSuperClass</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a8bfa7122b5f501c389a13c2d55219f44">ClassDef::hasNonReferenceSuperClass</a>.
</div>
</div>

### includeInfo() {#a5d42a0caefc7e005ea3c631060e99b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IncludeInfo * ClassDefAliasImpl::includeInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 651 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d42a0caefc7e005ea3c631060e99b67">651</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *<a href="#a5d42a0caefc7e005ea3c631060e99b67">includeInfo</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">includeInfo</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">ClassDef::includeInfo</a>.
</div>
</div>

### inheritanceGraphFileName() {#a92ae76c1dfc81b0c710c81ef51f26b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::inheritanceGraphFileName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns the file name to use for the inheritance graph

Definition at line 607 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92ae76c1dfc81b0c710c81ef51f26b49">607</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a92ae76c1dfc81b0c710c81ef51f26b49">inheritanceGraphFileName</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a4feb0d6c2afb9ab04ba7faec2becf27e">inheritanceGraphFileName</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a4feb0d6c2afb9ab04ba7faec2becf27e">ClassDef::inheritanceGraphFileName</a>.
</div>
</div>

### isAbstract() {#adaae961f8756744ea5dda669438bb72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isAbstract ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if there is at least one pure virtual member in this class.

Definition at line 668 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adaae961f8756744ea5dda669438bb72e">668</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adaae961f8756744ea5dda669438bb72e">isAbstract</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a12dd6a6b0ac63233a82327a8b2d2d9f2">isAbstract</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a12dd6a6b0ac63233a82327a8b2d2d9f2">ClassDef::isAbstract</a>.
</div>
</div>

### isAccessibleMember() {#a645b16eec442e33bc9e1ec74d905ae7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isAccessibleMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns TRUE iff <em>md</em> is a member of this class or of the the public/protected members of a base class

Definition at line 643 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a645b16eec442e33bc9e1ec74d905ae7e">643</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a645b16eec442e33bc9e1ec74d905ae7e">isAccessibleMember</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aa4f8aa899e9bf12dacd3442c9647bac4">isAccessibleMember</a>(md); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#aa4f8aa899e9bf12dacd3442c9647bac4">ClassDef::isAccessibleMember</a>.
</div>
</div>

### isBaseClass() {#a7f39d12e122ea5b3b193bbcebf0d4ffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ClassDefAliasImpl::isBaseClass (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * bcd, bool followInstances, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; templSpec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE iff <em>bcd</em> is a direct or indirect base class of this class.


This function will recursively traverse all branches of the inheritance tree.

Definition at line 639 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7f39d12e122ea5b3b193bbcebf0d4ffa">639</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7f39d12e122ea5b3b193bbcebf0d4ffa">isBaseClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bcd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> followInstances,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;templSpec)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3e118df515565a29662b41396ee66579">isBaseClass</a>(bcd,followInstances,templSpec); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a3e118df515565a29662b41396ee66579">ClassDef::isBaseClass</a>.
</div>
</div>

### isCSharp() {#a79e5f3bb598a5c4e7d7da910b94346a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isCSharp ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is implemented in C#.

Definition at line 674 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a79e5f3bb598a5c4e7d7da910b94346a7">674</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a79e5f3bb598a5c4e7d7da910b94346a7">isCSharp</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8bfbc9a9cc5af4db69a0b5a796a28d38">isCSharp</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a8bfbc9a9cc5af4db69a0b5a796a28d38">ClassDef::isCSharp</a>.
</div>
</div>

### isEmbeddedInOuterScope() {#a7c79bfd6caa7a9f75b579efc5e6c8d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isEmbeddedInOuterScope ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 704 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c79bfd6caa7a9f75b579efc5e6c8d21">704</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7c79bfd6caa7a9f75b579efc5e6c8d21">isEmbeddedInOuterScope</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac86d2e29cb6233d073aa4c9b5ea726af">isEmbeddedInOuterScope</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ac86d2e29cb6233d073aa4c9b5ea726af">ClassDef::isEmbeddedInOuterScope</a>.
</div>
</div>

### isExtension() {#ad58aee30483201711f9c22c4a7a76f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isExtension ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class represents an Objective-C 2.0 extension (nameless category)

Definition at line 682 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad58aee30483201711f9c22c4a7a76f37">682</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad58aee30483201711f9c22c4a7a76f37">isExtension</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8a066b13127c13f73ae916af7d883ea1">isExtension</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a8a066b13127c13f73ae916af7d883ea1">ClassDef::isExtension</a>.
</div>
</div>

### isFinal() {#a3b5f214b1d0ca22e9cca64ceff86fad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isFinal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is marked as final.

Definition at line 676 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b5f214b1d0ca22e9cca64ceff86fad8">676</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3b5f214b1d0ca22e9cca64ceff86fad8">isFinal</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a18c81095d49e7a4e05820d9928deaa45">isFinal</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a18c81095d49e7a4e05820d9928deaa45">ClassDef::isFinal</a>.
</div>
</div>

### isFortran() {#a00c035549072771ff77d41853d1dcb85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isFortran ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is implemented in Fortran.

Definition at line 672 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a00c035549072771ff77d41853d1dcb85">672</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a00c035549072771ff77d41853d1dcb85">isFortran</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a25f184cac0ea4de2d27b0c0957ab9b77">isFortran</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a25f184cac0ea4de2d27b0c0957ab9b77">ClassDef::isFortran</a>.
</div>
</div>

### isForwardDeclared() {#a57c5f72005a5274806e9c313008fe20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isForwardDeclared ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class represents a forward declaration of a template class.

Definition at line 684 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57c5f72005a5274806e9c313008fe20c">684</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a57c5f72005a5274806e9c313008fe20c">isForwardDeclared</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8c23670661fa0360c44d3352b16135b4">isForwardDeclared</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a8c23670661fa0360c44d3352b16135b4">ClassDef::isForwardDeclared</a>.
</div>
</div>

### isImplicitTemplateInstance() {#a3983c632458a22f0a08586f8cecd5a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isImplicitTemplateInstance ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 750 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3983c632458a22f0a08586f8cecd5a3f">750</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3983c632458a22f0a08586f8cecd5a3f">isImplicitTemplateInstance</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">isImplicitTemplateInstance</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">ClassDef::isImplicitTemplateInstance</a>.
</div>
</div>

### isInterface() {#ad8ef9734df70fb412b8448263a6710cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isInterface ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class represents an interface.

Definition at line 686 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8ef9734df70fb412b8448263a6710cc">686</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad8ef9734df70fb412b8448263a6710cc">isInterface</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aebcf69f2e74678dc5e62f1b528c9b902">isInterface</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#aebcf69f2e74678dc5e62f1b528c9b902">ClassDef::isInterface</a>.
</div>
</div>

### isJavaEnum() {#a8f5e61e688959db751fdd0f4c348bff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isJavaEnum ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 712 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f5e61e688959db751fdd0f4c348bff0">712</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8f5e61e688959db751fdd0f4c348bff0">isJavaEnum</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a9a3699b6766321cef5a194b6fa1a9d2c">isJavaEnum</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a9a3699b6766321cef5a194b6fa1a9d2c">ClassDef::isJavaEnum</a>.
</div>
</div>

### isLinkable() {#acb73f5827e37675b97aea0a28f152f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isLinkable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns TRUE iff it is possible to link to this item. This can be a link to another project imported via a tag file.

Definition at line 625 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb73f5827e37675b97aea0a28f152f42">625</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acb73f5827e37675b97aea0a28f152f42">isLinkable</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>.
</div>
</div>

### isLinkableInProject() {#a9cf9b733ce1e3dd0b66576d7a936cce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isLinkableInProject ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns TRUE iff it is possible to link to this item within this project.

Definition at line 623 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cf9b733ce1e3dd0b66576d7a936cce6">623</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9cf9b733ce1e3dd0b66576d7a936cce6">isLinkableInProject</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">isLinkableInProject</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#a845891c7206d40c3664b562636cdf9fc">Definition::isLinkableInProject</a>.
</div>
</div>

### isLocal() {#aa0182439370e6edec85940f146165a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isLocal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this is a local class definition, see EXTRACT\_LOCAL\_CLASSES.

Definition at line 597 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0182439370e6edec85940f146165a6c">597</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa0182439370e6edec85940f146165a6c">isLocal</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a6b24aeece30ae83930ed2a3ca0621fec">isLocal</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a6b24aeece30ae83930ed2a3ca0621fec">ClassDef::isLocal</a>.
</div>
</div>

### isObjectiveC() {#af999602a0c50fba3fc8e8e9a6099117b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isObjectiveC ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is implemented in Objective-C.

Definition at line 670 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af999602a0c50fba3fc8e8e9a6099117b">670</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af999602a0c50fba3fc8e8e9a6099117b">isObjectiveC</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a4d9613dc45d98c8cd04a6fcf6a4f21ee">isObjectiveC</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a4d9613dc45d98c8cd04a6fcf6a4f21ee">ClassDef::isObjectiveC</a>.
</div>
</div>

### isPublished() {#a33f513d25096ffbdd609f8a8b8d90eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isPublished ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is marked as published.

Definition at line 680 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33f513d25096ffbdd609f8a8b8d90eaa">680</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a33f513d25096ffbdd609f8a8b8d90eaa">isPublished</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ab61c051bbda755836c90d7be3d63e4f2">isPublished</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ab61c051bbda755836c90d7be3d63e4f2">ClassDef::isPublished</a>.
</div>
</div>

### isReference() {#a4a640308f08565df3c59d2e6e6fd346f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isReference ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns TRUE if this definition is imported via a tag file.

Definition at line 595 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a640308f08565df3c59d2e6e6fd346f">595</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4a640308f08565df3c59d2e6e6fd346f">isReference</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>.
</div>
</div>

### isSealed() {#a845e9d5013f50f4cc3b993f9c25e19bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isSealed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is marked as sealed.

Definition at line 678 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a845e9d5013f50f4cc3b993f9c25e19bc">678</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a845e9d5013f50f4cc3b993f9c25e19bc">isSealed</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3bcc0025ce9b44d8617da2abaf0eb978">isSealed</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a3bcc0025ce9b44d8617da2abaf0eb978">ClassDef::isSealed</a>.
</div>
</div>

### isSimple() {#a009dcf17da2c27f28a96b4853d86a1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isSimple ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 706 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a009dcf17da2c27f28a96b4853d86a1b2">706</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a009dcf17da2c27f28a96b4853d86a1b2">isSimple</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7396ab268485c570718f3274105b3f48">isSimple</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a7396ab268485c570718f3274105b3f48">ClassDef::isSimple</a>.
</div>
</div>

### isSliceLocal() {#af586f33895a2216917c713a592650c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isSliceLocal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 730 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af586f33895a2216917c713a592650c93">730</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af586f33895a2216917c713a592650c93">isSliceLocal</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a0e9ae30aa6558cef5fd9bda03c1bb569">isSliceLocal</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a0e9ae30aa6558cef5fd9bda03c1bb569">ClassDef::isSliceLocal</a>.
</div>
</div>

### isSmartPointer() {#af8842bc054a73e6f2afde250689769c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * ClassDefAliasImpl::isSmartPointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 710 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8842bc054a73e6f2afde250689769c5">710</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *<a href="#af8842bc054a73e6f2afde250689769c5">isSmartPointer</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a88fd3d3f7762f2a3c7b3634b554ce579">isSmartPointer</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a88fd3d3f7762f2a3c7b3634b554ce579">ClassDef::isSmartPointer</a>.
</div>
</div>

### isSubClass() {#a0f71e5d60cca54183d1065a41c1a0f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isSubClass (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * bcd, int level=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE iff <em>bcd</em> is a direct or indirect sub class of this class.

Definition at line 641 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f71e5d60cca54183d1065a41c1a0f44">641</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0f71e5d60cca54183d1065a41c1a0f44">isSubClass</a>(<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bcd,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level=0)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a9a4c36f29d33a44a6b7460e89a7cd741">isSubClass</a>(bcd,level); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a9a4c36f29d33a44a6b7460e89a7cd741">ClassDef::isSubClass</a>.
</div>
</div>

### isTemplate() {#af13b5351fc7fd510363e990fa879f98f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isTemplate ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if this class is a template.

Definition at line 649 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af13b5351fc7fd510363e990fa879f98f">649</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af13b5351fc7fd510363e990fa879f98f">isTemplate</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a30f19d5b8fb17b204b9e41d19b2ca49f">isTemplate</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a30f19d5b8fb17b204b9e41d19b2ca49f">ClassDef::isTemplate</a>.
</div>
</div>

### isTemplateArgument() {#a4ad1e6b4087d769162b741416eb71aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isTemplateArgument ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 659 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ad1e6b4087d769162b741416eb71aad">659</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4ad1e6b4087d769162b741416eb71aad">isTemplateArgument</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a9eabb427f58a6631c73f76c6856694a7">isTemplateArgument</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a9eabb427f58a6631c73f76c6856694a7">ClassDef::isTemplateArgument</a>.
</div>
</div>

### isUsedOnly() {#af649a11e97e72bb215cbf6b63bc6dec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isUsedOnly ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 700 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af649a11e97e72bb215cbf6b63bc6dec8">700</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af649a11e97e72bb215cbf6b63bc6dec8">isUsedOnly</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afee08a2576eb4d2888560c89ab2e1614">isUsedOnly</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afee08a2576eb4d2888560c89ab2e1614">ClassDef::isUsedOnly</a>.
</div>
</div>

### isVisibleInHierarchy() {#a2dec55de26c5156f759c5e74f541a3c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::isVisibleInHierarchy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

the class is visible in a class diagram, or class hierarchy

Definition at line 627 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2dec55de26c5156f759c5e74f541a3c9">627</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2dec55de26c5156f759c5e74f541a3c9">isVisibleInHierarchy</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">isVisibleInHierarchy</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">ClassDef::isVisibleInHierarchy</a>.
</div>
</div>

### memberNameInfoLinkedMap() {#a352f59ecd49f57e3672483e74a3f28fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberNameInfoLinkedMap &amp; ClassDefAliasImpl::memberNameInfoLinkedMap ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns a dictionary of all members.


This includes any inherited members. Members are sorted alphabetically.

Definition at line 619 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a352f59ecd49f57e3672483e74a3f28fb">619</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membernameinfolinkedmap">MemberNameInfoLinkedMap</a> &amp;<a href="#a352f59ecd49f57e3672483e74a3f28fb">memberNameInfoLinkedMap</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac8f58a78e8196768f3ddd17e645cf7f9">memberNameInfoLinkedMap</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ac8f58a78e8196768f3ddd17e645cf7f9">ClassDef::memberNameInfoLinkedMap</a>.
</div>
</div>

### moveTo() {#a48c89c5ecd68496abd8b1ac56530110c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::moveTo (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 583 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48c89c5ecd68496abd8b1ac56530110c">583</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a48c89c5ecd68496abd8b1ac56530110c">moveTo</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### protection() {#a7961a65064ffd08298daa974dbf22f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Protection ClassDefAliasImpl::protection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Return the protection level (Public,Protected,Private) in which this compound was found.

Definition at line 621 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7961a65064ffd08298daa974dbf22f62">621</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> <a href="#a7961a65064ffd08298daa974dbf22f62">protection</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a>.
</div>
</div>

### qualifiedNameWithTemplateParameters() {#a2e7190f6e1928c0e8d70d6cc013cc401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::qualifiedNameWithTemplateParameters (const <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> * actualParams=nullptr, uint32_t * actualParamIndex=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 665 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e7190f6e1928c0e8d70d6cc013cc401">665</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2e7190f6e1928c0e8d70d6cc013cc401">qualifiedNameWithTemplateParameters</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/arguments-h/#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> *actualParams=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,uint32_t *actualParamIndex=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,actualParams,actualParamIndex); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>.
</div>
</div>

### requiresClause() {#a01f7627552da826d1fc811a1cb7745be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::requiresClause ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 734 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01f7627552da826d1fc811a1cb7745be">734</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a01f7627552da826d1fc811a1cb7745be">requiresClause</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af404e73b14943149542cf4202bc0ab6d">requiresClause</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#af404e73b14943149542cf4202bc0ab6d">ClassDef::requiresClause</a>.
</div>
</div>

### subClasses() {#a8da844453583bd41555356e618e421d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BaseClassList &amp; ClassDefAliasImpl::subClasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the list of sub classes that directly derive from this class.

Definition at line 617 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8da844453583bd41555356e618e421d3">617</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;<a href="#a8da844453583bd41555356e618e421d3">subClasses</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a>.
</div>
</div>

### subGrouping() {#a751ea04eced6b1babc036079c65442b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::subGrouping ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 728 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a751ea04eced6b1babc036079c65442b3">728</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a751ea04eced6b1babc036079c65442b3">subGrouping</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a1e2ce9f8d0cb3b6f1ba0317ca8dbb714">subGrouping</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a1e2ce9f8d0cb3b6f1ba0317ca8dbb714">ClassDef::subGrouping</a>.
</div>
</div>

### tagLessReference() {#ad2fdbc08bbbbc42580f6cc5dcedd6bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * ClassDefAliasImpl::tagLessReference ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 708 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2fdbc08bbbbc42580f6cc5dcedd6bef">708</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#ad2fdbc08bbbbc42580f6cc5dcedd6bef">tagLessReference</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7b4e443b14553fba6f95e3462b531149">tagLessReference</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a7b4e443b14553fba6f95e3462b531149">ClassDef::tagLessReference</a>.
</div>
</div>

### templateArguments() {#a77a2605db1e0eb2e8de6af646aa7e3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArgumentList &amp; ClassDefAliasImpl::templateArguments ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the template arguments of this class.

Definition at line 631 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77a2605db1e0eb2e8de6af646aa7e3fa">631</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;<a href="#a77a2605db1e0eb2e8de6af646aa7e3fa">templateArguments</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">ClassDef::templateArguments</a>.
</div>
</div>

### templateMaster() {#aec00fde6dc30bb24809fee577bb09815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * ClassDefAliasImpl::templateMaster ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the template master of which this class is an instance.


Returns 0 if not applicable.

Definition at line 647 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec00fde6dc30bb24809fee577bb09815">647</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#aec00fde6dc30bb24809fee577bb09815">templateMaster</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae587759f556ea0d641b92a30e923a7c9">templateMaster</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ae587759f556ea0d641b92a30e923a7c9">ClassDef::templateMaster</a>.
</div>
</div>

### templateTypeConstraints() {#ad805eac8641d4d75315d8385315cd117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConstraintClassList &amp; ClassDefAliasImpl::templateTypeConstraints ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 657 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad805eac8641d4d75315d8385315cd117">657</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/constraintclasslist">ConstraintClassList</a> &amp;<a href="#ad805eac8641d4d75315d8385315cd117">templateTypeConstraints</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#acd8e27ea299fea8b7d180608bfb1326b">templateTypeConstraints</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#acd8e27ea299fea8b7d180608bfb1326b">ClassDef::templateTypeConstraints</a>.
</div>
</div>

### title() {#a358d46451cf46a373a32d0c5658b0936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ClassDefAliasImpl::title ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 714 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a358d46451cf46a373a32d0c5658b0936">714</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a358d46451cf46a373a32d0c5658b0936">title</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afb51998523ff484408b2a96fd4f3fced">title</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afb51998523ff484408b2a96fd4f3fced">ClassDef::title</a>.

Referenced by <a href="#ab287ccfb0386977fce96aa616e9be50e">writeMemberDeclarations</a>.
</div>
</div>

### typeConstraints() {#a5850425ae3d9bfdb3892661066d8bd9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArgumentList &amp; ClassDefAliasImpl::typeConstraints ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 720 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5850425ae3d9bfdb3892661066d8bd9f">720</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;<a href="#a5850425ae3d9bfdb3892661066d8bd9f">typeConstraints</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aa4c4caac2adb12c3207df5936ba2c90b">typeConstraints</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#aa4c4caac2adb12c3207df5936ba2c90b">ClassDef::typeConstraints</a>.
</div>
</div>

### updateBaseClasses() {#a742f87acdae8e420b133af8dbfc92ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::updateBaseClasses (const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp; bcd)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Update the list of base classes to the one passed.

Definition at line 784 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a742f87acdae8e420b133af8dbfc92ee7">784</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a742f87acdae8e420b133af8dbfc92ee7">updateBaseClasses</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### updateSubClasses() {#a502bc75feea6d219fea06fd859fdae8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::updateSubClasses (const <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp; bcd)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Update the list of sub classes to the one passed.

Definition at line 785 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a502bc75feea6d219fea06fd859fdae8b">785</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a502bc75feea6d219fea06fd859fdae8b">updateSubClasses</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### usedByImplementationClasses() {#a16cff2ab73c4abbd38d29b5a12e8021c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UsesClassList &amp; ClassDefAliasImpl::usedByImplementationClasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 655 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16cff2ab73c4abbd38d29b5a12e8021c">655</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/usesclasslist">UsesClassList</a> &amp;<a href="#a16cff2ab73c4abbd38d29b5a12e8021c">usedByImplementationClasses</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ade6f41d07606c61673264a5d50e95c61">usedByImplementationClasses</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ade6f41d07606c61673264a5d50e95c61">ClassDef::usedByImplementationClasses</a>.
</div>
</div>

### usedFiles() {#a39a5532e4d59a5a5adcad9e5d7ec4cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileList &amp; ClassDefAliasImpl::usedFiles ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 718 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39a5532e4d59a5a5adcad9e5d7ec4cab">718</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filelist">FileList</a> &amp;<a href="#a39a5532e4d59a5a5adcad9e5d7ec4cab">usedFiles</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ab6ba54124ee74df07036e2473579264d">usedFiles</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ab6ba54124ee74df07036e2473579264d">ClassDef::usedFiles</a>.
</div>
</div>

### usedImplementationClasses() {#a257058fa8508a33ca9dbbfc8715838e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UsesClassList &amp; ClassDefAliasImpl::usedImplementationClasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 653 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a257058fa8508a33ca9dbbfc8715838e4">653</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/usesclasslist">UsesClassList</a> &amp;<a href="#a257058fa8508a33ca9dbbfc8715838e4">usedImplementationClasses</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a4a15dff9d9567c126433228fff77837b">usedImplementationClasses</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a4a15dff9d9567c126433228fff77837b">ClassDef::usedImplementationClasses</a>.
</div>
</div>

### visibleInParentsDeclList() {#ae4d8df5b0e45883b18308263d215200f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ClassDefAliasImpl::visibleInParentsDeclList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

show this class in the declaration section of its parent?

Definition at line 629 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae4d8df5b0e45883b18308263d215200f">629</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae4d8df5b0e45883b18308263d215200f">visibleInParentsDeclList</a>()</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a1a79f778ae2201c52ee19c048763d4fa">visibleInParentsDeclList</a>(); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a1a79f778ae2201c52ee19c048763d4fa">ClassDef::visibleInParentsDeclList</a>.
</div>
</div>

### writeDeclaration() {#a6effa63252fa897e5521fd8034bb19a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeDeclaration (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, bool inGroup, int indentLevel, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 761 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6effa63252fa897e5521fd8034bb19a9">761</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6effa63252fa897e5521fd8034bb19a9">writeDeclaration</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inGroup,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indentLevel, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#acfcf16726b8d952b1c76d43adfbef197">writeDeclaration</a>(ol,md,inGroup,indentLevel,inheritedFrom,inheritId); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#acfcf16726b8d952b1c76d43adfbef197">ClassDef::writeDeclaration</a>.
</div>
</div>

### writeDeclarationLink() {#abcfb957d1b34d6e323a5ae8f8f7c0da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeDeclarationLink (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, bool &amp; found, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header, bool localNames)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 747 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcfb957d1b34d6e323a5ae8f8f7c0da3">747</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abcfb957d1b34d6e323a5ae8f8f7c0da3">writeDeclarationLink</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;found,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;header,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> localNames)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#acd75a76f95d8eacddd4afbb7dc8693a2">writeDeclarationLink</a>(ol,found,header,localNames); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#acd75a76f95d8eacddd4afbb7dc8693a2">ClassDef::writeDeclarationLink</a>.
</div>
</div>

### writeDocumentation() {#a236a08389de317adcab69a7ab6e9a37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 753 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a236a08389de317adcab69a7ab6e9a37a">753</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a236a08389de317adcab69a7ab6e9a37a">writeDocumentation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a283ca4e39a593316c8c6c83085088900">writeDocumentation</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a283ca4e39a593316c8c6c83085088900">ClassDef::writeDocumentation</a>.
</div>
</div>

### writeDocumentationForInnerClasses() {#aa63ae9765c16beef2b4a889b0f5d321b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeDocumentationForInnerClasses (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 755 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa63ae9765c16beef2b4a889b0f5d321b">755</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa63ae9765c16beef2b4a889b0f5d321b">writeDocumentationForInnerClasses</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afd404f2052b5c688bf0815741a290842">writeDocumentationForInnerClasses</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afd404f2052b5c688bf0815741a290842">ClassDef::writeDocumentationForInnerClasses</a>.
</div>
</div>

### writeInlineDocumentation() {#a8c919b56012472db7a02ccb01316ccab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeInlineDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 770 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c919b56012472db7a02ccb01316ccab">770</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c919b56012472db7a02ccb01316ccab">writeInlineDocumentation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af59b44de9052b4e62482853fdb7a514a">writeInlineDocumentation</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#af59b44de9052b4e62482853fdb7a514a">ClassDef::writeInlineDocumentation</a>.
</div>
</div>

### writeMemberDeclarations() {#ab287ccfb0386977fce96aa616e9be50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeMemberDeclarations (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp; visitedClasses, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; subTitle=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool showInline=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * inheritedFrom=nullptr, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt2=<a href="/web-doxygen/docs/api/classes/memberlisttype/#a6bba5f5f3ba3a36e97d8d7106001480d">MemberListType::Invalid</a>(), bool invert=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, bool showAlways=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 774 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab287ccfb0386977fce96aa616e9be50e">774</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab287ccfb0386977fce96aa616e9be50e">writeMemberDeclarations</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,<a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp;visitedClasses,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a358d46451cf46a373a32d0c5658b0936">title</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;subTitle=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showInline=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *inheritedFrom=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt2=<a href="/web-doxygen/docs/api/classes/memberlisttype/#a6bba5f5f3ba3a36e97d8d7106001480d">MemberListType::Invalid</a>(),</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> invert=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showAlways=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac598c1ecb31cdb19524cc60cfe312667">writeMemberDeclarations</a>(ol,visitedClasses,lt,<a href="#a358d46451cf46a373a32d0c5658b0936">title</a>,subTitle,showInline,inheritedFrom,lt2,invert,showAlways); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#a6bba5f5f3ba3a36e97d8d7106001480d">MemberListType::Invalid</a>, <a href="#a358d46451cf46a373a32d0c5658b0936">title</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ac598c1ecb31cdb19524cc60cfe312667">ClassDef::writeMemberDeclarations</a>.
</div>
</div>

### writeMemberList() {#afcedf72f74d9a02cd4e29852c1e07ebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeMemberList (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 759 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcedf72f74d9a02cd4e29852c1e07ebe">759</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afcedf72f74d9a02cd4e29852c1e07ebe">writeMemberList</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a30391896721a6454f35d69ef5457080b">writeMemberList</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a30391896721a6454f35d69ef5457080b">ClassDef::writeMemberList</a>.
</div>
</div>

### writeMemberPages() {#a672214abd88e36416d36b390728fc0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeMemberPages (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 757 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a672214abd88e36416d36b390728fc0f4">757</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a672214abd88e36416d36b390728fc0f4">writeMemberPages</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a21e64cf1626ca35924f114aaadac8009">writeMemberPages</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a21e64cf1626ca35924f114aaadac8009">ClassDef::writeMemberPages</a>.
</div>
</div>

### writePageNavigation() {#a190101033114f81cf21225e28525d833}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writePageNavigation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 768 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a190101033114f81cf21225e28525d833">768</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a190101033114f81cf21225e28525d833">writePageNavigation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a8188a9157bac12e715b2a94372a5b59d">writePageNavigation</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a8188a9157bac12e715b2a94372a5b59d">ClassDef::writePageNavigation</a>.
</div>
</div>

### writeQuickMemberLinks() {#a70e4e875c4a4b14689d58f1114ead623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeQuickMemberLinks (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 764 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70e4e875c4a4b14689d58f1114ead623">764</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a70e4e875c4a4b14689d58f1114ead623">writeQuickMemberLinks</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a6f85844c1b5d67ca6110b3c48053bc77">writeQuickMemberLinks</a>(ol,md); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a6f85844c1b5d67ca6110b3c48053bc77">ClassDef::writeQuickMemberLinks</a>.
</div>
</div>

### writeSummaryLinks() {#a2bcc1c98274b691e8709551d753b0a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeSummaryLinks (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 766 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2bcc1c98274b691e8709551d753b0a18">766</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2bcc1c98274b691e8709551d753b0a18">writeSummaryLinks</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a1e4c88be7cbea1cd3c46833f69843612">writeSummaryLinks</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a1e4c88be7cbea1cd3c46833f69843612">ClassDef::writeSummaryLinks</a>.
</div>
</div>

### writeTagFile() {#a076783e77d8c5731d465d196336416fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClassDefAliasImpl::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; ol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 772 of file <a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a076783e77d8c5731d465d196336416fb">772</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a076783e77d8c5731d465d196336416fb">writeTagFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;ol)</span><span class="doxyHighlightKeyword"> const override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a>()-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af5fb9d775ecdb41ff87abcc2eb44f105">writeTagFile</a>(ol); }</span></span></div>

</div>


References <a href="#ab1366e62ee0c1a0e917952eb62b3fcab">getCdAlias</a> and <a href="/web-doxygen/docs/api/classes/classdef/#af5fb9d775ecdb41ff87abcc2eb44f105">ClassDef::writeTagFile</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/classdef-cpp">classdef.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
