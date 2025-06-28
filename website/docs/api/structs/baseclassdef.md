---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/baseclassdef
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `BaseClassDef` Struct Reference

<p>Class that contains information about an inheritance relation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct BaseClassDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/classdef-h">src/classdef.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a> (ClassDef *cd, const QCString &amp;n, Protection p, Specifier v, const QCString &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a62f0f7057f4cd514f3d1417191ff26">classDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class definition that this relation inherits from. <a href="#a2a62f0f7057f4cd514f3d1417191ff26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7703a5a743ee3b6c066d8037fc71f4e">usedName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>name used in the inheritance list (may be a typedef name instead of the class name) <a href="#ae7703a5a743ee3b6c066d8037fc71f4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a986f56300bfa53f7c4cff58196294">prot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> level of the inheritance relation: Public, Protected, or Private. <a href="#ab5a986f56300bfa53f7c4cff58196294">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a844100c6fcd90233e01e52fc92107464">virt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtualness of the inheritance relation: Normal, or Virtual. <a href="#a844100c6fcd90233e01e52fc92107464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8a712d468d70c6c80b5c07f49711ae">templSpecifiers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Template arguments used for the base class. <a href="#a2b8a712d468d70c6c80b5c07f49711ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class that contains information about an inheritance relation.</p>

<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### BaseClassDef() {#a20901e8922d1379dd9343fde68dca5a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseClassDef::BaseClassDef (<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p, <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> v, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; t)</td>
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


<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20901e8922d1379dd9343fde68dca5a9">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a>(<a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p, <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> v,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;t) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a2a62f0f7057f4cd514f3d1417191ff26">classDef</a>(cd), <a href="#ae7703a5a743ee3b6c066d8037fc71f4e">usedName</a>(n), <a href="#ab5a986f56300bfa53f7c4cff58196294">prot</a>(p), <a href="#a844100c6fcd90233e01e52fc92107464">virt</a>(v), <a href="#a2b8a712d468d70c6c80b5c07f49711ae">templSpecifiers</a>(t) {}</span></span></div>

</div>


References <a href="#a2a62f0f7057f4cd514f3d1417191ff26">classDef</a>, <a href="#ab5a986f56300bfa53f7c4cff58196294">prot</a>, <a href="#a2b8a712d468d70c6c80b5c07f49711ae">templSpecifiers</a>, <a href="#ae7703a5a743ee3b6c066d8037fc71f4e">usedName</a> and <a href="#a844100c6fcd90233e01e52fc92107464">virt</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### classDef {#a2a62f0f7057f4cd514f3d1417191ff26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef* BaseClassDef::classDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Class definition that this relation inherits from.</p>

<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a62f0f7057f4cd514f3d1417191ff26">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *<a href="#a2a62f0f7057f4cd514f3d1417191ff26">classDef</a>;</span></span></div>

</div>


Referenced by <a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### prot {#ab5a986f56300bfa53f7c4cff58196294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Protection BaseClassDef::prot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> level of the inheritance relation: Public, Protected, or Private.</p>

<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5a986f56300bfa53f7c4cff58196294">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> <a href="#ab5a986f56300bfa53f7c4cff58196294">prot</a>;</span></span></div>

</div>


Referenced by <a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a>.
</div>
</div>

### templSpecifiers {#a2b8a712d468d70c6c80b5c07f49711ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString BaseClassDef::templSpecifiers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Template arguments used for the base class.</p>

<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b8a712d468d70c6c80b5c07f49711ae">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2b8a712d468d70c6c80b5c07f49711ae">templSpecifiers</a>;</span></span></div>

</div>


Referenced by <a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### usedName {#ae7703a5a743ee3b6c066d8037fc71f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString BaseClassDef::usedName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>name used in the inheritance list (may be a typedef name instead of the class name)</p>

<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7703a5a743ee3b6c066d8037fc71f4e">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>   <a href="#ae7703a5a743ee3b6c066d8037fc71f4e">usedName</a>;</span></span></div>

</div>


Referenced by <a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a>.
</div>
</div>

### virt {#a844100c6fcd90233e01e52fc92107464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Specifier BaseClassDef::virt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Virtualness of the inheritance relation: Normal, or Virtual.</p>

<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a844100c6fcd90233e01e52fc92107464">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a>  <a href="#a844100c6fcd90233e01e52fc92107464">virt</a>;</span></span></div>

</div>


Referenced by <a href="#a20901e8922d1379dd9343fde68dca5a9">BaseClassDef</a> and <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
