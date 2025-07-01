---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/templateinstancedef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TemplateInstanceDef` Struct Reference

Class that contains information about a template instance relation. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
struct TemplateInstanceDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/classdef-h">src/classdef.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d59e4a9d097b853c9fd3ee94b048e0">TemplateInstanceDef</a> (const QCString &amp;ts, ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad956c19b3608a6ab8e6b4b15856a9c">templSpec</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c9868371e51ddc02ac1e6074ad7f00">classDef</a></td>
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

Class that contains information about a template instance relation.

Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxySectionDef">

## Public Constructors

### TemplateInstanceDef() {#af4d59e4a9d097b853c9fd3ee94b048e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TemplateInstanceDef::TemplateInstanceDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ts, <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
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



Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af4d59e4a9d097b853c9fd3ee94b048e0">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af4d59e4a9d097b853c9fd3ee94b048e0">TemplateInstanceDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ts,<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd) : <a href="#a2ad956c19b3608a6ab8e6b4b15856a9c">templSpec</a>(ts), <a href="#ac8c9868371e51ddc02ac1e6074ad7f00">classDef</a>(cd) {}</span></span></div>

</div>


References <a href="#ac8c9868371e51ddc02ac1e6074ad7f00">classDef</a> and <a href="#a2ad956c19b3608a6ab8e6b4b15856a9c">templSpec</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### classDef {#ac8c9868371e51ddc02ac1e6074ad7f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef* TemplateInstanceDef::classDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8c9868371e51ddc02ac1e6074ad7f00">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#ac8c9868371e51ddc02ac1e6074ad7f00">classDef</a>;</span></span></div>

</div>


Referenced by <a href="#af4d59e4a9d097b853c9fd3ee94b048e0">TemplateInstanceDef</a>.
</div>
</div>

### templSpec {#a2ad956c19b3608a6ab8e6b4b15856a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TemplateInstanceDef::templSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ad956c19b3608a6ab8e6b4b15856a9c">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2ad956c19b3608a6ab8e6b4b15856a9c">templSpec</a>;</span></span></div>

</div>


Referenced by <a href="#af4d59e4a9d097b853c9fd3ee94b048e0">TemplateInstanceDef</a>.
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
