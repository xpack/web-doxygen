---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/conceptdefmutable
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ConceptDefMutable` Class Reference



## Declaration

<div class="doxyDeclaration">
class ConceptDefMutable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/conceptdef-h">src/conceptdef.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8529a2b82c87e29a8745644bf48ddf98">setIncludeFile</a> (FileDef *fd, const QCString &amp;incName, bool local, bool force)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb821b50428c9a2f1db4b15590152168">setTemplateArguments</a> (const ArgumentList &amp;al)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afea314262cd0e59dcacd0fef974e0891">setNamespace</a> (NamespaceDef *nd)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70261b250e44a6ea6217b70167e58711">setFileDef</a> (FileDef *fd)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff1e192cf1e4d4ce9c809d0e487d538">writeTagFile</a> (TextStream &amp;)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ac93bdff9848bc001e93f55ccb4d71">writeDocumentation</a> (OutputList &amp;ol)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f5756b0da1dc49c05e9eb6af214016">setInitializer</a> (const QCString &amp;init)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9c676ae5e9ac665306b370a1959446">findSectionsInDocumentation</a> ()=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4ffd35c01c274db2c20a6a32c9e63c">setGroupId</a> (int id)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa31429fc142be78fdbe11ff30e933960">setModuleDef</a> (ModuleDef *mod)=0</td>
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


<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### findSectionsInDocumentation() {#afa9c676ae5e9ac665306b370a1959446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::findSectionsInDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00056">56</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#afa9c676ae5e9ac665306b370a1959446">findSectionsInDocumentation</a>.

Referenced by <a href="#afa9c676ae5e9ac665306b370a1959446">findSectionsInDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad0183e79b7d98cfc8d0fd1b32efa27d5">findSectionsInDocumentation</a>.
</div>
</div>

### setFileDef() {#a70261b250e44a6ea6217b70167e58711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setFileDef (<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a70261b250e44a6ea6217b70167e58711">setFileDef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a> and <a href="#a70261b250e44a6ea6217b70167e58711">setFileDef</a>.
</div>
</div>

### setGroupId() {#add4ffd35c01c274db2c20a6a32c9e63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setGroupId (int id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00057">57</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#add4ffd35c01c274db2c20a6a32c9e63c">setGroupId</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a> and <a href="#add4ffd35c01c274db2c20a6a32c9e63c">setGroupId</a>.
</div>
</div>

### setIncludeFile() {#a8529a2b82c87e29a8745644bf48ddf98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setIncludeFile (<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; incName, bool local, bool force)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00049">49</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a8529a2b82c87e29a8745644bf48ddf98">setIncludeFile</a>.

Referenced by <a href="#a8529a2b82c87e29a8745644bf48ddf98">setIncludeFile</a>.
</div>
</div>

### setInitializer() {#a83f5756b0da1dc49c05e9eb6af214016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setInitializer (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; init)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a83f5756b0da1dc49c05e9eb6af214016">setInitializer</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a> and <a href="#a83f5756b0da1dc49c05e9eb6af214016">setInitializer</a>.
</div>
</div>

### setModuleDef() {#aa31429fc142be78fdbe11ff30e933960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setModuleDef (<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

References <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#a6278cdad145147794f426e0415f7f2cd">createConceptDef</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#ac3907be09ae35f7ef088faa47d2d6a06">createConceptDefAlias</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="#aa31429fc142be78fdbe11ff30e933960">setModuleDef</a>.

Referenced by <a href="#aa31429fc142be78fdbe11ff30e933960">setModuleDef</a>.
</div>
</div>

### setNamespace() {#afea314262cd0e59dcacd0fef974e0891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setNamespace (<a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00051">51</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#afea314262cd0e59dcacd0fef974e0891">setNamespace</a>.

Referenced by <a href="#afea314262cd0e59dcacd0fef974e0891">setNamespace</a>.
</div>
</div>

### setTemplateArguments() {#afb821b50428c9a2f1db4b15590152168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::setTemplateArguments (const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00050">50</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#afb821b50428c9a2f1db4b15590152168">setTemplateArguments</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a> and <a href="#afb821b50428c9a2f1db4b15590152168">setTemplateArguments</a>.
</div>
</div>

### writeDocumentation() {#ad3ac93bdff9848bc001e93f55ccb4d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#ad3ac93bdff9848bc001e93f55ccb4d71">writeDocumentation</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae7c1288552887f734e87c470ea2c91c1">generateConceptDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34eca88c480e8203f29afff92f5393df">generateNamespaceConceptDocs</a> and <a href="#ad3ac93bdff9848bc001e93f55ccb4d71">writeDocumentation</a>.
</div>
</div>

### writeTagFile() {#a7ff1e192cf1e4d4ce9c809d0e487d538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void ConceptDefMutable::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/conceptdef-h/#l00053">53</a> of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>

Reference <a href="#a7ff1e192cf1e4d4ce9c809d0e487d538">writeTagFile</a>.

Referenced by <a href="#a7ff1e192cf1e4d4ce9c809d0e487d538">writeTagFile</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>.
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
