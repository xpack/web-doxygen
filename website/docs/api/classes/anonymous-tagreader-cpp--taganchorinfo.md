---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-tagreader-cpp-/taganchorinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TagAnchorInfo` Class Reference

<p>Information about an linkable anchor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{tagreader.cpp}::TagAnchorInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a766ccc17e27576324a3676eb1ba2a735">TagAnchorInfo</a> (const QCString &amp;f, const QCString &amp;l, const QCString &amp;t=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaad82bef7c2fcacc359428e760989475">label</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a790fcdd783a7ea16c1ba98182a43aa6b">fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7c343e5281f855a7259775d3a4b0cf">title</a></td>
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

<p>Information about an linkable anchor.</p>

<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TagAnchorInfo() {#a766ccc17e27576324a3676eb1ba2a735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{tagreader.cpp}::TagAnchorInfo::TagAnchorInfo (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; f, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; t=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a766ccc17e27576324a3676eb1ba2a735">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a766ccc17e27576324a3676eb1ba2a735">TagAnchorInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;t=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#aaad82bef7c2fcacc359428e760989475">label</a>(l), <a href="#a790fcdd783a7ea16c1ba98182a43aa6b">fileName</a>(f), <a href="#aec7c343e5281f855a7259775d3a4b0cf">title</a>(t) {}</span></span></div>

</div>


<p>References <a href="#a790fcdd783a7ea16c1ba98182a43aa6b">fileName</a>, <a href="#aaad82bef7c2fcacc359428e760989475">label</a> and <a href="#aec7c343e5281f855a7259775d3a4b0cf">title</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fileName {#a790fcdd783a7ea16c1ba98182a43aa6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous{tagreader.cpp}::TagAnchorInfo::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a790fcdd783a7ea16c1ba98182a43aa6b">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a790fcdd783a7ea16c1ba98182a43aa6b">fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a766ccc17e27576324a3676eb1ba2a735">TagAnchorInfo</a>.</p>

</div>
</div>

### label {#aaad82bef7c2fcacc359428e760989475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous{tagreader.cpp}::TagAnchorInfo::label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaad82bef7c2fcacc359428e760989475">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aaad82bef7c2fcacc359428e760989475">label</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a766ccc17e27576324a3676eb1ba2a735">TagAnchorInfo</a>.</p>

</div>
</div>

### title {#aec7c343e5281f855a7259775d3a4b0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString anonymous{tagreader.cpp}::TagAnchorInfo::title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec7c343e5281f855a7259775d3a4b0cf">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aec7c343e5281f855a7259775d3a4b0cf">title</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a766ccc17e27576324a3676eb1ba2a735">TagAnchorInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
