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



<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a2399adf8c0604e50bb4c0911ef961742">addCodeGen</a>.</p>


<p>Referenced by <a href="#a2399adf8c0604e50bb4c0911ef961742">addCodeGen</a>.</p>

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



<p>Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a25a640422f1a26c32e99bab05d044738">addIndexItem</a>.</p>


<p>Referenced by <a href="#a25a640422f1a26c32e99bab05d044738">addIndexItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6a14eebaf70a50055e47c6738c56de13">OutputList::addIndexItem</a>.</p>

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



<p>Definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7045a43d7af51c6afc747cf4fbb83e62">addLabel</a>.</p>


<p>Referenced by <a href="#a7045a43d7af51c6afc747cf4fbb83e62">addLabel</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a87a285c01c1913708553746b1f2813f0">OutputList::addLabel</a>.</p>

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



<p>Definition at line 323 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a80b9bba0ea2a5777a3d1a6b5455d6985">cleanup</a>.</p>


<p>Referenced by <a href="#a80b9bba0ea2a5777a3d1a6b5455d6985">cleanup</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac5e2f6ef346a21e513ea4bd3f53616ba">OutputList::cleanup</a>.</p>

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



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a685aff27480f0f7cfe980bdd91cfffaf">clone</a>.</p>


<p>Referenced by <a href="#a685aff27480f0f7cfe980bdd91cfffaf">clone</a>.</p>

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



<p>Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aac6eb7a359ed49bbeb245e3e7b0993eb">docify</a>.</p>


<p>Referenced by <a href="#aac6eb7a359ed49bbeb245e3e7b0993eb">docify</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5647a62e8819abb6e6b2378a7c115bbd">OutputList::docify</a>.</p>

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



<p>Definition at line 190 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a251e99f1dd3a2ca68601bac19b82e34e">endAnonTypeScope</a>.</p>


<p>Referenced by <a href="#a251e99f1dd3a2ca68601bac19b82e34e">endAnonTypeScope</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acd5534bf6194d070548a92fae1438f71">OutputList::endAnonTypeScope</a>.</p>

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



<p>Definition at line 228 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aeba9dcd8b62329cd89ae44948320ffb7">endBold</a>.</p>


<p>Referenced by <a href="#aeba9dcd8b62329cd89ae44948320ffb7">endBold</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa3f855a4e60d2a7c6769b66d43c69b23">OutputList::endBold</a>.</p>

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



<p>Definition at line 276 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a14ff59f95f9e1d0378ca4a740b715d84">endCallGraph</a>.</p>


<p>Referenced by <a href="#a14ff59f95f9e1d0378ca4a740b715d84">endCallGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abcfc4105b1d8a3ad0e21d36a3d82aac3">OutputList::endCallGraph</a>.</p>

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



<p>Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#afac6536bc0b0f3702c307df16e33d377">endCenter</a>.</p>


<p>Referenced by <a href="#afac6536bc0b0f3702c307df16e33d377">endCenter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad71b2d5a74052d9539968a25e7d86bb0">OutputList::endCenter</a>.</p>

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



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#abf06294041a469daea14c657e7f8f8a1">endClassDiagram</a>.</p>


<p>Referenced by <a href="#abf06294041a469daea14c657e7f8f8a1">endClassDiagram</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa85387b820d582f467d4575f4598b175">OutputList::endClassDiagram</a>.</p>

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



<p>Definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae4a763b35a02d7ea5e883a2f20de2dd5">endCompoundTemplateParams</a>.</p>


<p>Referenced by <a href="#ae4a763b35a02d7ea5e883a2f20de2dd5">endCompoundTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a49fa25db298df5eba06f13e6d037da8c">OutputList::endCompoundTemplateParams</a>.</p>

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



<p>Definition at line 306 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a22a61ff0c02d0f91fcfa7b4f7ac7f405">endConstraintDocs</a>.</p>


<p>Referenced by <a href="#a22a61ff0c02d0f91fcfa7b4f7ac7f405">endConstraintDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7f4d066d76f000ebeb4d810521573fdf">OutputList::endConstraintDocs</a>.</p>

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



<p>Definition at line 307 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a38b9f1b3191f567cf6c95a6c3521e8fb">endConstraintList</a>.</p>


<p>Referenced by <a href="#a38b9f1b3191f567cf6c95a6c3521e8fb">endConstraintList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1f970355071c4cdb7e2e125b8e235070">OutputList::endConstraintList</a>.</p>

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



<p>Definition at line 302 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aa6d996d867bc819fccaf3b6471247469">endConstraintParam</a>.</p>


<p>Referenced by <a href="#aa6d996d867bc819fccaf3b6471247469">endConstraintParam</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a9d50347ddbe39ce2328b87913c64bfdb">OutputList::endConstraintParam</a>.</p>

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



<p>Definition at line 304 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab13fa68b965aa0974f29be60dff9db84">endConstraintType</a>.</p>


<p>Referenced by <a href="#ab13fa68b965aa0974f29be60dff9db84">endConstraintType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0a3b0e8b9a13d824c67f0ca04c5fed0d">OutputList::endConstraintType</a>.</p>

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



<p>Definition at line 257 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a54cc5e51ef3ce1f73ce8fe5076728ce2">endContents</a>.</p>


<p>Referenced by <a href="#a54cc5e51ef3ce1f73ce8fe5076728ce2">endContents</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a317bae5a753eac709cf776b2ec2fb732">OutputList::endContents</a>.</p>

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



<p>Definition at line 221 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ac7c4412fd00138e2fc488aadc7f30245">endDescForItem</a>.</p>


<p>Referenced by <a href="#ac7c4412fd00138e2fc488aadc7f30245">endDescForItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e1d56ddf6a6238a4e1b8733d057c782">OutputList::endDescForItem</a>.</p>

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



<p>Definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aa739019fb6ba6bf3574124960a0c008d">endDescTable</a>.</p>


<p>Referenced by <a href="#aa739019fb6ba6bf3574124960a0c008d">endDescTable</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a223fb4453aeeaf8270e8bd5f875ed9c9">OutputList::endDescTable</a>.</p>

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



<p>Definition at line 270 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a0da533da32a0c6732034fd20e5a2ac8e">endDescTableData</a>.</p>


<p>Referenced by <a href="#a0da533da32a0c6732034fd20e5a2ac8e">endDescTableData</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a66b7fd1338764cbe47b66d3f9e77bb07">OutputList::endDescTableData</a>.</p>

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



<p>Definition at line 268 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad99cfd41eafdc5084b1295c5566952fe">endDescTableInit</a>.</p>


<p>Referenced by <a href="#ad99cfd41eafdc5084b1295c5566952fe">endDescTableInit</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aec12276dffdde910102f7b2227cf79fc">OutputList::endDescTableInit</a>.</p>

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



<p>Definition at line 264 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a396567c15638c9a422a2d81f965f961e">endDescTableRow</a>.</p>


<p>Referenced by <a href="#a396567c15638c9a422a2d81f965f961e">endDescTableRow</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b3d38267387585eb41163745d8c364f">OutputList::endDescTableRow</a>.</p>

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



<p>Definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8eff9a7f506c0f6e778f3e1042a1164c">endDescTableTitle</a>.</p>


<p>Referenced by <a href="#a8eff9a7f506c0f6e778f3e1042a1164c">endDescTableTitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a51b3d439827ec272ecc6e8c2e108eac0">OutputList::endDescTableTitle</a>.</p>

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



<p>Definition at line 278 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3975a13911703f0137c23fcb011f28d6">endDirDepGraph</a>.</p>


