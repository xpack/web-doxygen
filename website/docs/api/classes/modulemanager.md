---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/modulemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ModuleManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class ModuleManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/moduledef-h">src/moduledef.h</a>&gt;
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager</a> ()</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14868f4f33ffb566217d87d8aab83d5a">~ModuleManager</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e2356fcdbce7babc9b65ba24be66fc9">createModuleDef</a> (const QCString &amp;fileName, int line, int column, bool exported, const QCString &amp;moduleName, const QCString &amp;partitionName=QCString())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c52b0e721084bfe1ebaa565674a736d">clear</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c564c642161994958220628ac58aef8">addHeader</a> (const QCString &amp;moduleFile, int line, const QCString &amp;headerName, bool isSystem)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e02d3fa979bbdad8d4995915a9f834">addImport</a> (const QCString &amp;moduleFile, int line, const QCString &amp;importName, bool isExported, const QCString &amp;partitionName=QCString())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2ffe69d7a921c13b6d0e16918a250d">addClassToModule</a> (const Entry *root, ClassDef *cd)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6698b2bf23de9dc94a27ad7b898c205b">addConceptToModule</a> (const Entry *root, ConceptDef *cd)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eaf52205769b3910d40de52c5eefd51">addMemberToModule</a> (const Entry *root, MemberDef *md)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c2fea37704d58f2127c5f892851b48">addDocs</a> (const Entry *root)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698e0a915bfb6a6d27731b5290580c96">addTagInfo</a> (const QCString &amp;moduleFile, const QCString &amp;tagName, const QCString &amp;clangId)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c75f10f5345207329e3468f53416b55">addListReferences</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92f20a151f253a36ec65c90e3da01a81">addMembersToMemberGroup</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b3d835cba0b9c103a0f5c274a0ac44">distributeMemberGroupDocumentation</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e165a10a456a00a6735f9a7ae4d74a">findSectionsInDocumentation</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ab9d867637b915d193705ede03cc32">sortMemberLists</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5ccba7154d90c27699bad5517f8b18">resolvePartitions</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec82e2c6d7aac89ee42416993ce59da">resolveImports</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd67a3f8ef0181d7a4179931452449df">collectExportedSymbols</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5dfdf8729dadf9a45fa931f88d94ac">countMembers</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9030220578ccc7735cdc9ffddf539d79">writeDocumentation</a> (OutputList &amp;ol)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f8092eef42a35f8f8e03f19e83bc08">numDocumentedModules</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67868bc8d9b96f5e5812ad1f677d4765">modules</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecdc9e1a3ae62f9eee56d612ec1dfd7">modules</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a> (const QCString &amp;moduleName) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a> (ModuleDef *intfMod, ModuleDef *mod)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ebe7e944c71ea43b47da0b331789ab">collectExportedSymbolsRecursively</a> (ModuleDef *intfMod, ModuleDef *mod)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/modulemanager/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/modulemanager">ModuleManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f48cf5d05907a6acc4b9c6ddec752b7">instance</a> ()</td>
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


<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### ModuleManager() {#a2940b3dd370b9c454c7cc600c540bb0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleManager::ModuleManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1221 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2940b3dd370b9c454c7cc600c540bb0e">1221</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager::ModuleManager</a>() : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/modulemanager/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>.</p>


