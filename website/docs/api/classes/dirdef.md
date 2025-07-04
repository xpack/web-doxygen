---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dirdef
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DirDef` Class Reference

<p>A model of a directory symbol. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DirDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dirdef-h">src/dirdef.h</a>&gt;
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa198c67f6d58fdae57c8502913ed35d7">shortName</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fe601b4ae16a054ac736cca97548ed3">addSubDir</a> (DirDef *subdir)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af40b99e4906aef816aa768682712df74">getFiles</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c119d890d9b9ae662b007099f53a743">addFile</a> (FileDef *fd)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc75cce4fc67690a3ebbd158e3d63938">subDirs</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5aedb69f8e651bb29d872f2f143a8d">hasSubdirs</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033ad6b8c0287ed15da29dadca48eb6f">level</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddd6f5e08f9a04cc43cf15e388bc2af">parent</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa1d07e132f8bd8d7f2ee10e712e978">dirIndex</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dirdef/useddirlinkedmap">UsedDirLinkedMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf2258b5d619e2eb34f09dd33d34de0f">usedDirs</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f20c877247e4d8d75c9bbd560ce8ea8">isParentOf</a> (const DirDef *dir) const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e56a10ce2c4dc81dd0d2124ba770166">depGraphIsTrivial</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b6f68862a45953981fccc3ffd549a2">shortTitle</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8085285cb7436bd9dce9221dee46b05c">hasDetailedDescription</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b146ceae4f86a05243c6410932e0df">writeDocumentation</a> (OutputList &amp;ol)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eab2330477387d00617df76a77645b7">writeTagFile</a> (TextStream &amp;t)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6abc229cda99ea58cd1baf0f5f9947">setDiskName</a> (const QCString &amp;name)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3263b4e2536de932eb0f765023da57">setDirIndex</a> (int index)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a8557aa86a9e48a43f8d323263ed77">sort</a> ()=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813174b06fcb3d896bfb6eecec0a5b85">setParent</a> (DirDef *parent)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f12566739a8f408796d45d77e53d34">setLevel</a> ()=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7080956a2fe6049dc2fa115cfd1aef5b">addUsesDependency</a> (const DirDef *usedDir, const FileDef *srcFd, const FileDef *dstFd, bool srcDirect, bool dstDirect)=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30adfc53f0749f09c2e633841872739b">computeDependencies</a> ()=0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfe0be42e2ba6482648633cefdf3a06">hasDirectoryGraph</a> () const =0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26dd3df593f8ab9e0f082f3b72d5805">overrideDirectoryGraph</a> (bool e)=0</td>
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

<p>A model of a directory symbol.</p>

<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### addFile() {#a1c119d890d9b9ae662b007099f53a743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::addFile (<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>.</p>

</div>
</div>

### addSubDir() {#a3fe601b4ae16a054ac736cca97548ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::addSubDir (<a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * subdir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### addUsesDependency() {#a7080956a2fe6049dc2fa115cfd1aef5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::addUsesDependency (const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * usedDir, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * srcFd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * dstFd, bool srcDirect, bool dstDirect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>.</p>

</div>
</div>

### computeDependencies() {#a30adfc53f0749f09c2e633841872739b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::computeDependencies ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### depGraphIsTrivial() {#a9e56a10ce2c4dc81dd0d2124ba770166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool DirDef::depGraphIsTrivial ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### dirIndex() {#a5fa1d07e132f8bd8d7f2ee10e712e978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int DirDef::dirIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>.</p>

</div>
</div>

### getFiles() {#af40b99e4906aef816aa768682712df74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const FileList &amp; DirDef::getFiles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab4880c04672f3a3dbf9e7d5f519b845f">dirHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#af23bb9f6e1a0a0bddb2da660425f7da4">generateXMLForDir</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>.</p>

</div>
</div>

### hasDetailedDescription() {#a8085285cb7436bd9dce9221dee46b05c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool DirDef::hasDetailedDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### hasDirectoryGraph() {#a8dfe0be42e2ba6482648633cefdf3a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool DirDef::hasDirectoryGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### hasSubdirs() {#afa5aedb69f8e651bb29d872f2f143a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool DirDef::hasSubdirs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>.</p>

</div>
</div>

### isParentOf() {#a0f20c877247e4d8d75c9bbd560ce8ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool DirDef::isParentOf (const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### level() {#a033ad6b8c0287ed15da29dadca48eb6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int DirDef::level ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a20837cde372c359b1ce5070096d472e0">isAtMaxDepth</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a06bc59d070bef262bba33da842fde24c">DirDefImpl::setLevel</a>.</p>

</div>
</div>

### overrideDirectoryGraph() {#ac26dd3df593f8ab9e0f082f3b72d5805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::overrideDirectoryGraph (bool e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>.</p>

</div>
</div>

### parent() {#a6ddd6f5e08f9a04cc43cf15e388bc2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual DirDef * DirDef::parent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a66144b339b4b4744d7d7ab092ed16e34">DirDefImpl::isParentOf</a>, <a href="#a813174b06fcb3d896bfb6eecec0a5b85">setParent</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a> and <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8bb54d0765a6b45bf091337783b4680a">writePartialDirPath</a>.</p>

</div>
</div>

### setDirIndex() {#aea3263b4e2536de932eb0f765023da57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::setDirIndex (int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### setDiskName() {#afe6abc229cda99ea58cd1baf0f5f9947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::setDiskName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Reference <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>

</div>
</div>

### setLevel() {#a14f12566739a8f408796d45d77e53d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::setLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a06bc59d070bef262bba33da842fde24c">DirDefImpl::setLevel</a>.</p>

</div>
</div>

### setParent() {#a813174b06fcb3d896bfb6eecec0a5b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::setParent (<a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Reference <a href="#a6ddd6f5e08f9a04cc43cf15e388bc2af">parent</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a29208422e0e3f2fb904e071fecd7986b">DirDefImpl::addSubDir</a>.</p>

</div>
</div>

### shortName() {#aa198c67f6d58fdae57c8502913ed35d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const QCString DirDef::shortName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a868969982c8fee16854bcc7735cd977e">compareDirDefs</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a08a51ed53b0b61d7839aa40d04080f9d">DirDefImpl::createNewDir</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a> and <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8bb54d0765a6b45bf091337783b4680a">writePartialDirPath</a>.</p>

</div>
</div>

### shortTitle() {#af8b6f68862a45953981fccc3ffd549a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString DirDef::shortTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### sort() {#a04a8557aa86a9e48a43f8d323263ed77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### subDirs() {#abc75cce4fc67690a3ebbd158e3d63938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const DirList &amp; DirDef::subDirs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab4880c04672f3a3dbf9e7d5f519b845f">dirHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#af23bb9f6e1a0a0bddb2da660425f7da4">generateXMLForDir</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>.</p>

</div>
</div>

### usedDirs() {#acf2258b5d619e2eb34f09dd33d34de0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const UsedDirLinkedMap &amp; DirDef::usedDirs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a> and <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a>.</p>

</div>
</div>

### writeDocumentation() {#a18b146ceae4f86a05243c6410932e0df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

### writeTagFile() {#a6eab2330477387d00617df76a77645b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void DirDef::writeTagFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