<p>Referenced by <a href="#a3975a13911703f0137c23fcb011f28d6">endDirDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a22010864383bf5332fe866e90f21bd2a">OutputList::endDirDepGraph</a>.</p>

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



<p>Definition at line 272 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a85da45c99b7e32ea195bf761badef17e">endDotGraph</a>.</p>


<p>Referenced by <a href="#a85da45c99b7e32ea195bf761badef17e">endDotGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abf5c8af1474707f76b32e631f033903a">OutputList::endDotGraph</a>.</p>

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



<p>Definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7468a0ce3722e8bef650142f7156db55">endDoxyAnchor</a>.</p>


<p>Referenced by <a href="#a7468a0ce3722e8bef650142f7156db55">endDoxyAnchor</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a554df4a05f695ab67b514a12d9d19f6d">OutputList::endDoxyAnchor</a>.</p>

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



<p>Definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a37834e6f65935417349d2385634a2c21">endEmphasis</a>.</p>


<p>Referenced by <a href="#a37834e6f65935417349d2385634a2c21">endEmphasis</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5674d5d9336eb1f7f6cb83c058f5ad8f">OutputList::endEmphasis</a>.</p>

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



<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad2f10d9cc4f4ff526bff1d3898f33934">endExamples</a>.</p>


<p>Referenced by <a href="#ad2f10d9cc4f4ff526bff1d3898f33934">endExamples</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5ee61a2f622e01eb1aa47f22faafd3b9">OutputList::endExamples</a>.</p>

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



<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aec223180ecc276ad0d0382a7de95bfb9">endFile</a>.</p>


<p>Referenced by <a href="#aec223180ecc276ad0d0382a7de95bfb9">endFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5b0f833d3150110151ae6a095a8549a5">OutputList::endFile</a>.</p>

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



<p>Definition at line 280 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aab20e32028a6c404de530f20a8d08afe">endGroupCollaboration</a>.</p>


<p>Referenced by <a href="#aab20e32028a6c404de530f20a8d08afe">endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a28746bbb2c399e6478adca394e6caba7">OutputList::endGroupCollaboration</a>.</p>

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



<p>Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7c1550c8839cbd8b1ebe15247624502b">endGroupHeader</a>.</p>


<p>Referenced by <a href="#a7c1550c8839cbd8b1ebe15247624502b">endGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa655c0592e136ba962ac45bb69482638">OutputList::endGroupHeader</a>.</p>

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



<p>Definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aa0cb366bd225ec3b8637dbf745bb8495">endHeaderSection</a>.</p>


<p>Referenced by <a href="#aa0cb366bd225ec3b8637dbf745bb8495">endHeaderSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a327fd876b42a81d55c668042dc3104d7">OutputList::endHeaderSection</a>.</p>

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



<p>Definition at line 274 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7c2ff3af9f3bc519bf30ab81fd72cd75">endInclDepGraph</a>.</p>


<p>Referenced by <a href="#a7c2ff3af9f3bc519bf30ab81fd72cd75">endInclDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f1710357f5571f2ce129c6bbd7fd88b">OutputList::endInclDepGraph</a>.</p>

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



<p>Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#addf2b99b43f4d42da4ff4201ad2daf3d">endIndent</a>.</p>


<p>Referenced by <a href="#addf2b99b43f4d42da4ff4201ad2daf3d">endIndent</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07c0ce4a1d6d962c658f6611e4eeab83">OutputList::endIndent</a>.</p>

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



<p>Definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a499b7e7082ce98ac420b4713a0a4fb0a">endIndexItem</a>.</p>


<p>Referenced by <a href="#a499b7e7082ce98ac420b4713a0a4fb0a">endIndexItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4a6abff25168fc20dbbeb1dab35ddbc7">OutputList::endIndexItem</a>.</p>

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



<p>Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#af6b5aa596df8637546d29846c07c971e">endIndexKey</a>.</p>


<p>Referenced by <a href="#af6b5aa596df8637546d29846c07c971e">endIndexKey</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a68031752ec7526128f5c77b7e18e932e">OutputList::endIndexKey</a>.</p>

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



<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7c5b6593573ffe5ab167aa4f3b2ffdb9">endIndexList</a>.</p>


<p>Referenced by <a href="#a7c5b6593573ffe5ab167aa4f3b2ffdb9">endIndexList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5577c7f73e2b8925ba8aedad6c5d1cc9">OutputList::endIndexList</a>.</p>

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



<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a157226abc71a5e32f8cb882cc4d943b1">endIndexListItem</a>.</p>


<p>Referenced by <a href="#a157226abc71a5e32f8cb882cc4d943b1">endIndexListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aac70ec48d9f50b625f757a02a7758712">OutputList::endIndexListItem</a>.</p>

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



<p>Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a927f5983fc93c11d18237ca76fb74eb5">endIndexSection</a>.</p>


<p>Referenced by <a href="#a927f5983fc93c11d18237ca76fb74eb5">endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a59226412e1c0b732f16dfbf601c2c388">OutputList::endIndexSection</a>.</p>

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



<p>Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae711fa5b116608e306734eec728f6d79">endIndexValue</a>.</p>


<p>Referenced by <a href="#ae711fa5b116608e306734eec728f6d79">endIndexValue</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a15cba49ad2f72c412b909f4b39098dd0">OutputList::endIndexValue</a>.</p>

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



<p>Definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a60ae605fb609b3390e640b46ea9485df">endInlineHeader</a>.</p>


<p>Referenced by <a href="#a60ae605fb609b3390e640b46ea9485df">endInlineHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a38e8c68dc35efa5e22e9152f25d8b4eb">OutputList::endInlineHeader</a>.</p>

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



<p>Definition at line 315 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a89b792e5046631e4093bcf4a61411eeb">endInlineMemberDoc</a>.</p>


<p>Referenced by <a href="#a89b792e5046631e4093bcf4a61411eeb">endInlineMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a70aceb24f76c182ccc5f52285aa235e8">OutputList::endInlineMemberDoc</a>.</p>

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



<p>Definition at line 313 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3b809e57901e6c2e3cff2a413f2af5de">endInlineMemberName</a>.</p>


<p>Referenced by <a href="#a3b809e57901e6c2e3cff2a413f2af5de">endInlineMemberName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad8d98f7851b5215e0f810b0cfcc40e91">OutputList::endInlineMemberName</a>.</p>

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



<p>Definition at line 311 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7ca6cba268cc3096f54b1c9d58876d22">endInlineMemberType</a>.</p>


<p>Referenced by <a href="#a7ca6cba268cc3096f54b1c9d58876d22">endInlineMemberType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a3545005c4ed9d2e9058dd3baed0ee5a8">OutputList::endInlineMemberType</a>.</p>

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



<p>Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a10e1c75aa036fadb2b4914564c1be3ff">endItemList</a>.</p>


<p>Referenced by <a href="#a10e1c75aa036fadb2b4914564c1be3ff">endItemList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac6efca5985597bb6e51427c51d40732f">OutputList::endItemList</a>.</p>

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



<p>Definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aa3e20dae21d9d6e5b11a94a38b10896a">endItemListItem</a>.</p>


<p>Referenced by <a href="#aa3e20dae21d9d6e5b11a94a38b10896a">endItemListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a784d921c1961db570e1b12905fe97c05">OutputList::endItemListItem</a>.</p>

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



<p>Definition at line 318 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a695f6a7ee5d38ef46da40bc44fca8828">endLabels</a>.</p>


<p>Referenced by <a href="#a695f6a7ee5d38ef46da40bc44fca8828">endLabels</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aaf53a952591ed98b004311c5570411a0">OutputList::endLabels</a>.</p>

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



