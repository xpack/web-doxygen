---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/moduledef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ModuleDef` Class Reference



## Declaration

<div class="doxyDeclaration">
class ModuleDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/moduledef-h">src/moduledef.h</a>&gt;
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#a82a3183d65cc275d89f034e34e8441ad">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a82a3183d65cc275d89f034e34e8441ad">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12e647dac4252e05f6fb1ee7baca63e">moduleType</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4cd5c7bdf1a32b417a91bef67922ac">partitionName</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6475ff59e947a37cd72298df322c7f">writeDocumentation</a> (OutputList &amp;ol)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7976078c9a788d21dfd6c45ad10ee3b3">isPrimaryInterface</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d36e2cd44ba84b804f14cec1f079c4">getMemberList</a> (MemberListType lt) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabba3ab3dd5ccde53dc5208a768e237d">getMemberLists</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b6c98c1199174f0cb721735c589d67">getMemberGroups</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700be2bc780c86774c4f5bee08316f0a">countVisibleMembers</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb422153b08d7da56d56a96acba60370">getClasses</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade149e97f8df65bf64a4833caa43c6de">getConcepts</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4be407234caa61526c302a84515ae84">getFileDef</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/moduledef-h/#ad2e25aa6a36e0c0605e01d8df04203a6">ImportInfoMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1734f3b5ad6bf0e63dba2e560bd16101">getImports</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/moduledef-h/#ad2e25aa6a36e0c0605e01d8df04203a6">ImportInfoMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4544f603eb8890d545250d45406ae85">getExports</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/moduledef-h/#a2f3a0410bbdf86a1d5d0071667395ac1">ModuleMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76e79082a9b20245851ecbb0fa7ba394">partitions</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c4c80fbac9be1a16e4d081eeea2497">writeTagFile</a> (TextStream &amp;tagFile) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filelist">FileList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac88969f1e19df5e0444bcef41af2ed79">getUsedFiles</a> () const =0</td>
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


<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### Type {#a82a3183d65cc275d89f034e34e8441ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class ModuleDef::Type </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Interface<a id="a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Implementation<a id="a82a3183d65cc275d89f034e34e8441adab672f52ade975e864ae6b58722c03689"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00069">69</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">Interface</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82a3183d65cc275d89f034e34e8441adab672f52ade975e864ae6b58722c03689">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a82a3183d65cc275d89f034e34e8441adab672f52ade975e864ae6b58722c03689">Implementation</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### countVisibleMembers() {#a700be2bc780c86774c4f5bee08316f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int ModuleDef::countVisibleMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00081">81</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### getClasses() {#aeb422153b08d7da56d56a96acba60370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ClassLinkedRefMap &amp; ModuleDef::getClasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00082">82</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### getConcepts() {#ade149e97f8df65bf64a4833caa43c6de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ConceptLinkedRefMap &amp; ModuleDef::getConcepts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00083">83</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### getExports() {#ad4544f603eb8890d545250d45406ae85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ImportInfoMap &amp; ModuleDef::getExports ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00086">86</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>.
</div>
</div>

### getFileDef() {#af4be407234caa61526c302a84515ae84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual FileDef * ModuleDef::getFileDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00084">84</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/modulemanager/#a4ec82e2c6d7aac89ee42416993ce59da">ModuleManager::resolveImports</a> and <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a16de9b0536cf33e6b6380cf55ecb3ca5">ModuleDefImpl::sortMemberLists</a>.
</div>
</div>

### getImports() {#a1734f3b5ad6bf0e63dba2e560bd16101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ImportInfoMap &amp; ModuleDef::getImports ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00085">85</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/modulemanager/#abe59aee08bdd26b109a69b54f6e018ab">ModuleManager::resolvePartitionsRecursively</a>.
</div>
</div>

### getMemberGroups() {#a58b6c98c1199174f0cb721735c589d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberGroupList &amp; ModuleDef::getMemberGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00080">80</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>.
</div>
</div>

### getMemberList() {#a46d36e2cd44ba84b804f14cec1f079c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual MemberList * ModuleDef::getMemberList (<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> lt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a98f02f28ab5ec9b1a51543a7ef4ba1ab">writeModuleMembers</a>.
</div>
</div>

### getMemberLists() {#aabba3ab3dd5ccde53dc5208a768e237d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const MemberLists &amp; ModuleDef::getMemberLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00079">79</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>.
</div>
</div>

### getUsedFiles() {#ac88969f1e19df5e0444bcef41af2ed79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual FileList ModuleDef::getUsedFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00089">89</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2b0628c4001ddb19730a764b29b0be44">generateSqlite3ForModule</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>.
</div>
</div>

### isPrimaryInterface() {#a7976078c9a788d21dfd6c45ad10ee3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool ModuleDef::isPrimaryInterface ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00077">77</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>

Referenced by <a href="/web-doxygen/docs/api/classes/index/#a90c09c50cfa52cf8893122a2bcdd479b">Index::addModuleMemberNameToIndex</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>.
</div>
</div>

### moduleType() {#aa12e647dac4252e05f6fb1ee7baca63e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Type ModuleDef::moduleType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00074">74</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>
</div>
</div>

### partitionName() {#a0c4cd5c7bdf1a32b417a91bef67922ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString ModuleDef::partitionName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00075">75</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>
</div>
</div>

### partitions() {#a76e79082a9b20245851ecbb0fa7ba394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const ModuleMap &amp; ModuleDef::partitions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00087">87</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>
</div>
</div>

### writeDocumentation() {#abe6475ff59e947a37cd72298df322c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ModuleDef::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00076">76</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>
</div>
</div>

### writeTagFile() {#af5c4c80fbac9be1a16e4d081eeea2497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ModuleDef::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; tagFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/moduledef-h/#l00088">88</a> of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
