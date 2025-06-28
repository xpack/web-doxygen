---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/latexdocvisitor-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `latexdocvisitor.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stack&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docvisitor-h">docvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/latexdocvisitor">LatexDocVisitor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concrete visitor implementation for LaTeX output. <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/latexdocvisitor/activerowspan">ActiveRowSpan</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/latexdocvisitor/tablestate">TableState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/latexdocvisitor/latexlistiteminfo">LatexListItemInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TexOrPdf { <a href="#ac63cb3ba9a18f02ff6bde1a72b79b492">...</a> }</td>
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


<div class="doxySectionDef">

## Enumerations

### TexOrPdf {#ac63cb3ba9a18f02ff6bde1a72b79b492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class TexOrPdf </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO<a id="ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251"></a></td>
<td class="doxyEnumItemDescription"><p>not called through texorpdf</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TEX<a id="ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b"></a></td>
<td class="doxyEnumItemDescription"><p>called through texorpdf as TeX (first) part</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PDF<a id="ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1"></a></td>
<td class="doxyEnumItemDescription"><p>called through texorpdf as PDF (second) part</p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">NO</a>,  </span><span class="doxyHighlightComment">//!&lt; not called through texorpdf</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">TEX</a>, </span><span class="doxyHighlightComment">//!&lt; called through texorpdf as TeX (first) part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">PDF</a>, </span><span class="doxyHighlightComment">//!&lt; called through texorpdf as PDF (second) part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