<p>Definition at line 320 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7b88cf6885c4ca71693bb3ca988a48b2">endLocalToc</a>.</p>


<p>Referenced by <a href="#a7b88cf6885c4ca71693bb3ca988a48b2">endLocalToc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a90e0efde7c8ea06a10471c9e77516648">OutputList::endLocalToc</a>.</p>

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



<p>Definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad7a6280b740a76252834564a1f4fbce9">endMemberDeclaration</a>.</p>


<p>Referenced by <a href="#ad7a6280b740a76252834564a1f4fbce9">endMemberDeclaration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acd8c06dad427743e4bf81f94bd450e6f">OutputList::endMemberDeclaration</a>.</p>

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



<p>Definition at line 230 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a9ae7d5969b715c6e25b3937179bdfcda">endMemberDescription</a>.</p>


<p>Referenced by <a href="#a9ae7d5969b715c6e25b3937179bdfcda">endMemberDescription</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a3824b9043050bea2202a29c15b4c5344">OutputList::endMemberDescription</a>.</p>

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



<p>Definition at line 213 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#afe07b6722ddad023f2a87715be57d02a">endMemberDoc</a>.</p>


<p>Referenced by <a href="#afe07b6722ddad023f2a87715be57d02a">endMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1fb2fb5d619d66c8653e05a46a18ef48">OutputList::endMemberDoc</a>.</p>

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



<p>Definition at line 184 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aa4eb90cc7d89d88a0d2333be8063394f">endMemberDocList</a>.</p>


<p>Referenced by <a href="#aa4eb90cc7d89d88a0d2333be8063394f">endMemberDocList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a65672c5fa7d9f56208917e3d4b8e1895">OutputList::endMemberDocList</a>.</p>

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



<p>Definition at line 288 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a97574716039c8331afbd0295e0cd7dac">endMemberDocName</a>.</p>


<p>Referenced by <a href="#a97574716039c8331afbd0295e0cd7dac">endMemberDocName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1c30d8717346992a8a9c35f2ae92271f">OutputList::endMemberDocName</a>.</p>

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



<p>Definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aac37e18752d8dac929d084738ea62392">endMemberDocPrefixItem</a>.</p>


<p>Referenced by <a href="#aac37e18752d8dac929d084738ea62392">endMemberDocPrefixItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7119d284c2d0a7d635d103969d9e628e">OutputList::endMemberDocPrefixItem</a>.</p>

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



<p>Definition at line 309 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a24f794d0e5c68e92203f4ce949d9948a">endMemberDocSimple</a>.</p>


<p>Referenced by <a href="#a24f794d0e5c68e92203f4ce949d9948a">endMemberDocSimple</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adafe6153e5b6d4d5252abce4ccde8147">OutputList::endMemberDocSimple</a>.</p>

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



<p>Definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a595fff4a7d0ae9b9d7642237c28f8901">endMemberGroup</a>.</p>


<p>Referenced by <a href="#a595fff4a7d0ae9b9d7642237c28f8901">endMemberGroup</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac38b30488a0d82de3aa04b7ae30ed48e">OutputList::endMemberGroup</a>.</p>

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



<p>Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a0c8b5416218377138621fb34b840b790">endMemberGroupDocs</a>.</p>


<p>Referenced by <a href="#a0c8b5416218377138621fb34b840b790">endMemberGroupDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a3cf86cdcd2fb2e853a0bd5be6edb1858">OutputList::endMemberGroupDocs</a>.</p>

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



<p>Definition at line 198 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a50e780b2fe3496ff171dbb1e6759b341">endMemberGroupHeader</a>.</p>


<p>Referenced by <a href="#a50e780b2fe3496ff171dbb1e6759b341">endMemberGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac13352584de9c19dd2776d49c1e9bf30">OutputList::endMemberGroupHeader</a>.</p>

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



<p>Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6a824e30a4173507c3d8b8fc1d391840">endMemberHeader</a>.</p>


<p>Referenced by <a href="#a6a824e30a4173507c3d8b8fc1d391840">endMemberHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad50904387e56ccb6532385bfe525e9a2">OutputList::endMemberHeader</a>.</p>

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



<p>Definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a> and <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a>.</p>


<p>Referenced by <a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7bcc956b2ecbc3aed4f265593621dc0d">OutputList::endMemberItem</a>.</p>

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



<p>Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7f70ed026824c54b80bb9019bb8fd735">endMemberList</a>.</p>


<p>Referenced by <a href="#a7f70ed026824c54b80bb9019bb8fd735">endMemberList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7c8d844390c3ab106b675144baa48fc7">OutputList::endMemberList</a>.</p>

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



<p>Definition at line 176 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a667642e79b9e787ffaaed927431106e7">endMemberSections</a>.</p>


<p>Referenced by <a href="#a667642e79b9e787ffaaed927431106e7">endMemberSections</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aff8a0fa5afe518609c8e95ae05a57ee6">OutputList::endMemberSections</a>.</p>

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



<p>Definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a024f537b0e167928d8fbbd7c83126afe">endMemberSubtitle</a>.</p>


<p>Referenced by <a href="#a024f537b0e167928d8fbbd7c83126afe">endMemberSubtitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad7bb1f47d3fe0d2bc473093e405f348e">OutputList::endMemberSubtitle</a>.</p>

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



<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae5d41dae8e31415f650b52a29eba2817">endMemberTemplateParams</a>.</p>


<p>Referenced by <a href="#ae5d41dae8e31415f650b52a29eba2817">endMemberTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1b4540041426548396bf81bff58483ad">OutputList::endMemberTemplateParams</a>.</p>

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



<p>Definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a39d62301cd87ef0c6e51bc7c55c9982b">endPageDoc</a>.</p>


<p>Referenced by <a href="#a39d62301cd87ef0c6e51bc7c55c9982b">endPageDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a58cd93dd010aa638e8b54259bdea9b74">OutputList::endPageDoc</a>.</p>

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



<p>Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ac0916dd878a34ca4c4b65492dc17b3c8">endPageRef</a>.</p>


<p>Referenced by <a href="#ac0916dd878a34ca4c4b65492dc17b3c8">endPageRef</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a00f61efb96bdef4833ba228f08c7f18e">OutputList::endPageRef</a>.</p>

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



<p>Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8f725c5406981a4aaa9aba38078ffc71">endParagraph</a>.</p>


<p>Referenced by <a href="#a8f725c5406981a4aaa9aba38078ffc71">endParagraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6523eb013a6f759d505650de41855085">OutputList::endParagraph</a>.</p>

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



<p>Definition at line 296 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a35d39fdc7cdaec182baa7fb3d909fab7">endParameterDefVal</a>.</p>


<p>Referenced by <a href="#a35d39fdc7cdaec182baa7fb3d909fab7">endParameterDefVal</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8be0158b8b2a857157cfe92b802e0609">OutputList::endParameterDefVal</a>.</p>

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



<p>Definition at line 294 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6cbac7733e17d57b2caccb30e3bf98e2">endParameterExtra</a>.</p>


<p>Referenced by <a href="#a6cbac7733e17d57b2caccb30e3bf98e2">endParameterExtra</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0da2c95a60c78bda71d5f35d5adeb02f">OutputList::endParameterExtra</a>.</p>

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



<p>Definition at line 298 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a514360a2c3c4b46107f244004e6befa5">endParameterList</a>.</p>


