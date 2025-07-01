---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/baseinfo
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `BaseInfo` Struct Reference

This class stores information about an inheritance relation. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
struct BaseInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/entry-h">src/entry.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e40125106e491f74d910970db6a277">BaseInfo</a> (const QCString &amp;n, Protection p, Specifier v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bba327d477830b4664f9d03b05c97b">name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
the name of the base class <a href="#ae8bba327d477830b4664f9d03b05c97b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf46efd63ca2b598a79324042bac83f3">prot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
inheritance type <a href="#aaf46efd63ca2b598a79324042bac83f3">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32fa6c3344b6608768043f6ee5a8e6b">virt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
virtualness <a href="#ab32fa6c3344b6608768043f6ee5a8e6b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

This class stores information about an inheritance relation.

Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.

<div class="doxySectionDef">

## Public Constructors

### BaseInfo() {#ab2e40125106e491f74d910970db6a277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseInfo::BaseInfo (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p, <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> v)</td>
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




Creates an object representing an inheritance relation

Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2e40125106e491f74d910970db6a277">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab2e40125106e491f74d910970db6a277">BaseInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p,<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> v) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae8bba327d477830b4664f9d03b05c97b">name</a>(n),<a href="#aaf46efd63ca2b598a79324042bac83f3">prot</a>(p),<a href="#ab32fa6c3344b6608768043f6ee5a8e6b">virt</a>(v) {}</span></span></div>

</div>


References <a href="#ae8bba327d477830b4664f9d03b05c97b">name</a>, <a href="#aaf46efd63ca2b598a79324042bac83f3">prot</a> and <a href="#ab32fa6c3344b6608768043f6ee5a8e6b">virt</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### name {#ae8bba327d477830b4664f9d03b05c97b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString BaseInfo::name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

the name of the base class

Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8bba327d477830b4664f9d03b05c97b">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>   <a href="#ae8bba327d477830b4664f9d03b05c97b">name</a>; </span><span class="doxyHighlightComment">//!&lt; the name of the base class</span></span></div>

</div>


Referenced by <a href="#ab2e40125106e491f74d910970db6a277">BaseInfo</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abc809fca2014e90fe0aee477a1964ed7">computePageRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#aafd3846f78cc76b992152366c99f7d74">anonymous\_namespace{tagreader.cpp}::TagFileParser::dump</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae13abaf328534f92b57bb6af8208f31d">findBaseClassesForClass</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>.
</div>
</div>

### prot {#aaf46efd63ca2b598a79324042bac83f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Protection BaseInfo::prot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

inheritance type

Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf46efd63ca2b598a79324042bac83f3">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> <a href="#aaf46efd63ca2b598a79324042bac83f3">prot</a>; </span><span class="doxyHighlightComment">//!&lt; inheritance type</span></span></div>

</div>


Referenced by <a href="#ab2e40125106e491f74d910970db6a277">BaseInfo</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>.
</div>
</div>

### virt {#ab32fa6c3344b6608768043f6ee5a8e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Specifier BaseInfo::virt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

virtualness

Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab32fa6c3344b6608768043f6ee5a8e6b">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a>  <a href="#ab32fa6c3344b6608768043f6ee5a8e6b">virt</a>; </span><span class="doxyHighlightComment">//!&lt; virtualness</span></span></div>

</div>


Referenced by <a href="#ab2e40125106e491f74d910970db6a277">BaseInfo</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
