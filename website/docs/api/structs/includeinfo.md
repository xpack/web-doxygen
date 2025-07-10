---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/includeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IncludeInfo` Struct Reference

<p>Class representing the data associated with a #include statement. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct IncludeInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/filedef-h">src/filedef.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0240d2d2720adacd4821c605d2e508dc">IncludeInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee20e83eddd15705a5904f698327b36">IncludeInfo</a> (const FileDef *fd, const QCString &amp;in, IncludeKind k)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ea4d136292663b672a8aeec5944548">fileDef</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17debda9cc01be4435a3cafc64061cc6">kind</a> = <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a></td>
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

<p>Class representing the data associated with a #include statement.</p>

<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IncludeInfo() {#a0240d2d2720adacd4821c605d2e508dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IncludeInfo::IncludeInfo ()</td>
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



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0240d2d2720adacd4821c605d2e508dc">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0240d2d2720adacd4821c605d2e508dc">IncludeInfo</a>() {}</span></span></div>

</div>

</div>
</div>

### IncludeInfo() {#a6ee20e83eddd15705a5904f698327b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IncludeInfo::IncludeInfo (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; in, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> k)</td>
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



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ee20e83eddd15705a5904f698327b36">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6ee20e83eddd15705a5904f698327b36">IncludeInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;in,<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> k)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    : <a href="#ac9ea4d136292663b672a8aeec5944548">fileDef</a>(fd), <a href="#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a>(in), <a href="#a17debda9cc01be4435a3cafc64061cc6">kind</a>(k) {}</span></span></div>

</div>


<p>References <a href="#ac9ea4d136292663b672a8aeec5944548">fileDef</a>, <a href="#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a> and <a href="#a17debda9cc01be4435a3cafc64061cc6">kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fileDef {#ac9ea4d136292663b672a8aeec5944548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FileDef* IncludeInfo::fileDef = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac9ea4d136292663b672a8aeec5944548">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#ac9ea4d136292663b672a8aeec5944548">fileDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a7b0a42da35d51f4e7f198975258cf9fd">PerlModGenerator::addIncludeInfo</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a6ee20e83eddd15705a5904f698327b36">IncludeInfo</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8961a6e2496115a7cde0222c4ee213d6">writeIncludeInfo</a>.</p>

</div>
</div>

### includeName {#a0f8b77f07d748ea1612db5d4c47c5c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString IncludeInfo::includeName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f8b77f07d748ea1612db5d4c47c5c37">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a7b0a42da35d51f4e7f198975258cf9fd">PerlModGenerator::addIncludeInfo</a>, <a href="/web-doxygen/docs/api/classes/docsets/#a68e99525be1bdf8596ca067a014e9931">DocSets::addIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="#a6ee20e83eddd15705a5904f698327b36">IncludeInfo</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8961a6e2496115a7cde0222c4ee213d6">writeIncludeInfo</a>.</p>

</div>
</div>

### kind {#a17debda9cc01be4435a3cafc64061cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IncludeKind IncludeInfo::kind = <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17debda9cc01be4435a3cafc64061cc6">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a> <a href="#a17debda9cc01be4435a3cafc64061cc6">kind</a> = <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a7b0a42da35d51f4e7f198975258cf9fd">PerlModGenerator::addIncludeInfo</a>, <a href="#a6ee20e83eddd15705a5904f698327b36">IncludeInfo</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8961a6e2496115a7cde0222c4ee213d6">writeIncludeInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