<p>Referenced by <a href="#a514360a2c3c4b46107f244004e6befa5">endParameterList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ab7c1be88384dc59f5ca11f8da2113a4d">OutputList::endParameterList</a>.</p>

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



<p>Definition at line 292 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a9958dc52e088a6c840c324f992a61782">endParameterName</a>.</p>


<p>Referenced by <a href="#a9958dc52e088a6c840c324f992a61782">endParameterName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a93053950ab9941273ab071bbb0646c35">OutputList::endParameterName</a>.</p>

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



<p>Definition at line 290 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a436aab094abf10c862af8e86712ac7df">endParameterType</a>.</p>


<p>Referenced by <a href="#a436aab094abf10c862af8e86712ac7df">endParameterType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acb73d83bd4b05b5041de62a7336747e5">OutputList::endParameterType</a>.</p>

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



<p>Definition at line 325 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a43b7360d19bc7009a3d6ff1ec1398664">endPlainFile</a>.</p>


<p>Referenced by <a href="#a43b7360d19bc7009a3d6ff1ec1398664">endPlainFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aef22d797dc5dae4fcce9984246587932">OutputList::endPlainFile</a>.</p>

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



<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab8f1a4a235cb4e41997f238b2c969d18">endProjectNumber</a>.</p>


<p>Referenced by <a href="#ab8f1a4a235cb4e41997f238b2c969d18">endProjectNumber</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad6faf5debd750bf3fb143ffc571a0d22">OutputList::endProjectNumber</a>.</p>

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



<p>Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a779e6a499dbba756b5589de4cab1d8a8">endQuickIndices</a>.</p>


<p>Referenced by <a href="#a779e6a499dbba756b5589de4cab1d8a8">endQuickIndices</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ab1da800b31634af3c518bfa8c0b8323b">OutputList::endQuickIndices</a>.</p>

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



<p>Definition at line 241 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aaf3c9cb988a0e2d49068465772433409">endSection</a>.</p>


<p>Referenced by <a href="#aaf3c9cb988a0e2d49068465772433409">endSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a135844f68859bdb67f2614664ae26f8d">OutputList::endSection</a>.</p>

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



<p>Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a74f9d5740031dd466964edd9c1d8e366">endSmall</a>.</p>


<p>Referenced by <a href="#a74f9d5740031dd466964edd9c1d8e366">endSmall</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8142de5d17dd16fce39b80c0dfc3dfe2">OutputList::endSmall</a>.</p>

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



<p>Definition at line 283 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="#aad5585b6af901be0830ae54b693668ce">endTextBlock</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>


<p>Referenced by <a href="#aad5585b6af901be0830ae54b693668ce">endTextBlock</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a06ee92661f22a8e270e6b1cc538773b5">OutputList::endTextBlock</a>.</p>

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



<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a578bfc0ee8985ffdf1e141445e3479e4">endTextLink</a>.</p>


<p>Referenced by <a href="#a578bfc0ee8985ffdf1e141445e3479e4">endTextLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a74e89e9bcca41e9203ca080fc127a004">OutputList::endTextLink</a>.</p>

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



<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">endTitleHead</a>.</p>


<p>Referenced by <a href="#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">endTitleHead</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0d24b8d36374b773ce723e4b3ae650e7">OutputList::endTitleHead</a>.</p>

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



<p>Definition at line 322 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a20804e800904af439381fbf9f11be3d3">endTocEntry</a>.</p>


<p>Referenced by <a href="#a20804e800904af439381fbf9f11be3d3">endTocEntry</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ab34d0753ec12c656b36dd16cf16b9987">OutputList::endTocEntry</a>.</p>

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



<p>Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3a10feddac419bcac5c2456710213600">endTypewriter</a>.</p>


<p>Referenced by <a href="#a3a10feddac419bcac5c2456710213600">endTypewriter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad83302c45e73f387c9dc13789df012f7">OutputList::endTypewriter</a>.</p>

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



<p>Definition at line 299 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="#a41b77727f57a04d415d7acfa77dfcf13">exceptionEntry</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.</p>


<p>Referenced by <a href="#a41b77727f57a04d415d7acfa77dfcf13">exceptionEntry</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">OutputList::exceptionEntry</a>.</p>

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



<p>Definition at line 203 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#aa837f5a6ce555e11398b3df3ecb3e88f">insertMemberAlign</a>.</p>


<p>Referenced by <a href="#aa837f5a6ce555e11398b3df3ecb3e88f">insertMemberAlign</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>.</p>

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



<p>Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a2082c126cedbfc6c0491fc8b96ccba7a">insertMemberAlignLeft</a>.</p>


<p>Referenced by <a href="#a2082c126cedbfc6c0491fc8b96ccba7a">insertMemberAlignLeft</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1d117e436431c6c8976e8e1e3167b20c">OutputList::insertMemberAlignLeft</a>.</p>

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



<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a707578caad094f7af3f04f1b4a54f052">lastIndexPage</a>.</p>


<p>Referenced by <a href="#a707578caad094f7af3f04f1b4a54f052">lastIndexPage</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a9edb8dc61594b5f30bb7f4b004b04f41">OutputList::lastIndexPage</a>.</p>

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



<p>Definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a5a3b3d5489a1fcb2d885e3544da2a924">lineBreak</a>.</p>


<p>Referenced by <a href="#a5a3b3d5489a1fcb2d885e3544da2a924">lineBreak</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adfbaf25ba726ceec65db99fec11ec2ef">OutputList::lineBreak</a>.</p>

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



<p>Definition at line 189 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a373de27a917a5e5b6421fa26f87c4449">startAnonTypeScope</a>.</p>


<p>Referenced by <a href="#a373de27a917a5e5b6421fa26f87c4449">startAnonTypeScope</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a74d52604537a67d666ce88405c23dc49">OutputList::startAnonTypeScope</a>.</p>

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



<p>Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3b32f7ed14989d25fd76888ab942e65b">startBold</a>.</p>


<p>Referenced by <a href="#a3b32f7ed14989d25fd76888ab942e65b">startBold</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a796018ee85949771252f36fea9a288d0">OutputList::startBold</a>.</p>

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



<p>Definition at line 275 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#adb8e5518bbf7f0829f3a2572a1720079">startCallGraph</a>.</p>


<p>Referenced by <a href="#adb8e5518bbf7f0829f3a2572a1720079">startCallGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a20837aeac45ccb44d354e42e75eb51c9">OutputList::startCallGraph</a>.</p>

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



<p>Definition at line 222 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8a4437f40ef79e76ed6aca6e2b6eb4e5">startCenter</a>.</p>


<p>Referenced by <a href="#a8a4437f40ef79e76ed6aca6e2b6eb4e5">startCenter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acc709b251fc97e9e5c7d3d205ffb0a5e">OutputList::startCenter</a>.</p>

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



<p>Definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a9b1cedf05d8efc75853f8e7c7582f322">startClassDiagram</a>.</p>


<p>Referenced by <a href="#a9b1cedf05d8efc75853f8e7c7582f322">startClassDiagram</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a10f734424e06f796ca4c962e0017d8b6">OutputList::startClassDiagram</a>.</p>

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



<p>Definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a94f617fe193172f0f97b27c499de9cfa">startCompoundTemplateParams</a>.</p>


<p>Referenced by <a href="#a94f617fe193172f0f97b27c499de9cfa">startCompoundTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac9278fb907b0c4dda297a1acb6738c2d">OutputList::startCompoundTemplateParams</a>.</p>

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



<p>Definition at line 305 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7dc709f71d6789db7c3b4443ed448b1a">startConstraintDocs</a>.</p>


