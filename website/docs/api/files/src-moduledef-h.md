---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/moduledef-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `moduledef.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/importinfo">ImportInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/modulelinkedrefmap">ModuleLinkedRefMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/modulelist">ModuleList</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/modulemanager">ModuleManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e833aa0c18e4ff8bbad698de175438a">ImportInfoList</a> = std::vector&lt; <a href="/web-doxygen/docs/api/structs/importinfo">ImportInfo</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3a0410bbdf86a1d5d0071667395ac1">ModuleMap</a> = std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e25aa6a36e0c0605e01d8df04203a6">ImportInfoMap</a> = std::unordered_map&lt; std::string, <a href="#a4e833aa0c18e4ff8bbad698de175438a">ImportInfoList</a> &gt;</td>
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

</table>


<div class="doxySectionDef">

## Typedefs

### ImportInfoList {#a4e833aa0c18e4ff8bbad698de175438a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ImportInfoList =  std::vector&lt;ImportInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e833aa0c18e4ff8bbad698de175438a">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a4e833aa0c18e4ff8bbad698de175438a">ImportInfoList</a> = std::vector&lt;ImportInfo&gt;;</span></span></div>

</div>

</div>
</div>

### ImportInfoMap {#ad2e25aa6a36e0c0605e01d8df04203a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ImportInfoMap =  std::unordered_map&lt;std::string,ImportInfoList&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2e25aa6a36e0c0605e01d8df04203a6">61</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad2e25aa6a36e0c0605e01d8df04203a6">ImportInfoMap</a> = std::unordered_map&lt;std::string,ImportInfoList&gt;;</span></span></div>

</div>

</div>
</div>

### ModuleMap {#a2f3a0410bbdf86a1d5d0071667395ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ModuleMap =  std::unordered_map&lt;std::string,ModuleDef *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f3a0410bbdf86a1d5d0071667395ac1">60</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a2f3a0410bbdf86a1d5d0071667395ac1">ModuleMap</a> = std::unordered_map&lt;std::string,ModuleDef *&gt;;</span></span></div>

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



<p>Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1157 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a51a89405a199c1c00e23bfd95ad2f7a9">1157</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *<a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a51a89405a199c1c00e23bfd95ad2f7a9">toModuleDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
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



<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>, definition at line 1163 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#ab13462c5eba6cf9fe954cb86ec529437">1163</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *<a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a51a89405a199c1c00e23bfd95ad2f7a9">toModuleDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/moduledefimpl">ModuleDefImpl</a>)) ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
