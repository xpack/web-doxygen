---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/arguments-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `arguments.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/argument">Argument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
This class contains the information about the argument of a function or template. <a href="/web-doxygen/docs/api/structs/argument/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
This class represents an function or template argument list. <a href="/web-doxygen/docs/api/classes/argumentlist/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> = std::vector&lt; <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">RefQualifierType { <a href="#a4f78d801ad01da94c75f928280228884">...</a> }</td>
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

### ArgumentLists {#ab331f620c4acf00958747569efc1199a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ArgumentLists =  std::vector&lt;ArgumentList&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab331f620c4acf00958747569efc1199a">145</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ab331f620c4acf00958747569efc1199a">ArgumentLists</a> = std::vector&lt;ArgumentList&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### RefQualifierType {#a4f78d801ad01da94c75f928280228884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class RefQualifierType </td>
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
<td class="doxyEnumItemName">None<a id="a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LValue<a id="a4f78d801ad01da94c75f928280228884a74accfde3d3f8e8a27c326eba229d16c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RValue<a id="a4f78d801ad01da94c75f928280228884ac756c8b5e0e5217b000321397a40be7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">None</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f78d801ad01da94c75f928280228884a74accfde3d3f8e8a27c326eba229d16c">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f78d801ad01da94c75f928280228884a74accfde3d3f8e8a27c326eba229d16c">LValue</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f78d801ad01da94c75f928280228884ac756c8b5e0e5217b000321397a40be7e">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f78d801ad01da94c75f928280228884ac756c8b5e0e5217b000321397a40be7e">RValue</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