<p>Referenced by <a href="#a7dc709f71d6789db7c3b4443ed448b1a">startConstraintDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e2a94bd45cf237f40a9a0e7eb1386d2">OutputList::startConstraintDocs</a>.</p>

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



<p>Definition at line 300 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a04817619e41efde49c970d1975151edf">startConstraintList</a>.</p>


<p>Referenced by <a href="#a04817619e41efde49c970d1975151edf">startConstraintList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa97f8716fbd06a49dd172b5c65bb2c56">OutputList::startConstraintList</a>.</p>

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



<p>Definition at line 301 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae9d43c719e2fccb17737dfebaec0a07c">startConstraintParam</a>.</p>


<p>Referenced by <a href="#ae9d43c719e2fccb17737dfebaec0a07c">startConstraintParam</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a552198c8c605b7d5bc9cb49885e5cf87">OutputList::startConstraintParam</a>.</p>

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



<p>Definition at line 303 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a24edd015165887d5e18c316e68c655c4">startConstraintType</a>.</p>


<p>Referenced by <a href="#a24edd015165887d5e18c316e68c655c4">startConstraintType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a711c480e26d4492f5cd83fc4c9947105">OutputList::startConstraintType</a>.</p>

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



<p>Definition at line 256 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae686f96a24cb17e204b8d497701d5d62">startContents</a>.</p>


<p>Referenced by <a href="#ae686f96a24cb17e204b8d497701d5d62">startContents</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac891ad4a7081e1ab9d42a637596111db">OutputList::startContents</a>.</p>

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



<p>Definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a62c4d70eded6831c56b01a78ed8de5a9">startDescForItem</a>.</p>


<p>Referenced by <a href="#a62c4d70eded6831c56b01a78ed8de5a9">startDescForItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8ac4a6e52094643a093fcdeedf1ae0bc">OutputList::startDescForItem</a>.</p>

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



<p>Definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a099593df5a76ae4bb6826aa8be58ca71">startDescTable</a>.</p>


<p>Referenced by <a href="#a099593df5a76ae4bb6826aa8be58ca71">startDescTable</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7d6b8dd40e3bded41a971c0144fed3db">OutputList::startDescTable</a>.</p>

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



<p>Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a14febd9e78a190e5e6fc1b0000a86845">startDescTableData</a>.</p>


<p>Referenced by <a href="#a14febd9e78a190e5e6fc1b0000a86845">startDescTableData</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8823d3ed58554ae3eeb9169ff920ba00">OutputList::startDescTableData</a>.</p>

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



<p>Definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab38bee163993a50c58b8bd4c79216d1a">startDescTableInit</a>.</p>


<p>Referenced by <a href="#ab38bee163993a50c58b8bd4c79216d1a">startDescTableInit</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a20199e8a222bcea2abb9a43a52926ea9">OutputList::startDescTableInit</a>.</p>

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



<p>Definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6ee5d670908097c2bc08bedf6e1c32c6">startDescTableRow</a>.</p>


<p>Referenced by <a href="#a6ee5d670908097c2bc08bedf6e1c32c6">startDescTableRow</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af4b472918891fdf268e7f13ccdc4e88a">OutputList::startDescTableRow</a>.</p>

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



<p>Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab1af7866c36c8c7fe2d2375558935b85">startDescTableTitle</a>.</p>


<p>Referenced by <a href="#ab1af7866c36c8c7fe2d2375558935b85">startDescTableTitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6b984edbfa21eecfe20b2a7a3ef0fc97">OutputList::startDescTableTitle</a>.</p>

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



<p>Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aba0e8dca170cca694dc0166fb95aa13e">startDirDepGraph</a>.</p>


<p>Referenced by <a href="#aba0e8dca170cca694dc0166fb95aa13e">startDirDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6ecc6dca9d8d4bc9720971ffc1c5b788">OutputList::startDirDepGraph</a>.</p>

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



<p>Definition at line 271 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad2819be1125a573d7abdbf5a522b9310">startDotGraph</a>.</p>


<p>Referenced by <a href="#ad2819be1125a573d7abdbf5a522b9310">startDotGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac6fc93128d92c79a08995457b10f6e1f">OutputList::startDotGraph</a>.</p>

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



<p>Definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aecae8460986ee6b91397ae321ce627a1">startDoxyAnchor</a>.</p>


<p>Referenced by <a href="#aecae8460986ee6b91397ae321ce627a1">startDoxyAnchor</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aae4920963ec75457cd7e3662aedded3a">OutputList::startDoxyAnchor</a>.</p>

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



<p>Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#adcc1b898c2dcc3f6062da795a440da48">startEmphasis</a>.</p>


<p>Referenced by <a href="#adcc1b898c2dcc3f6062da795a440da48">startEmphasis</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aba5576798309803175cefaedf33b2a28">OutputList::startEmphasis</a>.</p>

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



<p>Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8c05d1ccc1a97e87db2eb6ac111ba720">startExamples</a>.</p>


<p>Referenced by <a href="#a8c05d1ccc1a97e87db2eb6ac111ba720">startExamples</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f81a490c1354748afe7e3b834f1907b">OutputList::startExamples</a>.</p>

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



<p>Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a751894ca7271d62e186144bf6ea750b4">startFile</a>.</p>


<p>Referenced by <a href="#a751894ca7271d62e186144bf6ea750b4">startFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a518814a98f44c11f73dbea3b7b3ed795">OutputList::startFile</a>.</p>

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



<p>Definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a695dc048f7688078bff6ba6eae779dea">startGroupCollaboration</a>.</p>


<p>Referenced by <a href="#a695dc048f7688078bff6ba6eae779dea">startGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a41473666261dc8b245cb4daee6bc53a0">OutputList::startGroupCollaboration</a>.</p>

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



<p>Definition at line 171 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3c25f35ecd9dbcbcd1804513473f8683">startGroupHeader</a>.</p>


<p>Referenced by <a href="#a3c25f35ecd9dbcbcd1804513473f8683">startGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a2cf4898386fe73bfd645d4765e713a2b">OutputList::startGroupHeader</a>.</p>

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



<p>Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#af915369f4ac0e6faeb3d558de0a5ccea">startHeaderSection</a>.</p>


<p>Referenced by <a href="#af915369f4ac0e6faeb3d558de0a5ccea">startHeaderSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a545dcbbbcdf8aac24e32df2abe0ea22d">OutputList::startHeaderSection</a>.</p>

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



<p>Definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">startInclDepGraph</a>.</p>


<p>Referenced by <a href="#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">startInclDepGraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1d3ded0121b9163ac3b11c0bb8e380c4">OutputList::startInclDepGraph</a>.</p>

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



<p>Definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3942248646635d62ce76ff4c58501013">startIndent</a>.</p>


<p>Referenced by <a href="#a3942248646635d62ce76ff4c58501013">startIndent</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5805e09c663ccde368463f3c6a767a59">OutputList::startIndent</a>.</p>

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



<p>Definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab4fea7fc7613b609e6b63ebe49e2637f">startIndexItem</a>.</p>


<p>Referenced by <a href="#ab4fea7fc7613b609e6b63ebe49e2637f">startIndexItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0d0615da54716436c72e53f16b80adfc">OutputList::startIndexItem</a>.</p>

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



<p>Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a4a2892a4a593cce615ffce7172eabc42">startIndexKey</a>.</p>


<p>Referenced by <a href="#a4a2892a4a593cce615ffce7172eabc42">startIndexKey</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a193f96c7af956fe9443ffc099fc5cc13">OutputList::startIndexKey</a>.</p>

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



<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6b2597524bf7275b5af10536cdf49f31">startIndexList</a>.</p>


