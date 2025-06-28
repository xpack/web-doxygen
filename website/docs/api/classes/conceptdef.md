---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/conceptdef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ConceptDef` Class Reference



## Declaration

<div class="doxyDeclaration">
class ConceptDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/conceptdef-h">src/conceptdef.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb00801461a766bf65806e07f241faa">hasDetailedDescription</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c84ee0b30b5f9ccd3df69135b57b8">includeInfo</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc85d76254ee240faaf13633a0639ba">getTemplateParameterList</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3f52dc1f9634dfa1f1c0702f918e81">initializer</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a825b1919254a35b14906922cc2fb2c60">writeDeclarationLink</a> (OutputList &amp;ol, bool &amp;found, const QCString &amp;header, bool localNames) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c3f2f2547ecee0747b50d7fc06e04ef">getNamespaceDef</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0ed9ee2cbf2c93f995d74cc66d5399">getFileDef</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22d1722d752a5036bbf9e7740ce627f">getModuleDef</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa525b7f265d7f3d5ccb94b368cd2386f">title</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad913c61003e396a42d00f5a95cbbbeaf">groupId</a> () const =0</td>
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


<p>Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### getFileDef() {#aeb0ed9ee2cbf2c93f995d74cc66d5399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const FileDef * ConceptDef::getFileDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#aeb0ed9ee2cbf2c93f995d74cc66d5399">getFileDef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a67d97db3c717b89b9a6211ae48e9273b">findModuleDef</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aac5793331bb86627d87dd42dcaa637b4">generateXMLForConcept</a>, <a href="#aeb0ed9ee2cbf2c93f995d74cc66d5399">getFileDef</a>, <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#aa671cbcf01bbf8c35cf41d13ac9d6893">ConceptDefAliasImpl::getFileDef</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a48aeba774bb636ba277d83e94b205291">writeTemplateList</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ac0b889d39e09da6746de7b90d6de3ad0">writeTemplateList</a>.
</div>
</div>

### getModuleDef() {#aa22d1722d752a5036bbf9e7740ce627f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ModuleDef * ConceptDef::getModuleDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#aa22d1722d752a5036bbf9e7740ce627f">getModuleDef</a>.

Referenced by <a href="#aa22d1722d752a5036bbf9e7740ce627f">getModuleDef</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a522e825388ef007a54952f47999dc4f1">ConceptDefAliasImpl::getModuleDef</a>.
</div>
</div>

### getNamespaceDef() {#a9c3f2f2547ecee0747b50d7fc06e04ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const NamespaceDef * ConceptDef::getNamespaceDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a9c3f2f2547ecee0747b50d7fc06e04ef">getNamespaceDef</a>.

Referenced by <a href="#a9c3f2f2547ecee0747b50d7fc06e04ef">getNamespaceDef</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a431f10112903420524c8ed80e3977b75">ConceptDefAliasImpl::getNamespaceDef</a>.
</div>
</div>

### getTemplateParameterList() {#a3dc85d76254ee240faaf13633a0639ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual ArgumentList ConceptDef::getTemplateParameterList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a3dc85d76254ee240faaf13633a0639ba">getTemplateParameterList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a57fa20826d8322a1247f63872fade06f">addTemplateList</a>, <a href="#a3dc85d76254ee240faaf13633a0639ba">getTemplateParameterList</a>, <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a9671c75fea49e1cbf0d24f70cfdb5649">ConceptDefAliasImpl::getTemplateParameterList</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a48aeba774bb636ba277d83e94b205291">writeTemplateList</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ac0b889d39e09da6746de7b90d6de3ad0">writeTemplateList</a>.
</div>
</div>

### groupId() {#ad913c61003e396a42d00f5a95cbbbeaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int ConceptDef::groupId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#ad913c61003e396a42d00f5a95cbbbeaf">groupId</a>.

Referenced by <a href="#ad913c61003e396a42d00f5a95cbbbeaf">groupId</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a62b03a6340cf9cba13660cd2ee4f788c">ConceptDefAliasImpl::groupId</a>.
</div>
</div>

### hasDetailedDescription() {#accb00801461a766bf65806e07f241faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ConceptDef::hasDetailedDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#accb00801461a766bf65806e07f241faa">hasDetailedDescription</a>.

Referenced by <a href="#accb00801461a766bf65806e07f241faa">hasDetailedDescription</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a779cb6cecef73ed77f3753ab2d5133ca">ConceptDefAliasImpl::hasDetailedDescription</a>.
</div>
</div>

### includeInfo() {#a4a1c84ee0b30b5f9ccd3df69135b57b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const IncludeInfo * ConceptDef::includeInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a4a1c84ee0b30b5f9ccd3df69135b57b8">includeInfo</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#ac1f8e6fa454368157eb7cdb564ee6a40">PerlModGenerator::generatePerlModForConcept</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aac5793331bb86627d87dd42dcaa637b4">generateXMLForConcept</a>, <a href="#a4a1c84ee0b30b5f9ccd3df69135b57b8">includeInfo</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a748463776e82566bf28a107112c91906">ConceptDefAliasImpl::includeInfo</a>.
</div>
</div>

### initializer() {#a1d3f52dc1f9634dfa1f1c0702f918e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ConceptDef::initializer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a1d3f52dc1f9634dfa1f1c0702f918e81">initializer</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#ac1f8e6fa454368157eb7cdb564ee6a40">PerlModGenerator::generatePerlModForConcept</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aac5793331bb86627d87dd42dcaa637b4">generateXMLForConcept</a>, <a href="#a1d3f52dc1f9634dfa1f1c0702f918e81">initializer</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#a6e1277dac905c15297702f979b78f424">ConceptDefAliasImpl::initializer</a>.
</div>
</div>

### title() {#aa525b7f265d7f3d5ccb94b368cd2386f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ConceptDef::title ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#aa525b7f265d7f3d5ccb94b368cd2386f">title</a>.

Referenced by <a href="#aa525b7f265d7f3d5ccb94b368cd2386f">title</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#ac743fbe417cb5acf1f79e6369f357720">ConceptDefAliasImpl::title</a>.
</div>
</div>

### writeDeclarationLink() {#a825b1919254a35b14906922cc2fb2c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDef::writeDeclarationLink (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol, bool &amp; found, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header, bool localNames)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a825b1919254a35b14906922cc2fb2c60">writeDeclarationLink</a>.

Referenced by <a href="#a825b1919254a35b14906922cc2fb2c60">writeDeclarationLink</a> and <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#aa2734a1141fc21435d070d167ac98048">ConceptDefAliasImpl::writeDeclarationLink</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
