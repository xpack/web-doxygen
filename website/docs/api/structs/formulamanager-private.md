---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/formulamanager/private
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct FormulaManager::Private { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap</a>&lt; <a href="/web-doxygen/docs/api/classes/formula">Formula</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a656bd0f666894d84c292bd7b1ec9e296">formulas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; int, <a href="/web-doxygen/docs/api/classes/formula">Formula</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8682571613089ab5c3ebcc642a6aaf">formulaIdMap</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c22106da2adbdc4ebcc5237f51e95ce">repositoriesValid</a> = true</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f9ca400f79ee303624f850efe0d490c">tempFiles</a></td>
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


<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>

<div class="doxySectionDef">

## Public Member Attributes

### formulaIdMap {#a9a8682571613089ab5c3ebcc642a6aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;int,Formula *&gt; FormulaManager::Private::formulaIdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/formula-cpp/#l00045">45</a> of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a8682571613089ab5c3ebcc642a6aaf">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::map&lt;int,Formula *&gt; <a href="#a9a8682571613089ab5c3ebcc642a6aaf">formulaIdMap</a>;</span></span></div>

</div>

</div>
</div>

### formulas {#a656bd0f666894d84c292bd7b1ec9e296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkedMap&lt;Formula&gt; FormulaManager::Private::formulas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/formula-cpp/#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a656bd0f666894d84c292bd7b1ec9e296">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/linkedmap">LinkedMap&lt;Formula&gt;</a>      <a href="#a656bd0f666894d84c292bd7b1ec9e296">formulas</a>;</span></span></div>

</div>

</div>
</div>

### repositoriesValid {#a0c22106da2adbdc4ebcc5237f51e95ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FormulaManager::Private::repositoriesValid = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/formula-cpp/#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c22106da2adbdc4ebcc5237f51e95ce">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                    <a href="#a0c22106da2adbdc4ebcc5237f51e95ce">repositoriesValid</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### tempFiles {#a9f9ca400f79ee303624f850efe0d490c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector FormulaManager::Private::tempFiles</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/formula-cpp/#l00047">47</a> of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f9ca400f79ee303624f850efe0d490c">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a>            <a href="#a9f9ca400f79ee303624f850efe0d490c">tempFiles</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
