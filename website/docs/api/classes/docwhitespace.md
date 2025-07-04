---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docwhitespace
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocWhiteSpace` Class Reference

<p>Node representing some amount of white space. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocWhiteSpace { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docnode">DocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract node interface with type information. <a href="/web-doxygen/docs/api/classes/docnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85792c7b27dd56ea6ddb87eb3a6feef">DocWhiteSpace</a> (DocParser *parser, DocNodeVariant *parent, const QCString &amp;chars)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ca8e032f7dd53157380d4c0a29d080">m_chars</a></td>
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

<p>Node representing some amount of white space.</p>

<p>Definition at line 353 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocWhiteSpace() {#ae85792c7b27dd56ea6ddb87eb3a6feef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocWhiteSpace::DocWhiteSpace (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; chars)</td>
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



<p>Definition at line 356 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae85792c7b27dd56ea6ddb87eb3a6feef">356</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae85792c7b27dd56ea6ddb87eb3a6feef">DocWhiteSpace</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#a81ca8e032f7dd53157380d4c0a29d080">m_chars</a>(<a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>) {}</span></span></div>

</div>


<p>References <a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="#a81ca8e032f7dd53157380d4c0a29d080">m_chars</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### chars() {#a9e8fbf6c6ca3efa8f4e7d9fce2352023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocWhiteSpace::chars ()</td>
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



<p>Definition at line 358 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">358</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a81ca8e032f7dd53157380d4c0a29d080">m_chars</a>; }</span></span></div>

</div>


<p>Reference <a href="#a81ca8e032f7dd53157380d4c0a29d080">m_chars</a>.</p>


<p>Referenced by <a href="#ae85792c7b27dd56ea6ddb87eb3a6feef">DocWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab014c099dfdb3ac2e7cda9129c153253">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa071942797e234052d70817a97ecfc20">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ae8521140810fce270f060a974a5c223e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a315f64205ff8e9d75ddd63e31f068269">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#aed18dc85fa4e2c986036d240902b70cc">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af154c4b8688beaef882211c40763fec3">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a5a1580dc76cff9388253fc5f0214b8bf">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_chars {#a81ca8e032f7dd53157380d4c0a29d080}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocWhiteSpace::m_chars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81ca8e032f7dd53157380d4c0a29d080">360</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#a81ca8e032f7dd53157380d4c0a29d080">m_chars</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a> and <a href="#ae85792c7b27dd56ea6ddb87eb3a6feef">DocWhiteSpace</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
