---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/commentinprepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CommentInPrepass` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct CommentInPrepass { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6054092fbb3738893659caf7ee73388">CommentInPrepass</a> (int col, const QCString &amp;s)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b0d18b00f30aa819ec490f79e24018">column</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121d4cd80b9102d3c562acbef48952ca">str</a></td>
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


<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CommentInPrepass() {#af6054092fbb3738893659caf7ee73388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CommentInPrepass::CommentInPrepass (int col, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6054092fbb3738893659caf7ee73388">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af6054092fbb3738893659caf7ee73388">CommentInPrepass</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> col, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s) : <a href="#a84b0d18b00f30aa819ec490f79e24018">column</a>(col), <a href="#a121d4cd80b9102d3c562acbef48952ca">str</a>(s) {}</span></span></div>

</div>


<p>References <a href="#a84b0d18b00f30aa819ec490f79e24018">column</a> and <a href="#a121d4cd80b9102d3c562acbef48952ca">str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### column {#a84b0d18b00f30aa819ec490f79e24018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CommentInPrepass::column</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84b0d18b00f30aa819ec490f79e24018">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a84b0d18b00f30aa819ec490f79e24018">column</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af6054092fbb3738893659caf7ee73388">CommentInPrepass</a> and <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a58823d73b17b4a3c6b782a7e14904c77">locatePrepassComment</a>.</p>

</div>
</div>

### str {#a121d4cd80b9102d3c562acbef48952ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString CommentInPrepass::str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a121d4cd80b9102d3c562acbef48952ca">148</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a121d4cd80b9102d3c562acbef48952ca">str</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af6054092fbb3738893659caf7ee73388">CommentInPrepass</a> and <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a9e2f432a75f34796b2cdda24ee7cb9b0">updateVariablePrepassComment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
