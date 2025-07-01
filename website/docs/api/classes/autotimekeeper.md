---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/autotimekeeper
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `AutoTimeKeeper` Class Reference



## Declaration

<div class="doxyDeclaration">
class AutoTimeKeeper { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0744b11f3cd97a1429bda7c614d9aa">AutoTimeKeeper</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27439f74d48591cc5813ad2bb06915ff">~AutoTimeKeeper</a> ()</td>
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


Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxySectionDef">

## Public Constructors

### AutoTimeKeeper() {#a2e0744b11f3cd97a1429bda7c614d9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoTimeKeeper::AutoTimeKeeper ()</td>
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



Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e0744b11f3cd97a1429bda7c614d9aa">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2e0744b11f3cd97a1429bda7c614d9aa">AutoTimeKeeper</a>() { <a href="/web-doxygen/docs/api/classes/systimekeeper/#ab2bf7ce3a2c5b37234e10ea15d667779">SysTimeKeeper::instance</a>().<a href="/web-doxygen/docs/api/classes/systimekeeper/#a4bb2350f48a1ce554f4499edbd8ba8ec">start</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/systimekeeper/#ab2bf7ce3a2c5b37234e10ea15d667779">SysTimeKeeper::instance</a> and <a href="/web-doxygen/docs/api/classes/systimekeeper/#a4bb2350f48a1ce554f4499edbd8ba8ec">SysTimeKeeper::start</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AutoTimeKeeper() {#a27439f74d48591cc5813ad2bb06915ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoTimeKeeper::~AutoTimeKeeper ()</td>
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



Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27439f74d48591cc5813ad2bb06915ff">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#a27439f74d48591cc5813ad2bb06915ff">~AutoTimeKeeper</a>() { <a href="/web-doxygen/docs/api/classes/systimekeeper/#ab2bf7ce3a2c5b37234e10ea15d667779">SysTimeKeeper::instance</a>().<a href="/web-doxygen/docs/api/classes/systimekeeper/#a46b40aa916ae6873c566c85a88dd9f96">stop</a>();  }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/systimekeeper/#ab2bf7ce3a2c5b37234e10ea15d667779">SysTimeKeeper::instance</a> and <a href="/web-doxygen/docs/api/classes/systimekeeper/#a46b40aa916ae6873c566c85a88dd9f96">SysTimeKeeper::stop</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
