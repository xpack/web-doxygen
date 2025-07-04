---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/moduledef-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `moduledef.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/headerinfo">HeaderInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/modulemanager/private">Private</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ac7e5562ea564ca2b29069e08e7734">HeaderInfoVector</a> = std::vector&lt; <a href="/web-doxygen/docs/api/structs/headerinfo">HeaderInfo</a> &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a89405a199c1c00e23bfd95ad2f7a9">toModuleDef</a> (Definition *d)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13462c5eba6cf9fe954cb86ec529437">toModuleDef</a> (const Definition *d)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a> (ModuleDef *m)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f27679f854f3305dc4d3cd7726750b5">toModuleDefImpl</a> (const std::unique_ptr&lt; ModuleDef &gt; &amp;m)</td>
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


<div class="doxySectionDef">

## Typedefs

### HeaderInfoVector {#a19ac7e5562ea564ca2b29069e08e7734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using HeaderInfoVector =  std::vector&lt;HeaderInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19ac7e5562ea564ca2b29069e08e7734">45</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a19ac7e5562ea564ca2b29069e08e7734">HeaderInfoVector</a> = std::vector&lt;HeaderInfo&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### toModuleDef() {#a51a89405a199c1c00e23bfd95ad2f7a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleDef * toModuleDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1157 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51a89405a199c1c00e23bfd95ad2f7a9">1157</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *<a href="#a51a89405a199c1c00e23bfd95ad2f7a9">toModuleDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a>)) ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a31ba3cfbe898329d92215b8314227b0d">ClassDefImpl::moveTo</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a263db4e9ffc625509018045b0345b31c">MemberDefImpl::moveTo</a>.</p>

</div>
</div>

### toModuleDef() {#ab13462c5eba6cf9fe954cb86ec529437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleDef * toModuleDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1163 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab13462c5eba6cf9fe954cb86ec529437">1163</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *<a href="#a51a89405a199c1c00e23bfd95ad2f7a9">toModuleDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a>)) ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### toModuleDefImpl() {#a2c21fb00589383686a05fc5f92c6e754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleDefImpl * toModuleDefImpl (<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * m)</td>
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



<p>Definition at line 1169 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c21fb00589383686a05fc5f92c6e754">1169</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a> *<a href="#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(<a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *m)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(m); }</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/modulemanager/#a6e2ffe69d7a921c13b6d0e16918a250d">ModuleManager::addClassToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a6698b2bf23de9dc94a27ad7b898c205b">ModuleManager::addConceptToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a5c564c642161994958220628ac58aef8">ModuleManager::addHeader</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#af2e02d3fa979bbdad8d4995915a9f834">ModuleManager::addImport</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a0c75f10f5345207329e3468f53416b55">ModuleManager::addListReferences</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a92f20a151f253a36ec65c90e3da01a81">ModuleManager::addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a8eaf52205769b3910d40de52c5eefd51">ModuleManager::addMemberToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a698e0a915bfb6a6d27731b5290580c96">ModuleManager::addTagInfo</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abd67a3f8ef0181d7a4179931452449df">ModuleManager::collectExportedSymbols</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a56ebe7e944c71ea43b47da0b331789ab">ModuleManager::collectExportedSymbolsRecursively</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a5d5dfdf8729dadf9a45fa931f88d94ac">ModuleManager::countMembers</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#af3b3d835cba0b9c103a0f5c274a0ac44">ModuleManager::distributeMemberGroupDocumentation</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#ab8e165a10a456a00a6735f9a7ae4d74a">ModuleManager::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a9a5ccba7154d90c27699bad5517f8b18">ModuleManager::resolvePartitions</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#abe59aee08bdd26b109a69b54f6e018ab">ModuleManager::resolvePartitionsRecursively</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a45ab9d867637b915d193705ede03cc32">ModuleManager::sortMemberLists</a> and <a href="/web-doxygen/docs/api/classes/modulelinkedrefmap/#aebc005e13bdcb448da76f4b43b2ea72e">ModuleLinkedRefMap::writeDeclaration</a>.</p>

</div>
</div>

### toModuleDefImpl() {#a5f27679f854f3305dc4d3cd7726750b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleDefImpl * toModuleDefImpl (const std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> &gt; &amp; m)</td>
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



<p>Definition at line 1175 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f27679f854f3305dc4d3cd7726750b5">1175</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a> *<a href="#a2c21fb00589383686a05fc5f92c6e754">toModuleDefImpl</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;ModuleDef&gt; &amp;m)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(m.get()); }</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