<p>Referenced by <a href="#a6b2597524bf7275b5af10536cdf49f31">startIndexList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ace955285a164c7f27f0923986a36cff5">OutputList::startIndexList</a>.</p>

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



<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aff1ac58d5e1754872e65e7a3db6f2241">startIndexListItem</a>.</p>


<p>Referenced by <a href="#aff1ac58d5e1754872e65e7a3db6f2241">startIndexListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adf2df33c38b53c9b95fe003aed5bc222">OutputList::startIndexListItem</a>.</p>

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



<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae869ad0ddcd664eebbedee81ad94e925">startIndexSection</a>.</p>


<p>Referenced by <a href="#ae869ad0ddcd664eebbedee81ad94e925">startIndexSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae92e8fd973796141115ea4ef0b15cf5b">OutputList::startIndexSection</a>.</p>

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



<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a7a7025f965ca3fcf915dbf010a4a416a">startIndexValue</a>.</p>


<p>Referenced by <a href="#a7a7025f965ca3fcf915dbf010a4a416a">startIndexValue</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a9ffa966ddc43f8d39e5a1e74a814ebef">OutputList::startIndexValue</a>.</p>

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



<p>Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a0ccc69fb60f4b835a7eed748a9fea1a6">startInlineHeader</a>.</p>


<p>Referenced by <a href="#a0ccc69fb60f4b835a7eed748a9fea1a6">startInlineHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8e3c4abdce2bc3800e782a435db5437f">OutputList::startInlineHeader</a>.</p>

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



<p>Definition at line 314 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab46c5f34ec08151ad23e699ec093e858">startInlineMemberDoc</a>.</p>


<p>Referenced by <a href="#ab46c5f34ec08151ad23e699ec093e858">startInlineMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4627e1a2c83cf21e9b63b6c9b99e5381">OutputList::startInlineMemberDoc</a>.</p>

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



<p>Definition at line 312 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a0776046486af09020f31ee8f87f8c1d0">startInlineMemberName</a>.</p>


<p>Referenced by <a href="#a0776046486af09020f31ee8f87f8c1d0">startInlineMemberName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abd00519713f4249371669240e568d29d">OutputList::startInlineMemberName</a>.</p>

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



<p>Definition at line 310 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6735e2e800ba3e27cd0fb768e78fd1b2">startInlineMemberType</a>.</p>


<p>Referenced by <a href="#a6735e2e800ba3e27cd0fb768e78fd1b2">startInlineMemberType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a41ac30b73768699a957c5714e4c347b4">OutputList::startInlineMemberType</a>.</p>

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



<p>Definition at line 158 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">startItemList</a>.</p>


<p>Referenced by <a href="#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">startItemList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a1677b65eb8f01a10b1d767758338a212">OutputList::startItemList</a>.</p>

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



<p>Definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#af2f528b46750b254f7a799fcd6ed28d7">startItemListItem</a>.</p>


<p>Referenced by <a href="#af2f528b46750b254f7a799fcd6ed28d7">startItemListItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a77e30e9a84b48907b886e8231dbbc20b">OutputList::startItemListItem</a>.</p>

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



<p>Definition at line 316 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad79d3695d6eef65e69af540fc5e2187f">startLabels</a>.</p>


<p>Referenced by <a href="#ad79d3695d6eef65e69af540fc5e2187f">startLabels</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac8244f86d2d0ccbf7e9b0641f1d3a8f6">OutputList::startLabels</a>.</p>

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



<p>Definition at line 319 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6b77f3e740d66edde2819141517d8788">startLocalToc</a>.</p>


<p>Referenced by <a href="#a6b77f3e740d66edde2819141517d8788">startLocalToc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af987cfff8d8cad1bd500f87ad547d0cc">OutputList::startLocalToc</a>.</p>

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



<p>Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ac38369ad05d7e5584a64b32576dc95e6">startMemberDeclaration</a>.</p>


<p>Referenced by <a href="#ac38369ad05d7e5584a64b32576dc95e6">startMemberDeclaration</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a09a4062cfac0ed8f9d3dec4cd42f1aa7">OutputList::startMemberDeclaration</a>.</p>

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



<p>Definition at line 229 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aef4e50ba3e911eec35461895c2864b7a">startMemberDescription</a>.</p>


<p>Referenced by <a href="#aef4e50ba3e911eec35461895c2864b7a">startMemberDescription</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4988f821b416a64d12c7fbc0a4273bba">OutputList::startMemberDescription</a>.</p>

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



<p>Definition at line 210 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a116232c9975fe8505bf789dd51eadb56">startMemberDoc</a>.</p>


<p>Referenced by <a href="#a116232c9975fe8505bf789dd51eadb56">startMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0a9ce398bc0c3a3ef316e0c97cc33ce5">OutputList::startMemberDoc</a>.</p>

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



<p>Definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3cc64b48e08f8c37ae68c052666e2581">startMemberDocList</a>.</p>


<p>Referenced by <a href="#a3cc64b48e08f8c37ae68c052666e2581">startMemberDocList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ada069f601f0651010bc78b3ccb0f6f11">OutputList::startMemberDocList</a>.</p>

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



<p>Definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a> and <a href="#a45d8c190fc894d6743423e628c19294b">startMemberDocName</a>.</p>


<p>Referenced by <a href="#a45d8c190fc894d6743423e628c19294b">startMemberDocName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b9d56f0ab609c25ba0b449e4d977f80">OutputList::startMemberDocName</a>.</p>

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



<p>Definition at line 285 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a5995a8429533bd21364530edeb763711">startMemberDocPrefixItem</a>.</p>


<p>Referenced by <a href="#a5995a8429533bd21364530edeb763711">startMemberDocPrefixItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acc616cc002e406c1c5816f020fb7d60c">OutputList::startMemberDocPrefixItem</a>.</p>

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



<p>Definition at line 308 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a0593059cb1552745f7a97a3040dd5e7c">startMemberDocSimple</a>.</p>


<p>Referenced by <a href="#a0593059cb1552745f7a97a3040dd5e7c">startMemberDocSimple</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac9ba52ac9477c974842dacd16aeb4420">OutputList::startMemberDocSimple</a>.</p>

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



<p>Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a36689312cd35c431b1ce66ac3ba35594">startMemberGroup</a>.</p>


<p>Referenced by <a href="#a36689312cd35c431b1ce66ac3ba35594">startMemberGroup</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6e6c176d640939fce848f044037209c8">OutputList::startMemberGroup</a>.</p>

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



<p>Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ac57ae72f8115bbe8ed6b303cffb984f7">startMemberGroupDocs</a>.</p>


<p>Referenced by <a href="#ac57ae72f8115bbe8ed6b303cffb984f7">startMemberGroupDocs</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac78054f50bad730b62b3456699d9a350">OutputList::startMemberGroupDocs</a>.</p>

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



<p>Definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3593d54f692a41d566ae01109aeef05e">startMemberGroupHeader</a>.</p>


<p>Referenced by <a href="#a3593d54f692a41d566ae01109aeef05e">startMemberGroupHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae7ca8c46242c727aa527ab392db22707">OutputList::startMemberGroupHeader</a>.</p>

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



<p>Definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a38cce7e6f2c721d28cd581fffc261667">startMemberHeader</a>.</p>


<p>Referenced by <a href="#a38cce7e6f2c721d28cd581fffc261667">startMemberHeader</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af6404ab3a071c87189d8b8dd2f0d2ef1">OutputList::startMemberHeader</a>.</p>

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



<p>Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a> and <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a>.</p>


