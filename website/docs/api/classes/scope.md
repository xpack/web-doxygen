---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/scope
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Scope` Class Reference

<p>Contains names of used modules and names of local variables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class Scope { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f8159aa48746bb58e6724ff4a36619">useNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>contains names of used modules <a href="#ae1f8159aa48746bb58e6724ff4a36619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa482827cfef7e8fc106ac71e3abb1398">localVars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>contains names of local variables <a href="#aa482827cfef7e8fc106ac71e3abb1398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d33523531c274635347daf1d40ddc9a">externalVars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>contains names of external entities <a href="#a5d33523531c274635347daf1d40ddc9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Contains names of used modules and names of local variables.</p>

<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### externalVars {#a5d33523531c274635347daf1d40ddc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringUnorderedSet Scope::externalVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>contains names of external entities</p>

<p>Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d33523531c274635347daf1d40ddc9a">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> <a href="#a5d33523531c274635347daf1d40ddc9a">externalVars</a>; </span><span class="doxyHighlightComment">//!&lt; contains names of external entities</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>.</p>

</div>
</div>

### localVars {#aa482827cfef7e8fc106ac71e3abb1398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringUnorderedSet Scope::localVars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>contains names of local variables</p>

<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa482827cfef7e8fc106ac71e3abb1398">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> <a href="#aa482827cfef7e8fc106ac71e3abb1398">localVars</a>; </span><span class="doxyHighlightComment">//!&lt; contains names of local variables</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aa3d64c285d12ea68252876251ea0fc2d">getFortranDefs</a>.</p>

</div>
</div>

### useNames {#ae1f8159aa48746bb58e6724ff4a36619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;QCString&gt; Scope::useNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>contains names of used modules</p>

<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1f8159aa48746bb58e6724ff4a36619">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;QCString&gt; <a href="#ae1f8159aa48746bb58e6724ff4a36619">useNames</a>; </span><span class="doxyHighlightComment">//!&lt; contains names of used modules</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a8e24461e4a28d3b200f27ade4dbc7a53">addUse</a> and <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a239ee1e47d4722402cd650ae2d0cd59f">endScope</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/fortrancode-l">fortrancode.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