<p>Referenced by <a href="#a4f48cf5d05907a6acc4b9c6ddec752b7">instance</a> and <a href="#a14868f4f33ffb566217d87d8aab83d5a">~ModuleManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~ModuleManager() {#a14868f4f33ffb566217d87d8aab83d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleManager::~ModuleManager ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>


<p>Reference <a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addClassToModule() {#a6e2ffe69d7a921c13b6d0e16918a250d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addClassToModule (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1291 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e2ffe69d7a921c13b6d0e16918a250d">1291</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e2ffe69d7a921c13b6d0e16918a250d">ModuleManager::addClassToModule</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.find(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a48485218477ceb4bff6608fb8c7d1d45">addClassToModule</a>(root,cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> cdm = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cdm) cdm-&gt;setModuleDef(mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a48485218477ceb4bff6608fb8c7d1d45">ModuleDefImpl::addClassToModule</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a2d0bf73f7801534e7e2b6e5fc03ed6f5">toClassDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>.</p>

</div>
</div>

### addConceptToModule() {#a6698b2bf23de9dc94a27ad7b898c205b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addConceptToModule (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1303 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6698b2bf23de9dc94a27ad7b898c205b">1303</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6698b2bf23de9dc94a27ad7b898c205b">ModuleManager::addConceptToModule</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.find(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3bed85d27e567e04fe01b0192a58db97">addConceptToModule</a>(root,cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> cdm = <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cdm) cdm-&gt;setModuleDef(mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3bed85d27e567e04fe01b0192a58db97">ModuleDefImpl::addConceptToModule</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>.</p>

</div>
</div>

### addDocs() {#a55c2fea37704d58f2127c5f892851b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addDocs (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1551 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55c2fea37704d58f2127c5f892851b48">1551</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a55c2fea37704d58f2127c5f892851b48">ModuleManager::addDocs</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"file={} module={}"</span><span class="doxyHighlight">,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">brief</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span><span class="doxyHighlightStringLiteral">"Ignoring documentation for module partition {}. Please place documentation at the primary module name"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">        root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.find(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod = <a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">setDocumentation</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac6841c6ec8fd7ae6121364e7e1895e94">docFile</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">docLine</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">setBriefDescription</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">brief</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a9a0b7ed65e6082088ededf633771d3d1">briefFile</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#add7a19978ab2b30a9755b8d5e3cbd00a">briefLine</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#ac56880b010eb61a4abad5169d9883812">setId</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a338fb12273a1a4f5dc124a1faf47d473">id</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a2aeddc8e815902e89321704b079a7e9a">setHidden</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#acc4d59ae7ae3e94c3365ab8027593727">hidden</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a21f0601d0ac0f9d245c7a40e28adc3c6">setBodySegment</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a9a2b1e3404f4723d8a6bef5966146ed0">bodyLine</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a2db88158279ecfe391ea775f63869fc1">endBodyLine</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">        mod-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#af9e3dad84347230faa673e71db8d0c87">setRefItems</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac5f693ab011ce4fcc391a3bc95b0307d">sli</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//mod-&gt;addSectionsToDefinition(root-&gt;anchors);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>(root,mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span><span class="doxyHighlightStringLiteral">"Found documentation for module {} but it has no primary interface unit."</span><span class="doxyHighlight">,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a>,</span><span class="doxyHighlightStringLiteral">"Found documentation for unknown module {}."</span><span class="doxyHighlight">,root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a623caa8256bca5d7b0f640cd8182bcc6">addModuleToGroups</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/entry/#a9a2b1e3404f4723d8a6bef5966146ed0">Entry::bodyLine</a>, <a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">Entry::brief</a>, <a href="/web-doxygen/docs/api/classes/entry/#a9a0b7ed65e6082088ededf633771d3d1">Entry::briefFile</a>, <a href="/web-doxygen/docs/api/classes/entry/#add7a19978ab2b30a9755b8d5e3cbd00a">Entry::briefLine</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">Entry::doc</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac6841c6ec8fd7ae6121364e7e1895e94">Entry::docFile</a>, <a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">Entry::docLine</a>, <a href="/web-doxygen/docs/api/classes/entry/#a2db88158279ecfe391ea775f63869fc1">Entry::endBodyLine</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a>, <a href="/web-doxygen/docs/api/classes/entry/#acc4d59ae7ae3e94c3365ab8027593727">Entry::hidden</a>, <a href="/web-doxygen/docs/api/classes/entry/#a338fb12273a1a4f5dc124a1faf47d473">Entry::id</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">Entry::name</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a21f0601d0ac0f9d245c7a40e28adc3c6">DefinitionMutable::setBodySegment</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ae704468ccbae4cbc26922db573676feb">DefinitionMutable::setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">DefinitionMutable::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a2aeddc8e815902e89321704b079a7e9a">DefinitionMutable::setHidden</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#ac56880b010eb61a4abad5169d9883812">DefinitionMutable::setId</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#af9e3dad84347230faa673e71db8d0c87">DefinitionMutable::setRefItems</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac5f693ab011ce4fcc391a3bc95b0307d">Entry::sli</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab9145bae1ceb13c316c9ced4b3bbf1d9">findModuleDocumentation</a>.</p>

</div>
</div>

### addHeader() {#a5c564c642161994958220628ac58aef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleFile, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; headerName, bool isSystem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1256 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c564c642161994958220628ac58aef8">1256</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5c564c642161994958220628ac58aef8">ModuleManager::addHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;headerName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isSystem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"{}:{} headerName={} isSystem={}"</span><span class="doxyHighlight">,moduleFile,line,headerName,isSystem);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.find(moduleFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#afbaf12976ba6620dccd9067b26244e51">addHeader</a>(line,headerName,isSystem);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"imported header '{}' found in file '{}' that is not a module"</span><span class="doxyHighlight">,headerName,moduleFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;headers.emplace_back(moduleFile,headerName,isSystem);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#afbaf12976ba6620dccd9067b26244e51">ModuleDefImpl::addHeader</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>

</div>
</div>

### addImport() {#af2e02d3fa979bbdad8d4995915a9f834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addImport (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleFile, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; importName, bool isExported, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; partitionName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1272 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2e02d3fa979bbdad8d4995915a9f834">1272</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af2e02d3fa979bbdad8d4995915a9f834">ModuleManager::addImport</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;importName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isExported,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;partitionName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"{}:{} importName={},isExported={},partitionName={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">      moduleFile,line,importName,isExported,partitionName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.find(moduleFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod) </span><span class="doxyHighlightComment">// import inside a module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"in module"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#acabf04c9722d33c1b5240a56ad93d572">addImport</a>(line,importName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()?mod-&gt;name():importName,partitionName,isExported);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// import outside of a module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"outside module"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;externalImports[moduleFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].emplace_back(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,importName,line,partitionName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#acabf04c9722d33c1b5240a56ad93d572">ModuleDefImpl::addImport</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>

</div>
</div>

### addListReferences() {#a0c75f10f5345207329e3468f53416b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addListReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1605 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c75f10f5345207329e3468f53416b55">1605</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c75f10f5345207329e3468f53416b55">ModuleManager::addListReferences</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#af8b51e8153660a718610d9b6d45c5ece">addListReferences</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#af8b51e8153660a718610d9b6d45c5ece">ModuleDefImpl::addListReferences</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a855be67fd81a52fbfc822a4e4b41cc7e">addListReferences</a>.</p>

</div>
</div>

### addMembersToMemberGroup() {#a92f20a151f253a36ec65c90e3da01a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addMembersToMemberGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1613 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92f20a151f253a36ec65c90e3da01a81">1613</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a92f20a151f253a36ec65c90e3da01a81">ModuleManager::addMembersToMemberGroup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7f60015e8ba306c476a8dd34d0c17b3e">addMembersToMemberGroup</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7f60015e8ba306c476a8dd34d0c17b3e">ModuleDefImpl::addMembersToMemberGroup</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4219b5e9c9b107b0b5380459e032a142">addMembersToMemberGroup</a>.</p>

</div>
</div>

### addMemberToModule() {#a8eaf52205769b3910d40de52c5eefd51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addMemberToModule (const <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root, <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1315 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8eaf52205769b3910d40de52c5eefd51">1315</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8eaf52205769b3910d40de52c5eefd51">ModuleManager::addMemberToModule</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *root,<a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.find(root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod &amp;&amp; root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a2fa31dcb2c0d8d9c4383e638cf1e4f7e">exported</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">addMemberToModule</a>(root,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mdm = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mdm) mdm-&gt;setModuleDef(mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/entry/#a2fa31dcb2c0d8d9c4383e638cf1e4f7e">Entry::exported</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a9ea80ba313803ae565f05ce1c8eb6bb5">toMemberDefMutable</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a745ab96a81d2f900d75b86848050a8a7">addDefineDoc</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>.</p>

</div>
</div>

### addTagInfo() {#a698e0a915bfb6a6d27731b5290580c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::addTagInfo (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; clangId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1327 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a698e0a915bfb6a6d27731b5290580c96">1327</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a698e0a915bfb6a6d27731b5290580c96">ModuleManager::addTagInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tagFile,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;clangId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.find(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a> *modi = <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">    modi-&gt;<a href="/web-doxygen/docs/api/classes/definitionmixin/#a5b7806d54dc3504a626078ac0d22dc19">setReference</a>(tagFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">    modi-&gt;<a href="/web-doxygen/docs/api/classes/definitionmixin/#a34b916976d8f272c97f00d74001fdd0c">setId</a>(clangId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#a34b916976d8f272c97f00d74001fdd0c">DefinitionMixin&lt; Base &gt;::setId</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#a5b7806d54dc3504a626078ac0d22dc19">DefinitionMixin&lt; Base &gt;::setReference</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>

</div>
</div>

### clear() {#a5c52b0e721084bfe1ebaa565674a736d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1247 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c52b0e721084bfe1ebaa565674a736d">1247</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5c52b0e721084bfe1ebaa565674a736d">ModuleManager::clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;headers.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;externalImports.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae12e94f5218f3afc8df4086a2121cd4d">cleanUpDoxygen</a>.</p>

</div>
</div>

### collectExportedSymbols() {#abd67a3f8ef0181d7a4179931452449df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::collectExportedSymbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1481 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd67a3f8ef0181d7a4179931452449df">1481</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd67a3f8ef0181d7a4179931452449df">ModuleManager::collectExportedSymbols</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) </span><span class="doxyHighlightComment">// that is a primary interface</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[partitionName,partitionMod] : mod-&gt;partitions())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a56ebe7e944c71ea43b47da0b331789ab">collectExportedSymbolsRecursively</a>(mod.get(),partitionMod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// collect all files that contribute to this module (e.g. implementation/partition modules)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.find(mod-&gt;name().str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> contributingMod : it-&gt;second)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"  adding contributing module {} to interface module {} type={} partition={} isPrimaryIntf={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">              contributingMod-&gt;qualifiedName(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">              mod-&gt;name(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">              contributingMod-&gt;moduleType()==<a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">ModuleDef::Type::Interface</a> ? </span><span class="doxyHighlightStringLiteral">"Interface"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"Implementation"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">              contributingMod-&gt;partitionName(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">              contributingMod-&gt;isPrimaryInterface());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad73b4b387c45a77c380e316935219960">addContributingModule</a>(<a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(contributingMod));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad73b4b387c45a77c380e316935219960">ModuleDefImpl::addContributingModule</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="#a56ebe7e944c71ea43b47da0b331789ab">collectExportedSymbolsRecursively</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">ModuleDef::Interface</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>

</div>
</div>

### countMembers() {#a5d5dfdf8729dadf9a45fa931f88d94ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::countMembers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1512 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d5dfdf8729dadf9a45fa931f88d94ac">1512</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5d5dfdf8729dadf9a45fa931f88d94ac">ModuleManager::countMembers</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a01e7f4a4b80099931204de9422e35971">countMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a01e7f4a4b80099931204de9422e35971">ModuleDefImpl::countMembers</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>

</div>
</div>

### createModuleDef() {#a7e2356fcdbce7babc9b65ba24be66fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::createModuleDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, int column, bool exported, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; partitionName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1225 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e2356fcdbce7babc9b65ba24be66fc9">1225</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7e2356fcdbce7babc9b65ba24be66fc9">ModuleManager::createModuleDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> column,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> exported,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;partitionName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"{}:{}: Found module name='{}' partition='{}' exported='{}'"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">      fileName,line,moduleName,partitionName,exported);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ad">ModuleDef::Type</a> mt = exported ? <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">ModuleDef::Type::Interface</a> : <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441adab672f52ade975e864ae6b58722c03689">ModuleDef::Type::Implementation</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;ModuleDef&gt; modDef = std::make_unique&lt;ModuleDefImpl&gt;(fileName,line,column,moduleName,mt,partitionName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mod = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap.add(fileName,std::move(modDef));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.find(moduleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it == <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/modulelist">ModuleList</a> ml;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">    ml.push_back(mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.emplace(moduleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),ml);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    it-&gt;second.push_back(mod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441adab672f52ade975e864ae6b58722c03689">ModuleDef::Implementation</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">ModuleDef::Interface</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### distributeMemberGroupDocumentation() {#af3b3d835cba0b9c103a0f5c274a0ac44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::distributeMemberGroupDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1621 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3b3d835cba0b9c103a0f5c274a0ac44">1621</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af3b3d835cba0b9c103a0f5c274a0ac44">ModuleManager::distributeMemberGroupDocumentation</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a0a2898e2921749716d8af3dcc9e952d4">distributeMemberGroupDocumentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a0a2898e2921749716d8af3dcc9e952d4">ModuleDefImpl::distributeMemberGroupDocumentation</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5f7021c47224d92c76642ad8501d5eb6">distributeMemberGroupDocumentation</a>.</p>

</div>
</div>

### findSectionsInDocumentation() {#ab8e165a10a456a00a6735f9a7ae4d74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::findSectionsInDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1629 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8e165a10a456a00a6735f9a7ae4d74a">1629</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8e165a10a456a00a6735f9a7ae4d74a">ModuleManager::findSectionsInDocumentation</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#ab485ec1999243c813656dd89d7ed21f3">findSectionsInDocumentation</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ab485ec1999243c813656dd89d7ed21f3">ModuleDefImpl::findSectionsInDocumentation</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad0183e79b7d98cfc8d0fd1b32efa27d5">findSectionsInDocumentation</a>.</p>

</div>
</div>

### getPrimaryInterface() {#a80b6d2e3602cbd740b728267e66ba355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleDef * ModuleManager::getPrimaryInterface (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; moduleName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 138 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1589 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80b6d2e3602cbd740b728267e66ba355">1589</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *<a href="#a80b6d2e3602cbd740b728267e66ba355">ModuleManager::getPrimaryInterface</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;moduleName)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.find(moduleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : it-&gt;second)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> mod;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a55c2fea37704d58f2127c5f892851b48">addDocs</a>, <a href="#a4ec82e2c6d7aac89ee42416993ce59da">resolveImports</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ab005d7c2cbab0f77eb6a92940d9ce416">writeExports</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>.</p>

</div>
</div>

### modules() {#a67868bc8d9b96f5e5812ad1f677d4765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleLinkedMap &amp; ModuleManager::modules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1546 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67868bc8d9b96f5e5812ad1f677d4765">1546</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a> &amp;<a href="#a67868bc8d9b96f5e5812ad1f677d4765">ModuleManager::modules</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>.</p>

</div>
</div>

### modules() {#acecdc9e1a3ae62f9eee56d612ec1dfd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleLinkedMap &amp; ModuleManager::modules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1541 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acecdc9e1a3ae62f9eee56d612ec1dfd7">1541</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a> &amp;<a href="#a67868bc8d9b96f5e5812ad1f677d4765">ModuleManager::modules</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>.</p>

</div>
</div>

### numDocumentedModules() {#a11f8092eef42a35f8f8e03f19e83bc08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ModuleManager::numDocumentedModules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1531 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a11f8092eef42a35f8f8e03f19e83bc08">1531</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a11f8092eef42a35f8f8e03f19e83bc08">ModuleManager::numDocumentedModules</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/index/#ac2bc41479d376ce6d2e6fb8060a7bd9d">Index::countDataStructures</a>.</p>

</div>
</div>

### resolveImports() {#a4ec82e2c6d7aac89ee42416993ce59da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::resolveImports ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1414 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ec82e2c6d7aac89ee42416993ce59da">1414</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ec82e2c6d7aac89ee42416993ce59da">ModuleManager::resolveImports</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = mod-&gt;getFileDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[fileName,importInfoList] : mod-&gt;getImports())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;importInfo : importInfoList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *importedModule = <a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a>(importInfo.importName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *importedFd = importedModule ? importedModule-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#af4be407234caa61526c302a84515ae84">getFileDef</a>() : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"module: addIncludeDependency {}-&gt;{}:{} fd={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">              mod-&gt;qualifiedName(), importInfo.qualifiedName(), importInfo.line, fd?fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">          fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#af56d10caad769cdcef8b885f09dbb2c6">addIncludeDependency</a>(importedFd,importInfo.<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>(),<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[fileName,importInfoList] : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;externalImports)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;importInfo : importInfoList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(fileName),ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"externalImport name={} fd={}"</span><span class="doxyHighlight">,fileName,(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">*)fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod = <a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a>(importInfo.importName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *importedFd = mod ? mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#af4be407234caa61526c302a84515ae84">getFileDef</a>() : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">        fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#af56d10caad769cdcef8b885f09dbb2c6">addIncludeDependency</a>(importedFd,importInfo.importName,<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (importedFd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">          importedFd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a2a164a0ef6d6c1cf6fc18092dd5430fe">addIncludedByDependency</a>(fd,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(fileName)),<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;headerInfo : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;headers)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,headerInfo.fileName,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"header name={} fd={}"</span><span class="doxyHighlight">,headerInfo.fileName,(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">*)fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> resolvedHeader = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a97fa1635ca734b061444c678b7525475">determineAbsoluteIncludeName</a>(headerInfo.fileName,headerInfo.headerName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *importFd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,resolvedHeader,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">      fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#af56d10caad769cdcef8b885f09dbb2c6">addIncludeDependency</a>(importFd, headerInfo.headerName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">                               headerInfo.isSystem ? <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">IncludeKind::ImportSystem</a> : <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (importFd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">        importFd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a2a164a0ef6d6c1cf6fc18092dd5430fe">addIncludedByDependency</a>(fd,headerInfo.<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>,<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">IncludeKind::ImportModule</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a2a164a0ef6d6c1cf6fc18092dd5430fe">FileDef::addIncludedByDependency</a>, <a href="/web-doxygen/docs/api/classes/filedef/#af56d10caad769cdcef8b885f09dbb2c6">FileDef::addIncludeDependency</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a97fa1635ca734b061444c678b7525475">determineAbsoluteIncludeName</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">FileDef::fileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#af4be407234caa61526c302a84515ae84">ModuleDef::getFileDef</a>, <a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">ImportLocal</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a57522338dd8bf2361634a923a2b71b81">ImportModule</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ac597d64b5224025af7bef1aad3172845">ImportSystem</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>.</p>

</div>
</div>

### resolvePartitions() {#a9a5ccba7154d90c27699bad5517f8b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::resolvePartitions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1381 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a5ccba7154d90c27699bad5517f8b18">1381</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a5ccba7154d90c27699bad5517f8b18">ModuleManager::resolvePartitions</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;moduleType()==<a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">ModuleDef::Type::Interface</a> &amp;&amp; mod-&gt;partitionName().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// that is a primary interface</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a>(mod.get(),mod.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// copy exported imports to m_exportedModules</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[fileName,importInfoList] : mod-&gt;getImports())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;importInfo : importInfoList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (importInfo.exported &amp;&amp; mod-&gt;name()!=importInfo.importName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8399ce3a312563dda063fa5ebcbfb7d4">addExportedModule</a>(importInfo.importName,importInfo);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// also link the ModuleDef and FileDef together</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>,mod-&gt;getDefFileName(),ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">      fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a0294b0d683e277fc4ee9a4e6e375bc33">setModuleDef</a>(mod.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a960231c59e2b71db94ad0cc5ebde5eb1">setFileDef</a>(fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8399ce3a312563dda063fa5ebcbfb7d4">ModuleDefImpl::addExportedModule</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a82a3183d65cc275d89f034e34e8441ada3c1aac82863ed9e5a9aca8ce687f711d">ModuleDef::Interface</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a960231c59e2b71db94ad0cc5ebde5eb1">ModuleDefImpl::setFileDef</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a0294b0d683e277fc4ee9a4e6e375bc33">FileDef::setModuleDef</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>

</div>
</div>

### sortMemberLists() {#a45ab9d867637b915d193705ede03cc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::sortMemberLists ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1637 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a45ab9d867637b915d193705ede03cc32">1637</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a45ab9d867637b915d193705ede03cc32">ModuleManager::sortMemberLists</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface()) <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(mod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a16de9b0536cf33e6b6380cf55ecb3ca5">sortMemberLists</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a16de9b0536cf33e6b6380cf55ecb3ca5">ModuleDefImpl::sortMemberLists</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a510e0aa934874b28d777e3e1d1c13341">sortMemberLists</a>.</p>

</div>
</div>

### writeDocumentation() {#a9030220578ccc7735cdc9ffddf539d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1520 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9030220578ccc7735cdc9ffddf539d79">1520</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9030220578ccc7735cdc9ffddf539d79">ModuleManager::writeDocumentation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleFileMap) </span><span class="doxyHighlightComment">// foreach module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;isPrimaryInterface())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">      mod-&gt;writeDocumentation(ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectExportedSymbolsRecursively() {#a56ebe7e944c71ea43b47da0b331789ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::collectExportedSymbolsRecursively (<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * intfMod, <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1473 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56ebe7e944c71ea43b47da0b331789ab">1473</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a56ebe7e944c71ea43b47da0b331789ab">ModuleManager::collectExportedSymbolsRecursively</a>(<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *intfMod, <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *partitionMod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"{}: collecting symbols for partition {}"</span><span class="doxyHighlight">,intfMod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>(),partitionMod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> intfModImpl      = <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(intfMod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> partitionModImpl = <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(partitionMod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">  intfModImpl-&gt;mergeSymbolsFrom(partitionModImpl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="#abd67a3f8ef0181d7a4179931452449df">collectExportedSymbols</a>.</p>

</div>
</div>

### resolvePartitionsRecursively() {#abe59aee08bdd26b109a69b54f6e018ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleManager::resolvePartitionsRecursively (<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * intfMod, <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1339 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe59aee08bdd26b109a69b54f6e018ab">1339</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abe59aee08bdd26b109a69b54f6e018ab">ModuleManager::resolvePartitionsRecursively</a>(<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *intfMod, <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[partitionFileName,importInfoList] : mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a1734f3b5ad6bf0e63dba2e560bd16101">getImports</a>()) </span><span class="doxyHighlightComment">// foreach import</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;importInfo : importInfoList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"partitionFileName={} importName={} partitionName={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">          partitionFileName,importInfo.importName,importInfo.partitionName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (importInfo.importName==intfMod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() &amp;&amp; !importInfo.partitionName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">          importInfo.exported) </span><span class="doxyHighlightComment">// that is an exported partition of this module</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.find(importInfo.importName.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it != <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>-&gt;moduleNameMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> importedMod : it-&gt;second)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (importedMod-&gt;qualifiedName()==importInfo.importName+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+importInfo.partitionName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"Interface module {} exports partition {}:{}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">                  mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),importedMod-&gt;name(),importedMod-&gt;partitionName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(intfMod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a081e6f14489f0d6aaa301b077bd58dff">addPartition</a>(<a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(importedMod));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(importedMod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a70a5f2c3ffc442c2030107cfe4d181a8">setPrimaryInterface</a>(intfMod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[partitionFileName_,partitionImportInfoList] : importedMod-&gt;getImports())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;partitionImportInfo : partitionImportInfoList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (partitionImportInfo.exported &amp;&amp; intfMod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()!=partitionImportInfo.importName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(intfMod)-&gt;<a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8399ce3a312563dda063fa5ebcbfb7d4">addExportedModule</a>(partitionImportInfo.importName,partitionImportInfo);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">                }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a>(intfMod,importedMod);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8399ce3a312563dda063fa5ebcbfb7d4">ModuleDefImpl::addExportedModule</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a081e6f14489f0d6aaa301b077bd58dff">ModuleDefImpl::addPartition</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a1734f3b5ad6bf0e63dba2e560bd16101">ModuleDef::getImports</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>, <a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a70a5f2c3ffc442c2030107cfe4d181a8">ModuleDefImpl::setPrimaryInterface</a> and <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>.</p>


<p>Referenced by <a href="#a9a5ccba7154d90c27699bad5517f8b18">resolvePartitions</a> and <a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aa5dcfed912fdd26bb8f4385fc1b7128b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; ModuleManager::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aa5dcfed912fdd26bb8f4385fc1b7128b">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a6e2ffe69d7a921c13b6d0e16918a250d">addClassToModule</a>, <a href="#a6698b2bf23de9dc94a27ad7b898c205b">addConceptToModule</a>, <a href="#a55c2fea37704d58f2127c5f892851b48">addDocs</a>, <a href="#a5c564c642161994958220628ac58aef8">addHeader</a>, <a href="#af2e02d3fa979bbdad8d4995915a9f834">addImport</a>, <a href="#a0c75f10f5345207329e3468f53416b55">addListReferences</a>, <a href="#a92f20a151f253a36ec65c90e3da01a81">addMembersToMemberGroup</a>, <a href="#a8eaf52205769b3910d40de52c5eefd51">addMemberToModule</a>, <a href="#a698e0a915bfb6a6d27731b5290580c96">addTagInfo</a>, <a href="#a5c52b0e721084bfe1ebaa565674a736d">clear</a>, <a href="#abd67a3f8ef0181d7a4179931452449df">collectExportedSymbols</a>, <a href="#a5d5dfdf8729dadf9a45fa931f88d94ac">countMembers</a>, <a href="#a7e2356fcdbce7babc9b65ba24be66fc9">createModuleDef</a>, <a href="#af3b3d835cba0b9c103a0f5c274a0ac44">distributeMemberGroupDocumentation</a>, <a href="#ab8e165a10a456a00a6735f9a7ae4d74a">findSectionsInDocumentation</a>, <a href="#a80b6d2e3602cbd740b728267e66ba355">getPrimaryInterface</a>, <a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager</a>, <a href="#a67868bc8d9b96f5e5812ad1f677d4765">modules</a>, <a href="#acecdc9e1a3ae62f9eee56d612ec1dfd7">modules</a>, <a href="#a11f8092eef42a35f8f8e03f19e83bc08">numDocumentedModules</a>, <a href="#a4ec82e2c6d7aac89ee42416993ce59da">resolveImports</a>, <a href="#a9a5ccba7154d90c27699bad5517f8b18">resolvePartitions</a>, <a href="#abe59aee08bdd26b109a69b54f6e018ab">resolvePartitionsRecursively</a>, <a href="#a45ab9d867637b915d193705ede03cc32">sortMemberLists</a> and <a href="#a9030220578ccc7735cdc9ffddf539d79">writeDocumentation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a4f48cf5d05907a6acc4b9c6ddec752b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleManager &amp; ModuleManager::instance ()</td>
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



<p>Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1215 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f48cf5d05907a6acc4b9c6ddec752b7">1215</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager</a> &amp;<a href="#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager</a> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a2940b3dd370b9c454c7cc600c540bb0e">ModuleManager</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a745ab96a81d2f900d75b86848050a8a7">addDefineDoc</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a84f44faa684a361d36970a435c382b0f">addEnumDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ba474a85367760e0e849c9732d5fa26">addInterfaceOrServiceToServiceOrSingleton</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a855be67fd81a52fbfc822a4e4b41cc7e">addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4219b5e9c9b107b0b5380459e032a142">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous_namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae12e94f5218f3afc8df4086a2121cd4d">cleanUpDoxygen</a>, <a href="/web-doxygen/docs/api/classes/index/#ac2bc41479d376ce6d2e6fb8060a7bd9d">Index::countDataStructures</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a777a8d72bf18dc4c572fb70528ec18b2">countMembers</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a2634e192e6fb1db99bb22fb62a9e8c0f">createJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5f7021c47224d92c76642ad8501d5eb6">distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9a5dbcad360a1ad2a8f9403ae344d638">DocbookGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab9145bae1ceb13c316c9ced4b3bbf1d9">findModuleDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad0183e79b7d98cfc8d0fd1b32efa27d5">findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4c5977a4e048326d58cabd7d348463ea">PerlModGenerator::generatePerlModOutput</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a510e0aa934874b28d777e3e1d1c13341">sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ab005d7c2cbab0f77eb6a92940d9ce416">writeExports</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab475ddec4d159a00ecdf12cba6f2e332">writeModuleList</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