<p>Referenced by <a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad7e741530682b5707eb04b3f4009523d">OutputList::startMemberItem</a>.</p>

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



<p>Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#abc21f85b1ee972d5143aa0e10c12a74c">startMemberList</a>.</p>


<p>Referenced by <a href="#abc21f85b1ee972d5143aa0e10c12a74c">startMemberList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7431bc4b23642f75af48f25a415d4ec8">OutputList::startMemberList</a>.</p>

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



<p>Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a479613dbc7e8b8967342736b76a00b59">startMemberSections</a>.</p>


<p>Referenced by <a href="#a479613dbc7e8b8967342736b76a00b59">startMemberSections</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f8bf0192c18e0ea785c412b23f6fd3f">OutputList::startMemberSections</a>.</p>

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



<p>Definition at line 181 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a47701af94cd5ea03b74733c9d7926251">startMemberSubtitle</a>.</p>


<p>Referenced by <a href="#a47701af94cd5ea03b74733c9d7926251">startMemberSubtitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#add8c37a5cb21fb366c941cea862b2285">OutputList::startMemberSubtitle</a>.</p>

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



<p>Definition at line 193 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a84b6535ee5e38767846bea0e6ba96c8a">startMemberTemplateParams</a>.</p>


<p>Referenced by <a href="#a84b6535ee5e38767846bea0e6ba96c8a">startMemberTemplateParams</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af5a6611d3aa4b11eafd0a785d1757483">OutputList::startMemberTemplateParams</a>.</p>

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



<p>Definition at line 258 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a2b784e509b334fac1a75627148761be8">startPageDoc</a>.</p>


<p>Referenced by <a href="#a2b784e509b334fac1a75627148761be8">startPageDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aba6135c0dcee35b209b1a4996a5763c1">OutputList::startPageDoc</a>.</p>

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



<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad700dc5ae546c3e60eaf3a0fc821f626">startPageRef</a>.</p>


<p>Referenced by <a href="#ad700dc5ae546c3e60eaf3a0fc821f626">startPageRef</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a6f14fd99b68f6df4f9510dbc627f5a43">OutputList::startPageRef</a>.</p>

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



<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#af0f23248db3a810e3fa1a22efd6dc810">startParagraph</a>.</p>


<p>Referenced by <a href="#af0f23248db3a810e3fa1a22efd6dc810">startParagraph</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a583c7e58d6b910b7bdf67120ee4e6875">OutputList::startParagraph</a>.</p>

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



<p>Definition at line 295 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ad6785e89293e0a1a656cea7f3a11ce0f">startParameterDefVal</a>.</p>


<p>Referenced by <a href="#ad6785e89293e0a1a656cea7f3a11ce0f">startParameterDefVal</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7350c12854789b59595b4ad1d40a651c">OutputList::startParameterDefVal</a>.</p>

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



<p>Definition at line 293 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aca6ab24e04280715dbb109c2fff18356">startParameterExtra</a>.</p>


<p>Referenced by <a href="#aca6ab24e04280715dbb109c2fff18356">startParameterExtra</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a251c67c01e2bcc17814da33c186bd1f9">OutputList::startParameterExtra</a>.</p>

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



<p>Definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">startParameterList</a>.</p>


<p>Referenced by <a href="#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">startParameterList</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a297f991eafa9e368a982c936891bb79e">OutputList::startParameterList</a>.</p>

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



<p>Definition at line 291 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a230c27f71a06e4127b602b621f548985">startParameterName</a>.</p>


<p>Referenced by <a href="#a230c27f71a06e4127b602b621f548985">startParameterName</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acde2fcc0d42034b7f342d12119957a81">OutputList::startParameterName</a>.</p>

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



<p>Definition at line 289 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a1976bdf79e45f6747ef356cae0a95411">startParameterType</a>.</p>


<p>Referenced by <a href="#a1976bdf79e45f6747ef356cae0a95411">startParameterType</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a8db9e1278341d4eeb45328fd9967a6b5">OutputList::startParameterType</a>.</p>

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



<p>Definition at line 324 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8a3d61c68c3ec0817933b533ced5806a">startPlainFile</a>.</p>


<p>Referenced by <a href="#a8a3d61c68c3ec0817933b533ced5806a">startPlainFile</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acbe23584d1d25c0df38c01be7b431a90">OutputList::startPlainFile</a>.</p>

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



<p>Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a9aa73996eef9d354eda1aa7bef80a92d">startProjectNumber</a>.</p>


<p>Referenced by <a href="#a9aa73996eef9d354eda1aa7bef80a92d">startProjectNumber</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e35c28c310e74b57645aff8119c1546">OutputList::startProjectNumber</a>.</p>

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



<p>Definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a49399b68dc9d396e2decd25c69fe9c71">startQuickIndices</a>.</p>


<p>Referenced by <a href="#a49399b68dc9d396e2decd25c69fe9c71">startQuickIndices</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a74849c1452e8884292ed85bf7c22f2bc">OutputList::startQuickIndices</a>.</p>

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



<p>Definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#adcf099495987baa700a91ebd8284efd2">startSection</a>.</p>


<p>Referenced by <a href="#adcf099495987baa700a91ebd8284efd2">startSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae5bcc70f52a38c5c65e7271d18d3e1ed">OutputList::startSection</a>.</p>

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



<p>Definition at line 224 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aa535ab26ba3724479354f6944e780f39">startSmall</a>.</p>


<p>Referenced by <a href="#aa535ab26ba3724479354f6944e780f39">startSmall</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#acf8ce762c6c7838d86ad132f20a2306a">OutputList::startSmall</a>.</p>

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



<p>Definition at line 282 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#af2409cde2f7961ca5cf4b967335c5f50">startTextBlock</a>.</p>


<p>Referenced by <a href="#af2409cde2f7961ca5cf4b967335c5f50">startTextBlock</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a5e4b1b0039100083a979ff8d90adce58">OutputList::startTextBlock</a>.</p>

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



<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a075de9b4d65864892a5a4bea2ae751dd">startTextLink</a>.</p>


<p>Referenced by <a href="#a075de9b4d65864892a5a4bea2ae751dd">startTextLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#af084d8a76621939675ae543f47032fa4">OutputList::startTextLink</a>.</p>

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



<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a39e6e6ec7f39f8847632b75dfa5490a9">startTitleHead</a>.</p>


<p>Referenced by <a href="#a39e6e6ec7f39f8847632b75dfa5490a9">startTitleHead</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a218206d83bfa847f783bf2d2346caac6">OutputList::startTitleHead</a>.</p>

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



<p>Definition at line 321 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#af1602bf413b97f22052cf036643f3f1c">startTocEntry</a>.</p>


<p>Referenced by <a href="#af1602bf413b97f22052cf036643f3f1c">startTocEntry</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a132bb85c7da750fadfa35352227b8766">OutputList::startTocEntry</a>.</p>

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



<p>Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a8d12471e1fa0455d4957b72f25c64302">startTypewriter</a>.</p>


<p>Referenced by <a href="#a8d12471e1fa0455d4957b72f25c64302">startTypewriter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a848e77a8fd7af578497f7ee1ec163b98">OutputList::startTypewriter</a>.</p>

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



<p>Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a>.</p>


<p>Referenced by <a href="#aa9af48be8371aee3f0d0b65d4fd22015">endMemberItem</a>, <a href="#a859d57760dab81918c1f54667a4b7bb6">startMemberItem</a>, <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a> and <a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a>.</p>

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



<p>Definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#afda0d70c12b2ac6fc6e66a4543b19a44">writeAnchor</a>.</p>


