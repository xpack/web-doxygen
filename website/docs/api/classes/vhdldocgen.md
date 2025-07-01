---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdldocgen
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `VhdlDocGen` Class Reference

Class for generating documentation specific for VHDL. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class VhdlDocGen { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">src/vhdldocgen.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VhdlClasses { <a href="#a010ab08982f29df8c0f3d3f0f642f0f0">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a010ab08982f29df8c0f3d3f0f642f0f0">VhdlClasses</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ab1504610c798f4924026a48bb4301">convert</a> (Protection prot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987fee1e906fac322dda62613525a8f9">init</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad28f49b99078162fd63bd325db5c2b2b">convertFileNameToClassName</a> (const QCString &amp;name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d0f125a2bffca08e8c52644bf8c6f2">isSubClass</a> (ClassDef *cd, ClassDef *scd, bool followInstances, int level)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c14782849e08d5ef42d9ae8290c18b">getIndexWord</a> (const QCString &amp;, int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a05cf7bd081febd19a0065eed17098">deleteCharRev</a> (QCString &amp;s, char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4bf0d0561d8ef807b56c1f29765713e">deleteAllChars</a> (QCString &amp;s, char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f4758858cac73d07721ea31f42bea8e">parseFuncProto</a> (const QCString &amp;text, QCString &amp;name, QCString &amp;ret, bool doc=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8681769cd2f027fbf46a4836d3825e9">computeVhdlComponentRelations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24155445ad4e0328e60f78bf4a4a41f">findKeyWord</a> (const QCString &amp;word)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad890048820909df255f6ee3f95d6ed80">getPackageName</a> (const QCString &amp;name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a> (const QCString &amp;className, const QCString &amp;memName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00216e37afbb1841a9631a80379b7f0a">findAllPackages</a> (ClassDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358ec24d6f67dee4fb2f983181a314fe">findMemberDef</a> (ClassDef *cd, const QCString &amp;key, MemberListType type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
This function returns the entity|package in which the key (type) is found. <a href="#a358ec24d6f67dee4fb2f983181a314fe">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a> (const QCString &amp;name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765683cbd1cf5a8e7374b64a9ac37d98">findFunction</a> (const QCString &amp;name, const QCString &amp;package)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d4c791af3f2943467c7c7af558d83a">getClassTitle</a> (const ClassDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67f47b8dc11d967ee47e9bda86fff7e0">writeInlineClassLink</a> (const ClassDef *, OutputList &amp;ol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> (MemberDefMutable *mdef, TextStream &amp;tagFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb04cd03e2039ecab3a0a8f31ee4c890">isConstraint</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57efdf5bddd0b36667c8aa21256ebac7">isConfig</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af13dd5eb831c1df008b0fd41928f4b7c">isAlias</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f582b69841bae3ec6f1281604b6f0c8">isLibrary</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c19429669d382581ba37aee5f39278">isGeneric</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73186f5d1ba5e6c11c6f006708da79a6">isPort</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3fdc795bf951ef11221894512b8bc6c">isComponent</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca017e059b8a2972c2cad968800c0564">isPackage</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65218023c4970a90f3bce70938a99781">isEntity</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c3cdcd27394531385ccd8c56257edc1">isConstant</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ab98ceef0a36aea7a15c548ec9aa455">isVType</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57f7d02afdd7034f78894b20e6ff4aa">isSubType</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8808d28bf43d889892a8b6bad0793d7d">isVhdlFunction</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">isProcess</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07199651d2f493ee3afe42975df77efb">isSignal</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc9e668acc7c79f211709e2a0eeccad">isAttribute</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb01b11d2a225ee8d8c43a56862be8b">isSignals</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">isProcedure</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0634a061165ad22c27eef2ac12057d0">isRecord</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0281ffc4e374d27d703419ae289e3b8c">isArchitecture</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4861484cc952d96afcfe277cf958aff0">isUnit</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e9aff43352b39d31806d0616e2c7af">isPackageBody</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877e8a81695500e7ad5ed8d76fdbaffc">isVariable</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac9c26b1b0fb7402cc58acaf569df89">isFile</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069c8ad206be372bd948cc8e964218ed">isGroup</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">isCompInst</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ef68e914c38033a48b6fdac2907689">isMisc</a> (const MemberDef *mdef)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802a7b8116fa1b8b46895c25a32c5677">prepareComment</a> (QCString &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a> (const QCString &amp;, OutputList &amp;ol, const MemberDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a> (const QCString &amp;, OutputList &amp;ol, const MemberDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca249e8052f477d893edfc767948fcf">writeFunctionProto</a> (OutputList &amp;ol, const ArgumentList &amp;al, const MemberDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b60db653850e1be9084b27153e6758">writeProcessProto</a> (OutputList &amp;ol, const ArgumentList &amp;al, const MemberDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab757dead7796d93d5a534ae1c11e69">writeProcedureProto</a> (OutputList &amp;ol, const ArgumentList &amp;al, const MemberDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee87f24daab068f794ea908f33a86c3f">writeFuncProcDocu</a> (const MemberDef *mdef, OutputList &amp;ol, const ArgumentList &amp;al, bool type=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d4d0c22eac6e04a900b847c702a157">writeRecordProto</a> (const MemberDef *mdef, OutputList &amp;ol, const ArgumentList &amp;al)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a> (const MemberDef *mdef, const Definition *d, OutputList &amp;ol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99c6269bf6155f83a12ab796edd4acf">writeVhdlDeclarations</a> (const MemberList *, OutputList &amp;, const GroupDef *, const ClassDef *, const FileDef *, const NamespaceDef *, const ModuleDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a> (MemberDefMutable *mdef, OutputList &amp;ol, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *mod, bool inGroup)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc394d10d64e221682e9619eef74fde5">writePlainVHDLDeclarations</a> (const MemberList *ml, OutputList &amp;ol, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *mod, VhdlSpecifier specifier)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b65f506a9133e6bbc8e8665e2901625">writeVHDLDeclarations</a> (const MemberList *ml, OutputList &amp;ol, const ClassDef *cd, const NamespaceDef *nd, const FileDef *fd, const GroupDef *gd, const ModuleDef *mod, const QCString &amp;title, const QCString &amp;subtitle, bool showEnumValues, VhdlSpecifier type)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac2f4932405d6a1773bea6eb84885ec">writeClassType</a> (const ClassDef *, OutputList &amp;ol, QCString &amp;cname)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1876213c101b31a44336d48b6b33e9ec">convertArgumentListToString</a> (const ArgumentList &amp;al, bool f)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6524e8718f3f956610df4dfc71be204c">getProcessNumber</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e65f831a03ff54d13240da96843cd60">getRecordNumber</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4458b0e27e9b97db254d082d1487d2">getClassName</a> (const ClassDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a0f5ef9f02fff9ab8ad1b70709cd887">isNumber</a> (const std::string &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4325f5840fe29089b4d3ea4b8c8b0fef">getProtectionName</a> (int prot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a78fda163916d84fc8067d577f9bf3">parseUCF</a> (const QCString &amp;input, Entry *entity, const QCString &amp;f, bool vendor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13551a402d45747996978c41713af58">findArchitecture</a> (const ClassDef *cd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084d328a5d3f98e4846a0b0f1499d151">correctMemberProperties</a> (MemberDefMutable *md)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c145b8082cd9865b477141ab58dcb20">writeSource</a> (const MemberDef *mdef, OutputList &amp;ol, const QCString &amp;cname)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4584e2262b81979f6d9b88c070c78753">parseForConfig</a> (QCString &amp;entity, QCString &amp;arch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411f4f042964d6e24c0376f1378da1a8">parseForBinding</a> (QCString &amp;entity, QCString &amp;arch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4892ca19efc7055ce4b5c3004ce550ed">addBaseClass</a> (ClassDef *cd, ClassDef *ent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f3686f7bccb7f7d9ef304724198661">findVhdlClass</a> (const QCString &amp;className)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2de08afddfa24b4a037c36ac329185ff">createFlowChart</a> (const MemberDef *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7808cdf56c299daceed3212b65b8a031">setFlowMember</a> (const MemberDef *flowMember)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b2126cfa1cf80aeab17ae40d673d67">getFlowMember</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7df19eb23b1532bc1d05c7ffe6cd76">isVhdlClass</a> (const Entry *cu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e16e249eaf1829c224b054ff743ce7">resetCodeVhdlParserState</a> ()</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5659d6cb4369b41809c279d006b44c">findAllArchitectures</a> (std::vector&lt; QCString &gt; &amp;ql, const ClassDef *cd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12798636d1b8304132df8d68d293d6d2">compareArgList</a> (const ArgumentList &amp;, const ArgumentList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e37fa3f47b3d836813a1cf2a7fef036">writeVhdlLink</a> (const ClassDef *cdd, OutputList &amp;ol, QCString &amp;type, QCString &amp;name, QCString &amp;beh)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdbd7a613237d2a86532bfe548209a1d">writeStringLink</a> (const MemberDef *mdef, QCString mem, OutputList &amp;ol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b6f99e6d3882e29a2a4ff830741c77">writeRecUnitDocu</a> (const MemberDef *md, OutputList &amp;ol, QCString largs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad197f46fa25960c771c0e8b897ded06d">writeRecordUnit</a> (QCString &amp;largs, QCString &amp;ltype, OutputList &amp;ol, MemberDefMutable *mdef)</td>
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

Class for generating documentation specific for VHDL.

Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>.

<div class="doxySectionDef">

## Enumerations

### VhdlClasses {#a010ab08982f29df8c0f3d3f0f642f0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum VhdlDocGen::VhdlClasses </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENTITYCLASS<a id="a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACKBODYCLASS<a id="a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARCHITECTURECLASS<a id="a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PACKAGECLASS<a id="a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>,         </span><span class="doxyHighlightComment">// Overlays: Public</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>,       </span><span class="doxyHighlightComment">// Overlays: Protected</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">ARCHITECTURECLASS</a>,   </span><span class="doxyHighlightComment">// Overlays: Private</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">PACKAGECLASS</a>         </span><span class="doxyHighlightComment">// Overlays: Package</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addBaseClass() {#a4892ca19efc7055ce4b5c3004ce550ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::addBaseClass (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * ent)</td>
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



Declaration at line 202 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2356 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4892ca19efc7055ce4b5c3004ce550ed">2356</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>(<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd,<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/classdef-h/#a173eca34c5a9473651c05a4d92c355fe">BaseClassList</a> bcl = cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : bcl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ccd = bcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ccd==ent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n = bcd.usedName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = n.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(i&lt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">        bcd.usedName.append(</span><span class="doxyHighlightStringLiteral">"(2)"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> <a href="/web-doxygen/docs/api/namespaces/reg">reg</a>(R</span><span class="doxyHighlightStringLiteral">"(\d+)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s=n.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> r=n.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(n.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      std::string t=r.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      <a href="#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>(r,</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>(r,</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">      r.<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(r.<a href="/web-doxygen/docs/api/classes/qcstring/#a100a41fa6ba318b8b2ace175cd20f1eb">toInt</a>()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/namespaces/reg/#ab6913d787be9fe9992c8804af851fab9">reg::replace</a>(t, <a href="/web-doxygen/docs/api/namespaces/reg">reg</a>, r.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">      s.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(t.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">      bcd.usedName=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">      bcd.templSpecifiers=t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span><span class="doxyLineContent"><span class="doxyHighlight">  cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a053f323d6b837a81cd86a82ce3c4d4a4">updateBaseClasses</a>(bcl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="#ae4bf0d0561d8ef807b56c1f29765713e">deleteAllChars</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#ab6913d787be9fe9992c8804af851fab9">reg::replace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a100a41fa6ba318b8b2ace175cd20f1eb">QCString::toInt</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a053f323d6b837a81cd86a82ce3c4d4a4">ClassDef::updateBaseClasses</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>.
</div>
</div>

### computeVhdlComponentRelations() {#ab8681769cd2f027fbf46a4836d3825e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::computeVhdlComponentRelations ()</td>
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



Declaration at line 107 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2154 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8681769cd2f027fbf46a4836d3825e9">2154</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8681769cd2f027fbf46a4836d3825e9">VhdlDocGen::computeVhdlComponentRelations</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> entity,arch,inst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cur : <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a182203e7e4b8c08526f2bda22d394855">getVhdlInstList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cur-&gt;isStatic ) </span><span class="doxyHighlightComment">//  was bind</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cur-&gt;includeName==</span><span class="doxyHighlightStringLiteral">"entity"</span><span class="doxyHighlight"> || cur-&gt;includeName==</span><span class="doxyHighlightStringLiteral">"component"</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">      entity=cur-&gt;includeName+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+cur-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> rr=<a href="#a411f4f042964d6e24c0376f1378da1a8">VhdlDocGen::parseForBinding</a>(entity,arch);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cur-&gt;includeName.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">      entity=cur-&gt;type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *classEntity= <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(<a href="#a34f3686f7bccb7f7d9ef304724198661">VhdlDocGen::findVhdlClass</a>(entity));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">    inst=<a href="#ae1c14782849e08d5ef42d9ae8290c18b">VhdlDocGen::getIndexWord</a>(cur-&gt;args,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *cd=<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(inst));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdefmutable">ClassDefMutable</a> *ar=<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(cur-&gt;args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>(classEntity,ar,cd,cur);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="#a34f3686f7bccb7f7d9ef304724198661">findVhdlClass</a>, <a href="#ae1c14782849e08d5ef42d9ae8290c18b">getIndexWord</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a182203e7e4b8c08526f2bda22d394855">getVhdlInstList</a>, <a href="#a411f4f042964d6e24c0376f1378da1a8">parseForBinding</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.
</div>
</div>

### convert() {#ab1ab1504610c798f4924026a48bb4301}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlClasses VhdlDocGen::convert (<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot)</td>
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



Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1ab1504610c798f4924026a48bb4301">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a010ab08982f29df8c0f3d3f0f642f0f0">VhdlClasses</a> <a href="#ab1ab1504610c798f4924026a48bb4301">convert</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (prot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Public:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Protected: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Private:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">ARCHITECTURECLASS</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Package:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">PACKAGECLASS</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">ARCHITECTURECLASS</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">PACKAGECLASS</a> and <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a2c46ad2d91b685cb40efdc4ffeb85e61">DotGfxHierarchyTable::addClassList</a>, <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a>, <a href="#a2c4458b0e27e9b97db254d082d1487d2">getClassName</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#afd3e992f2869f52cc7b033a65ccc2d1a">ClassDefImpl::setProtection</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="#a67f47b8dc11d967ee47e9bda86fff7e0">writeInlineClassLink</a> and <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### convertArgumentListToString() {#a1876213c101b31a44336d48b6b33e9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::convertArgumentListToString (const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, bool f)</td>
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



Declaration at line 184 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1156 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1876213c101b31a44336d48b6b33e9ec">1156</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1876213c101b31a44336d48b6b33e9ec">VhdlDocGen::convertArgumentListToString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> func)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argString;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;arg : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sem) argString.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (func)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=arg.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=arg.type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=arg.defval+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=arg.name+</span><span class="doxyHighlightStringLiteral">" :"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=arg.attrib+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">      argString+=arg.type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">    sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> argString;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### convertFileNameToClassName() {#ad28f49b99078162fd63bd325db5c2b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::convertFileNameToClassName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1899 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad28f49b99078162fd63bd325db5c2b2b">1899</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad28f49b99078162fd63bd325db5c2b2b">VhdlDocGen::convertFileNameToClassName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n=name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">  n=n.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,6);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">((i=n.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">))&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">    n=n.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(i,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">((i=n.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">))&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">    n=n.<a href="/web-doxygen/docs/api/classes/qcstring/#ab536413a2bab9fe536e82067a3f164ed">replace</a>(i,2,</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#ab536413a2bab9fe536e82067a3f164ed">QCString::replace</a>.
</div>
</div>

### correctMemberProperties() {#a084d328a5d3f98e4846a0b0f1499d151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::correctMemberProperties (<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> * md)</td>
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



Declaration at line 196 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1214 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a084d328a5d3f98e4846a0b0f1499d151">1214</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a084d328a5d3f98e4846a0b0f1499d151">VhdlDocGen::correctMemberProperties</a>(<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>()==</span><span class="doxyHighlightStringLiteral">"package"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">setVhdlSpecifiers</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>()==</span><span class="doxyHighlightStringLiteral">"configuration"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">setVhdlSpecifiers</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">VhdlSpecifier::CONFIG</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>()==</span><span class="doxyHighlightStringLiteral">"library"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">setVhdlSpecifiers</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>()==</span><span class="doxyHighlightStringLiteral">"use"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">setVhdlSpecifiers</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()==</span><span class="doxyHighlightStringLiteral">"misc"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">setVhdlSpecifiers</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()==</span><span class="doxyHighlightStringLiteral">"ucf_const"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">    md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">setVhdlSpecifiers</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mm=md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mm&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">      md-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a22b8c8f07db7eb0435d27a79d2d32655">setName</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(mm));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">VhdlSpecifier::TYPE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> largs=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bRec=largs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"record"</span><span class="doxyHighlight">) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bUnit=largs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"units"</span><span class="doxyHighlight">) ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bRec || bUnit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">      md-&gt;<a href="/web-doxygen/docs/api/classes/memberdefmutable/#abbad7cf3e7d64daf5bce70f56038e59d">setType</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">CONFIG</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">INSTANTIATION</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">LIBRARY</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">MISCELLANEOUS</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a22b8c8f07db7eb0435d27a79d2d32655">DefinitionMutable::setName</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#abbad7cf3e7d64daf5bce70f56038e59d">MemberDefMutable::setType</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4c3e0a615dd21afcf98e801abc3ffb43">MemberDefMutable::setVhdlSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">TYPE</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">UCF\_CONST</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">USE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3d2bdb9a2c2b81909c7835cece01d448">vhdlCorrectMemberProperties</a>.
</div>
</div>

### createFlowChart() {#a2de08afddfa24b4a037c36ac329185ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::createFlowChart (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 206 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2402 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2de08afddfa24b4a037c36ac329185ff">2402</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2de08afddfa24b4a037c36ac329185ff">VhdlDocGen::createFlowChart</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> codeFragment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mm=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((mm=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a180fa3a09e24b54ffad20ec6bcef86da">findMemFlow</a>(mdef))!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// don't create the same flowchart twice</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7808cdf56c299daceed3212b65b8a031">VhdlDocGen::setFlowMember</a>(mm);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3ab79d2d52d43f3c22214135a989f88d">mdList</a>.push_back(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//fprintf(stderr,"\n create flow mem %s %p\n",qPrint(mdef-&gt;name()),mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> actualStart= mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> actualEnd=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a>* fd=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b=<a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>( fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(), </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, actualStart, actualEnd, codeFragment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!b) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parser { <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>-&gt;getOutlineParser(</span><span class="doxyHighlightStringLiteral">".vhd"</span><span class="doxyHighlight">) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7808cdf56c299daceed3212b65b8a031">VhdlDocGen::setFlowMember</a>(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; root = std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> filesInSameTu;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;parseInput(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,codeFragment.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),root,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a180fa3a09e24b54ffad20ec6bcef86da">findMemFlow</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3ab79d2d52d43f3c22214135a989f88d">mdList</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a> and <a href="#a7808cdf56c299daceed3212b65b8a031">setFlowMember</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>.
</div>
</div>

### deleteAllChars() {#ae4bf0d0561d8ef807b56c1f29765713e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::deleteAllChars (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, char c)</td>
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



Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 727 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae4bf0d0561d8ef807b56c1f29765713e">727</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(c,-1,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (index &gt; -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">    s = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(index,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    index=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(c,-1,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>.

Referenced by <a href="#a4892ca19efc7055ce4b5c3004ce550ed">addBaseClass</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>.
</div>
</div>

### deleteCharRev() {#a82a05cf7bd081febd19a0065eed17098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::deleteCharRev (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, char c)</td>
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




deletes a char backwards in a string

Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 716 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82a05cf7bd081febd19a0065eed17098">716</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a82a05cf7bd081febd19a0065eed17098">VhdlDocGen::deleteCharRev</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(c,-1,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index &gt; -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">    s = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(index,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a9f4758858cac73d07721ea31f42bea8e">parseFuncProto</a>.
</div>
</div>

### findAllPackages() {#a00216e37afbb1841a9631a80379b7f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::findAllPackages (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cdef)</td>
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




finds all included packages of an Entity or Package

Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 362 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a00216e37afbb1841a9631a80379b7f0a">362</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>( <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g_vhdlMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.find(cdef)!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.end()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;ClassDef*&gt; cList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *mem=cdef-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::VariableMembers());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *mem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aca017e059b8a2972c2cad968800c0564">VhdlDocGen::isPackage</a>(md))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd=<a href="#ad890048820909df255f6ee3f95d6ed80">VhdlDocGen::getPackageName</a>(md-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">          cList.push_back(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.emplace(cdef,cList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span><span class="doxyHighlightComment">//for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// findAllPackages</span></span></div>

</div>


References <a href="#a00216e37afbb1841a9631a80379b7f0a">findAllPackages</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g\_packages</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g\_vhdlMutex</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">ClassDef::getMemberList</a>, <a href="#ad890048820909df255f6ee3f95d6ed80">getPackageName</a> and <a href="#aca017e059b8a2972c2cad968800c0564">isPackage</a>.

Referenced by <a href="#a00216e37afbb1841a9631a80379b7f0a">findAllPackages</a> and <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a>.
</div>
</div>

### findArchitecture() {#ab13551a402d45747996978c41713af58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ClassDef * VhdlDocGen::findArchitecture (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



Declaration at line 194 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 549 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab13551a402d45747996978c41713af58">549</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* <a href="#ab13551a402d45747996978c41713af58">VhdlDocGen::findArchitecture</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;citer : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> jj=citer-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(jj.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ql[0])==nn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> citer.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### findFunction() {#a765683cbd1cf5a8e7374b64a9ac37d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * VhdlDocGen::findFunction (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; funcname, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; package)</td>
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




returns the function with the matching argument list is called in <a href="/web-doxygen/docs/api/files/src/vhdlcode-l">vhdlcode.l</a>

Declaration at line 119 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 392 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a765683cbd1cf5a8e7374b64a9ac37d98">392</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* <a href="#a765683cbd1cf5a8e7374b64a9ac37d98">VhdlDocGen::findFunction</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; funcname, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; package)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cdef=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(package);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cdef==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *mem=cdef-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubMethods());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mdef : *mem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mname=mdef-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(mdef) || <a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(mdef)) &amp;&amp; (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ac853f7c85a98e5ef7040604706c7b80c">compareString</a>(funcname,mname)==0))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span><span class="doxyHighlightComment">//for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">} </span><span class="doxyHighlightComment">//findFunction</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ac853f7c85a98e5ef7040604706c7b80c">compareString</a>, <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">ClassDef::getMemberList</a>, <a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">isProcedure</a> and <a href="#a8808d28bf43d889892a8b6bad0793d7d">isVhdlFunction</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#adb5cfe08b5887df4a026299543638531">writeFuncProto</a>.
</div>
</div>

### findKeyWord() {#af24155445ad4e0328e60f78bf4a4a41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * VhdlDocGen::findKeyWord (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; kw)</td>
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




returns the color of a keyword

Declaration at line 109 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af24155445ad4e0328e60f78bf4a4a41f">180</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; kw)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string word=kw.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (word.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a35879b543355733a32a4f8f31c84015b">g_vhdlKeyWordSet0</a>.find(word)!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a35879b543355733a32a4f8f31c84015b">g_vhdlKeyWordSet0</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"keywordflow"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#afc785c02b3f5126f0cf9a9365fd5539d">g_vhdlKeyWordSet1</a>.find(word)!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#afc785c02b3f5126f0cf9a9365fd5539d">g_vhdlKeyWordSet1</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aa5bbf68b43e28bc0d97f5eaa113dba61">g_vhdlKeyWordSet2</a>.find(word)!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aa5bbf68b43e28bc0d97f5eaa113dba61">g_vhdlKeyWordSet2</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"vhdllogic"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ad1d25df0469c1e88bd16bcae72325430">g_vhdlKeyWordSet3</a>.find(word)!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ad1d25df0469c1e88bd16bcae72325430">g_vhdlKeyWordSet3</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"vhdlkeyword"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a35879b543355733a32a4f8f31c84015b">g\_vhdlKeyWordSet0</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#afc785c02b3f5126f0cf9a9365fd5539d">g\_vhdlKeyWordSet1</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aa5bbf68b43e28bc0d97f5eaa113dba61">g\_vhdlKeyWordSet2</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ad1d25df0469c1e88bd16bcae72325430">g\_vhdlKeyWordSet3</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a64ea38c6553eebe39c034c704bcc2eeb">writeColoredWord</a>, <a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a>, <a href="#a9ca249e8052f477d893edfc767948fcf">writeFunctionProto</a> and <a href="#a4ab757dead7796d93d5a534ae1c11e69">writeProcedureProto</a>.
</div>
</div>

### findMember() {#ab6898e9270508ce95ad8ebb5ecbedaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * VhdlDocGen::findMember (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; className, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memName)</td>
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



Declaration at line 112 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">217</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; className, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; memName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g_vhdlMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ecd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(className);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("VhdlDocGen::findMember(%s,%s)=%p\n",qPrint(className),qPrint(memName),cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  mdef=<a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(cd,memName,MemberListType::VariableMembers());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  mdef=<a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(cd,memName,MemberListType::PubMethods());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// nothing found so far</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if we are an architecture or package body search in entity</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>())==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">VhdlDocGen::ARCHITECTURECLASS</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>())==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// searching upper/lower case names</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tt=d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    ecd =<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(tt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ecd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      tt=tt.<a href="/web-doxygen/docs/api/classes/qcstring/#a113ff6fe5b14585eebdcafbf2fe88cc4">upper</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      ecd =<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(tt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ecd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      tt=tt.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      ecd =<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(tt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ecd) </span><span class="doxyHighlightComment">//d &amp;&amp; d-&gt;definitionType()==Definition::TypeClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//ClassDef *ecd = (ClassDef*)d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef=<a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(ecd,memName,MemberListType::VariableMembers());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef=<a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(cd,memName,MemberListType::PubMethods());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>())==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">VhdlDocGen::ARCHITECTURECLASS</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>())==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tt=d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *acd =<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(tt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!acd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      tt=tt.<a href="/web-doxygen/docs/api/classes/qcstring/#a113ff6fe5b14585eebdcafbf2fe88cc4">upper</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      acd =<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(tt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!acd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      tt=tt.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      acd =<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(tt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (acd) </span><span class="doxyHighlightComment">//d &amp;&amp; d-&gt;definitionType()==Definition::TypeClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.find(acd)==<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>(acd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    ecd=cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.find(ecd)==<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.end()) <a href="#a00216e37afbb1841a9631a80379b7f0a">VhdlDocGen::findAllPackages</a>(ecd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ecd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> cList_it = <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.find(ecd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cList_it!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cdp : cList_it-&gt;second)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef=<a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(cdp,memName,MemberListType::VariableMembers());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">        mdef=<a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(cdp,memName,MemberListType::PubMethods());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">//findMember</span></span></div>

</div>


References <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">ARCHITECTURECLASS</a>, <a href="#ab1ab1504610c798f4924026a48bb4301">convert</a>, <a href="#a00216e37afbb1841a9631a80379b7f0a">findAllPackages</a>, <a href="#a358ec24d6f67dee4fb2f983181a314fe">findMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g\_packages</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g\_vhdlMutex</a>, <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a113ff6fe5b14585eebdcafbf2fe88cc4">QCString::upper</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a0cf2ae6bf35f920987bb1804a5fed8b7">generateMemLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="#abdbd7a613237d2a86532bfe548209a1d">writeStringLink</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### findMemberDef() {#a358ec24d6f67dee4fb2f983181a314fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * VhdlDocGen::findMemberDef (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> type)</td>
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

This function returns the entity|package in which the key (type) is found.

Declaration at line 115 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 318 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a358ec24d6f67dee4fb2f983181a314fe">318</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* <a href="#a358ec24d6f67dee4fb2f983181a314fe">VhdlDocGen::findMemberDef</a>(<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; key,<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g_vhdlMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> keyType=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a86061734049a0f06f636e4b51e0f1ac2">symbolName</a>()+</span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">+key;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("\n %s | %s | %s",qPrint(cd-&gt;symbolName()),key.data(,),qPrint(keyType));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.find(keyType.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::find(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g_classList</a>.begin(),<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g_classList</a>.end(),cd)!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g_classList</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g_classList</a>.push_back(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//int l=ml-&gt;count();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    fprintf(stderr,"\n loading entity %s %s: %d",qPrint(cd-&gt;symbolName()),qPrint(keyType),l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tkey=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a86061734049a0f06f636e4b51e0f1ac2">symbolName</a>()+</span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">+md-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.find(tkey.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.emplace(tkey.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">  it=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.find(keyType.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">//findMemberDef</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g\_classList</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g\_varMap</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g\_vhdlMutex</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">ClassDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/definition/#a86061734049a0f06f636e4b51e0f1ac2">Definition::symbolName</a>.

Referenced by <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a>.
</div>
</div>

### findVhdlClass() {#a34f3686f7bccb7f7d9ef304724198661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * VhdlDocGen::findVhdlClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; className)</td>
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



Declaration at line 203 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2128 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34f3686f7bccb7f7d9ef304724198661">2128</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* <a href="#a34f3686f7bccb7f7d9ef304724198661">VhdlDocGen::findVhdlClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;className )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(className.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(cd-&gt;name()))==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cd.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight"> }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>.

Referenced by <a href="#ab8681769cd2f027fbf46a4836d3825e9">computeVhdlComponentRelations</a>.
</div>
</div>

### formatString() {#aacccadab8f7d60dc0e4b2892ea724c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::formatString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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




inserts white spaces for better readings and writes a colored string to the output

Declaration at line 157 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 851 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacccadab8f7d60dc0e4b2892ea724c2b">851</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs = s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"is"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"IS"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"of"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"OF"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> j=0;j&lt;len;j++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=qcs[j];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> b=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;0) b=qcs[j-1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">|| c==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">  || c==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight"> ) </span><span class="doxyHighlightComment">// || (c==':' &amp;&amp; b!='=')) // || (c=='=' &amp;&amp; b!='&gt;'))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;=index &amp;&amp; temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(index-1) != </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">        temp+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">      temp+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">      temp+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (b==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// := operator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">        temp.<a href="/web-doxygen/docs/api/classes/qcstring/#ab536413a2bab9fe536e82067a3f164ed">replace</a>(index-1,1,</span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">        temp+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// = operator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">        temp+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">        temp+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">        temp+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">      temp+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">    index=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">// for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">  temp=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// printf("\n [%s]",qPrint(qcs));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>(temp,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab536413a2bab9fe536e82067a3f164ed">QCString::replace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a>.

Referenced by <a href="#a9ca249e8052f477d893edfc767948fcf">writeFunctionProto</a>, <a href="#a4ab757dead7796d93d5a534ae1c11e69">writeProcedureProto</a>, <a href="#ad197f46fa25960c771c0e8b897ded06d">writeRecordUnit</a>, <a href="#a81b6f99e6d3882e29a2a4ff830741c77">writeRecUnitDocu</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>, <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### getClass() {#aa09142ff1ca07603f8bb2150ce9ceab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * VhdlDocGen::getClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Declaration at line 118 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa09142ff1ca07603f8bb2150ce9ceab5">201</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">VhdlDocGen::getClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>-&gt;find(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(name).<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>.

Referenced by <a href="#a765683cbd1cf5a8e7374b64a9ac37d98">findFunction</a>, <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a>, <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a0cf2ae6bf35f920987bb1804a5fed8b7">generateMemLink</a>, <a href="#ad890048820909df255f6ee3f95d6ed80">getPackageName</a>, <a href="#a67f47b8dc11d967ee47e9bda86fff7e0">writeInlineClassLink</a> and <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### getClassName() {#a2c4458b0e27e9b97db254d082d1487d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::getClassName (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



Declaration at line 188 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 446 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c4458b0e27e9b97db254d082d1487d2">446</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>())==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    temp=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">    temp.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">className</a>(),</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">ClassDef::className</a>, <a href="#ab1ab1504610c798f4924026a48bb4301">convert</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="#ad5d4c791af3f2943467c7c7af558d83a">getClassTitle</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a> and <a href="#a0ac2f4932405d6a1773bea6eb84885ec">writeClassType</a>.
</div>
</div>

### getClassTitle() {#ad5d4c791af3f2943467c7c7af558d83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::getClassTitle (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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




returns the class title+ref

Declaration at line 121 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 434 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5d4c791af3f2943467c7c7af558d83a">434</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad5d4c791af3f2943467c7c7af558d83a">VhdlDocGen::getClassTitle</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pageTitle;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  pageTitle=<a href="#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  pageTitle+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">  pageTitle+=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>(cd),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> pageTitle;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">} </span><span class="doxyHighlightComment">// getClassTitle</span></span></div>

</div>


References <a href="#a2c4458b0e27e9b97db254d082d1487d2">getClassName</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator\_vhdlType</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#aad52021f24ded4afff433ac446dfc545">ClassDefImpl::title</a>.
</div>
</div>

### getFlowMember() {#a12b2126cfa1cf80aeab17ae40d673d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MemberDef * VhdlDocGen::getFlowMember ()</td>
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



Declaration at line 210 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12b2126cfa1cf80aeab17ae40d673d67">82</a></span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* <a href="#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a591d0ef44da80f3a2f87515755126295">VHDLOutlineParser::addVhdlType</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#aaadfeca7904b4d69db2cda56d753d7a6">FlowChart::convertNameToFileName</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab36fc7f90b85f9a369604444f3a6e203">VHDLOutlineParser::createFlow</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad52018c3c0f56dc9cfdfad34b45fae26">VHDLOutlineParser::handleFlowComment</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9ddf7f6aff23849c4bbb90afbabd38c1">FlowChart::moveToPrevLevel</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a6b88a70b1cfd1bfcea94a62ec57d8741">HtmlDocVisitor::operator()</a>.
</div>
</div>

### getIndexWord() {#ae1c14782849e08d5ef42d9ae8290c18b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::getIndexWord (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; c, int index)</td>
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



Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 684 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1c14782849e08d5ef42d9ae8290c18b">684</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae1c14782849e08d5ef42d9ae8290c18b">VhdlDocGen::getIndexWord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;c,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> <a href="/web-doxygen/docs/api/namespaces/reg">reg</a>(R</span><span class="doxyHighlightStringLiteral">"([\s:|])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(c.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="/web-doxygen/docs/api/namespaces/reg">reg</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index &lt; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(ql.size()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ql[index]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#ab8681769cd2f027fbf46a4836d3825e9">computeVhdlComponentRelations</a> and <a href="#a9f4758858cac73d07721ea31f42bea8e">parseFuncProto</a>.
</div>
</div>

### getPackageName() {#ad890048820909df255f6ee3f95d6ed80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef * VhdlDocGen::getPackageName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad890048820909df255f6ee3f95d6ed80">207</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* <a href="#ad890048820909df255f6ee3f95d6ed80">VhdlDocGen::getPackageName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>.

Referenced by <a href="#a00216e37afbb1841a9631a80379b7f0a">findAllPackages</a>.
</div>
</div>

### getProcessNumber() {#a6524e8718f3f956610df4dfc71be204c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::getProcessNumber ()</td>
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




returns the next number of an anonymous process

Declaration at line 185 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 756 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6524e8718f3f956610df4dfc71be204c">756</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6524e8718f3f956610df4dfc71be204c">VhdlDocGen::getProcessNumber</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> stringCounter;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs(</span><span class="doxyHighlightStringLiteral">"PROCESS_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buf[8];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(buf,8,</span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">,stringCounter++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(&amp;buf[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>.
</div>
</div>

### getProtectionName() {#a4325f5840fe29089b4d3ea4b8c8b0fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::getProtectionName (int prot)</td>
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



Declaration at line 190 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 698 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4325f5840fe29089b4d3ea4b8c8b0fef">698</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4325f5840fe29089b4d3ea4b8c8b0fef">VhdlDocGen::getProtectionName</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prot==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"entity"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prot==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">VhdlDocGen::ARCHITECTURECLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"architecture"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prot==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">VhdlDocGen::PACKAGECLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"package"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (prot==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"package body"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">ARCHITECTURECLASS</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">PACKAGECLASS</a> and <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>.
</div>
</div>

### getRecordNumber() {#a2e65f831a03ff54d13240da96843cd60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::getRecordNumber ()</td>
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




returns the next number of a record|unit member

Declaration at line 186 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 744 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e65f831a03ff54d13240da96843cd60">744</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buf[12];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(buf,12,</span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a56d899e3d331a47d8c765340997d0207">recordCounter</a>++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs(&amp;buf[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a56d899e3d331a47d8c765340997d0207">recordCounter</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>.
</div>
</div>

### init() {#a987fee1e906fac322dda62613525a8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::init ()</td>
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



Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a987fee1e906fac322dda62613525a8f9">173</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a987fee1e906fac322dda62613525a8f9">VhdlDocGen::init</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>.
</div>
</div>

### isAlias() {#af13dd5eb831c1df008b0fd41928f4b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isAlias (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 128 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2446 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af13dd5eb831c1df008b0fd41928f4b7c">2446</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af13dd5eb831c1df008b0fd41928f4b7c">VhdlDocGen::isAlias</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">VhdlSpecifier::ALIAS</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">ALIAS</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isArchitecture() {#a0281ffc4e374d27d703419ae289e3b8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isArchitecture (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 145 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2480 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0281ffc4e374d27d703419ae289e3b8c">2480</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0281ffc4e374d27d703419ae289e3b8c">VhdlDocGen::isArchitecture</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">VhdlSpecifier::ARCHITECTURE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">ARCHITECTURE</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.
</div>
</div>

### isAttribute() {#a2dc9e668acc7c79f211709e2a0eeccad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isAttribute (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 141 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2472 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2dc9e668acc7c79f211709e2a0eeccad">2472</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2dc9e668acc7c79f211709e2a0eeccad">VhdlDocGen::isAttribute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">VhdlSpecifier::ATTRIBUTE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">ATTRIBUTE</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isCompInst() {#ab9e42b2cf2d969dcc943ec355d4fa6b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isCompInst (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 151 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2492 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">2492</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">INSTANTIATION</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### isComponent() {#ad3fdc795bf951ef11221894512b8bc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isComponent (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2454 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3fdc795bf951ef11221894512b8bc6c">2454</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad3fdc795bf951ef11221894512b8bc6c">VhdlDocGen::isComponent</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">VhdlSpecifier::COMPONENT</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">COMPONENT</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### isConfig() {#a57efdf5bddd0b36667c8aa21256ebac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isConfig (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 127 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2444 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57efdf5bddd0b36667c8aa21256ebac7">2444</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a57efdf5bddd0b36667c8aa21256ebac7">VhdlDocGen::isConfig</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">VhdlSpecifier::CONFIG</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">CONFIG</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### isConstant() {#a2c3cdcd27394531385ccd8c56257edc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isConstant (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 135 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2460 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c3cdcd27394531385ccd8c56257edc1">2460</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2c3cdcd27394531385ccd8c56257edc1">VhdlDocGen::isConstant</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">VhdlSpecifier::CONSTANT</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">CONSTANT</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isConstraint() {#adb04cd03e2039ecab3a0a8f31ee4c890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isConstraint (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2442 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb04cd03e2039ecab3a0a8f31ee4c890">2442</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adb04cd03e2039ecab3a0a8f31ee4c890">VhdlDocGen::isConstraint</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">UCF\_CONST</a>.

Referenced by <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isEntity() {#a65218023c4970a90f3bce70938a99781}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isEntity (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 134 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2458 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a65218023c4970a90f3bce70938a99781">2458</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a65218023c4970a90f3bce70938a99781">VhdlDocGen::isEntity</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">VhdlSpecifier::ENTITY</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">ENTITY</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isFile() {#a7ac9c26b1b0fb7402cc58acaf569df89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isFile (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 149 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2488 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ac9c26b1b0fb7402cc58acaf569df89">2488</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7ac9c26b1b0fb7402cc58acaf569df89">VhdlDocGen::isFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VhdlSpecifier::VFILE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VFILE</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isGeneric() {#ae3c19429669d382581ba37aee5f39278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isGeneric (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2450 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3c19429669d382581ba37aee5f39278">2450</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae3c19429669d382581ba37aee5f39278">VhdlDocGen::isGeneric</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">GENERIC</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isGroup() {#a069c8ad206be372bd948cc8e964218ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isGroup (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 150 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2490 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a069c8ad206be372bd948cc8e964218ed">2490</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a069c8ad206be372bd948cc8e964218ed">VhdlDocGen::isGroup</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">VhdlSpecifier::GROUP</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">GROUP</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isLibrary() {#a3f582b69841bae3ec6f1281604b6f0c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isLibrary (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 129 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2448 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f582b69841bae3ec6f1281604b6f0c8">2448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3f582b69841bae3ec6f1281604b6f0c8">VhdlDocGen::isLibrary</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">LIBRARY</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isMisc() {#a55ef68e914c38033a48b6fdac2907689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isMisc (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 152 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2494 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55ef68e914c38033a48b6fdac2907689">2494</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a55ef68e914c38033a48b6fdac2907689">VhdlDocGen::isMisc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">MISCELLANEOUS</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### isNumber() {#a6a0f5ef9f02fff9ab8ad1b70709cd887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isNumber (const std::string &amp; s)</td>
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




returns TRUE if this string is a number

Declaration at line 189 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 839 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a0f5ef9f02fff9ab8ad1b70709cd887">839</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6a0f5ef9f02fff9ab8ad1b70709cd887">VhdlDocGen::isNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string&amp; s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> regg(R</span><span class="doxyHighlightStringLiteral">"([0-9][0-9eEfFbBcCdDaA_.#+?xXzZ-]*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>(s,regg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// isNumber</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#ab09e45c115a5beefe878b915613bd3a3">checkVhdlString</a>, <a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a> and <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#a5ab4cb556cb2bcbce39b40bbe297fd1d">writeWord</a>.
</div>
</div>

### isPackage() {#aca017e059b8a2972c2cad968800c0564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isPackage (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 133 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2456 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca017e059b8a2972c2cad968800c0564">2456</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aca017e059b8a2972c2cad968800c0564">VhdlDocGen::isPackage</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">USE</a>.

Referenced by <a href="#a00216e37afbb1841a9631a80379b7f0a">findAllPackages</a>, <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isPackageBody() {#ab6e9aff43352b39d31806d0616e2c7af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isPackageBody (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 147 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2484 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6e9aff43352b39d31806d0616e2c7af">2484</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab6e9aff43352b39d31806d0616e2c7af">VhdlDocGen::isPackageBody</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">VhdlSpecifier::PACKAGE_BODY</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">PACKAGE\_BODY</a>.
</div>
</div>

### isPort() {#a73186f5d1ba5e6c11c6f006708da79a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isPort (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2452 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73186f5d1ba5e6c11c6f006708da79a6">2452</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a73186f5d1ba5e6c11c6f006708da79a6">VhdlDocGen::isPort</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">VhdlSpecifier::PORT</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">PORT</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isProcedure() {#aed906dd71cdcb8aca1bc6e3f9fba9732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isProcedure (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 143 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2476 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">2476</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">PROCEDURE</a>.

Referenced by <a href="#a765683cbd1cf5a8e7374b64a9ac37d98">findFunction</a>, <a href="#aee87f24daab068f794ea908f33a86c3f">writeFuncProcDocu</a>, <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isProcess() {#a212ea7da7de8f22c3ca1dd14a38a67ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isProcess (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 139 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2468 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">2468</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">VhdlDocGen::isProcess</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">VhdlSpecifier::PROCESS</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">PROCESS</a>.

Referenced by <a href="#aee87f24daab068f794ea908f33a86c3f">writeFuncProcDocu</a>, <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isRecord() {#ac0634a061165ad22c27eef2ac12057d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isRecord (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 144 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2478 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0634a061165ad22c27eef2ac12057d0">2478</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac0634a061165ad22c27eef2ac12057d0">VhdlDocGen::isRecord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">VhdlSpecifier::RECORD</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">RECORD</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isSignal() {#a07199651d2f493ee3afe42975df77efb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isSignal (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 140 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2470 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07199651d2f493ee3afe42975df77efb">2470</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a07199651d2f493ee3afe42975df77efb">VhdlDocGen::isSignal</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2471</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">VhdlSpecifier::SIGNAL</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">SIGNAL</a>.
</div>
</div>

### isSignals() {#a7fb01b11d2a225ee8d8c43a56862be8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isSignals (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 142 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2474 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fb01b11d2a225ee8d8c43a56862be8b">2474</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7fb01b11d2a225ee8d8c43a56862be8b">VhdlDocGen::isSignals</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">VhdlSpecifier::SIGNAL</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">SIGNAL</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isSubClass() {#ac7d0f125a2bffca08e8c52644bf8c6f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isSubClass (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * scd, bool followInstances, int level)</td>
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



Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2322 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7d0f125a2bffca08e8c52644bf8c6f2">2322</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a>(<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd,<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *scd, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> followInstances,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("isBaseClass(cd=%s) looking for %s\n",qPrint(name()),qPrint(bcd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&gt;255)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Possible recursive class relation while inside {} and looking for {}\n"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),scd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">    abort();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd :cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ccd=bcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!followInstances &amp;&amp; ccd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae587759f556ea0d641b92a30e923a7c9">templateMaster</a>()) ccd=ccd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ae587759f556ea0d641b92a30e923a7c9">templateMaster</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("isSubClass() subclass %s\n",qPrint(ccd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ccd==scd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">      found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level &lt;256)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">        level = ccd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3e118df515565a29662b41396ee66579">isBaseClass</a>(scd,followInstances);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">          found=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a3e118df515565a29662b41396ee66579">ClassDef::isBaseClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a> and <a href="/web-doxygen/docs/api/classes/classdef/#ae587759f556ea0d641b92a30e923a7c9">ClassDef::templateMaster</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab534a27eef617922af2a5d7baafffcae">addInstance</a>.
</div>
</div>

### isSubType() {#ab57f7d02afdd7034f78894b20e6ff4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isSubType (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2464 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab57f7d02afdd7034f78894b20e6ff4aa">2464</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab57f7d02afdd7034f78894b20e6ff4aa">VhdlDocGen::isSubType</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">VhdlSpecifier::SUBTYPE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">SUBTYPE</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isUnit() {#a4861484cc952d96afcfe277cf958aff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isUnit (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 146 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2482 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4861484cc952d96afcfe277cf958aff0">2482</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4861484cc952d96afcfe277cf958aff0">VhdlDocGen::isUnit</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">VhdlSpecifier::UNITS</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">UNITS</a>.
</div>
</div>

### isVariable() {#a877e8a81695500e7ad5ed8d76fdbaffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isVariable (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 148 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2486 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a877e8a81695500e7ad5ed8d76fdbaffc">2486</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a877e8a81695500e7ad5ed8d76fdbaffc">VhdlDocGen::isVariable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">VhdlSpecifier::SHAREDVARIABLE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">SHAREDVARIABLE</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### isVhdlClass() {#a7b7df19eb23b1532bc1d05c7ffe6cd76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isVhdlClass (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * cu)</td>
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



Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b7df19eb23b1532bc1d05c7ffe6cd76">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7b7df19eb23b1532bc1d05c7ffe6cd76">isVhdlClass</a> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *cu)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cu-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">vhdlSpec</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">VhdlSpecifier::ENTITY</a>       ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">             cu-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">vhdlSpec</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">VhdlSpecifier::PACKAGE</a>      ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">             cu-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">vhdlSpec</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">VhdlSpecifier::ARCHITECTURE</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">             cu-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">vhdlSpec</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">VhdlSpecifier::PACKAGE_BODY</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">ARCHITECTURE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">ENTITY</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">PACKAGE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">PACKAGE\_BODY</a> and <a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">Entry::vhdlSpec</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#afd4e9dc2db18f93819d8fbddf554efa4">VHDLOutlineParser::mapLibPackage</a>.
</div>
</div>

### isVhdlFunction() {#a8808d28bf43d889892a8b6bad0793d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isVhdlFunction (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 138 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2466 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8808d28bf43d889892a8b6bad0793d7d">2466</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2467</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">FUNCTION</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>.

Referenced by <a href="#a765683cbd1cf5a8e7374b64a9ac37d98">findFunction</a>, <a href="#aee87f24daab068f794ea908f33a86c3f">writeFuncProcDocu</a>, <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a> and <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### isVType() {#a8ab98ceef0a36aea7a15c548ec9aa455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::isVType (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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



Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2462 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ab98ceef0a36aea7a15c548ec9aa455">2462</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8ab98ceef0a36aea7a15c548ec9aa455">VhdlDocGen::isVType</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">VhdlSpecifier::TYPE</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">TYPE</a>.

Referenced by <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">writeTagFile</a>.
</div>
</div>

### parseForBinding() {#a411f4f042964d6e24c0376f1378da1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::parseForBinding (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; entity, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; arch)</td>
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



Declaration at line 201 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2094 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a411f4f042964d6e24c0376f1378da1a8">2094</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#a411f4f042964d6e24c0376f1378da1a8">VhdlDocGen::parseForBinding</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; entity,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; arch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> exp(R</span><span class="doxyHighlightStringLiteral">"([()\s])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ql = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(entity.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),exp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(ql,</span><span class="doxyHighlightStringLiteral">"open"</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"open"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()&lt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string label=ql[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">  entity = ql[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index=entity.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">    entity.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,index+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()==3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">    arch=ql[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(label);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#ab8681769cd2f027fbf46a4836d3825e9">computeVhdlComponentRelations</a>.
</div>
</div>

### parseForConfig() {#a4584e2262b81979f6d9b88c070c78753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VhdlDocGen::parseForConfig (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; entity, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; arch)</td>
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



Declaration at line 200 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2062 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4584e2262b81979f6d9b88c070c78753">2062</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4584e2262b81979f6d9b88c070c78753">VhdlDocGen::parseForConfig</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; entity,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; arch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!entity.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> exp(R</span><span class="doxyHighlightStringLiteral">"([:()\s])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(entity.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),exp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()&lt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> label(ql[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">  entity = ql[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index = entity.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">    entity.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,index+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()==3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">    arch = ql[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">    ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(arch.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),exp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()&gt;1) </span><span class="doxyHighlightComment">// expression</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">      arch=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> label; </span><span class="doxyHighlightComment">// label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### parseFuncProto() {#a9f4758858cac73d07721ea31f42bea8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::parseFuncProto (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ret, bool doc=false)</td>
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




parses a function proto

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">text</td>
<td class="doxyParamItemDescription">function string</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">name</td>
<td class="doxyParamItemDescription">points to the function name</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ret</td>
<td class="doxyParamItemDescription">Stores the return type</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">doc</td>
<td class="doxyParamItemDescription">???</td>
</tr>
</table>
</dd>
</dl>

Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 634 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f4758858cac73d07721ea31f42bea8e">634</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; name,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; ret,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s1(text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&lt;0) index=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-index)&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">    temp=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(index+1,(<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-index-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//getFuncParams(qlist,temp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    name=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    name=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>-index)&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">      ret=</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">    s1=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> s=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s==-1) s=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==-1 || i&lt;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">      s1=<a href="#ae1c14782849e08d5ef42d9ae8290c18b">VhdlDocGen::getIndexWord</a>(s1,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// s&lt;i, s=start of name, i=end of name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">      s1=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(s,(i-s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    name=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">  index=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"return"</span><span class="doxyHighlight">,-1,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index !=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">    ret=s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(index+6,s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">    ret=ret.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a82a05cf7bd081febd19a0065eed17098">VhdlDocGen::deleteCharRev</a>(ret,</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a82a05cf7bd081febd19a0065eed17098">deleteCharRev</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="#ae1c14782849e08d5ef42d9ae8290c18b">getIndexWord</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#adb5cfe08b5887df4a026299543638531">writeFuncProto</a>.
</div>
</div>

### parseUCF() {#ac5a78fda163916d84fc8067d577f9bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::parseUCF (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * entity, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; f, bool vendor)</td>
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



Declaration at line 192 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1920 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5a78fda163916d84fc8067d577f9bf3">1920</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input,<a href="/web-doxygen/docs/api/classes/entry">Entry</a>* entity,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> altera)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ucFile(input);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNo=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>(</span><span class="doxyHighlightStringLiteral">"#!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!ucFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=ucFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;0) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNo++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> temp=ucFile.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">    temp=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bb=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"//"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (temp.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">        brief+=temp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">        brief.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"\\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!temp.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">) &amp;&amp; !bb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (altera)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> in=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"-name"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (in&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">            temp=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,in+5);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">          temp.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"set_location_assignment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>(entity,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),temp,lineNo,fileName,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> ee(R</span><span class="doxyHighlightStringLiteral">"([\s=])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> in=<a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),ee);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (in&lt;0) in=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ff=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(in);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">          temp.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(ff);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">          ff.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>(entity,ff,temp,lineNo,fileName,brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span><span class="doxyHighlightComment">//temp</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">    ucFile=ucFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">// while</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a17c0d52cf3683a329ebcc7417519b310">initUCF</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>.
</div>
</div>

### prepareComment() {#a802a7b8116fa1b8b46895c25a32c5677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::prepareComment (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; qcs)</td>
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




strips the "--!" prefixes of vhdl comments

Declaration at line 156 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 594 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a802a7b8116fa1b8b46895c25a32c5677">594</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; qcs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* sc=</span><span class="doxyHighlightStringLiteral">"--!"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(sc)) qcs = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(sc));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(R</span><span class="doxyHighlightStringLiteral">"(\n[ \t]*--!)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  std::string s = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> iter(s,re);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/reg/iterator">reg::Iterator</a> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  std::string result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sl=s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> ( ; iter!=<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a> ; ++iter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;match = *iter;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = match.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=s.substr(p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    p = match.position()+match.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=s.substr(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs = result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">  qcs=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab3687656c1045cb4c1c5177bbab2c83e">VHDLOutlineParser::checkMultiComment</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>.
</div>
</div>

### resetCodeVhdlParserState() {#a60e16e249eaf1829c224b054ff743ce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::resetCodeVhdlParserState ()</td>
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



Declaration at line 220 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2434 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60e16e249eaf1829c224b054ff743ce7">2434</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a60e16e249eaf1829c224b054ff743ce7">VhdlDocGen::resetCodeVhdlParserState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g_vhdlMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g_varMap</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g_classList</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g_packages</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a15003ec22aceea0954f320c3092588b1">g\_classList</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a4f0ee2fc6fdee2414cb783cb977becd7">g\_packages</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a3cc5f535e1a84284407b715e1b40f93e">g\_varMap</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#aee6adbe29081b799cea6fc0a906df2f1">g\_vhdlMutex</a>.
</div>
</div>

### setFlowMember() {#a7808cdf56c299daceed3212b65b8a031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::setFlowMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * flowMember)</td>
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



Declaration at line 209 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7808cdf56c299daceed3212b65b8a031">77</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7808cdf56c299daceed3212b65b8a031">VhdlDocGen::setFlowMember</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a>=mem;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a>.

Referenced by <a href="#a2de08afddfa24b4a037c36ac329185ff">createFlowChart</a>.
</div>
</div>

### writeClassType() {#a0ac2f4932405d6a1773bea6eb84885ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::writeClassType (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cname)</td>
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



Declaration at line 182 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1799 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ac2f4932405d6a1773bea6eb84885ec">1799</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol ,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVhdlType(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>(cd),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">  cname=<a href="#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(qcs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//ol.insertMemberAlign();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// writeClassLink</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a2c4458b0e27e9b97db254d082d1487d2">getClassName</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">OutputList::writeString</a>.
</div>
</div>

### writeFormatString() {#a0b58904c2803fe64c007b6c3ddda086e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeFormatString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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




writes a colored and formatted string

Declaration at line 159 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 770 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b58904c2803fe64c007b6c3ddda086e">770</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; s,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp;ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> <a href="/web-doxygen/docs/api/namespaces/reg">reg</a>(R</span><span class="doxyHighlightStringLiteral">"([\[\]./&lt;&gt;:\s,;'+*|&amp;=()\"-])");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs = s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  qcs+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span><span class="doxyHighlightComment">// parsing the last sign</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> find=qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> temp=qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> buf[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">  buf[1]=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="/web-doxygen/docs/api/namespaces/reg">reg</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (j&gt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">      find=find.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">      buf[0]=temp[j];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *ss=<a href="#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>(find);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> k=<a href="#a6a0f5ef9f02fff9ab8ad1b70709cd887">isNumber</a>(find.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()); </span><span class="doxyHighlightComment">// is this a number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (k)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(find,</span><span class="doxyHighlightStringLiteral">"vhdldigit"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j != 0 &amp;&amp; ss)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(find,ss,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>(mdef,find,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(&amp;buf[0],</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> st=temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,j+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">      find=st;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!find.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; find.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ii=find.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> com=find.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(ii+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(com,</span><span class="doxyHighlightStringLiteral">"keyword"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">          temp=find.<a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">remove</a>(0,ii+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">        temp=st;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">      j = <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(temp.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="/web-doxygen/docs/api/namespaces/reg">reg</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span><span class="doxyHighlightComment">//while</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(find,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// writeFormatString</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>, <a href="#af24155445ad4e0328e60f78bf4a4a41f">findKeyWord</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a6a0f5ef9f02fff9ab8ad1b70709cd887">isNumber</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66f15f4dde9edaf0aac741fa7d57bae8">QCString::remove</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="#abdbd7a613237d2a86532bfe548209a1d">writeStringLink</a>.

Referenced by <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="#aee87f24daab068f794ea908f33a86c3f">writeFuncProcDocu</a> and <a href="#a31b60db653850e1be9084b27153e6758">writeProcessProto</a>.
</div>
</div>

### writeFuncProcDocu() {#aee87f24daab068f794ea908f33a86c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::writeFuncProcDocu (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, bool type=false)</td>
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




writes a function|procedure documentation to the output

Declaration at line 163 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1067 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee87f24daab068f794ea908f33a86c3f">1067</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*type*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool sem=FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad32603ff4c4ba4d39e0bad7ede5924bf">enableAll</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index=al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" ( ) "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a1c30d8717346992a8a9c35f2ae92271f">endMemberDocName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">startParameterList</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//ol.startParameterName(FALSE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;arg : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">startParameterType</a>(first,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//   if (first) ol.writeChar('(');</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> attl=arg.defval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//bool bGen=attl.stripPrefix("generic");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//if (bGen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//  VhdlDocGen::writeFormatString(QCString("generic "),ol,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(md) || <a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(md) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(arg.defval,</span><span class="doxyHighlightStringLiteral">"keywordtype"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">endParameterType</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">startParameterName</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>(arg.name,ol,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(md))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(arg.attrib,</span><span class="doxyHighlightStringLiteral">"stringliteral"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(md))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"in"</span><span class="doxyHighlight">),</span><span class="doxyHighlightStringLiteral">"stringliteral"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">startEmphasis</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">enable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">VhdlDocGen::isProcess</a>(md))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightComment">// startFonts(arg.type,"vhdlkeyword",ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>(arg.type,ol,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5674d5d9336eb1f7f6cb83c058f5ad8f">endEmphasis</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">enable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (--index)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" , "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    ol.docify(" ) ");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">endParameterName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">endParameterName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//sem=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">    first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//ol.endParameterList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">} </span><span class="doxyHighlightComment">// writeDocFunProc</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">OutputList::disable</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">OutputList::enable</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad32603ff4c4ba4d39e0bad7ede5924bf">OutputList::enableAll</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5674d5d9336eb1f7f6cb83c058f5ad8f">OutputList::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a1c30d8717346992a8a9c35f2ae92271f">OutputList::endMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">OutputList::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">OutputList::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">OutputList::endParameterType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">isProcedure</a>, <a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">isProcess</a>, <a href="#a8808d28bf43d889892a8b6bad0793d7d">isVhdlFunction</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">Man</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">OutputList::startEmphasis</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">OutputList::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">OutputList::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">OutputList::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">OutputList::startParameterType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a>.

Referenced by <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### writeFunctionProto() {#a9ca249e8052f477d893edfc767948fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeFunctionProto (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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




writes a function prototype to the output

Declaration at line 160 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 963 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ca249e8052f477d893edfc767948fcf">963</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len=al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" ( "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;arg : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> att=arg.defval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bGen=att.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sem &amp;&amp; len &lt; 3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" , "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bGen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"generic "</span><span class="doxyHighlight">),ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!att.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str=<a href="#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>(att);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">      att+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(att,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(att,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn=arg.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">    nn+=</span><span class="doxyHighlightStringLiteral">": "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ss=arg.type.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>(); </span><span class="doxyHighlightComment">//.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> w=ss.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span><span class="doxyHighlightComment">//.upper();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(nn,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(</span><span class="doxyHighlightStringLiteral">"in "</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"stringliteral"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str=<a href="#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>(ss);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(w,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(w,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!arg.attrib.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(arg.attrib,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">    sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len &gt; 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" )"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> exp=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!exp.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"[ "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(exp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" ]"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">MemberDef::excpString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#af24155445ad4e0328e60f78bf4a4a41f">findKeyWord</a>, <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">OutputList::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### writeInlineClassLink() {#a67f47b8dc11d967ee47e9bda86fff7e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeInlineClassLink (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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




writes an inline link form entity|package to architecture|package body and vice verca

Declaration at line 122 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 465 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67f47b8dc11d967ee47e9bda86fff7e0">465</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd ,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;QCString&gt; ql;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn=cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">className</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a010ab08982f29df8c0f3d3f0f642f0f0">VhdlClasses</a> ii=<a href="#ab1ab1504610c798f4924026a48bb4301">convert</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type = <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>(cd),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//type=type.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">  type+=</span><span class="doxyHighlightStringLiteral">" &gt;&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a7da7adb1d98a6ee0f69281084f9ea9b2">OutputType::RTF</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">VhdlDocGen::PACKBODYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">    nn.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">    cd=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">VhdlDocGen::PACKAGECLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    nn.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    cd=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">VhdlDocGen::ARCHITECTURECLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> qlist=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(nn.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qlist.size()&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      nn=qlist[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      cd=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">VhdlDocGen::getClass</a>(nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> opp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9e5659d6cb4369b41809c279d006b44c">VhdlDocGen::findAllArchitectures</a>(ql,cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : ql)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> qlist=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(s.str(),</span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (qlist.size()&gt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s1(qlist[0]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s2(qlist[1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">        s1.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ql.size()==1) s1.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cc = <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>(cc,ol,type,s2,s1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>(cd,ol,type,nn,opp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">enable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">enable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a7da7adb1d98a6ee0f69281084f9ea9b2">OutputType::RTF</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// write</span></span></div>

</div>


References <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae0c7e4401e472ec3153e9793e240a431">ARCHITECTURECLASS</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">ClassDef::className</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="#ab1ab1504610c798f4924026a48bb4301">convert</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">OutputList::disable</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">OutputList::enable</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>, <a href="#a9e5659d6cb4369b41809c279d006b44c">findAllArchitectures</a>, <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ab51377e0618f4b5bc839c21db9339571">getSpecifierTypeFromClass</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">Man</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0ae69513dd677b13d97b6a2e3ae445d1ef">PACKAGECLASS</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a4cdc00f213301fb089eb3906a07efd20">PACKBODYCLASS</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a7da7adb1d98a6ee0f69281084f9ea9b2">RTF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator\_vhdlType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a6e37fa3f47b3d836813a1cf2a7fef036">writeVhdlLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2ee9959a879f505d8e3296acd74f4758">ClassDefImpl::writeMemberDeclarations</a>.
</div>
</div>

### writePlainVHDLDeclarations() {#afc394d10d64e221682e9619eef74fde5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writePlainVHDLDeclarations (const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> specifier)</td>
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



Declaration at line 174 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1691 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc394d10d64e221682e9619eef74fde5">1691</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a>* mlist,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> specifier)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a0bc125fc346e538d66d5ea1c33428f00">StringSet</a> pack;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;imd : *mlist)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(imd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> mems=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ad1902fdf699e7983c0dfc20a0e8192da">isBriefSectionVisible</a>() &amp;&amp; (mems==specifier) &amp;&amp; (mems!=<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first) { ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">startMemberList</a>();first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>(md,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ad1902fdf699e7983c0dfc20a0e8192da">isBriefSectionVisible</a>() &amp;&amp; (mems==specifier))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pack.find(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==pack.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first) ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">startMemberList</a>(),first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>(md,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">          pack.insert(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">//for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7c8d844390c3ab106b675144baa48fc7">endMemberList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">//plainDeclaration</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a7c8d844390c3ab106b675144baa48fc7">OutputList::endMemberList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ad1902fdf699e7983c0dfc20a0e8192da">MemberDef::isBriefSectionVisible</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">LIBRARY</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">OutputList::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.

Referenced by <a href="#a2b65f506a9133e6bbc8e8665e2901625">writeVHDLDeclarations</a>.
</div>
</div>

### writeProcedureProto() {#a4ab757dead7796d93d5a534ae1c11e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeProcedureProto (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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




writes a procedure prototype to the output

Declaration at line 162 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 908 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ab757dead7796d93d5a534ae1c11e69">908</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len=al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">size</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"( "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len &gt; 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;arg : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sem &amp;&amp; len &lt;3)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a188c7a8f0a0dc35ec5ea0f8b4a491d33">writeChar</a>(</span><span class="doxyHighlightCharLiteral">','</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn=arg.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">    nn+=</span><span class="doxyHighlightStringLiteral">": "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> defval = arg.defval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str=<a href="#af24155445ad4e0328e60f78bf4a4a41f">VhdlDocGen::findKeyWord</a>(defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">    defval+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(defval,str,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(defval,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol); </span><span class="doxyHighlightComment">// write type (variable,constant etc.)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(nn,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol); </span><span class="doxyHighlightComment">// write name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(arg.attrib,arg.type) != 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(arg.attrib.lower(),</span><span class="doxyHighlightStringLiteral">"stringliteral"</span><span class="doxyHighlight">,ol); </span><span class="doxyHighlightComment">// write in|out</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(arg.type,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">    sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len &gt; 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">//for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" )"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#af24155445ad4e0328e60f78bf4a4a41f">findKeyWord</a>, <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">OutputList::lineBreak</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a4d651caeb995400fad17d4ab4a020a3a">ArgumentList::size</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a188c7a8f0a0dc35ec5ea0f8b4a491d33">OutputList::writeChar</a>.

Referenced by <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### writeProcessProto() {#a31b60db653850e1be9084b27153e6758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeProcessProto (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef)</td>
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




writes a process prototype to the output

Declaration at line 161 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1041 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31b60db653850e1be9084b27153e6758">1041</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" ( "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;arg : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" , "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn=arg.name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// startFonts(nn,"vhdlchar",ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>(nn,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">    sem=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" )"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a>.

Referenced by <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### writeRecordProto() {#ae7d4d0c22eac6e04a900b847c702a157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeRecordProto (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al)</td>
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



Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>.

Reference <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a564ccf36eb7cf220de5f5252a9a2b0da">flowMember</a>.
</div>
</div>

### writeSource() {#a1c145b8082cd9865b477141ab58dcb20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeSource (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cname)</td>
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



Declaration at line 198 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1839 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c145b8082cd9865b477141ab58dcb20">1839</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;cname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> intf = <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>-&gt;getCodeParser(</span><span class="doxyHighlightStringLiteral">".vhd"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// pIntf-&gt;resetCodeParserState();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> codeFragment=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> fi=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">     fi=codeFragment.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">,++fi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight">(fi&gt;=0 &amp;&amp; j++ &lt;3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// show only the first four lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (j==4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">      codeFragment=codeFragment.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(fi);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">      codeFragment.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(</span><span class="doxyHighlightStringLiteral">"\n    ....    "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">  codeFragment.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;codeOL = ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a284458e4baf27869eb5bbb9776407e6c">codeGenerators</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  codeOL.<a href="/web-doxygen/docs/api/classes/outputcodelist/#ae6c741566f88d0cdbf6bdfceba362c5d">startCodeFragment</a>(</span><span class="doxyHighlightStringLiteral">"DoxyCode"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  intf-&gt;parseCode(     codeOL,           </span><span class="doxyHighlightComment">// codeOutIntf</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),       </span><span class="doxyHighlightComment">// scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">                       codeFragment,     </span><span class="doxyHighlightComment">// input</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">                       SrcLangExt::VHDL,  </span><span class="doxyHighlightComment">// lang</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(STRIP_CODE_COMMENTS),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,            </span><span class="doxyHighlightComment">// isExample</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),       </span><span class="doxyHighlightComment">// exampleName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">                       mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">getFileDef</a>(), </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">                       mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>(),      </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">                       mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>(),        </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,             </span><span class="doxyHighlightComment">// inlineFragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">                       mdef,             </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>              </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  codeOL.endCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCode"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(</span><span class="doxyHighlightKeyword">const_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(mdef));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">    mdm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a898bbc45a94a48ee24d546ca47a8fa08">writeSourceDef</a>(ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a3aedaf487c755d4749b10fa95729a2af">hasReferencesRelation</a>()) mdm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a4f8a1518f5eb3457b0b9bae26e2f4c73">writeSourceRefs</a>(ol,cname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abc1862f5e87a67541a4c40403a95fd81">hasReferencedByRelation</a>()) mdm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ab7a44940cbbf95d1ff1da5c27a291153">writeSourceReffedBy</a>(ol,cname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a284458e4baf27869eb5bbb9776407e6c">OutputList::codeGenerators</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5036fd8ee16b186925236105029ee823">MemberDef::getFileDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abc1862f5e87a67541a4c40403a95fd81">MemberDef::hasReferencedByRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a3aedaf487c755d4749b10fa95729a2af">MemberDef::hasReferencesRelation</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">OutputList::popGeneratorState</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">OutputList::pushGeneratorState</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#ae6c741566f88d0cdbf6bdfceba362c5d">OutputCodeList::startCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a898bbc45a94a48ee24d546ca47a8fa08">DefinitionMutable::writeSourceDef</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ab7a44940cbbf95d1ff1da5c27a291153">DefinitionMutable::writeSourceReffedBy</a> and <a href="/web-doxygen/docs/api/classes/definitionmutable/#a4f8a1518f5eb3457b0b9bae26e2f4c73">DefinitionMutable::writeSourceRefs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### writeTagFile() {#a76fe2943fccabc70c52ad3b6e31f4fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeTagFile (<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> * mdef, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; tagFile)</td>
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



Declaration at line 124 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1346 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">1346</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a76fe2943fccabc70c52ad3b6e31f4fa5">VhdlDocGen::writeTagFile</a>(<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdef,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;tagFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;member kind=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae3c19429669d382581ba37aee5f39278">VhdlDocGen::isGeneric</a>(mdef))      tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a73186f5d1ba5e6c11c6f006708da79a6">VhdlDocGen::isPort</a>(mdef))         tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"port"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a65218023c4970a90f3bce70938a99781">VhdlDocGen::isEntity</a>(mdef))       tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"entity"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad3fdc795bf951ef11221894512b8bc6c">VhdlDocGen::isComponent</a>(mdef))    tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"component"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8ab98ceef0a36aea7a15c548ec9aa455">VhdlDocGen::isVType</a>(mdef))        tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2c3cdcd27394531385ccd8c56257edc1">VhdlDocGen::isConstant</a>(mdef))     tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"constant"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab57f7d02afdd7034f78894b20e6ff4aa">VhdlDocGen::isSubType</a>(mdef))      tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"subtype"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(mdef)) tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(mdef))    tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"procedure"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">VhdlDocGen::isProcess</a>(mdef))      tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"process"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a7fb01b11d2a225ee8d8c43a56862be8b">VhdlDocGen::isSignals</a>(mdef))      tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2dc9e668acc7c79f211709e2a0eeccad">VhdlDocGen::isAttribute</a>(mdef))    tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"attribute"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac0634a061165ad22c27eef2ac12057d0">VhdlDocGen::isRecord</a>(mdef))       tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"record"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3f582b69841bae3ec6f1281604b6f0c8">VhdlDocGen::isLibrary</a>(mdef))      tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"library"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aca017e059b8a2972c2cad968800c0564">VhdlDocGen::isPackage</a>(mdef))      tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"package"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a877e8a81695500e7ad5ed8d76fdbaffc">VhdlDocGen::isVariable</a>(mdef))     tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"shared variable"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a7ac9c26b1b0fb7402cc58acaf569df89">VhdlDocGen::isFile</a>(mdef))         tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"file"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a069c8ad206be372bd948cc8e964218ed">VhdlDocGen::isGroup</a>(mdef))        tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"group"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(mdef))     tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"instantiation"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#af13dd5eb831c1df008b0fd41928f4b7c">VhdlDocGen::isAlias</a>(mdef))        tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"alias"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(mdef))     tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"configuration"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;type&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/type&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;name&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/name&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;anchorfile&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(fn) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/anchorfile&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;anchor&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/anchor&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">    tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;arglist&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a1876213c101b31a44336d48b6b33e9ec">VhdlDocGen::convertArgumentListToString</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/arglist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">    tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;arglist&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(<a href="#a1876213c101b31a44336d48b6b33e9ec">VhdlDocGen::convertArgumentListToString</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/arglist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">    tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;arglist&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/arglist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#accb2be5ad265e2c5214b857c075383b3">writeDocAnchorsToTagFile</a>(tagFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/member&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="#a1876213c101b31a44336d48b6b33e9ec">convertArgumentListToString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="#af13dd5eb831c1df008b0fd41928f4b7c">isAlias</a>, <a href="#a2dc9e668acc7c79f211709e2a0eeccad">isAttribute</a>, <a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">isCompInst</a>, <a href="#ad3fdc795bf951ef11221894512b8bc6c">isComponent</a>, <a href="#a2c3cdcd27394531385ccd8c56257edc1">isConstant</a>, <a href="#a65218023c4970a90f3bce70938a99781">isEntity</a>, <a href="#a7ac9c26b1b0fb7402cc58acaf569df89">isFile</a>, <a href="#ae3c19429669d382581ba37aee5f39278">isGeneric</a>, <a href="#a069c8ad206be372bd948cc8e964218ed">isGroup</a>, <a href="#a3f582b69841bae3ec6f1281604b6f0c8">isLibrary</a>, <a href="#aca017e059b8a2972c2cad968800c0564">isPackage</a>, <a href="#a73186f5d1ba5e6c11c6f006708da79a6">isPort</a>, <a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">isProcedure</a>, <a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">isProcess</a>, <a href="#ac0634a061165ad22c27eef2ac12057d0">isRecord</a>, <a href="#a7fb01b11d2a225ee8d8c43a56862be8b">isSignals</a>, <a href="#ab57f7d02afdd7034f78894b20e6ff4aa">isSubType</a>, <a href="#a877e8a81695500e7ad5ed8d76fdbaffc">isVariable</a>, <a href="#a8808d28bf43d889892a8b6bad0793d7d">isVhdlFunction</a>, <a href="#a8ab98ceef0a36aea7a15c548ec9aa455">isVType</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a> and <a href="/web-doxygen/docs/api/classes/definitionmutable/#accb2be5ad265e2c5214b857c075383b3">DefinitionMutable::writeDocAnchorsToTagFile</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a20813d8313b4dfdb5a6625efc4e989ef">MemberList::writeTagFile</a>.
</div>
</div>

### writeVHDLDeclaration() {#a99c857205029d5e52c0a7c26f18ef3ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeVHDLDeclaration (<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> * mdef, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod, bool inGroup)</td>
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



Declaration at line 170 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1392 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99c857205029d5e52c0a7c26f18ef3ed">1392</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>(<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a>* mdef,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*inGroup*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(cd!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || nd!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || fd!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || gd!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || mod!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">      ); </span><span class="doxyHighlightComment">// member should belong to something</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd) d=cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd) d=nd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd) d=fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod) d=mod;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd) d=gd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> d=mdef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write search index info</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.enabled())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.setCurrentDoc(mdef,mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.addWord(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">localName</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.addWord(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cname  = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cfname = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//HtmlHelp *htmlHelp=nullptr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  bool hasHtmlHelp = Config_getBool(GENERATE_HTML) &amp;&amp; Config_getBool(GENERATE_HTMLHELP);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  if (hasHtmlHelp) htmlHelp = HtmlHelp::getInstance();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search for the last anonymous scope in the member type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *annoClassDef=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a90092536a05578d258ca1381e3176c88">getClassDefOfAnonymousType</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// start a new member declaration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> memType = annoClassDef!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> ? <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">OutputGenerator::MemberItemType::AnonymousStart</a> :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::MemberItemType::Normal</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlightComment">  ///printf("startMemberItem for %s\n",qPrint(name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> mm=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">getVhdlSpecifiers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mm==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">      memType=<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbaf756dbefd44dd9270c676f74fb8d3708">OutputGenerator::MemberItemType::Templated</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">   ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad7e741530682b5707eb04b3f4009523d">startMemberItem</a>( mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(), memType );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// If there is no detailed description we need to write the anchor here.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> detailsVisible = mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a091d243bd31c95a34233e364dfdd9f5d">hasDetailedDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!detailsVisible)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> doxyName=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) doxyName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(cname+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> doxyArgs=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aae4920963ec75457cd7e3662aedded3a">startDoxyAnchor</a>(cfname,cname,mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),doxyName,doxyArgs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a87a285c01c1913708553746b1f2813f0">addLabel</a>(cfname,mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">OutputType::Man</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a08e3b0db5b64cd1da774369814896b78">OutputType::Latex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// *** write type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*VHDL CHANGE */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ltype(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> largs(mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *kl=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al = mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//VhdlDocGen::adjustRecordMember(mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd) gd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (mm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>(mdef,ol,nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ltype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>() &amp;&amp; mm==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>(ol,al,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>() &amp;&amp; mm==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>(ol,al,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">      kl=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">VhdlDocGen::getClass</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (kl &amp;&amp; (<a href="#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(kl-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">protection</a>())==<a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a>)) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (kl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">        nn=kl-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">VhdlSpecifier::PACKAGE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">        name.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">        name+=</span><span class="doxyHighlightStringLiteral">" &lt;"</span><span class="doxyHighlight">+mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()+</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">startEmphasis</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(kl-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),kl-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (largs==</span><span class="doxyHighlightStringLiteral">"context"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>(ltype,largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">VhdlSpecifier::PORT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">VhdlSpecifier::ALIAS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mm==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a1d117e436431c6c8976e8e1e3167b20c">insertMemberAlignLeft</a>(memType, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ltype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">VhdlSpecifier::PROCESS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>(ol,al,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">VhdlSpecifier::PACKAGE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">VhdlSpecifier::ENTITY</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">VhdlSpecifier::COMPONENT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">VhdlSpecifier::CONFIG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(mdef) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">        nn=largs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(nn.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">) || nn.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"package"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ltype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">        largs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">        largs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">            cfname,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">            mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(ltype);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad3fdc795bf951ef11221894512b8bc6c">VhdlDocGen::isComponent</a>(mdef) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a57efdf5bddd0b36667c8aa21256ebac7">VhdlDocGen::isConfig</a>(mdef)    ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a57efdf5bddd0b36667c8aa21256ebac7">VhdlDocGen::isConfig</a>(mdef) || <a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">          nn=ltype;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">          nn=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">        kl=<a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>(nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (kl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">          nn=kl-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">startEmphasis</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name(</span><span class="doxyHighlightStringLiteral">"&lt;Entity "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a57efdf5bddd0b36667c8aa21256ebac7">VhdlDocGen::isConfig</a>(mdef) || <a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">VhdlDocGen::isCompInst</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">            name+=ltype+</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">            name+=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()+</span><span class="doxyHighlightStringLiteral">"&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(kl-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),kl-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5674d5d9336eb1f7f6cb83c058f5ad8f">endEmphasis</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">          ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">VhdlSpecifier::SIGNAL</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">VhdlSpecifier::ATTRIBUTE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">VhdlSpecifier::SUBTYPE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">VhdlSpecifier::CONSTANT</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">VhdlSpecifier::SHAREDVARIABLE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VhdlSpecifier::VFILE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">VhdlSpecifier::GROUP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">VhdlSpecifier::TYPE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ltype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">VhdlSpecifier::RECORD</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">VhdlSpecifier::UNITS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="#ad197f46fa25960c771c0e8b897ded06d">writeRecordUnit</a>(largs,ltype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> htmlOn = ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a046bd3dcc4d8e2cc12821fba1394d818">isEnabled</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (htmlOn &amp;&amp; </span><span class="doxyHighlightComment">/*Config_getBool(HTML_ALIGN_MEMBERS) &amp;&amp;*/</span><span class="doxyHighlight"> !ltype.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ltype.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (htmlOn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">enable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!detailsVisible)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a554df4a05f695ab67b514a12d9d19f6d">endDoxyAnchor</a>(cfname,mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a7bcc956b2ecbc3aed4f265593621dc0d">endMemberItem</a>(memType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;   <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(BRIEF_MEMBER_DESC) </span><span class="doxyHighlightComment">/* &amp;&amp; !annMemb */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a4988f821b416a64d12c7fbc0a4273bba">startMemberDescription</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(), <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), mm == <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">VhdlSpecifier::PORT</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">briefFile</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">briefLine</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">                   mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>()?mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>():d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">                   mdef,s,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (detailsVisible)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">getGroupDef</a>()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> &amp;&amp; gd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// forward link to the group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#af084d8a76621939675ae543f47032fa4">startTextLink</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// local link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#af084d8a76621939675ae543f47032fa4">startTextLink</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a74e89e9bcca41e9203ca080fc127a004">endTextLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a3824b9043050bea2202a29c15b4c5344">endMemberDescription</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">  mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a1212af3d2b7edf710bbda655097a8a7b">warnIfUndocumented</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// end writeVhdlDeclaration</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a87a285c01c1913708553746b1f2813f0">OutputList::addLabel</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">ALIAS</a>, <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">OutputGenerator::AnonymousStart</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">ATTRIBUTE</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac74d77550941a8f568ea56fecc30c873">Definition::briefFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8073d399d39c43e66a4b487b3e06ade1">Definition::briefLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">COMPONENT</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">CONFIG</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">CONSTANT</a>, <a href="#ab1ab1504610c798f4924026a48bb4301">convert</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a192e28bf96098f41db170be0680d5375">OutputList::disable</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a91f9afddff1974d7805c3d022b754ddf">OutputList::disableAllBut</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a306f5cfd7c296b5a52160343d9631916">OutputList::enable</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a554df4a05f695ab67b514a12d9d19f6d">OutputList::endDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5674d5d9336eb1f7f6cb83c058f5ad8f">OutputList::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a3824b9043050bea2202a29c15b4c5344">OutputList::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a7bcc956b2ecbc3aed4f265593621dc0d">OutputList::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a74e89e9bcca41e9203ca080fc127a004">OutputList::endTextLink</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">ENTITY</a>, <a href="#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">ENTITYCLASS</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">FUNCTION</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">GENERIC</a>, <a href="#aa09142ff1ca07603f8bb2150ce9ceab5">getClass</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a90092536a05578d258ca1381e3176c88">MemberDef::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a43566d882fc7994385bbdaf7fe927e67">MemberDef::getGroupDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5cd379d53915c1fafe22420d04d26aa4">MemberDef::getVhdlSpecifiers</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">GROUP</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a091d243bd31c95a34233e364dfdd9f5d">MemberDef::hasDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a1d117e436431c6c8976e8e1e3167b20c">OutputList::insertMemberAlignLeft</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">INSTANTIATION</a>, <a href="#ab9e42b2cf2d969dcc943ec355d4fa6b2">isCompInst</a>, <a href="#ad3fdc795bf951ef11221894512b8bc6c">isComponent</a>, <a href="#a57efdf5bddd0b36667c8aa21256ebac7">isConfig</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a046bd3dcc4d8e2cc12821fba1394d818">OutputList::isEnabled</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a08e3b0db5b64cd1da774369814896b78">Latex</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">LIBRARY</a>, <a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">Definition::localName</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a627661c621eab1b7b298abc47d1a250d">Man</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">MISCELLANEOUS</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::Normal</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">PACKAGE</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">OutputList::popGeneratorState</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">PORT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">PROCEDURE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">PROCESS</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a759c68ae0af03a49aff1a86d383af68d">ClassDef::protection</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">OutputList::pushGeneratorState</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">RECORD</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">SHAREDVARIABLE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">SIGNAL</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aae4920963ec75457cd7e3662aedded3a">OutputList::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">OutputList::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a4988f821b416a64d12c7fbc0a4273bba">OutputList::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad7e741530682b5707eb04b3f4009523d">OutputList::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#af084d8a76621939675ae543f47032fa4">OutputList::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">SUBTYPE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbaf756dbefd44dd9270c676f74fb8d3708">OutputGenerator::Templated</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator\_vhdlType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">TYPE</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">UCF\_CONST</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">UNITS</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">USE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VFILE</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a1212af3d2b7edf710bbda655097a8a7b">MemberDef::warnIfUndocumented</a>, <a href="#a9ca249e8052f477d893edfc767948fcf">writeFunctionProto</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">OutputList::writeObjectLink</a>, <a href="#a4ab757dead7796d93d5a534ae1c11e69">writeProcedureProto</a>, <a href="#a31b60db653850e1be9084b27153e6758">writeProcessProto</a>, <a href="#ad197f46fa25960c771c0e8b897ded06d">writeRecordUnit</a>, <a href="#a1c145b8082cd9865b477141ab58dcb20">writeSource</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>.

Referenced by <a href="#afc394d10d64e221682e9619eef74fde5">writePlainVHDLDeclarations</a>.
</div>
</div>

### writeVhdlDeclarations() {#aa99c6269bf6155f83a12ab796edd4acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeVhdlDeclarations (const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
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



Declaration at line 168 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1183 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa99c6269bf6155f83a12ab796edd4acf">1183</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa99c6269bf6155f83a12ab796edd4acf">VhdlDocGen::writeVhdlDeclarations</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a>* ml,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>* gd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a>* nd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">VhdlSpecifier::COMPONENT</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">VhdlSpecifier::COMPONENT</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">VhdlSpecifier::CONSTANT</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">VhdlSpecifier::CONSTANT</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">VhdlSpecifier::TYPE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">VhdlSpecifier::TYPE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">VhdlSpecifier::SUBTYPE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">VhdlSpecifier::SUBTYPE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">VhdlSpecifier::PORT</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">VhdlSpecifier::PORT</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">VhdlSpecifier::PROCESS</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">VhdlSpecifier::PROCESS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">VhdlSpecifier::SIGNAL</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">VhdlSpecifier::SIGNAL</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">VhdlSpecifier::ATTRIBUTE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">VhdlSpecifier::ATTRIBUTE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">VhdlSpecifier::RECORD</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">VhdlSpecifier::RECORD</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">VhdlSpecifier::UNITS</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">VhdlSpecifier::UNITS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">VhdlSpecifier::SHAREDVARIABLE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">VhdlSpecifier::SHAREDVARIABLE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VhdlSpecifier::VFILE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VhdlSpecifier::VFILE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">VhdlSpecifier::GROUP</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">VhdlSpecifier::GROUP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">VhdlSpecifier::ALIAS</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">VhdlSpecifier::ALIAS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// configurations must be added to global file definitions.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">VhdlSpecifier::CONFIG</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">VhdlSpecifier::CONFIG</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator_vhdlType</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">VhdlSpecifier::UCF_CONST</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91adc6effcb98019a63f6d5ee5624a29058">ALIAS</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6461230ce7343a1f1091515aa3071f31">ATTRIBUTE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7fc67f9f99bcdc7656908ef20801d05b">COMPONENT</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a73e99d350a4aa6f1a5af04ec29173f73">CONFIG</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a8d6b5cada83510220f59e00ce86d4d92">CONSTANT</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">FUNCTION</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">GENERIC</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a720909a4b948fc9e33633b61960d6b3c">GROUP</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">INSTANTIATION</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">LIBRARY</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">MISCELLANEOUS</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">PORT</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">PROCEDURE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">PROCESS</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a921df56002ee5dc960debedc8ae06072">RECORD</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab22b8c1db6bfdab91c75225b09f6052e">SHAREDVARIABLE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac023ee28e6cb71d64feec71f0cbac067">SIGNAL</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa63881580161eaceee8aac4a5138a9cf">SUBTYPE</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5c766ca623cbbc0bf6fded310f85f857">theTranslator\_vhdlType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a948495146facadfe8859789036313d79">TYPE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa8d5924ee664d7dce82922af0698cb68">UCF\_CONST</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a456d42d0c8fd369eb23335d23fb3856a">UNITS</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">USE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a9e930dea59e2d5f4853d805d149ab727">VFILE</a> and <a href="#a2b65f506a9133e6bbc8e8665e2901625">writeVHDLDeclarations</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2ee9959a879f505d8e3296acd74f4758">ClassDefImpl::writeMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a69a98f0517265ac441324e7258b79d1a">FileDefImpl::writeMemberDeclarations</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a3d072ea5280ce80a6dbb16a26efacb21">GroupDefImpl::writeMemberDeclarations</a>.
</div>
</div>

### writeVHDLDeclarations() {#a2b65f506a9133e6bbc8e8665e2901625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeVHDLDeclarations (const <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd, const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; subtitle, bool showEnumValues, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> type)</td>
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



Declaration at line 178 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1745 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b65f506a9133e6bbc8e8665e2901625">1745</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a>* ml,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;subtitle,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*showEnumValues*/</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>(ml,type)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#af6404ab3a071c87189d8b8dd2f0d2ef1">startMemberHeader</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(title),type == <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">VhdlSpecifier::PORT</a> ? 3 : 2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>(title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad50904387e56ccb6532385bfe525e9a2">endMemberHeader</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!subtitle.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#add8c37a5cb21fb366c941cea862b2285">startMemberSubtitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a>(</span><span class="doxyHighlightStringLiteral">"[generated]"</span><span class="doxyHighlight">,-1,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,subtitle,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ad7bb1f47d3fe0d2bc473093e405f348e">endMemberSubtitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightComment">//printf("memberGroupList=%p\n",memberGroupList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>(ml,ol,cd,nd,fd,gd,mod,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> groupId=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#af6d805d822b673a443308b6363d9c85f">getMemberGroupList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>(&amp;mg-&gt;members(),type))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("mg-&gt;header=%s\n",qPrint(mg-&gt;header()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasHeader=!mg-&gt;header().isEmpty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> groupAnchor = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ml-&gt;<a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">listType</a>().<a href="/web-doxygen/docs/api/classes/memberlisttype/#a861c0ba298083d54ea3396001268f34d">toLabel</a>())+</span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(groupId++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ae7ca8c46242c727aa527ab392db22707">startMemberGroupHeader</a>(groupAnchor,hasHeader);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasHeader)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>(mg-&gt;header());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac13352584de9c19dd2776d49c1e9bf30">endMemberGroupHeader</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mg-&gt;documentation().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Member group has docs!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac78054f50bad730b62b3456699d9a350">startMemberGroupDocs</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a>(</span><span class="doxyHighlightStringLiteral">"[generated]"</span><span class="doxyHighlight">,-1,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,mg-&gt;documentation()+</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a3cf86cdcd2fb2e853a0bd5be6edb1858">endMemberGroupDocs</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a6e6c176d640939fce848f044037209c8">startMemberGroup</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("--- mg-&gt;writePlainDeclarations ---\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>(&amp;mg-&gt;members(),ol,cd,nd,fd,gd,mod,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac38b30488a0d82de3aa04b7ae30ed48e">endMemberGroup</a>(hasHeader);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// writeVHDLDeclarations</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac38b30488a0d82de3aa04b7ae30ed48e">OutputList::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a3cf86cdcd2fb2e853a0bd5be6edb1858">OutputList::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac13352584de9c19dd2776d49c1e9bf30">OutputList::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad50904387e56ccb6532385bfe525e9a2">OutputList::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ad7bb1f47d3fe0d2bc473093e405f348e">OutputList::endMemberSubtitle</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af6d805d822b673a443308b6363d9c85f">MemberList::getMemberGroupList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa31a7d651481862036f72381f7e2a96d">MemberList::listType</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">OutputList::parseText</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a463c00141b4c3a7f76acd3540052f8f5">PORT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a6e6c176d640939fce848f044037209c8">OutputList::startMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac78054f50bad730b62b3456699d9a350">OutputList::startMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ae7ca8c46242c727aa527ab392db22707">OutputList::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#af6404ab3a071c87189d8b8dd2f0d2ef1">OutputList::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#add8c37a5cb21fb366c941cea862b2285">OutputList::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/memberlisttype/#a861c0ba298083d54ea3396001268f34d">MemberListType::toLabel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#afc394d10d64e221682e9619eef74fde5">writePlainVHDLDeclarations</a>.

Referenced by <a href="#aa99c6269bf6155f83a12ab796edd4acf">writeVhdlDeclarations</a>.
</div>
</div>

### writeVHDLTypeDocumentation() {#a0218e5158efa51df8490073c645c9a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::writeVHDLTypeDocumentation (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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



Declaration at line 166 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1262 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0218e5158efa51df8490073c645c9a79">1262</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* mdef, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasParams = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> hasParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ttype=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> largs=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#a8808d28bf43d889892a8b6bad0793d7d">VhdlDocGen::isVhdlFunction</a>(mdef) || <a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">VhdlDocGen::isProcedure</a>(mdef) || <a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">VhdlDocGen::isProcess</a>(mdef)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nn=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">    nn=nn.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> na=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* memdef=<a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>(na,nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memdef &amp;&amp; memdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(memdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ttype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">    hasParams = <a href="#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>(mdef,ol, mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">isVariable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adb04cd03e2039ecab3a0a8f31ee4c890">VhdlDocGen::isConstraint</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">      largs=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(largs,</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> hasParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3f582b69841bae3ec6f1281604b6f0c8">VhdlDocGen::isLibrary</a>(mdef) || <a href="#aca017e059b8a2972c2cad968800c0564">VhdlDocGen::isPackage</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> hasParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// QCString largs=mdef-&gt;argsString();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> c=largs==</span><span class="doxyHighlightStringLiteral">"context"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brec=largs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"record"</span><span class="doxyHighlight">)  ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!brec &amp;&amp; !c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ttype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c || brec || largs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"units"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">          largs=ttype;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>(mdef,ol,largs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> hasParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a73186f5d1ba5e6c11c6f006708da79a6">VhdlDocGen::isPort</a>(mdef) || <a href="#ae3c19429669d382581ba37aee5f39278">VhdlDocGen::isGeneric</a>(mdef))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// QCString largs=mdef-&gt;argsString();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(largs,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> hasParams;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a>, <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="#adb04cd03e2039ecab3a0a8f31ee4c890">isConstraint</a>, <a href="#ae3c19429669d382581ba37aee5f39278">isGeneric</a>, <a href="#a3f582b69841bae3ec6f1281604b6f0c8">isLibrary</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="#aca017e059b8a2972c2cad968800c0564">isPackage</a>, <a href="#a73186f5d1ba5e6c11c6f006708da79a6">isPort</a>, <a href="#aed906dd71cdcb8aca1bc6e3f9fba9732">isProcedure</a>, <a href="#a212ea7da7de8f22c3ca1dd14a38a67ef">isProcess</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ad7b6f788b487058e9e6ac65b092479b9">MemberDef::isVariable</a>, <a href="#a8808d28bf43d889892a8b6bad0793d7d">isVhdlFunction</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>, <a href="#aee87f24daab068f794ea908f33a86c3f">writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a> and <a href="#a81b6f99e6d3882e29a2a4ff830741c77">writeRecUnitDocu</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### compareArgList() {#a12798636d1b8304132df8d68d293d6d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VhdlDocGen::compareArgList (const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;, const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;)</td>
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



Definition at line 224 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>.
</div>
</div>

### findAllArchitectures() {#a9e5659d6cb4369b41809c279d006b44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::findAllArchitectures (std::vector&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &gt; &amp; ql, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



Declaration at line 223 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 532 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e5659d6cb4369b41809c279d006b44c">532</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e5659d6cb4369b41809c279d006b44c">VhdlDocGen::findAllArchitectures</a>(std::vector&lt;QCString&gt;&amp; qll,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;citer : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> className=citer-&gt;className();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd != citer.get() &amp;&amp; (pos=className.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> postfix=className.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(pos+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">className</a>(),postfix)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">        qll.push_back(className);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">// for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">//findAllArchitectures</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a2bdad1ebef918dac2ae32233c26ef723">ClassDef::className</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>.

Referenced by <a href="#a67f47b8dc11d967ee47e9bda86fff7e0">writeInlineClassLink</a>.
</div>
</div>

### writeRecordUnit() {#ad197f46fa25960c771c0e8b897ded06d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeRecordUnit (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; largs, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ltype, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> * mdef)</td>
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



Declaration at line 228 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2266 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad197f46fa25960c771c0e8b897ded06d">2266</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">  <a href="#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* largs */</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ltype,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol ,<a href="/web-doxygen/docs/api/classes/memberdefmutable">MemberDefMutable</a> *mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//sets the real record member name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">    mdef-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a22b8c8f07db7eb0435d27a79d2d32655">setName</a>(mdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(mdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ltype.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(ltype,ol,mdef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a22b8c8f07db7eb0435d27a79d2d32655">DefinitionMutable::setName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>.

Referenced by <a href="#a99c857205029d5e52c0a7c26f18ef3ed">writeVHDLDeclaration</a>.
</div>
</div>

### writeRecUnitDocu() {#a81b6f99e6d3882e29a2a4ff830741c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeRecUnitDocu (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> largs)</td>
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



Declaration at line 227 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2286 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81b6f99e6d3882e29a2a4ff830741c77">2286</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> largs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(largs.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len=ql.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">startParameterList</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;len;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ql[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">startParameterType</a>(first,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">endParameterType</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">startParameterName</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">VhdlDocGen::formatString</a>(n,ol,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">endParameterName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((len-i)&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">    first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">//#</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">OutputList::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">OutputList::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">OutputList::endParameterType</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#aacccadab8f7d60dc0e4b2892ea724c2b">formatString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">OutputList::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">OutputList::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">OutputList::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">OutputList::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a0218e5158efa51df8490073c645c9a79">writeVHDLTypeDocumentation</a>.
</div>
</div>

### writeStringLink() {#abdbd7a613237d2a86532bfe548209a1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeStringLink (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * mdef, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mem, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
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




writes a link if the string is linkable else a formatted string

Declaration at line 226 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 1815 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abdbd7a613237d2a86532bfe548209a1d">1815</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *mdef,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mem, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd=mdef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a>* memdef=<a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">VhdlDocGen::findMember</a>(n,mem);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memdef &amp;&amp; memdef-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>(memdef,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">        ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>(mem,</span><span class="doxyHighlightStringLiteral">"vhdlchar"</span><span class="doxyHighlight">,ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">// found component</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="#ab6898e9270508ce95ad8ebb5ecbedaa6">findMember</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a> and <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>.

Referenced by <a href="#a0b58904c2803fe64c007b6c3ddda086e">writeFormatString</a>.
</div>
</div>

### writeVhdlLink() {#a6e37fa3f47b3d836813a1cf2a7fef036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlDocGen::writeVhdlLink (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cdd, <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; beh)</td>
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



Declaration at line 225 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 570 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e37fa3f47b3d836813a1cf2a7fef036">570</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>* ccd ,<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a>&amp; ol,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; type,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; nn,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; behav)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ccd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">  nn.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(ccd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>(),ccd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),nn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!behav.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">    behav.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">startBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(behav);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">OutputList::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">OutputList::writeObjectLink</a>.

Referenced by <a href="#a67f47b8dc11d967ee47e9bda86fff7e0">writeInlineClassLink</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
