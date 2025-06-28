---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/outputgenintf
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutputGenIntf` Class Reference

<p>Abstract interface for output generators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class OutputGenIntf { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/outputgen-h">src/outputgen.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for HTML output. <a href="/web-doxygen/docs/api/classes/htmlgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/latexgenerator">LatexGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for LaTeX output. <a href="/web-doxygen/docs/api/classes/latexgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/mangenerator">ManGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for Man page output. <a href="/web-doxygen/docs/api/classes/mangenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/rtfgenerator">RTFGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for RTF output. <a href="/web-doxygen/docs/api/classes/rtfgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a> () const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685aff27480f0f7cfe980bdd91cfffaf">clone</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2399adf8c0604e50bb4c0911ef961742">addCodeGen</a> (OutputCodeList &amp;list)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbad8b45e48b0d0dd8139c9c5ce5e74d">writeDoc</a> (const IDocNodeAST *ast, const Definition *ctx, const MemberDef *md, int id)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae869ad0ddcd664eebbedee81ad94e925">startIndexSection</a> (IndexSection is)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a927f5983fc93c11d18237ca76fb74eb5">endIndexSection</a> (IndexSection is)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85839f2257cc6632c3307df7f1c48cd4">writePageLink</a> (const QCString &amp;name, bool first)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa73996eef9d354eda1aa7bef80a92d">startProjectNumber</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8f1a4a235cb4e41997f238b2c969d18">endProjectNumber</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2711a39698d7169932b7e24b9223ef06">writeStyleInfo</a> (int part)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d7c1c55247348a93966711afbb983f">writeSearchInfo</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06d07286c1a5e0e8dd4dcb413eea3ee">writeFooter</a> (const QCString &amp;navPath)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751894ca7271d62e186144bf6ea750b4">startFile</a> (const QCString &amp;name, const QCString &amp;manName, const QCString &amp;title, int id, int hierarchyLevel)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec223180ecc276ad0d0382a7de95bfb9">endFile</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e6e6ec7f39f8847632b75dfa5490a9">startTitleHead</a> (const QCString &amp;fileName)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">endTitleHead</a> (const QCString &amp;fileName, const QCString &amp;name)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0f23248db3a810e3fa1a22efd6dc810">startParagraph</a> (const QCString &amp;classDef=QCString())=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f725c5406981a4aaa9aba38078ffc71">endParagraph</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9425335496ccadd1a9c8235cf31280e1">writeString</a> (const QCString &amp;text)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff1ac58d5e1754872e65e7a3db6f2241">startIndexListItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157226abc71a5e32f8cb882cc4d943b1">endIndexListItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2597524bf7275b5af10536cdf49f31">startIndexList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c5b6593573ffe5ab167aa4f3b2ffdb9">endIndexList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2892a4a593cce615ffce7172eabc42">startIndexKey</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6b5aa596df8637546d29846c07c971e">endIndexKey</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7025f965ca3fcf915dbf010a4a416a">startIndexValue</a> (bool b)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae711fa5b116608e306734eec728f6d79">endIndexValue</a> (const QCString &amp;name, bool b)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">startItemList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e1c75aa036fadb2b4914564c1be3ff">endItemList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4fea7fc7613b609e6b63ebe49e2637f">startIndexItem</a> (const QCString &amp;ref, const QCString &amp;file)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499b7e7082ce98ac420b4713a0a4fb0a">endIndexItem</a> (const QCString &amp;ref, const QCString &amp;file)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6eb7a359ed49bbeb245e3e7b0993eb">docify</a> (const QCString &amp;s)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53380f84190045f14ef3c6ae2f5dd275">writeObjectLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075de9b4d65864892a5a4bea2ae751dd">startTextLink</a> (const QCString &amp;file, const QCString &amp;anchor)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578bfc0ee8985ffdf1e141445e3479e4">endTextLink</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a> (const QCString &amp;type, const QCString &amp;file, const QCString &amp;path, const QCString &amp;name)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d12471e1fa0455d4957b72f25c64302">startTypewriter</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a10feddac419bcac5c2456710213600">endTypewriter</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c25f35ecd9dbcbcd1804513473f8683">startGroupHeader</a> (const QCString &amp;id, int extraLevels=0)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1550c8839cbd8b1ebe15247624502b">endGroupHeader</a> (int extraLevels=0)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f528b46750b254f7a799fcd6ed28d7">startItemListItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e20dae21d9d6e5b11a94a38b10896a">endItemListItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a479613dbc7e8b8967342736b76a00b59">startMemberSections</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667642e79b9e787ffaaed927431106e7">endMemberSections</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af915369f4ac0e6faeb3d558de0a5ccea">startHeaderSection</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0cb366bd225ec3b8637dbf745bb8495">endHeaderSection</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cce7e6f2c721d28cd581fffc261667">startMemberHeader</a> (const QCString &amp;anchor, int typ=2)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a824e30a4173507c3d8b8fc1d391840">endMemberHeader</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47701af94cd5ea03b74733c9d7926251">startMemberSubtitle</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024f537b0e167928d8fbbd7c83126afe">endMemberSubtitle</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc64b48e08f8c37ae68c052666e2581">startMemberDocList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4eb90cc7d89d88a0d2333be8063394f">endMemberDocList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc21f85b1ee972d5143aa0e10c12a74c">startMemberList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f70ed026824c54b80bb9019bb8fd735">endMemberList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ccc69fb60f4b835a7eed748a9fea1a6">startInlineHeader</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ae605fb609b3390e640b46ea9485df">endInlineHeader</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a373de27a917a5e5b6421fa26f87c4449">startAnonTypeScope</a> (int i1)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251e99f1dd3a2ca68601bac19b82e34e">endAnonTypeScope</a> (int i1)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a> (const QCString &amp;anchor, OutputGenerator::MemberItemType type, const QCString &amp;id=QCString())=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a> (OutputGenerator::MemberItemType type)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b6535ee5e38767846bea0e6ba96c8a">startMemberTemplateParams</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5d41dae8e31415f650b52a29eba2817">endMemberTemplateParams</a> (const QCString &amp;anchor, const QCString &amp;inheritId)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f617fe193172f0f97b27c499de9cfa">startCompoundTemplateParams</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a763b35a02d7ea5e883a2f20de2dd5">endCompoundTemplateParams</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3593d54f692a41d566ae01109aeef05e">startMemberGroupHeader</a> (const QCString &amp;id, bool b)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50e780b2fe3496ff171dbb1e6759b341">endMemberGroupHeader</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac57ae72f8115bbe8ed6b303cffb984f7">startMemberGroupDocs</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8b5416218377138621fb34b840b790">endMemberGroupDocs</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36689312cd35c431b1ce66ac3ba35594">startMemberGroup</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595fff4a7d0ae9b9d7642237c28f8901">endMemberGroup</a> (bool last)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa837f5a6ce555e11398b3df3ecb3e88f">insertMemberAlign</a> (bool templ=FALSE)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2082c126cedbfc6c0491fc8b96ccba7a">insertMemberAlignLeft</a> (OutputGenerator::MemberItemType typ=OutputGenerator::MemberItemType::Normal, bool templ=FALSE)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e67a4680207146c0717f53e778ad83e">writeRuler</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda0d70c12b2ac6fc6e66a4543b19a44">writeAnchor</a> (const QCString &amp;fileName, const QCString &amp;name)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc1b898c2dcc3f6062da795a440da48">startEmphasis</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37834e6f65935417349d2385634a2c21">endEmphasis</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b1f57669e3d916ca995a880935a6df">writeChar</a> (char c)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a116232c9975fe8505bf789dd51eadb56">startMemberDoc</a> (const QCString &amp;clName, const QCString &amp;memName, const QCString &amp;anchor, const QCString &amp;title, int memCount, int memTotal, bool showInline)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe07b6722ddad023f2a87715be57d02a">endMemberDoc</a> (bool hasArgs)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecae8460986ee6b91397ae321ce627a1">startDoxyAnchor</a> (const QCString &amp;fName, const QCString &amp;manName, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;args)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7468a0ce3722e8bef650142f7156db55">endDoxyAnchor</a> (const QCString &amp;fn, const QCString &amp;anchor)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7045a43d7af51c6afc747cf4fbb83e62">addLabel</a> (const QCString &amp;fName, const QCString &amp;anchor)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ffbea116a5c5bf0c54b43ba3f6a4132">writeLatexSpacing</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c4d70eded6831c56b01a78ed8de5a9">startDescForItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7c4412fd00138e2fc488aadc7f30245">endDescForItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4437f40ef79e76ed6aca6e2b6eb4e5">startCenter</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac6536bc0b0f3702c307df16e33d377">endCenter</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa535ab26ba3724479354f6944e780f39">startSmall</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f9d5740031dd466964edd9c1d8e366">endSmall</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3b3d5489a1fcb2d885e3544da2a924">lineBreak</a> (const QCString &amp;style=QCString())=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b32f7ed14989d25fd76888ab942e65b">startBold</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba9dcd8b62329cd89ae44948320ffb7">endBold</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4e50ba3e911eec35461895c2864b7a">startMemberDescription</a> (const QCString &amp;anchor, const QCString &amp;inheritId=QCString(), bool typ=false)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ae7d5969b715c6e25b3937179bdfcda">endMemberDescription</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38369ad05d7e5584a64b32576dc95e6">startMemberDeclaration</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a6280b740a76252834564a1f4fbce9">endMemberDeclaration</a> (const QCString &amp;anchor, const QCString &amp;inheritId)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec93094d1142185397b89f683e3f805c">writeInheritedSectionTitle</a> (const QCString &amp;id, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;title, const QCString &amp;name)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c05d1ccc1a97e87db2eb6ac111ba720">startExamples</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2f10d9cc4f4ff526bff1d3898f33934">endExamples</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3942248646635d62ce76ff4c58501013">startIndent</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf2b99b43f4d42da4ff4201ad2daf3d">endIndent</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf099495987baa700a91ebd8284efd2">startSection</a> (const QCString &amp;lab, const QCString &amp;title, SectionType t)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3c9cb988a0e2d49068465772433409">endSection</a> (const QCString &amp;lab, SectionType t)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a640422f1a26c32e99bab05d044738">addIndexItem</a> (const QCString &amp;s1, const QCString &amp;s2)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc8d2bf34bb5f53b758cbcac0074e3c">writeSynopsis</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b1cedf05d8efc75853f8e7c7582f322">startClassDiagram</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf06294041a469daea14c657e7f8f8a1">endClassDiagram</a> (const ClassDiagram &amp;d, const QCString &amp;f, const QCString &amp;n)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad700dc5ae546c3e60eaf3a0fc821f626">startPageRef</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0916dd878a34ca4c4b65492dc17b3c8">endPageRef</a> (const QCString &amp;c, const QCString &amp;a)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49399b68dc9d396e2decd25c69fe9c71">startQuickIndices</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779e6a499dbba756b5589de4cab1d8a8">endQuickIndices</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa7b661bcbc35895bd704e48999c3849">writeSplitBar</a> (const QCString &amp;name, const QCString &amp;allMembersFile)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93da7f6e4680d6426a444871a0dd272">writeNavigationPath</a> (const QCString &amp;s)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9673da2d9860875be433aa9885da80d">writeLogo</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeaa883814a4981f89c3383a1dac404b">writeQuickLinks</a> (HighlightedItem hli, const QCString &amp;file, bool extraTabs)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a84ef9ad423d5893da62114366f71b">writeSummaryLink</a> (const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;title, bool first)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3253ebaf15e52566edf6b5804ed0e930">writePageOutline</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae686f96a24cb17e204b8d497701d5d62">startContents</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54cc5e51ef3ce1f73ce8fe5076728ce2">endContents</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b784e509b334fac1a75627148761be8">startPageDoc</a> (const QCString &amp;pageTitle)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d62301cd87ef0c6e51bc7c55c9982b">endPageDoc</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7523bc031627d3ffec3a61be2183983">writeNonBreakableSpace</a> (int num)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a099593df5a76ae4bb6826aa8be58ca71">startDescTable</a> (const QCString &amp;title, const bool hasInits)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa739019fb6ba6bf3574124960a0c008d">endDescTable</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee5d670908097c2bc08bedf6e1c32c6">startDescTableRow</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396567c15638c9a422a2d81f965f961e">endDescTableRow</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1af7866c36c8c7fe2d2375558935b85">startDescTableTitle</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eff9a7f506c0f6e778f3e1042a1164c">endDescTableTitle</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab38bee163993a50c58b8bd4c79216d1a">startDescTableInit</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99cfd41eafdc5084b1295c5566952fe">endDescTableInit</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14febd9e78a190e5e6fc1b0000a86845">startDescTableData</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da533da32a0c6732034fd20e5a2ac8e">endDescTableData</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2819be1125a573d7abdbf5a522b9310">startDotGraph</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85da45c99b7e32ea195bf761badef17e">endDotGraph</a> (DotClassGraph &amp;g)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">startInclDepGraph</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c2ff3af9f3bc519bf30ab81fd72cd75">endInclDepGraph</a> (DotInclDepGraph &amp;g)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8e5518bbf7f0829f3a2572a1720079">startCallGraph</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ff59f95f9e1d0378ca4a740b715d84">endCallGraph</a> (DotCallGraph &amp;g)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0e8dca170cca694dc0166fb95aa13e">startDirDepGraph</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3975a13911703f0137c23fcb011f28d6">endDirDepGraph</a> (DotDirDeps &amp;g)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695dc048f7688078bff6ba6eae779dea">startGroupCollaboration</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab20e32028a6c404de530f20a8d08afe">endGroupCollaboration</a> (DotGroupCollaboration &amp;g)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eac8c3de9fb5faac26a15e461441ac5">writeGraphicalHierarchy</a> (DotGfxHierarchyTable &amp;g)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2409cde2f7961ca5cf4b967335c5f50">startTextBlock</a> (bool dense=FALSE)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5585b6af901be0830ae54b693668ce">endTextBlock</a> (bool paraBreak=FALSE)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707578caad094f7af3f04f1b4a54f052">lastIndexPage</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5995a8429533bd21364530edeb763711">startMemberDocPrefixItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac37e18752d8dac929d084738ea62392">endMemberDocPrefixItem</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d8c190fc894d6743423e628c19294b">startMemberDocName</a> (bool align)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97574716039c8331afbd0295e0cd7dac">endMemberDocName</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1976bdf79e45f6747ef356cae0a95411">startParameterType</a> (bool first, const QCString &amp;key)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a436aab094abf10c862af8e86712ac7df">endParameterType</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a230c27f71a06e4127b602b621f548985">startParameterName</a> (bool one)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9958dc52e088a6c840c324f992a61782">endParameterName</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6ab24e04280715dbb109c2fff18356">startParameterExtra</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cbac7733e17d57b2caccb30e3bf98e2">endParameterExtra</a> (bool last, bool one, bool bracket)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6785e89293e0a1a656cea7f3a11ce0f">startParameterDefVal</a> (const char *separator)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d39fdc7cdaec182baa7fb3d909fab7">endParameterDefVal</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">startParameterList</a> (bool openBracket)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514360a2c3c4b46107f244004e6befa5">endParameterList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b77727f57a04d415d7acfa77dfcf13">exceptionEntry</a> (const QCString &amp;prefix, bool closeBracket)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04817619e41efde49c970d1975151edf">startConstraintList</a> (const QCString &amp;header)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9d43c719e2fccb17737dfebaec0a07c">startConstraintParam</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d996d867bc819fccaf3b6471247469">endConstraintParam</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24edd015165887d5e18c316e68c655c4">startConstraintType</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13fa68b965aa0974f29be60dff9db84">endConstraintType</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc709f71d6789db7c3b4443ed448b1a">startConstraintDocs</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a61ff0c02d0f91fcfa7b4f7ac7f405">endConstraintDocs</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b9f1b3191f567cf6c95a6c3521e8fb">endConstraintList</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0593059cb1552745f7a97a3040dd5e7c">startMemberDocSimple</a> (bool b)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f794d0e5c68e92203f4ce949d9948a">endMemberDocSimple</a> (bool b)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6735e2e800ba3e27cd0fb768e78fd1b2">startInlineMemberType</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca6cba268cc3096f54b1c9d58876d22">endInlineMemberType</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0776046486af09020f31ee8f87f8c1d0">startInlineMemberName</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b809e57901e6c2e3cff2a413f2af5de">endInlineMemberName</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab46c5f34ec08151ad23e699ec093e858">startInlineMemberDoc</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b792e5046631e4093bcf4a61411eeb">endInlineMemberDoc</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79d3695d6eef65e69af540fc5e2187f">startLabels</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272adadd57275dc0ffe350691531eca4">writeLabel</a> (const QCString &amp;l, bool isLast)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695f6a7ee5d38ef46da40bc44fca8828">endLabels</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b77f3e740d66edde2819141517d8788">startLocalToc</a> (int level)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b88cf6885c4ca71693bb3ca988a48b2">endLocalToc</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1602bf413b97f22052cf036643f3f1c">startTocEntry</a> (const SectionInfo *si)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20804e800904af439381fbf9f11be3d3">endTocEntry</a> (const SectionInfo *si)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80b9bba0ea2a5777a3d1a6b5455d6985">cleanup</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3d61c68c3ec0817933b533ced5806a">startPlainFile</a> (const QCString &amp;name)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43b7360d19bc7009a3d6ff1ec1398664">endPlainFile</a> ()=0</td>
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

<p>Abstract interface for output generators.</p>

<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGen() {#a2399adf8c0604e50bb4c0911ef961742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::addCodeGen (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; list)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00133">133</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a2399adf8c0604e50bb4c0911ef961742">addCodeGen</a>.

Referenced by <a href="#a2399adf8c0604e50bb4c0911ef961742">addCodeGen</a>.
</div>
</div>

### addIndexItem() {#a25a640422f1a26c32e99bab05d044738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::addIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00242">242</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a25a640422f1a26c32e99bab05d044738">addIndexItem</a>.

Referenced by <a href="#a25a640422f1a26c32e99bab05d044738">addIndexItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6a14eebaf70a50055e47c6738c56de13">OutputList::addIndexItem</a>.
</div>
</div>

### addLabel() {#a7045a43d7af51c6afc747cf4fbb83e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::addLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00218">218</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7045a43d7af51c6afc747cf4fbb83e62">addLabel</a>.

Referenced by <a href="#a7045a43d7af51c6afc747cf4fbb83e62">addLabel</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a87a285c01c1913708553746b1f2813f0">OutputList::addLabel</a>.
</div>
</div>

### cleanup() {#a80b9bba0ea2a5777a3d1a6b5455d6985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::cleanup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00323">323</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a80b9bba0ea2a5777a3d1a6b5455d6985">cleanup</a>.

Referenced by <a href="#a80b9bba0ea2a5777a3d1a6b5455d6985">cleanup</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac5e2f6ef346a21e513ea4bd3f53616ba">OutputList::cleanup</a>.
</div>
</div>

### clone() {#a685aff27480f0f7cfe980bdd91cfffaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; OutputGenIntf &gt; OutputGenIntf::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00132">132</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a685aff27480f0f7cfe980bdd91cfffaf">clone</a>.

Referenced by <a href="#a685aff27480f0f7cfe980bdd91cfffaf">clone</a>.
</div>
</div>

### docify() {#aac6eb7a359ed49bbeb245e3e7b0993eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::docify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00162">162</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aac6eb7a359ed49bbeb245e3e7b0993eb">docify</a>.

Referenced by <a href="#aac6eb7a359ed49bbeb245e3e7b0993eb">docify</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>.
</div>
</div>

### endAnonTypeScope() {#a251e99f1dd3a2ca68601bac19b82e34e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endAnonTypeScope (int i1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00190">190</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a251e99f1dd3a2ca68601bac19b82e34e">endAnonTypeScope</a>.

Referenced by <a href="#a251e99f1dd3a2ca68601bac19b82e34e">endAnonTypeScope</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acd5534bf6194d070548a92fae1438f71">OutputList::endAnonTypeScope</a>.
</div>
</div>

### endBold() {#aeba9dcd8b62329cd89ae44948320ffb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endBold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00228">228</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aeba9dcd8b62329cd89ae44948320ffb7">endBold</a>.

Referenced by <a href="#aeba9dcd8b62329cd89ae44948320ffb7">endBold</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>.
</div>
</div>

### endCallGraph() {#a14ff59f95f9e1d0378ca4a740b715d84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endCallGraph (<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp; g)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00276">276</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a14ff59f95f9e1d0378ca4a740b715d84">endCallGraph</a>.

Referenced by <a href="#a14ff59f95f9e1d0378ca4a740b715d84">endCallGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abcfc4105b1d8a3ad0e21d36a3d82aac3">OutputList::endCallGraph</a>.
</div>
</div>

### endCenter() {#afac6536bc0b0f3702c307df16e33d377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endCenter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00223">223</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#afac6536bc0b0f3702c307df16e33d377">endCenter</a>.

Referenced by <a href="#afac6536bc0b0f3702c307df16e33d377">endCenter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad71b2d5a74052d9539968a25e7d86bb0">OutputList::endCenter</a>.
</div>
</div>

### endClassDiagram() {#abf06294041a469daea14c657e7f8f8a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endClassDiagram (const <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp; d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; f, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00245">245</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#abf06294041a469daea14c657e7f8f8a1">endClassDiagram</a>.

Referenced by <a href="#abf06294041a469daea14c657e7f8f8a1">endClassDiagram</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa85387b820d582f467d4575f4598b175">OutputList::endClassDiagram</a>.
</div>
</div>

### endCompoundTemplateParams() {#ae4a763b35a02d7ea5e883a2f20de2dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endCompoundTemplateParams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00196">196</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae4a763b35a02d7ea5e883a2f20de2dd5">endCompoundTemplateParams</a>.

Referenced by <a href="#ae4a763b35a02d7ea5e883a2f20de2dd5">endCompoundTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a49fa25db298df5eba06f13e6d037da8c">OutputList::endCompoundTemplateParams</a>.
</div>
</div>

### endConstraintDocs() {#a22a61ff0c02d0f91fcfa7b4f7ac7f405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endConstraintDocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00306">306</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a22a61ff0c02d0f91fcfa7b4f7ac7f405">endConstraintDocs</a>.

Referenced by <a href="#a22a61ff0c02d0f91fcfa7b4f7ac7f405">endConstraintDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7f4d066d76f000ebeb4d810521573fdf">OutputList::endConstraintDocs</a>.
</div>
</div>

### endConstraintList() {#a38b9f1b3191f567cf6c95a6c3521e8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endConstraintList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00307">307</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a38b9f1b3191f567cf6c95a6c3521e8fb">endConstraintList</a>.

Referenced by <a href="#a38b9f1b3191f567cf6c95a6c3521e8fb">endConstraintList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1f970355071c4cdb7e2e125b8e235070">OutputList::endConstraintList</a>.
</div>
</div>

### endConstraintParam() {#aa6d996d867bc819fccaf3b6471247469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endConstraintParam ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00302">302</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aa6d996d867bc819fccaf3b6471247469">endConstraintParam</a>.

Referenced by <a href="#aa6d996d867bc819fccaf3b6471247469">endConstraintParam</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a9d50347ddbe39ce2328b87913c64bfdb">OutputList::endConstraintParam</a>.
</div>
</div>

### endConstraintType() {#ab13fa68b965aa0974f29be60dff9db84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endConstraintType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00304">304</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab13fa68b965aa0974f29be60dff9db84">endConstraintType</a>.

Referenced by <a href="#ab13fa68b965aa0974f29be60dff9db84">endConstraintType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0a3b0e8b9a13d824c67f0ca04c5fed0d">OutputList::endConstraintType</a>.
</div>
</div>

### endContents() {#a54cc5e51ef3ce1f73ce8fe5076728ce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endContents ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00257">257</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a54cc5e51ef3ce1f73ce8fe5076728ce2">endContents</a>.

Referenced by <a href="#a54cc5e51ef3ce1f73ce8fe5076728ce2">endContents</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a317bae5a753eac709cf776b2ec2fb732">OutputList::endContents</a>.
</div>
</div>

### endDescForItem() {#ac7c4412fd00138e2fc488aadc7f30245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDescForItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00221">221</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ac7c4412fd00138e2fc488aadc7f30245">endDescForItem</a>.

Referenced by <a href="#ac7c4412fd00138e2fc488aadc7f30245">endDescForItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e1d56ddf6a6238a4e1b8733d057c782">OutputList::endDescForItem</a>.
</div>
</div>

### endDescTable() {#aa739019fb6ba6bf3574124960a0c008d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDescTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00262">262</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aa739019fb6ba6bf3574124960a0c008d">endDescTable</a>.

Referenced by <a href="#aa739019fb6ba6bf3574124960a0c008d">endDescTable</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a223fb4453aeeaf8270e8bd5f875ed9c9">OutputList::endDescTable</a>.
</div>
</div>

### endDescTableData() {#a0da533da32a0c6732034fd20e5a2ac8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDescTableData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00270">270</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a0da533da32a0c6732034fd20e5a2ac8e">endDescTableData</a>.

Referenced by <a href="#a0da533da32a0c6732034fd20e5a2ac8e">endDescTableData</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a66b7fd1338764cbe47b66d3f9e77bb07">OutputList::endDescTableData</a>.
</div>
</div>

### endDescTableInit() {#ad99cfd41eafdc5084b1295c5566952fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDescTableInit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00268">268</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad99cfd41eafdc5084b1295c5566952fe">endDescTableInit</a>.

Referenced by <a href="#ad99cfd41eafdc5084b1295c5566952fe">endDescTableInit</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aec12276dffdde910102f7b2227cf79fc">OutputList::endDescTableInit</a>.
</div>
</div>

### endDescTableRow() {#a396567c15638c9a422a2d81f965f961e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDescTableRow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00264">264</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a396567c15638c9a422a2d81f965f961e">endDescTableRow</a>.

Referenced by <a href="#a396567c15638c9a422a2d81f965f961e">endDescTableRow</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b3d38267387585eb41163745d8c364f">OutputList::endDescTableRow</a>.
</div>
</div>

### endDescTableTitle() {#a8eff9a7f506c0f6e778f3e1042a1164c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDescTableTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00266">266</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8eff9a7f506c0f6e778f3e1042a1164c">endDescTableTitle</a>.

Referenced by <a href="#a8eff9a7f506c0f6e778f3e1042a1164c">endDescTableTitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a51b3d439827ec272ecc6e8c2e108eac0">OutputList::endDescTableTitle</a>.
</div>
</div>

### endDirDepGraph() {#a3975a13911703f0137c23fcb011f28d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDirDepGraph (<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp; g)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00278">278</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3975a13911703f0137c23fcb011f28d6">endDirDepGraph</a>.

Referenced by <a href="#a3975a13911703f0137c23fcb011f28d6">endDirDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a22010864383bf5332fe866e90f21bd2a">OutputList::endDirDepGraph</a>.
</div>
</div>

### endDotGraph() {#a85da45c99b7e32ea195bf761badef17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDotGraph (<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp; g)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00272">272</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a85da45c99b7e32ea195bf761badef17e">endDotGraph</a>.

Referenced by <a href="#a85da45c99b7e32ea195bf761badef17e">endDotGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abf5c8af1474707f76b32e631f033903a">OutputList::endDotGraph</a>.
</div>
</div>

### endDoxyAnchor() {#a7468a0ce3722e8bef650142f7156db55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00217">217</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7468a0ce3722e8bef650142f7156db55">endDoxyAnchor</a>.

Referenced by <a href="#a7468a0ce3722e8bef650142f7156db55">endDoxyAnchor</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a554df4a05f695ab67b514a12d9d19f6d">OutputList::endDoxyAnchor</a>.
</div>
</div>

### endEmphasis() {#a37834e6f65935417349d2385634a2c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endEmphasis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00208">208</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a37834e6f65935417349d2385634a2c21">endEmphasis</a>.

Referenced by <a href="#a37834e6f65935417349d2385634a2c21">endEmphasis</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5674d5d9336eb1f7f6cb83c058f5ad8f">OutputList::endEmphasis</a>.
</div>
</div>

### endExamples() {#ad2f10d9cc4f4ff526bff1d3898f33934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00237">237</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad2f10d9cc4f4ff526bff1d3898f33934">endExamples</a>.

Referenced by <a href="#ad2f10d9cc4f4ff526bff1d3898f33934">endExamples</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5ee61a2f622e01eb1aa47f22faafd3b9">OutputList::endExamples</a>.
</div>
</div>

### endFile() {#aec223180ecc276ad0d0382a7de95bfb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00144">144</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aec223180ecc276ad0d0382a7de95bfb9">endFile</a>.

Referenced by <a href="#aec223180ecc276ad0d0382a7de95bfb9">endFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5b0f833d3150110151ae6a095a8549a5">OutputList::endFile</a>.
</div>
</div>

### endGroupCollaboration() {#aab20e32028a6c404de530f20a8d08afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endGroupCollaboration (<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp; g)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00280">280</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aab20e32028a6c404de530f20a8d08afe">endGroupCollaboration</a>.

Referenced by <a href="#aab20e32028a6c404de530f20a8d08afe">endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a28746bbb2c399e6478adca394e6caba7">OutputList::endGroupCollaboration</a>.
</div>
</div>

### endGroupHeader() {#a7c1550c8839cbd8b1ebe15247624502b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endGroupHeader (int extraLevels=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00172">172</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7c1550c8839cbd8b1ebe15247624502b">endGroupHeader</a>.

Referenced by <a href="#a7c1550c8839cbd8b1ebe15247624502b">endGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa655c0592e136ba962ac45bb69482638">OutputList::endGroupHeader</a>.
</div>
</div>

### endHeaderSection() {#aa0cb366bd225ec3b8637dbf745bb8495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endHeaderSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00178">178</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aa0cb366bd225ec3b8637dbf745bb8495">endHeaderSection</a>.

Referenced by <a href="#aa0cb366bd225ec3b8637dbf745bb8495">endHeaderSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a327fd876b42a81d55c668042dc3104d7">OutputList::endHeaderSection</a>.
</div>
</div>

### endInclDepGraph() {#a7c2ff3af9f3bc519bf30ab81fd72cd75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endInclDepGraph (<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp; g)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00274">274</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7c2ff3af9f3bc519bf30ab81fd72cd75">endInclDepGraph</a>.

Referenced by <a href="#a7c2ff3af9f3bc519bf30ab81fd72cd75">endInclDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f1710357f5571f2ce129c6bbd7fd88b">OutputList::endInclDepGraph</a>.
</div>
</div>

### endIndent() {#addf2b99b43f4d42da4ff4201ad2daf3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00239">239</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#addf2b99b43f4d42da4ff4201ad2daf3d">endIndent</a>.

Referenced by <a href="#addf2b99b43f4d42da4ff4201ad2daf3d">endIndent</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07c0ce4a1d6d962c658f6611e4eeab83">OutputList::endIndent</a>.
</div>
</div>

### endIndexItem() {#a499b7e7082ce98ac420b4713a0a4fb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00161">161</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a499b7e7082ce98ac420b4713a0a4fb0a">endIndexItem</a>.

Referenced by <a href="#a499b7e7082ce98ac420b4713a0a4fb0a">endIndexItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4a6abff25168fc20dbbeb1dab35ddbc7">OutputList::endIndexItem</a>.
</div>
</div>

### endIndexKey() {#af6b5aa596df8637546d29846c07c971e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndexKey ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00155">155</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#af6b5aa596df8637546d29846c07c971e">endIndexKey</a>.

Referenced by <a href="#af6b5aa596df8637546d29846c07c971e">endIndexKey</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a68031752ec7526128f5c77b7e18e932e">OutputList::endIndexKey</a>.
</div>
</div>

### endIndexList() {#a7c5b6593573ffe5ab167aa4f3b2ffdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndexList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00153">153</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7c5b6593573ffe5ab167aa4f3b2ffdb9">endIndexList</a>.

Referenced by <a href="#a7c5b6593573ffe5ab167aa4f3b2ffdb9">endIndexList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5577c7f73e2b8925ba8aedad6c5d1cc9">OutputList::endIndexList</a>.
</div>
</div>

### endIndexListItem() {#a157226abc71a5e32f8cb882cc4d943b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndexListItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00151">151</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a157226abc71a5e32f8cb882cc4d943b1">endIndexListItem</a>.

Referenced by <a href="#a157226abc71a5e32f8cb882cc4d943b1">endIndexListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aac70ec48d9f50b625f757a02a7758712">OutputList::endIndexListItem</a>.
</div>
</div>

### endIndexSection() {#a927f5983fc93c11d18237ca76fb74eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00136">136</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a927f5983fc93c11d18237ca76fb74eb5">endIndexSection</a>.

Referenced by <a href="#a927f5983fc93c11d18237ca76fb74eb5">endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a59226412e1c0b732f16dfbf601c2c388">OutputList::endIndexSection</a>.
</div>
</div>

### endIndexValue() {#ae711fa5b116608e306734eec728f6d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endIndexValue (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00157">157</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae711fa5b116608e306734eec728f6d79">endIndexValue</a>.

Referenced by <a href="#ae711fa5b116608e306734eec728f6d79">endIndexValue</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a15cba49ad2f72c412b909f4b39098dd0">OutputList::endIndexValue</a>.
</div>
</div>

### endInlineHeader() {#a60ae605fb609b3390e640b46ea9485df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endInlineHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00188">188</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a60ae605fb609b3390e640b46ea9485df">endInlineHeader</a>.

Referenced by <a href="#a60ae605fb609b3390e640b46ea9485df">endInlineHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a38e8c68dc35efa5e22e9152f25d8b4eb">OutputList::endInlineHeader</a>.
</div>
</div>

### endInlineMemberDoc() {#a89b792e5046631e4093bcf4a61411eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endInlineMemberDoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00315">315</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a89b792e5046631e4093bcf4a61411eeb">endInlineMemberDoc</a>.

Referenced by <a href="#a89b792e5046631e4093bcf4a61411eeb">endInlineMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a70aceb24f76c182ccc5f52285aa235e8">OutputList::endInlineMemberDoc</a>.
</div>
</div>

### endInlineMemberName() {#a3b809e57901e6c2e3cff2a413f2af5de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endInlineMemberName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00313">313</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3b809e57901e6c2e3cff2a413f2af5de">endInlineMemberName</a>.

Referenced by <a href="#a3b809e57901e6c2e3cff2a413f2af5de">endInlineMemberName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad8d98f7851b5215e0f810b0cfcc40e91">OutputList::endInlineMemberName</a>.
</div>
</div>

### endInlineMemberType() {#a7ca6cba268cc3096f54b1c9d58876d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endInlineMemberType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00311">311</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7ca6cba268cc3096f54b1c9d58876d22">endInlineMemberType</a>.

Referenced by <a href="#a7ca6cba268cc3096f54b1c9d58876d22">endInlineMemberType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a3545005c4ed9d2e9058dd3baed0ee5a8">OutputList::endInlineMemberType</a>.
</div>
</div>

### endItemList() {#a10e1c75aa036fadb2b4914564c1be3ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endItemList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00159">159</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a10e1c75aa036fadb2b4914564c1be3ff">endItemList</a>.

Referenced by <a href="#a10e1c75aa036fadb2b4914564c1be3ff">endItemList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac6efca5985597bb6e51427c51d40732f">OutputList::endItemList</a>.
</div>
</div>

### endItemListItem() {#aa3e20dae21d9d6e5b11a94a38b10896a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endItemListItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00174">174</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aa3e20dae21d9d6e5b11a94a38b10896a">endItemListItem</a>.

Referenced by <a href="#aa3e20dae21d9d6e5b11a94a38b10896a">endItemListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a784d921c1961db570e1b12905fe97c05">OutputList::endItemListItem</a>.
</div>
</div>

### endLabels() {#a695f6a7ee5d38ef46da40bc44fca8828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endLabels ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00318">318</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a695f6a7ee5d38ef46da40bc44fca8828">endLabels</a>.

Referenced by <a href="#a695f6a7ee5d38ef46da40bc44fca8828">endLabels</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aaf53a952591ed98b004311c5570411a0">OutputList::endLabels</a>.
</div>
</div>

### endLocalToc() {#a7b88cf6885c4ca71693bb3ca988a48b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endLocalToc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00320">320</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7b88cf6885c4ca71693bb3ca988a48b2">endLocalToc</a>.

Referenced by <a href="#a7b88cf6885c4ca71693bb3ca988a48b2">endLocalToc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a90e0efde7c8ea06a10471c9e77516648">OutputList::endLocalToc</a>.
</div>
</div>

### endMemberDeclaration() {#ad7a6280b740a76252834564a1f4fbce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDeclaration (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00232">232</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad7a6280b740a76252834564a1f4fbce9">endMemberDeclaration</a>.

Referenced by <a href="#ad7a6280b740a76252834564a1f4fbce9">endMemberDeclaration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acd8c06dad427743e4bf81f94bd450e6f">OutputList::endMemberDeclaration</a>.
</div>
</div>

### endMemberDescription() {#a9ae7d5969b715c6e25b3937179bdfcda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDescription ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00230">230</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a9ae7d5969b715c6e25b3937179bdfcda">endMemberDescription</a>.

Referenced by <a href="#a9ae7d5969b715c6e25b3937179bdfcda">endMemberDescription</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a3824b9043050bea2202a29c15b4c5344">OutputList::endMemberDescription</a>.
</div>
</div>

### endMemberDoc() {#afe07b6722ddad023f2a87715be57d02a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDoc (bool hasArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00213">213</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#afe07b6722ddad023f2a87715be57d02a">endMemberDoc</a>.

Referenced by <a href="#afe07b6722ddad023f2a87715be57d02a">endMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1fb2fb5d619d66c8653e05a46a18ef48">OutputList::endMemberDoc</a>.
</div>
</div>

### endMemberDocList() {#aa4eb90cc7d89d88a0d2333be8063394f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDocList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00184">184</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aa4eb90cc7d89d88a0d2333be8063394f">endMemberDocList</a>.

Referenced by <a href="#aa4eb90cc7d89d88a0d2333be8063394f">endMemberDocList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a65672c5fa7d9f56208917e3d4b8e1895">OutputList::endMemberDocList</a>.
</div>
</div>

### endMemberDocName() {#a97574716039c8331afbd0295e0cd7dac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDocName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00288">288</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a97574716039c8331afbd0295e0cd7dac">endMemberDocName</a>.

Referenced by <a href="#a97574716039c8331afbd0295e0cd7dac">endMemberDocName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1c30d8717346992a8a9c35f2ae92271f">OutputList::endMemberDocName</a>.
</div>
</div>

### endMemberDocPrefixItem() {#aac37e18752d8dac929d084738ea62392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDocPrefixItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00286">286</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aac37e18752d8dac929d084738ea62392">endMemberDocPrefixItem</a>.

Referenced by <a href="#aac37e18752d8dac929d084738ea62392">endMemberDocPrefixItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7119d284c2d0a7d635d103969d9e628e">OutputList::endMemberDocPrefixItem</a>.
</div>
</div>

### endMemberDocSimple() {#a24f794d0e5c68e92203f4ce949d9948a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberDocSimple (bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00309">309</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a24f794d0e5c68e92203f4ce949d9948a">endMemberDocSimple</a>.

Referenced by <a href="#a24f794d0e5c68e92203f4ce949d9948a">endMemberDocSimple</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adafe6153e5b6d4d5252abce4ccde8147">OutputList::endMemberDocSimple</a>.
</div>
</div>

### endMemberGroup() {#a595fff4a7d0ae9b9d7642237c28f8901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberGroup (bool last)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00202">202</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a595fff4a7d0ae9b9d7642237c28f8901">endMemberGroup</a>.

Referenced by <a href="#a595fff4a7d0ae9b9d7642237c28f8901">endMemberGroup</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac38b30488a0d82de3aa04b7ae30ed48e">OutputList::endMemberGroup</a>.
</div>
</div>

### endMemberGroupDocs() {#a0c8b5416218377138621fb34b840b790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberGroupDocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00200">200</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a0c8b5416218377138621fb34b840b790">endMemberGroupDocs</a>.

Referenced by <a href="#a0c8b5416218377138621fb34b840b790">endMemberGroupDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a3cf86cdcd2fb2e853a0bd5be6edb1858">OutputList::endMemberGroupDocs</a>.
</div>
</div>

### endMemberGroupHeader() {#a50e780b2fe3496ff171dbb1e6759b341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberGroupHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00198">198</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a50e780b2fe3496ff171dbb1e6759b341">endMemberGroupHeader</a>.

Referenced by <a href="#a50e780b2fe3496ff171dbb1e6759b341">endMemberGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac13352584de9c19dd2776d49c1e9bf30">OutputList::endMemberGroupHeader</a>.
</div>
</div>

### endMemberHeader() {#a6a824e30a4173507c3d8b8fc1d391840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00180">180</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6a824e30a4173507c3d8b8fc1d391840">endMemberHeader</a>.

Referenced by <a href="#a6a824e30a4173507c3d8b8fc1d391840">endMemberHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad50904387e56ccb6532385bfe525e9a2">OutputList::endMemberHeader</a>.
</div>
</div>

### endMemberItem() {#aa9af48be8371aee3f0d0b65d4fd22015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberItem (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00192">192</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a> and <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a>.

Referenced by <a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7bcc956b2ecbc3aed4f265593621dc0d">OutputList::endMemberItem</a>.
</div>
</div>

### endMemberList() {#a7f70ed026824c54b80bb9019bb8fd735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00186">186</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7f70ed026824c54b80bb9019bb8fd735">endMemberList</a>.

Referenced by <a href="#a7f70ed026824c54b80bb9019bb8fd735">endMemberList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7c8d844390c3ab106b675144baa48fc7">OutputList::endMemberList</a>.
</div>
</div>

### endMemberSections() {#a667642e79b9e787ffaaed927431106e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00176">176</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a667642e79b9e787ffaaed927431106e7">endMemberSections</a>.

Referenced by <a href="#a667642e79b9e787ffaaed927431106e7">endMemberSections</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aff8a0fa5afe518609c8e95ae05a57ee6">OutputList::endMemberSections</a>.
</div>
</div>

### endMemberSubtitle() {#a024f537b0e167928d8fbbd7c83126afe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberSubtitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00182">182</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a024f537b0e167928d8fbbd7c83126afe">endMemberSubtitle</a>.

Referenced by <a href="#a024f537b0e167928d8fbbd7c83126afe">endMemberSubtitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad7bb1f47d3fe0d2bc473093e405f348e">OutputList::endMemberSubtitle</a>.
</div>
</div>

### endMemberTemplateParams() {#ae5d41dae8e31415f650b52a29eba2817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endMemberTemplateParams (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00194">194</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae5d41dae8e31415f650b52a29eba2817">endMemberTemplateParams</a>.

Referenced by <a href="#ae5d41dae8e31415f650b52a29eba2817">endMemberTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1b4540041426548396bf81bff58483ad">OutputList::endMemberTemplateParams</a>.
</div>
</div>

### endPageDoc() {#a39d62301cd87ef0c6e51bc7c55c9982b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endPageDoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00259">259</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a39d62301cd87ef0c6e51bc7c55c9982b">endPageDoc</a>.

Referenced by <a href="#a39d62301cd87ef0c6e51bc7c55c9982b">endPageDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a58cd93dd010aa638e8b54259bdea9b74">OutputList::endPageDoc</a>.
</div>
</div>

### endPageRef() {#ac0916dd878a34ca4c4b65492dc17b3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endPageRef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; c, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; a)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00247">247</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ac0916dd878a34ca4c4b65492dc17b3c8">endPageRef</a>.

Referenced by <a href="#ac0916dd878a34ca4c4b65492dc17b3c8">endPageRef</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a00f61efb96bdef4833ba228f08c7f18e">OutputList::endPageRef</a>.
</div>
</div>

### endParagraph() {#a8f725c5406981a4aaa9aba38078ffc71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endParagraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00148">148</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8f725c5406981a4aaa9aba38078ffc71">endParagraph</a>.

Referenced by <a href="#a8f725c5406981a4aaa9aba38078ffc71">endParagraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6523eb013a6f759d505650de41855085">OutputList::endParagraph</a>.
</div>
</div>

### endParameterDefVal() {#a35d39fdc7cdaec182baa7fb3d909fab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endParameterDefVal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00296">296</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a35d39fdc7cdaec182baa7fb3d909fab7">endParameterDefVal</a>.

Referenced by <a href="#a35d39fdc7cdaec182baa7fb3d909fab7">endParameterDefVal</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8be0158b8b2a857157cfe92b802e0609">OutputList::endParameterDefVal</a>.
</div>
</div>

### endParameterExtra() {#a6cbac7733e17d57b2caccb30e3bf98e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endParameterExtra (bool last, bool one, bool bracket)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00294">294</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6cbac7733e17d57b2caccb30e3bf98e2">endParameterExtra</a>.

Referenced by <a href="#a6cbac7733e17d57b2caccb30e3bf98e2">endParameterExtra</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">OutputList::endParameterExtra</a>.
</div>
</div>

### endParameterList() {#a514360a2c3c4b46107f244004e6befa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endParameterList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00298">298</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a514360a2c3c4b46107f244004e6befa5">endParameterList</a>.

Referenced by <a href="#a514360a2c3c4b46107f244004e6befa5">endParameterList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ab7c1be88384dc59f5ca11f8da2113a4d">OutputList::endParameterList</a>.
</div>
</div>

### endParameterName() {#a9958dc52e088a6c840c324f992a61782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endParameterName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00292">292</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a9958dc52e088a6c840c324f992a61782">endParameterName</a>.

Referenced by <a href="#a9958dc52e088a6c840c324f992a61782">endParameterName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">OutputList::endParameterName</a>.
</div>
</div>

### endParameterType() {#a436aab094abf10c862af8e86712ac7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endParameterType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00290">290</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a436aab094abf10c862af8e86712ac7df">endParameterType</a>.

Referenced by <a href="#a436aab094abf10c862af8e86712ac7df">endParameterType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">OutputList::endParameterType</a>.
</div>
</div>

### endPlainFile() {#a43b7360d19bc7009a3d6ff1ec1398664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endPlainFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00325">325</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a43b7360d19bc7009a3d6ff1ec1398664">endPlainFile</a>.

Referenced by <a href="#a43b7360d19bc7009a3d6ff1ec1398664">endPlainFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aef22d797dc5dae4fcce9984246587932">OutputList::endPlainFile</a>.
</div>
</div>

### endProjectNumber() {#ab8f1a4a235cb4e41997f238b2c969d18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endProjectNumber ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00139">139</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab8f1a4a235cb4e41997f238b2c969d18">endProjectNumber</a>.

Referenced by <a href="#ab8f1a4a235cb4e41997f238b2c969d18">endProjectNumber</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad6faf5debd750bf3fb143ffc571a0d22">OutputList::endProjectNumber</a>.
</div>
</div>

### endQuickIndices() {#a779e6a499dbba756b5589de4cab1d8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endQuickIndices ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00249">249</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a779e6a499dbba756b5589de4cab1d8a8">endQuickIndices</a>.

Referenced by <a href="#a779e6a499dbba756b5589de4cab1d8a8">endQuickIndices</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ab1da800b31634af3c518bfa8c0b8323b">OutputList::endQuickIndices</a>.
</div>
</div>

### endSection() {#aaf3c9cb988a0e2d49068465772433409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00241">241</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aaf3c9cb988a0e2d49068465772433409">endSection</a>.

Referenced by <a href="#aaf3c9cb988a0e2d49068465772433409">endSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a135844f68859bdb67f2614664ae26f8d">OutputList::endSection</a>.
</div>
</div>

### endSmall() {#a74f9d5740031dd466964edd9c1d8e366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endSmall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00225">225</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a74f9d5740031dd466964edd9c1d8e366">endSmall</a>.

Referenced by <a href="#a74f9d5740031dd466964edd9c1d8e366">endSmall</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8142de5d17dd16fce39b80c0dfc3dfe2">OutputList::endSmall</a>.
</div>
</div>

### endTextBlock() {#aad5585b6af901be0830ae54b693668ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endTextBlock (bool paraBreak=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00283">283</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="#aad5585b6af901be0830ae54b693668ce">endTextBlock</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.

Referenced by <a href="#aad5585b6af901be0830ae54b693668ce">endTextBlock</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a06ee92661f22a8e270e6b1cc538773b5">OutputList::endTextBlock</a>.
</div>
</div>

### endTextLink() {#a578bfc0ee8985ffdf1e141445e3479e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endTextLink ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00166">166</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a578bfc0ee8985ffdf1e141445e3479e4">endTextLink</a>.

Referenced by <a href="#a578bfc0ee8985ffdf1e141445e3479e4">endTextLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a74e89e9bcca41e9203ca080fc127a004">OutputList::endTextLink</a>.
</div>
</div>

### endTitleHead() {#abc47b7bf7e7ba0ab1b3a34f4e36e5a37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00146">146</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">endTitleHead</a>.

Referenced by <a href="#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">endTitleHead</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0d24b8d36374b773ce723e4b3ae650e7">OutputList::endTitleHead</a>.
</div>
</div>

### endTocEntry() {#a20804e800904af439381fbf9f11be3d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00322">322</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a20804e800904af439381fbf9f11be3d3">endTocEntry</a>.

Referenced by <a href="#a20804e800904af439381fbf9f11be3d3">endTocEntry</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ab34d0753ec12c656b36dd16cf16b9987">OutputList::endTocEntry</a>.
</div>
</div>

### endTypewriter() {#a3a10feddac419bcac5c2456710213600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::endTypewriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00170">170</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3a10feddac419bcac5c2456710213600">endTypewriter</a>.

Referenced by <a href="#a3a10feddac419bcac5c2456710213600">endTypewriter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad83302c45e73f387c9dc13789df012f7">OutputList::endTypewriter</a>.
</div>
</div>

### exceptionEntry() {#a41b77727f57a04d415d7acfa77dfcf13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::exceptionEntry (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix, bool closeBracket)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00299">299</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="#a41b77727f57a04d415d7acfa77dfcf13">exceptionEntry</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.

Referenced by <a href="#a41b77727f57a04d415d7acfa77dfcf13">exceptionEntry</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">OutputList::exceptionEntry</a>.
</div>
</div>

### insertMemberAlign() {#aa837f5a6ce555e11398b3df3ecb3e88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::insertMemberAlign (bool templ=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00203">203</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#aa837f5a6ce555e11398b3df3ecb3e88f">insertMemberAlign</a>.

Referenced by <a href="#aa837f5a6ce555e11398b3df3ecb3e88f">insertMemberAlign</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>.
</div>
</div>

### insertMemberAlignLeft() {#a2082c126cedbfc6c0491fc8b96ccba7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::insertMemberAlignLeft (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> typ=<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::MemberItemType::Normal</a>, bool templ=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00204">204</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a2082c126cedbfc6c0491fc8b96ccba7a">insertMemberAlignLeft</a>.

Referenced by <a href="#a2082c126cedbfc6c0491fc8b96ccba7a">insertMemberAlignLeft</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1d117e436431c6c8976e8e1e3167b20c">OutputList::insertMemberAlignLeft</a>.
</div>
</div>

### lastIndexPage() {#a707578caad094f7af3f04f1b4a54f052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::lastIndexPage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00284">284</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a707578caad094f7af3f04f1b4a54f052">lastIndexPage</a>.

Referenced by <a href="#a707578caad094f7af3f04f1b4a54f052">lastIndexPage</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a9edb8dc61594b5f30bb7f4b004b04f41">OutputList::lastIndexPage</a>.
</div>
</div>

### lineBreak() {#a5a3b3d5489a1fcb2d885e3544da2a924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::lineBreak (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00226">226</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a5a3b3d5489a1fcb2d885e3544da2a924">lineBreak</a>.

Referenced by <a href="#a5a3b3d5489a1fcb2d885e3544da2a924">lineBreak</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">OutputList::lineBreak</a>.
</div>
</div>

### startAnonTypeScope() {#a373de27a917a5e5b6421fa26f87c4449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startAnonTypeScope (int i1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00189">189</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a373de27a917a5e5b6421fa26f87c4449">startAnonTypeScope</a>.

Referenced by <a href="#a373de27a917a5e5b6421fa26f87c4449">startAnonTypeScope</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a74d52604537a67d666ce88405c23dc49">OutputList::startAnonTypeScope</a>.
</div>
</div>

### startBold() {#a3b32f7ed14989d25fd76888ab942e65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startBold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00227">227</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3b32f7ed14989d25fd76888ab942e65b">startBold</a>.

Referenced by <a href="#a3b32f7ed14989d25fd76888ab942e65b">startBold</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>.
</div>
</div>

### startCallGraph() {#adb8e5518bbf7f0829f3a2572a1720079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startCallGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00275">275</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#adb8e5518bbf7f0829f3a2572a1720079">startCallGraph</a>.

Referenced by <a href="#adb8e5518bbf7f0829f3a2572a1720079">startCallGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a20837aeac45ccb44d354e42e75eb51c9">OutputList::startCallGraph</a>.
</div>
</div>

### startCenter() {#a8a4437f40ef79e76ed6aca6e2b6eb4e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startCenter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00222">222</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8a4437f40ef79e76ed6aca6e2b6eb4e5">startCenter</a>.

Referenced by <a href="#a8a4437f40ef79e76ed6aca6e2b6eb4e5">startCenter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acc709b251fc97e9e5c7d3d205ffb0a5e">OutputList::startCenter</a>.
</div>
</div>

### startClassDiagram() {#a9b1cedf05d8efc75853f8e7c7582f322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startClassDiagram ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00244">244</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a9b1cedf05d8efc75853f8e7c7582f322">startClassDiagram</a>.

Referenced by <a href="#a9b1cedf05d8efc75853f8e7c7582f322">startClassDiagram</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a10f734424e06f796ca4c962e0017d8b6">OutputList::startClassDiagram</a>.
</div>
</div>

### startCompoundTemplateParams() {#a94f617fe193172f0f97b27c499de9cfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startCompoundTemplateParams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00195">195</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a94f617fe193172f0f97b27c499de9cfa">startCompoundTemplateParams</a>.

Referenced by <a href="#a94f617fe193172f0f97b27c499de9cfa">startCompoundTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac9278fb907b0c4dda297a1acb6738c2d">OutputList::startCompoundTemplateParams</a>.
</div>
</div>

### startConstraintDocs() {#a7dc709f71d6789db7c3b4443ed448b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startConstraintDocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00305">305</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7dc709f71d6789db7c3b4443ed448b1a">startConstraintDocs</a>.

Referenced by <a href="#a7dc709f71d6789db7c3b4443ed448b1a">startConstraintDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e2a94bd45cf237f40a9a0e7eb1386d2">OutputList::startConstraintDocs</a>.
</div>
</div>

### startConstraintList() {#a04817619e41efde49c970d1975151edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startConstraintList (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00300">300</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a04817619e41efde49c970d1975151edf">startConstraintList</a>.

Referenced by <a href="#a04817619e41efde49c970d1975151edf">startConstraintList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa97f8716fbd06a49dd172b5c65bb2c56">OutputList::startConstraintList</a>.
</div>
</div>

### startConstraintParam() {#ae9d43c719e2fccb17737dfebaec0a07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startConstraintParam ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00301">301</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae9d43c719e2fccb17737dfebaec0a07c">startConstraintParam</a>.

Referenced by <a href="#ae9d43c719e2fccb17737dfebaec0a07c">startConstraintParam</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a552198c8c605b7d5bc9cb49885e5cf87">OutputList::startConstraintParam</a>.
</div>
</div>

### startConstraintType() {#a24edd015165887d5e18c316e68c655c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startConstraintType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00303">303</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a24edd015165887d5e18c316e68c655c4">startConstraintType</a>.

Referenced by <a href="#a24edd015165887d5e18c316e68c655c4">startConstraintType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a711c480e26d4492f5cd83fc4c9947105">OutputList::startConstraintType</a>.
</div>
</div>

### startContents() {#ae686f96a24cb17e204b8d497701d5d62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startContents ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00256">256</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae686f96a24cb17e204b8d497701d5d62">startContents</a>.

Referenced by <a href="#ae686f96a24cb17e204b8d497701d5d62">startContents</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac891ad4a7081e1ab9d42a637596111db">OutputList::startContents</a>.
</div>
</div>

### startDescForItem() {#a62c4d70eded6831c56b01a78ed8de5a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDescForItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00220">220</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a62c4d70eded6831c56b01a78ed8de5a9">startDescForItem</a>.

Referenced by <a href="#a62c4d70eded6831c56b01a78ed8de5a9">startDescForItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8ac4a6e52094643a093fcdeedf1ae0bc">OutputList::startDescForItem</a>.
</div>
</div>

### startDescTable() {#a099593df5a76ae4bb6826aa8be58ca71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDescTable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const bool hasInits)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00261">261</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a099593df5a76ae4bb6826aa8be58ca71">startDescTable</a>.

Referenced by <a href="#a099593df5a76ae4bb6826aa8be58ca71">startDescTable</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7d6b8dd40e3bded41a971c0144fed3db">OutputList::startDescTable</a>.
</div>
</div>

### startDescTableData() {#a14febd9e78a190e5e6fc1b0000a86845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDescTableData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00269">269</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a14febd9e78a190e5e6fc1b0000a86845">startDescTableData</a>.

Referenced by <a href="#a14febd9e78a190e5e6fc1b0000a86845">startDescTableData</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8823d3ed58554ae3eeb9169ff920ba00">OutputList::startDescTableData</a>.
</div>
</div>

### startDescTableInit() {#ab38bee163993a50c58b8bd4c79216d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDescTableInit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00267">267</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab38bee163993a50c58b8bd4c79216d1a">startDescTableInit</a>.

Referenced by <a href="#ab38bee163993a50c58b8bd4c79216d1a">startDescTableInit</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a20199e8a222bcea2abb9a43a52926ea9">OutputList::startDescTableInit</a>.
</div>
</div>

### startDescTableRow() {#a6ee5d670908097c2bc08bedf6e1c32c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDescTableRow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00263">263</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6ee5d670908097c2bc08bedf6e1c32c6">startDescTableRow</a>.

Referenced by <a href="#a6ee5d670908097c2bc08bedf6e1c32c6">startDescTableRow</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af4b472918891fdf268e7f13ccdc4e88a">OutputList::startDescTableRow</a>.
</div>
</div>

### startDescTableTitle() {#ab1af7866c36c8c7fe2d2375558935b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDescTableTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00265">265</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab1af7866c36c8c7fe2d2375558935b85">startDescTableTitle</a>.

Referenced by <a href="#ab1af7866c36c8c7fe2d2375558935b85">startDescTableTitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6b984edbfa21eecfe20b2a7a3ef0fc97">OutputList::startDescTableTitle</a>.
</div>
</div>

### startDirDepGraph() {#aba0e8dca170cca694dc0166fb95aa13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDirDepGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00277">277</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aba0e8dca170cca694dc0166fb95aa13e">startDirDepGraph</a>.

Referenced by <a href="#aba0e8dca170cca694dc0166fb95aa13e">startDirDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6ecc6dca9d8d4bc9720971ffc1c5b788">OutputList::startDirDepGraph</a>.
</div>
</div>

### startDotGraph() {#ad2819be1125a573d7abdbf5a522b9310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDotGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00271">271</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad2819be1125a573d7abdbf5a522b9310">startDotGraph</a>.

Referenced by <a href="#ad2819be1125a573d7abdbf5a522b9310">startDotGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac6fc93128d92c79a08995457b10f6e1f">OutputList::startDotGraph</a>.
</div>
</div>

### startDoxyAnchor() {#aecae8460986ee6b91397ae321ce627a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00214">214</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aecae8460986ee6b91397ae321ce627a1">startDoxyAnchor</a>.

Referenced by <a href="#aecae8460986ee6b91397ae321ce627a1">startDoxyAnchor</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aae4920963ec75457cd7e3662aedded3a">OutputList::startDoxyAnchor</a>.
</div>
</div>

### startEmphasis() {#adcc1b898c2dcc3f6062da795a440da48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startEmphasis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00207">207</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#adcc1b898c2dcc3f6062da795a440da48">startEmphasis</a>.

Referenced by <a href="#adcc1b898c2dcc3f6062da795a440da48">startEmphasis</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">OutputList::startEmphasis</a>.
</div>
</div>

### startExamples() {#a8c05d1ccc1a97e87db2eb6ac111ba720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startExamples ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00236">236</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8c05d1ccc1a97e87db2eb6ac111ba720">startExamples</a>.

Referenced by <a href="#a8c05d1ccc1a97e87db2eb6ac111ba720">startExamples</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f81a490c1354748afe7e3b834f1907b">OutputList::startExamples</a>.
</div>
</div>

### startFile() {#a751894ca7271d62e186144bf6ea750b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int id, int hierarchyLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00143">143</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a751894ca7271d62e186144bf6ea750b4">startFile</a>.

Referenced by <a href="#a751894ca7271d62e186144bf6ea750b4">startFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a518814a98f44c11f73dbea3b7b3ed795">OutputList::startFile</a>.
</div>
</div>

### startGroupCollaboration() {#a695dc048f7688078bff6ba6eae779dea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startGroupCollaboration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00279">279</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a695dc048f7688078bff6ba6eae779dea">startGroupCollaboration</a>.

Referenced by <a href="#a695dc048f7688078bff6ba6eae779dea">startGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a41473666261dc8b245cb4daee6bc53a0">OutputList::startGroupCollaboration</a>.
</div>
</div>

### startGroupHeader() {#a3c25f35ecd9dbcbcd1804513473f8683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, int extraLevels=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00171">171</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3c25f35ecd9dbcbcd1804513473f8683">startGroupHeader</a>.

Referenced by <a href="#a3c25f35ecd9dbcbcd1804513473f8683">startGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a2cf4898386fe73bfd645d4765e713a2b">OutputList::startGroupHeader</a>.
</div>
</div>

### startHeaderSection() {#af915369f4ac0e6faeb3d558de0a5ccea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startHeaderSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00177">177</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#af915369f4ac0e6faeb3d558de0a5ccea">startHeaderSection</a>.

Referenced by <a href="#af915369f4ac0e6faeb3d558de0a5ccea">startHeaderSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a545dcbbbcdf8aac24e32df2abe0ea22d">OutputList::startHeaderSection</a>.
</div>
</div>

### startInclDepGraph() {#a8d87cbaafb593cdcbf9b2b98a7dd1f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startInclDepGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00273">273</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">startInclDepGraph</a>.

Referenced by <a href="#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">startInclDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1d3ded0121b9163ac3b11c0bb8e380c4">OutputList::startInclDepGraph</a>.
</div>
</div>

### startIndent() {#a3942248646635d62ce76ff4c58501013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00238">238</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3942248646635d62ce76ff4c58501013">startIndent</a>.

Referenced by <a href="#a3942248646635d62ce76ff4c58501013">startIndent</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5805e09c663ccde368463f3c6a767a59">OutputList::startIndent</a>.
</div>
</div>

### startIndexItem() {#ab4fea7fc7613b609e6b63ebe49e2637f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00160">160</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab4fea7fc7613b609e6b63ebe49e2637f">startIndexItem</a>.

Referenced by <a href="#ab4fea7fc7613b609e6b63ebe49e2637f">startIndexItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0d0615da54716436c72e53f16b80adfc">OutputList::startIndexItem</a>.
</div>
</div>

### startIndexKey() {#a4a2892a4a593cce615ffce7172eabc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndexKey ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00154">154</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a4a2892a4a593cce615ffce7172eabc42">startIndexKey</a>.

Referenced by <a href="#a4a2892a4a593cce615ffce7172eabc42">startIndexKey</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a193f96c7af956fe9443ffc099fc5cc13">OutputList::startIndexKey</a>.
</div>
</div>

### startIndexList() {#a6b2597524bf7275b5af10536cdf49f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndexList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00152">152</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6b2597524bf7275b5af10536cdf49f31">startIndexList</a>.

Referenced by <a href="#a6b2597524bf7275b5af10536cdf49f31">startIndexList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ace955285a164c7f27f0923986a36cff5">OutputList::startIndexList</a>.
</div>
</div>

### startIndexListItem() {#aff1ac58d5e1754872e65e7a3db6f2241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndexListItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00150">150</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aff1ac58d5e1754872e65e7a3db6f2241">startIndexListItem</a>.

Referenced by <a href="#aff1ac58d5e1754872e65e7a3db6f2241">startIndexListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adf2df33c38b53c9b95fe003aed5bc222">OutputList::startIndexListItem</a>.
</div>
</div>

### startIndexSection() {#ae869ad0ddcd664eebbedee81ad94e925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00135">135</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae869ad0ddcd664eebbedee81ad94e925">startIndexSection</a>.

Referenced by <a href="#ae869ad0ddcd664eebbedee81ad94e925">startIndexSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae92e8fd973796141115ea4ef0b15cf5b">OutputList::startIndexSection</a>.
</div>
</div>

### startIndexValue() {#a7a7025f965ca3fcf915dbf010a4a416a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startIndexValue (bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00156">156</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a7a7025f965ca3fcf915dbf010a4a416a">startIndexValue</a>.

Referenced by <a href="#a7a7025f965ca3fcf915dbf010a4a416a">startIndexValue</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a9ffa966ddc43f8d39e5a1e74a814ebef">OutputList::startIndexValue</a>.
</div>
</div>

### startInlineHeader() {#a0ccc69fb60f4b835a7eed748a9fea1a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startInlineHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00187">187</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a0ccc69fb60f4b835a7eed748a9fea1a6">startInlineHeader</a>.

Referenced by <a href="#a0ccc69fb60f4b835a7eed748a9fea1a6">startInlineHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8e3c4abdce2bc3800e782a435db5437f">OutputList::startInlineHeader</a>.
</div>
</div>

### startInlineMemberDoc() {#ab46c5f34ec08151ad23e699ec093e858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startInlineMemberDoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00314">314</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab46c5f34ec08151ad23e699ec093e858">startInlineMemberDoc</a>.

Referenced by <a href="#ab46c5f34ec08151ad23e699ec093e858">startInlineMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4627e1a2c83cf21e9b63b6c9b99e5381">OutputList::startInlineMemberDoc</a>.
</div>
</div>

### startInlineMemberName() {#a0776046486af09020f31ee8f87f8c1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startInlineMemberName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00312">312</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a0776046486af09020f31ee8f87f8c1d0">startInlineMemberName</a>.

Referenced by <a href="#a0776046486af09020f31ee8f87f8c1d0">startInlineMemberName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abd00519713f4249371669240e568d29d">OutputList::startInlineMemberName</a>.
</div>
</div>

### startInlineMemberType() {#a6735e2e800ba3e27cd0fb768e78fd1b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startInlineMemberType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00310">310</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6735e2e800ba3e27cd0fb768e78fd1b2">startInlineMemberType</a>.

Referenced by <a href="#a6735e2e800ba3e27cd0fb768e78fd1b2">startInlineMemberType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a41ac30b73768699a957c5714e4c347b4">OutputList::startInlineMemberType</a>.
</div>
</div>

### startItemList() {#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startItemList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00158">158</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">startItemList</a>.

Referenced by <a href="#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">startItemList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1677b65eb8f01a10b1d767758338a212">OutputList::startItemList</a>.
</div>
</div>

### startItemListItem() {#af2f528b46750b254f7a799fcd6ed28d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startItemListItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00173">173</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#af2f528b46750b254f7a799fcd6ed28d7">startItemListItem</a>.

Referenced by <a href="#af2f528b46750b254f7a799fcd6ed28d7">startItemListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a77e30e9a84b48907b886e8231dbbc20b">OutputList::startItemListItem</a>.
</div>
</div>

### startLabels() {#ad79d3695d6eef65e69af540fc5e2187f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startLabels ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00316">316</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad79d3695d6eef65e69af540fc5e2187f">startLabels</a>.

Referenced by <a href="#ad79d3695d6eef65e69af540fc5e2187f">startLabels</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac8244f86d2d0ccbf7e9b0641f1d3a8f6">OutputList::startLabels</a>.
</div>
</div>

### startLocalToc() {#a6b77f3e740d66edde2819141517d8788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startLocalToc (int level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00319">319</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6b77f3e740d66edde2819141517d8788">startLocalToc</a>.

Referenced by <a href="#a6b77f3e740d66edde2819141517d8788">startLocalToc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af987cfff8d8cad1bd500f87ad547d0cc">OutputList::startLocalToc</a>.
</div>
</div>

### startMemberDeclaration() {#ac38369ad05d7e5584a64b32576dc95e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDeclaration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00231">231</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ac38369ad05d7e5584a64b32576dc95e6">startMemberDeclaration</a>.

Referenced by <a href="#ac38369ad05d7e5584a64b32576dc95e6">startMemberDeclaration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a09a4062cfac0ed8f9d3dec4cd42f1aa7">OutputList::startMemberDeclaration</a>.
</div>
</div>

### startMemberDescription() {#aef4e50ba3e911eec35461895c2864b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDescription (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool typ=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00229">229</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aef4e50ba3e911eec35461895c2864b7a">startMemberDescription</a>.

Referenced by <a href="#aef4e50ba3e911eec35461895c2864b7a">startMemberDescription</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4988f821b416a64d12c7fbc0a4273bba">OutputList::startMemberDescription</a>.
</div>
</div>

### startMemberDoc() {#a116232c9975fe8505bf789dd51eadb56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; clName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int memCount, int memTotal, bool showInline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00210">210</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a116232c9975fe8505bf789dd51eadb56">startMemberDoc</a>.

Referenced by <a href="#a116232c9975fe8505bf789dd51eadb56">startMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0a9ce398bc0c3a3ef316e0c97cc33ce5">OutputList::startMemberDoc</a>.
</div>
</div>

### startMemberDocList() {#a3cc64b48e08f8c37ae68c052666e2581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDocList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00183">183</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3cc64b48e08f8c37ae68c052666e2581">startMemberDocList</a>.

Referenced by <a href="#a3cc64b48e08f8c37ae68c052666e2581">startMemberDocList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ada069f601f0651010bc78b3ccb0f6f11">OutputList::startMemberDocList</a>.
</div>
</div>

### startMemberDocName() {#a45d8c190fc894d6743423e628c19294b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDocName (bool align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00287">287</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a> and <a href="#a45d8c190fc894d6743423e628c19294b">startMemberDocName</a>.

Referenced by <a href="#a45d8c190fc894d6743423e628c19294b">startMemberDocName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b9d56f0ab609c25ba0b449e4d977f80">OutputList::startMemberDocName</a>.
</div>
</div>

### startMemberDocPrefixItem() {#a5995a8429533bd21364530edeb763711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDocPrefixItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00285">285</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a5995a8429533bd21364530edeb763711">startMemberDocPrefixItem</a>.

Referenced by <a href="#a5995a8429533bd21364530edeb763711">startMemberDocPrefixItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acc616cc002e406c1c5816f020fb7d60c">OutputList::startMemberDocPrefixItem</a>.
</div>
</div>

### startMemberDocSimple() {#a0593059cb1552745f7a97a3040dd5e7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberDocSimple (bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00308">308</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a0593059cb1552745f7a97a3040dd5e7c">startMemberDocSimple</a>.

Referenced by <a href="#a0593059cb1552745f7a97a3040dd5e7c">startMemberDocSimple</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac9ba52ac9477c974842dacd16aeb4420">OutputList::startMemberDocSimple</a>.
</div>
</div>

### startMemberGroup() {#a36689312cd35c431b1ce66ac3ba35594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00201">201</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a36689312cd35c431b1ce66ac3ba35594">startMemberGroup</a>.

Referenced by <a href="#a36689312cd35c431b1ce66ac3ba35594">startMemberGroup</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6e6c176d640939fce848f044037209c8">OutputList::startMemberGroup</a>.
</div>
</div>

### startMemberGroupDocs() {#ac57ae72f8115bbe8ed6b303cffb984f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberGroupDocs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00199">199</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ac57ae72f8115bbe8ed6b303cffb984f7">startMemberGroupDocs</a>.

Referenced by <a href="#ac57ae72f8115bbe8ed6b303cffb984f7">startMemberGroupDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac78054f50bad730b62b3456699d9a350">OutputList::startMemberGroupDocs</a>.
</div>
</div>

### startMemberGroupHeader() {#a3593d54f692a41d566ae01109aeef05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00197">197</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3593d54f692a41d566ae01109aeef05e">startMemberGroupHeader</a>.

Referenced by <a href="#a3593d54f692a41d566ae01109aeef05e">startMemberGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae7ca8c46242c727aa527ab392db22707">OutputList::startMemberGroupHeader</a>.
</div>
</div>

### startMemberHeader() {#a38cce7e6f2c721d28cd581fffc261667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int typ=2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00179">179</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a38cce7e6f2c721d28cd581fffc261667">startMemberHeader</a>.

Referenced by <a href="#a38cce7e6f2c721d28cd581fffc261667">startMemberHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af6404ab3a071c87189d8b8dd2f0d2ef1">OutputList::startMemberHeader</a>.
</div>
</div>

### startMemberItem() {#a859d57760dab81918c1f54667a4b7bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00191">191</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a> and <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a>.

Referenced by <a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad7e741530682b5707eb04b3f4009523d">OutputList::startMemberItem</a>.
</div>
</div>

### startMemberList() {#abc21f85b1ee972d5143aa0e10c12a74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00185">185</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#abc21f85b1ee972d5143aa0e10c12a74c">startMemberList</a>.

Referenced by <a href="#abc21f85b1ee972d5143aa0e10c12a74c">startMemberList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">OutputList::startMemberList</a>.
</div>
</div>

### startMemberSections() {#a479613dbc7e8b8967342736b76a00b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00175">175</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a479613dbc7e8b8967342736b76a00b59">startMemberSections</a>.

Referenced by <a href="#a479613dbc7e8b8967342736b76a00b59">startMemberSections</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f8bf0192c18e0ea785c412b23f6fd3f">OutputList::startMemberSections</a>.
</div>
</div>

### startMemberSubtitle() {#a47701af94cd5ea03b74733c9d7926251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberSubtitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00181">181</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a47701af94cd5ea03b74733c9d7926251">startMemberSubtitle</a>.

Referenced by <a href="#a47701af94cd5ea03b74733c9d7926251">startMemberSubtitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#add8c37a5cb21fb366c941cea862b2285">OutputList::startMemberSubtitle</a>.
</div>
</div>

### startMemberTemplateParams() {#a84b6535ee5e38767846bea0e6ba96c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startMemberTemplateParams ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00193">193</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a84b6535ee5e38767846bea0e6ba96c8a">startMemberTemplateParams</a>.

Referenced by <a href="#a84b6535ee5e38767846bea0e6ba96c8a">startMemberTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af5a6611d3aa4b11eafd0a785d1757483">OutputList::startMemberTemplateParams</a>.
</div>
</div>

### startPageDoc() {#a2b784e509b334fac1a75627148761be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startPageDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; pageTitle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00258">258</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a2b784e509b334fac1a75627148761be8">startPageDoc</a>.

Referenced by <a href="#a2b784e509b334fac1a75627148761be8">startPageDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aba6135c0dcee35b209b1a4996a5763c1">OutputList::startPageDoc</a>.
</div>
</div>

### startPageRef() {#ad700dc5ae546c3e60eaf3a0fc821f626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startPageRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00246">246</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad700dc5ae546c3e60eaf3a0fc821f626">startPageRef</a>.

Referenced by <a href="#ad700dc5ae546c3e60eaf3a0fc821f626">startPageRef</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f14fd99b68f6df4f9510dbc627f5a43">OutputList::startPageRef</a>.
</div>
</div>

### startParagraph() {#af0f23248db3a810e3fa1a22efd6dc810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startParagraph (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; classDef=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00147">147</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#af0f23248db3a810e3fa1a22efd6dc810">startParagraph</a>.

Referenced by <a href="#af0f23248db3a810e3fa1a22efd6dc810">startParagraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a583c7e58d6b910b7bdf67120ee4e6875">OutputList::startParagraph</a>.
</div>
</div>

### startParameterDefVal() {#ad6785e89293e0a1a656cea7f3a11ce0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startParameterDefVal (const char * separator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00295">295</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ad6785e89293e0a1a656cea7f3a11ce0f">startParameterDefVal</a>.

Referenced by <a href="#ad6785e89293e0a1a656cea7f3a11ce0f">startParameterDefVal</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7350c12854789b59595b4ad1d40a651c">OutputList::startParameterDefVal</a>.
</div>
</div>

### startParameterExtra() {#aca6ab24e04280715dbb109c2fff18356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startParameterExtra ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00293">293</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aca6ab24e04280715dbb109c2fff18356">startParameterExtra</a>.

Referenced by <a href="#aca6ab24e04280715dbb109c2fff18356">startParameterExtra</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">OutputList::startParameterExtra</a>.
</div>
</div>

### startParameterList() {#a8c23f7c0b2fd4ba55c2e5a262a3e3de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startParameterList (bool openBracket)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00297">297</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">startParameterList</a>.

Referenced by <a href="#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">startParameterList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">OutputList::startParameterList</a>.
</div>
</div>

### startParameterName() {#a230c27f71a06e4127b602b621f548985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startParameterName (bool one)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00291">291</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a230c27f71a06e4127b602b621f548985">startParameterName</a>.

Referenced by <a href="#a230c27f71a06e4127b602b621f548985">startParameterName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">OutputList::startParameterName</a>.
</div>
</div>

### startParameterType() {#a1976bdf79e45f6747ef356cae0a95411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startParameterType (bool first, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00289">289</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a1976bdf79e45f6747ef356cae0a95411">startParameterType</a>.

Referenced by <a href="#a1976bdf79e45f6747ef356cae0a95411">startParameterType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">OutputList::startParameterType</a>.
</div>
</div>

### startPlainFile() {#a8a3d61c68c3ec0817933b533ced5806a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startPlainFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00324">324</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8a3d61c68c3ec0817933b533ced5806a">startPlainFile</a>.

Referenced by <a href="#a8a3d61c68c3ec0817933b533ced5806a">startPlainFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acbe23584d1d25c0df38c01be7b431a90">OutputList::startPlainFile</a>.
</div>
</div>

### startProjectNumber() {#a9aa73996eef9d354eda1aa7bef80a92d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startProjectNumber ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00138">138</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a9aa73996eef9d354eda1aa7bef80a92d">startProjectNumber</a>.

Referenced by <a href="#a9aa73996eef9d354eda1aa7bef80a92d">startProjectNumber</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e35c28c310e74b57645aff8119c1546">OutputList::startProjectNumber</a>.
</div>
</div>

### startQuickIndices() {#a49399b68dc9d396e2decd25c69fe9c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startQuickIndices ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00248">248</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a49399b68dc9d396e2decd25c69fe9c71">startQuickIndices</a>.

Referenced by <a href="#a49399b68dc9d396e2decd25c69fe9c71">startQuickIndices</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a74849c1452e8884292ed85bf7c22f2bc">OutputList::startQuickIndices</a>.
</div>
</div>

### startSection() {#adcf099495987baa700a91ebd8284efd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00240">240</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#adcf099495987baa700a91ebd8284efd2">startSection</a>.

Referenced by <a href="#adcf099495987baa700a91ebd8284efd2">startSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae5bcc70f52a38c5c65e7271d18d3e1ed">OutputList::startSection</a>.
</div>
</div>

### startSmall() {#aa535ab26ba3724479354f6944e780f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startSmall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00224">224</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aa535ab26ba3724479354f6944e780f39">startSmall</a>.

Referenced by <a href="#aa535ab26ba3724479354f6944e780f39">startSmall</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acf8ce762c6c7838d86ad132f20a2306a">OutputList::startSmall</a>.
</div>
</div>

### startTextBlock() {#af2409cde2f7961ca5cf4b967335c5f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startTextBlock (bool dense=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00282">282</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#af2409cde2f7961ca5cf4b967335c5f50">startTextBlock</a>.

Referenced by <a href="#af2409cde2f7961ca5cf4b967335c5f50">startTextBlock</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e4b1b0039100083a979ff8d90adce58">OutputList::startTextBlock</a>.
</div>
</div>

### startTextLink() {#a075de9b4d65864892a5a4bea2ae751dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startTextLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00165">165</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a075de9b4d65864892a5a4bea2ae751dd">startTextLink</a>.

Referenced by <a href="#a075de9b4d65864892a5a4bea2ae751dd">startTextLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af084d8a76621939675ae543f47032fa4">OutputList::startTextLink</a>.
</div>
</div>

### startTitleHead() {#a39e6e6ec7f39f8847632b75dfa5490a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00145">145</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a39e6e6ec7f39f8847632b75dfa5490a9">startTitleHead</a>.

Referenced by <a href="#a39e6e6ec7f39f8847632b75dfa5490a9">startTitleHead</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a218206d83bfa847f783bf2d2346caac6">OutputList::startTitleHead</a>.
</div>
</div>

### startTocEntry() {#af1602bf413b97f22052cf036643f3f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00321">321</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#af1602bf413b97f22052cf036643f3f1c">startTocEntry</a>.

Referenced by <a href="#af1602bf413b97f22052cf036643f3f1c">startTocEntry</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a132bb85c7da750fadfa35352227b8766">OutputList::startTocEntry</a>.
</div>
</div>

### startTypewriter() {#a8d12471e1fa0455d4957b72f25c64302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::startTypewriter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00169">169</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a8d12471e1fa0455d4957b72f25c64302">startTypewriter</a>.

Referenced by <a href="#a8d12471e1fa0455d4957b72f25c64302">startTypewriter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a848e77a8fd7af578497f7ee1ec163b98">OutputList::startTypewriter</a>.
</div>
</div>

### type() {#a221f0f1fd10d58c14f9caf7faa36dde1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual OutputType OutputGenIntf::type ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00131">131</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a>.

Referenced by <a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a>, <a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a>, <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a> and <a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a>.
</div>
</div>

### writeAnchor() {#afda0d70c12b2ac6fc6e66a4543b19a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00206">206</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#afda0d70c12b2ac6fc6e66a4543b19a44">writeAnchor</a>.

Referenced by <a href="#afda0d70c12b2ac6fc6e66a4543b19a44">writeAnchor</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa14aecc6d7bfdeb2cfbd241fa55059a7">OutputList::writeAnchor</a>.
</div>
</div>

### writeChar() {#ab3b1f57669e3d916ca995a880935a6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeChar (char c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00209">209</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab3b1f57669e3d916ca995a880935a6df">writeChar</a>.

Referenced by <a href="#ab3b1f57669e3d916ca995a880935a6df">writeChar</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a188c7a8f0a0dc35ec5ea0f8b4a491d33">OutputList::writeChar</a>.
</div>
</div>

### writeDoc() {#abbad8b45e48b0d0dd8139c9c5ce5e74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeDoc (const <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> * ast, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, int id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00134">134</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#abbad8b45e48b0d0dd8139c9c5ce5e74d">writeDoc</a>.

Referenced by <a href="#abbad8b45e48b0d0dd8139c9c5ce5e74d">writeDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a475da5dda736fa915aca9fc855b1d2e7">OutputList::writeDoc</a>.
</div>
</div>

### writeFooter() {#ae06d07286c1a5e0e8dd4dcb413eea3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeFooter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; navPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00142">142</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ae06d07286c1a5e0e8dd4dcb413eea3ee">writeFooter</a>.

Referenced by <a href="#ae06d07286c1a5e0e8dd4dcb413eea3ee">writeFooter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#accf02a25e4bb1593eabc248373f08dd0">OutputList::writeFooter</a>.
</div>
</div>

### writeGraphicalHierarchy() {#a3eac8c3de9fb5faac26a15e461441ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeGraphicalHierarchy (<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp; g)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00281">281</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3eac8c3de9fb5faac26a15e461441ac5">writeGraphicalHierarchy</a>.

Referenced by <a href="#a3eac8c3de9fb5faac26a15e461441ac5">writeGraphicalHierarchy</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4d7e7f24d5fd2e4fc7cb62f992a7f10f">OutputList::writeGraphicalHierarchy</a>.
</div>
</div>

### writeInheritedSectionTitle() {#aec93094d1142185397b89f683e3f805c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeInheritedSectionTitle (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00233">233</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aec93094d1142185397b89f683e3f805c">writeInheritedSectionTitle</a>.

Referenced by <a href="#aec93094d1142185397b89f683e3f805c">writeInheritedSectionTitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae60261a39e2cc0d6fa5d78da1ae5caeb">OutputList::writeInheritedSectionTitle</a>.
</div>
</div>

### writeLabel() {#a272adadd57275dc0ffe350691531eca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, bool isLast)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00317">317</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a272adadd57275dc0ffe350691531eca4">writeLabel</a>.

Referenced by <a href="#a272adadd57275dc0ffe350691531eca4">writeLabel</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac700283b8e771ab0dd515d5f384632ff">OutputList::writeLabel</a>.
</div>
</div>

### writeLatexSpacing() {#a6ffbea116a5c5bf0c54b43ba3f6a4132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeLatexSpacing ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00219">219</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6ffbea116a5c5bf0c54b43ba3f6a4132">writeLatexSpacing</a>.

Referenced by <a href="#a6ffbea116a5c5bf0c54b43ba3f6a4132">writeLatexSpacing</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a2a7a1bca5871c912848bddde9b7dd3fc">OutputList::writeLatexSpacing</a>.
</div>
</div>

### writeLogo() {#ac9673da2d9860875be433aa9885da80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeLogo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00252">252</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ac9673da2d9860875be433aa9885da80d">writeLogo</a>.

Referenced by <a href="#ac9673da2d9860875be433aa9885da80d">writeLogo</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a739eb036549fb3787e5daa3d35bc1aff">OutputList::writeLogo</a>.
</div>
</div>

### writeNavigationPath() {#ab93da7f6e4680d6426a444871a0dd272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeNavigationPath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00251">251</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ab93da7f6e4680d6426a444871a0dd272">writeNavigationPath</a>.

Referenced by <a href="#ab93da7f6e4680d6426a444871a0dd272">writeNavigationPath</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ace864e843eca954efb12af825f56bdca">OutputList::writeNavigationPath</a>.
</div>
</div>

### writeNonBreakableSpace() {#ac7523bc031627d3ffec3a61be2183983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeNonBreakableSpace (int num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00260">260</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#ac7523bc031627d3ffec3a61be2183983">writeNonBreakableSpace</a>.

Referenced by <a href="#ac7523bc031627d3ffec3a61be2183983">writeNonBreakableSpace</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae6cc078977edd1e2a5ae2cf6ed64ed35">OutputList::writeNonBreakableSpace</a>.
</div>
</div>

### writeObjectLink() {#a53380f84190045f14ef3c6ae2f5dd275}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeObjectLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00163">163</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a53380f84190045f14ef3c6ae2f5dd275">writeObjectLink</a>.

Referenced by <a href="#a53380f84190045f14ef3c6ae2f5dd275">writeObjectLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">OutputList::writeObjectLink</a>.
</div>
</div>

### writePageLink() {#a85839f2257cc6632c3307df7f1c48cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writePageLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool first)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00137">137</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a85839f2257cc6632c3307df7f1c48cd4">writePageLink</a>.

Referenced by <a href="#a85839f2257cc6632c3307df7f1c48cd4">writePageLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad1ce4ae7803aba4c58764c906e943aab">OutputList::writePageLink</a>.
</div>
</div>

### writePageOutline() {#a3253ebaf15e52566edf6b5804ed0e930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writePageOutline ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00255">255</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3253ebaf15e52566edf6b5804ed0e930">writePageOutline</a>.

Referenced by <a href="#a3253ebaf15e52566edf6b5804ed0e930">writePageOutline</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abbe1d0534295cfb5717a33e1c1eb5fb4">OutputList::writePageOutline</a>.
</div>
</div>

### writeQuickLinks() {#abeaa883814a4981f89c3383a1dac404b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeQuickLinks (<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, bool extraTabs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00253">253</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#abeaa883814a4981f89c3383a1dac404b">writeQuickLinks</a>.

Referenced by <a href="#abeaa883814a4981f89c3383a1dac404b">writeQuickLinks</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#afc0312b9a48cae61656b930d878c718e">OutputList::writeQuickLinks</a>.
</div>
</div>

### writeRuler() {#a3e67a4680207146c0717f53e778ad83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeRuler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00205">205</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a3e67a4680207146c0717f53e778ad83e">writeRuler</a>.

Referenced by <a href="#a3e67a4680207146c0717f53e778ad83e">writeRuler</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a2203589f0bc276cb3ba01f529b9536a9">OutputList::writeRuler</a>.
</div>
</div>

### writeSearchInfo() {#a06d7c1c55247348a93966711afbb983f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeSearchInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00141">141</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a06d7c1c55247348a93966711afbb983f">writeSearchInfo</a>.

Referenced by <a href="#a06d7c1c55247348a93966711afbb983f">writeSearchInfo</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b776a7ac371d841b15862b074ddd97f">OutputList::writeSearchInfo</a>.
</div>
</div>

### writeSplitBar() {#aaa7b661bcbc35895bd704e48999c3849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeSplitBar (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; allMembersFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00250">250</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#aaa7b661bcbc35895bd704e48999c3849">writeSplitBar</a>.

Referenced by <a href="#aaa7b661bcbc35895bd704e48999c3849">writeSplitBar</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abeb86db48415009b3c09b723216fd8f6">OutputList::writeSplitBar</a>.
</div>
</div>

### writeStartAnnoItem() {#afd391f13f33ee9163d495756f978447b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeStartAnnoItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00167">167</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a> and <a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a>.

Referenced by <a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4e97c1da93e9caf6a6675f3972ba7750">OutputList::writeStartAnnoItem</a>.
</div>
</div>

### writeString() {#a9425335496ccadd1a9c8235cf31280e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00149">149</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a9425335496ccadd1a9c8235cf31280e1">writeString</a>.

Referenced by <a href="#a9425335496ccadd1a9c8235cf31280e1">writeString</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">OutputList::writeString</a>.
</div>
</div>

### writeStyleInfo() {#a2711a39698d7169932b7e24b9223ef06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeStyleInfo (int part)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00140">140</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a2711a39698d7169932b7e24b9223ef06">writeStyleInfo</a>.

Referenced by <a href="#a2711a39698d7169932b7e24b9223ef06">writeStyleInfo</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a85fc0afe789c21758373df15bcb81cc9">OutputList::writeStyleInfo</a>.
</div>
</div>

### writeSummaryLink() {#a08a84ef9ad423d5893da62114366f71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeSummaryLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, bool first)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00254">254</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a08a84ef9ad423d5893da62114366f71b">writeSummaryLink</a>.

Referenced by <a href="#a08a84ef9ad423d5893da62114366f71b">writeSummaryLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a956032c76c8c263139658a08dfe1e07f">OutputList::writeSummaryLink</a>.
</div>
</div>

### writeSynopsis() {#a6dc8d2bf34bb5f53b758cbcac0074e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutputGenIntf::writeSynopsis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00243">243</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

Reference <a href="#a6dc8d2bf34bb5f53b758cbcac0074e3c">writeSynopsis</a>.

Referenced by <a href="#a6dc8d2bf34bb5f53b758cbcac0074e3c">writeSynopsis</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7d9096a6b81f3183e6f3dc01e4e093f5">OutputList::writeSynopsis</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
