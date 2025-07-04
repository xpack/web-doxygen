---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/citeposition
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CitePosition` Class Reference

<p>class that provide information about the p[osition of a citation name <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class CitePosition { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ed6eef1e49b34920a2e57792546bd4">CitePosition</a> (const QCString &amp;fn, int l)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266c17e1bcb6dca43d0187737ba31851">fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf706f50c0da88fa95c4c34e7ee1e97">lineNr</a></td>
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

<p>class that provide information about the p[osition of a citation name</p>

<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CitePosition() {#ab9ed6eef1e49b34920a2e57792546bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CitePosition::CitePosition (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, int l)</td>
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



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab9ed6eef1e49b34920a2e57792546bd4">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab9ed6eef1e49b34920a2e57792546bd4">CitePosition</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fn, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l) : <a href="#a266c17e1bcb6dca43d0187737ba31851">fileName</a>(fn), <a href="#aedf706f50c0da88fa95c4c34e7ee1e97">lineNr</a>(l) {}</span></span></div>

</div>


<p>References <a href="#a266c17e1bcb6dca43d0187737ba31851">fileName</a> and <a href="#aedf706f50c0da88fa95c4c34e7ee1e97">lineNr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fileName {#a266c17e1bcb6dca43d0187737ba31851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString CitePosition::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a266c17e1bcb6dca43d0187737ba31851">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>    <a href="#a266c17e1bcb6dca43d0187737ba31851">fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab9ed6eef1e49b34920a2e57792546bd4">CitePosition</a>.</p>

</div>
</div>

### lineNr {#aedf706f50c0da88fa95c4c34e7ee1e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CitePosition::lineNr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aedf706f50c0da88fa95c4c34e7ee1e97">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">         <a href="#aedf706f50c0da88fa95c4c34e7ee1e97">lineNr</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab9ed6eef1e49b34920a2e57792546bd4">CitePosition</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
