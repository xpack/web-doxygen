---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/localdef
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LocalDef` Class Reference



## Declaration

<div class="doxyDeclaration">
class LocalDef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">src/scopedtypevariant.h</a>&gt;
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f9b2d7b294134d474b0ac1c72ea41f">insertBaseClass</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed8113c3b0036e4cdd6f2e9b06bd03d">baseClasses</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">m_baseClasses</a></td>
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



<p>Class representing a local class definition found while generating syntax highlighted code.</p>


<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### baseClasses() {#a4ed8113c3b0036e4cdd6f2e9b06bd03d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; QCString &gt; LocalDef::baseClasses ()</td>
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



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ed8113c3b0036e4cdd6f2e9b06bd03d">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;QCString&gt; <a href="#a4ed8113c3b0036e4cdd6f2e9b06bd03d">baseClasses</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">m_baseClasses</a>; }</span></span></div>

</div>


<p>Reference <a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">m_baseClasses</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>.</p>

</div>
</div>

### insertBaseClass() {#ae8f9b2d7b294134d474b0ac1c72ea41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LocalDef::insertBaseClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8f9b2d7b294134d474b0ac1c72ea41f">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae8f9b2d7b294134d474b0ac1c72ea41f">insertBaseClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name) { <a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">m_baseClasses</a>.push_back(name); }</span></span></div>

</div>


<p>Reference <a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">m_baseClasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_baseClasses {#ad0a3d2cea02e93b7ccce552b0cc5380f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;QCString&gt; LocalDef::m_baseClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;QCString&gt; <a href="#ad0a3d2cea02e93b7ccce552b0cc5380f">m_baseClasses</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a4ed8113c3b0036e4cdd6f2e9b06bd03d">baseClasses</a> and <a href="#ae8f9b2d7b294134d474b0ac1c72ea41f">insertBaseClass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
