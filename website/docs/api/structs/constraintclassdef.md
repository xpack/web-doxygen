---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/constraintclassdef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ConstraintClassDef` Struct Reference

Class that contains information about a type constraint relations. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
struct ConstraintClassDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/classdef-h">src/classdef.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511b92d880437fdff407845cc372ca1d">ConstraintClassDef</a> (ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0de42a40a226e9f3373d90386d9d271">addAccessor</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b68e8a482c234e891caf07a74608ef">classDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class definition that this relation uses. <a href="#a19b68e8a482c234e891caf07a74608ef">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a0bc125fc346e538d66d5ea1c33428f00">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c368314075b446f998c4c140d570a1">accessors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Dictionary of member types names that form the edge labels of the constraint relation. <a href="#a57c368314075b446f998c4c140d570a1">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

Class that contains information about a type constraint relations.

Definition at line 515 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxySectionDef">

## Public Constructors

### ConstraintClassDef() {#a511b92d880437fdff407845cc372ca1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintClassDef::ConstraintClassDef (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



Definition at line 517 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a511b92d880437fdff407845cc372ca1d">517</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a511b92d880437fdff407845cc372ca1d">ConstraintClassDef</a>(<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd) : <a href="#a19b68e8a482c234e891caf07a74608ef">classDef</a>(cd) {}</span></span></div>

</div>


Reference <a href="#a19b68e8a482c234e891caf07a74608ef">classDef</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAccessor() {#aa0de42a40a226e9f3373d90386d9d271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstraintClassDef::addAccessor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 518 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0de42a40a226e9f3373d90386d9d271">518</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa0de42a40a226e9f3373d90386d9d271">addAccessor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a57c368314075b446f998c4c140d570a1">accessors</a>.find(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())==<a href="#a57c368314075b446f998c4c140d570a1">accessors</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a57c368314075b446f998c4c140d570a1">accessors</a>.insert(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a57c368314075b446f998c4c140d570a1">accessors</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### accessors {#a57c368314075b446f998c4c140d570a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet ConstraintClassDef::accessors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Dictionary of member types names that form the edge labels of the constraint relation.

Definition at line 531 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57c368314075b446f998c4c140d570a1">531</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a0bc125fc346e538d66d5ea1c33428f00">StringSet</a> <a href="#a57c368314075b446f998c4c140d570a1">accessors</a>;</span></span></div>

</div>


Referenced by <a href="#aa0de42a40a226e9f3373d90386d9d271">addAccessor</a>.
</div>
</div>

### classDef {#a19b68e8a482c234e891caf07a74608ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef* ConstraintClassDef::classDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Class definition that this relation uses.

Definition at line 526 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19b68e8a482c234e891caf07a74608ef">526</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#a19b68e8a482c234e891caf07a74608ef">classDef</a>;</span></span></div>

</div>


Referenced by <a href="#a511b92d880437fdff407845cc372ca1d">ConstraintClassDef</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
