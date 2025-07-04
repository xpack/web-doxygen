---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/parsermanager/parserpair
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ParserPair` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct ParserManager::ParserPair { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746d87266d3fc699264d223d81183a28">ParserPair</a> (OutlineParserFactory opf, const CodeParserFactory &amp;cpf, const QCString &amp;pn)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cecf3732bcd6a43e43d5f6e1ff8f5d2">outlineParserFactory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249f575b6476cdf5464fbd3004e93c1a">codeParserFactory</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad33d6eddc9ddd59e6ee694152f453e2a">parserName</a></td>
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


<p>Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ParserPair() {#a746d87266d3fc699264d223d81183a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParserManager::ParserPair::ParserPair (<a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> opf, const <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a> &amp; cpf, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; pn)</td>
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



<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a746d87266d3fc699264d223d81183a28">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a746d87266d3fc699264d223d81183a28">ParserPair</a>(<a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> opf, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a> &amp;cpf, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;pn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">        : <a href="#a9cecf3732bcd6a43e43d5f6e1ff8f5d2">outlineParserFactory</a>(opf), <a href="#a249f575b6476cdf5464fbd3004e93c1a">codeParserFactory</a>(cpf), <a href="#ad33d6eddc9ddd59e6ee694152f453e2a">parserName</a>(pn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


<p>References <a href="#a249f575b6476cdf5464fbd3004e93c1a">codeParserFactory</a>, <a href="#a9cecf3732bcd6a43e43d5f6e1ff8f5d2">outlineParserFactory</a> and <a href="#ad33d6eddc9ddd59e6ee694152f453e2a">parserName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### codeParserFactory {#a249f575b6476cdf5464fbd3004e93c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeParserFactory ParserManager::ParserPair::codeParserFactory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a249f575b6476cdf5464fbd3004e93c1a">157</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a>    <a href="#a249f575b6476cdf5464fbd3004e93c1a">codeParserFactory</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a746d87266d3fc699264d223d81183a28">ParserPair</a>.</p>

</div>
</div>

### outlineParserFactory {#a9cecf3732bcd6a43e43d5f6e1ff8f5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutlineParserFactory ParserManager::ParserPair::outlineParserFactory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cecf3732bcd6a43e43d5f6e1ff8f5d2">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> <a href="#a9cecf3732bcd6a43e43d5f6e1ff8f5d2">outlineParserFactory</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a746d87266d3fc699264d223d81183a28">ParserPair</a>.</p>

</div>
</div>

### parserName {#ad33d6eddc9ddd59e6ee694152f453e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ParserManager::ParserPair::parserName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad33d6eddc9ddd59e6ee694152f453e2a">158</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad33d6eddc9ddd59e6ee694152f453e2a">parserName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a746d87266d3fc699264d223d81183a28">ParserPair</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
