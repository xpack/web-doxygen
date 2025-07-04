---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/define-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `define.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;unordered_map&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/define">Define</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A class representing a macro definition. <a href="/web-doxygen/docs/api/classes/define/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12649134897cf8c6af2e297e58f60a3">DefineList</a> = std::vector&lt; <a href="/web-doxygen/docs/api/classes/define">Define</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of all macro definitions. <a href="#ab12649134897cf8c6af2e297e58f60a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03cb5e6dd6299e96b69f71141d2d47d3">DefinesPerFileList</a> = std::unordered_map&lt; std::string, <a href="#ab12649134897cf8c6af2e297e58f60a3">DefineList</a> &gt;</td>
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

### DefineList {#ab12649134897cf8c6af2e297e58f60a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DefineList =  std::vector&lt;Define&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of all macro definitions.</p>

<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/define-h">define.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab12649134897cf8c6af2e297e58f60a3">49</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ab12649134897cf8c6af2e297e58f60a3">DefineList</a> = std::vector&lt;Define&gt;;</span></span></div>

</div>

</div>
</div>

### DefinesPerFileList {#a03cb5e6dd6299e96b69f71141d2d47d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DefinesPerFileList =  std::unordered_map&lt; std::string, DefineList &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/define-h">define.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03cb5e6dd6299e96b69f71141d2d47d3">50</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a03cb5e6dd6299e96b69f71141d2d47d3">DefinesPerFileList</a> = std::unordered_map&lt; std::string, DefineList &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