<p>Referenced by <a href="#afda0d70c12b2ac6fc6e66a4543b19a44">writeAnchor</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#aa14aecc6d7bfdeb2cfbd241fa55059a7">OutputList::writeAnchor</a>.</p>

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



<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab3b1f57669e3d916ca995a880935a6df">writeChar</a>.</p>


<p>Referenced by <a href="#ab3b1f57669e3d916ca995a880935a6df">writeChar</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a188c7a8f0a0dc35ec5ea0f8b4a491d33">OutputList::writeChar</a>.</p>

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



<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#abbad8b45e48b0d0dd8139c9c5ce5e74d">writeDoc</a>.</p>


<p>Referenced by <a href="#abbad8b45e48b0d0dd8139c9c5ce5e74d">writeDoc</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a475da5dda736fa915aca9fc855b1d2e7">OutputList::writeDoc</a>.</p>

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



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ae06d07286c1a5e0e8dd4dcb413eea3ee">writeFooter</a>.</p>


<p>Referenced by <a href="#ae06d07286c1a5e0e8dd4dcb413eea3ee">writeFooter</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#accf02a25e4bb1593eabc248373f08dd0">OutputList::writeFooter</a>.</p>

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



<p>Definition at line 281 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3eac8c3de9fb5faac26a15e461441ac5">writeGraphicalHierarchy</a>.</p>


<p>Referenced by <a href="#a3eac8c3de9fb5faac26a15e461441ac5">writeGraphicalHierarchy</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4d7e7f24d5fd2e4fc7cb62f992a7f10f">OutputList::writeGraphicalHierarchy</a>.</p>

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



<p>Definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aec93094d1142185397b89f683e3f805c">writeInheritedSectionTitle</a>.</p>


<p>Referenced by <a href="#aec93094d1142185397b89f683e3f805c">writeInheritedSectionTitle</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae60261a39e2cc0d6fa5d78da1ae5caeb">OutputList::writeInheritedSectionTitle</a>.</p>

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



<p>Definition at line 317 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a272adadd57275dc0ffe350691531eca4">writeLabel</a>.</p>


<p>Referenced by <a href="#a272adadd57275dc0ffe350691531eca4">writeLabel</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ac700283b8e771ab0dd515d5f384632ff">OutputList::writeLabel</a>.</p>

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



<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6ffbea116a5c5bf0c54b43ba3f6a4132">writeLatexSpacing</a>.</p>


<p>Referenced by <a href="#a6ffbea116a5c5bf0c54b43ba3f6a4132">writeLatexSpacing</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a2a7a1bca5871c912848bddde9b7dd3fc">OutputList::writeLatexSpacing</a>.</p>

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



<p>Definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ac9673da2d9860875be433aa9885da80d">writeLogo</a>.</p>


<p>Referenced by <a href="#ac9673da2d9860875be433aa9885da80d">writeLogo</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a739eb036549fb3787e5daa3d35bc1aff">OutputList::writeLogo</a>.</p>

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



<p>Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ab93da7f6e4680d6426a444871a0dd272">writeNavigationPath</a>.</p>


<p>Referenced by <a href="#ab93da7f6e4680d6426a444871a0dd272">writeNavigationPath</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ace864e843eca954efb12af825f56bdca">OutputList::writeNavigationPath</a>.</p>

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



<p>Definition at line 260 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#ac7523bc031627d3ffec3a61be2183983">writeNonBreakableSpace</a>.</p>


<p>Referenced by <a href="#ac7523bc031627d3ffec3a61be2183983">writeNonBreakableSpace</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ae6cc078977edd1e2a5ae2cf6ed64ed35">OutputList::writeNonBreakableSpace</a>.</p>

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



<p>Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a53380f84190045f14ef3c6ae2f5dd275">writeObjectLink</a>.</p>


<p>Referenced by <a href="#a53380f84190045f14ef3c6ae2f5dd275">writeObjectLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a411807a84d5f9e2fb716a0f66bde56b6">OutputList::writeObjectLink</a>.</p>

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



<p>Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a85839f2257cc6632c3307df7f1c48cd4">writePageLink</a>.</p>


<p>Referenced by <a href="#a85839f2257cc6632c3307df7f1c48cd4">writePageLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#ad1ce4ae7803aba4c58764c906e943aab">OutputList::writePageLink</a>.</p>

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



<p>Definition at line 255 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3253ebaf15e52566edf6b5804ed0e930">writePageOutline</a>.</p>


<p>Referenced by <a href="#a3253ebaf15e52566edf6b5804ed0e930">writePageOutline</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abbe1d0534295cfb5717a33e1c1eb5fb4">OutputList::writePageOutline</a>.</p>

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



<p>Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#abeaa883814a4981f89c3383a1dac404b">writeQuickLinks</a>.</p>


<p>Referenced by <a href="#abeaa883814a4981f89c3383a1dac404b">writeQuickLinks</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#afc0312b9a48cae61656b930d878c718e">OutputList::writeQuickLinks</a>.</p>

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



<p>Definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a3e67a4680207146c0717f53e778ad83e">writeRuler</a>.</p>


<p>Referenced by <a href="#a3e67a4680207146c0717f53e778ad83e">writeRuler</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a2203589f0bc276cb3ba01f529b9536a9">OutputList::writeRuler</a>.</p>

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



<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a06d7c1c55247348a93966711afbb983f">writeSearchInfo</a>.</p>


<p>Referenced by <a href="#a06d7c1c55247348a93966711afbb983f">writeSearchInfo</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a0b776a7ac371d841b15862b074ddd97f">OutputList::writeSearchInfo</a>.</p>

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



<p>Definition at line 250 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#aaa7b661bcbc35895bd704e48999c3849">writeSplitBar</a>.</p>


<p>Referenced by <a href="#aaa7b661bcbc35895bd704e48999c3849">writeSplitBar</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#abeb86db48415009b3c09b723216fd8f6">OutputList::writeSplitBar</a>.</p>

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



<p>Definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>References <a href="#a221f0f1fd10d58c14f9caf7faa36dde1">type</a> and <a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a>.</p>


<p>Referenced by <a href="#afd391f13f33ee9163d495756f978447b">writeStartAnnoItem</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a4e97c1da93e9caf6a6675f3972ba7750">OutputList::writeStartAnnoItem</a>.</p>

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



<p>Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a9425335496ccadd1a9c8235cf31280e1">writeString</a>.</p>


<p>Referenced by <a href="#a9425335496ccadd1a9c8235cf31280e1">writeString</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">OutputList::writeString</a>.</p>

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



<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a2711a39698d7169932b7e24b9223ef06">writeStyleInfo</a>.</p>


<p>Referenced by <a href="#a2711a39698d7169932b7e24b9223ef06">writeStyleInfo</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a85fc0afe789c21758373df15bcb81cc9">OutputList::writeStyleInfo</a>.</p>

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



<p>Definition at line 254 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a08a84ef9ad423d5893da62114366f71b">writeSummaryLink</a>.</p>


<p>Referenced by <a href="#a08a84ef9ad423d5893da62114366f71b">writeSummaryLink</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a956032c76c8c263139658a08dfe1e07f">OutputList::writeSummaryLink</a>.</p>

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



<p>Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>


<p>Reference <a href="#a6dc8d2bf34bb5f53b758cbcac0074e3c">writeSynopsis</a>.</p>


<p>Referenced by <a href="#a6dc8d2bf34bb5f53b758cbcac0074e3c">writeSynopsis</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a7d9096a6b81f3183e6f3dc01e4e093f5">OutputList::writeSynopsis</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
