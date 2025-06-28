---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/latexdocvisitor
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LatexDocVisitor` Class Reference

<p>Concrete visitor implementation for LaTeX output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LatexDocVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">src/latexdocvisitor.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docvisitor">DocVisitor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper base class for functionality shared by all visitors. <a href="/web-doxygen/docs/api/classes/docvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/latexdocvisitor/activerowspan">ActiveRowSpan</a> &gt; <a href="#ab64e4305bbc1a654dc064dcc253ba005">RowSpanList</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a> (TextStream &amp;t, OutputCodeList &amp;ci, LatexCodeGenerator &amp;lcg, const QCString &amp;langExt, int hierarchyLevel=0)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">operator()</a> (const DocWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610ca0d0e464f23b2e2c2defbd3bd6ec">operator()</a> (const DocLinkedWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8521140810fce270f060a974a5c223e">operator()</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe122c272f139d98332b7630945da0f">operator()</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60686dad3b83395d42770683c5e1e6a9">operator()</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73d9be71f9eba3b4aab19bb46c69fc8">operator()</a> (const DocURL &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d64467d16ca8ee73bafaf59414cfdd4">operator()</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d33c93c8ef27f3d559511b25c4e56b5">operator()</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41aaa90a6a3c9ec728048cbdb927c7ae">operator()</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a> (const DocVerbatim &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81236a6d08e29da34ec95bcc10aea214">operator()</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1c6d00759ad30078d9f5a51cbfc009">operator()</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c844f5b9078d32e11a14b45b6f5c2d">operator()</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8faec71974f8983332aa0e11a946276">operator()</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718f5fc73955ee4e43228ede93284235">operator()</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d7f8b6f817f43e94f39851a2cea219b">operator()</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da6db1950d1eab0b3aad3535af34d9b">operator()</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad18160e3390b23baf7afb39d4954c928">operator()</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a> (const DocAutoList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce72f4abb11b66d697afdff04056222">operator()</a> (const DocAutoListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28500ffefba81a29ea7a76a60c1f7d1b">operator()</a> (const DocPara &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc888f33013fa62f2219d43891d96503">operator()</a> (const DocRoot &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a> (const DocSimpleSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57335dd50faa9dc7ee78f420dc35efe3">operator()</a> (const DocTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66d381b7f99cc5e565063f73854573f">operator()</a> (const DocSimpleList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c4ad96f7c5f045fbd0547b623f27bf">operator()</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">operator()</a> (const DocSection &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a> (const DocHtmlList &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a> (const DocHtmlListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfb163f58dc53862618450a55e41979">operator()</a> (const DocHtmlDescList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4336aa37be77360c412335358cd88b46">operator()</a> (const DocHtmlDescTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">operator()</a> (const DocHtmlDescData &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a> (const DocHtmlTable &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4bd281a17c0748c2b5573eb9f6be86">operator()</a> (const DocHtmlCaption &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add62a038409ef396c163d584412289cc">operator()</a> (const DocHtmlRow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a> (const DocHtmlCell &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1a3bedb011096b811a8b1207cc6694">operator()</a> (const DocInternal &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ce90cc4d05a3748cffe6519957ba59">operator()</a> (const DocHRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72863fffe73366c27a00f8fdbc6395d4">operator()</a> (const DocHtmlSummary &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e9d73e9adb9aac3732cee17a4c67db">operator()</a> (const DocHtmlDetails &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f950e3e8499edfa159d43d35ebda0b0">operator()</a> (const DocHtmlHeader &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b453c4eabdf03f5d1b690a307d9c4e">operator()</a> (const DocImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470e988cd5cdc26026424ffc59fec3d1">operator()</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc17206d985451fd07d62880158be9f">operator()</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e9d5dd271f19f872a947b95d88dbde">operator()</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1352434f601deaf1e191f3db0c3404">operator()</a> (const DocPlantUmlFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59f1ab15f6ef3d9641ae8588f2c717d5">operator()</a> (const DocLink &amp;lnk)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d07320992840cbb96459bd77cd9608">operator()</a> (const DocRef &amp;ref)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4e5f6aea094c66e6d152fd2962a128">operator()</a> (const DocSecRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9a4f0271ea62f929b5072a2ac109b0">operator()</a> (const DocSecRefList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca420728eca4e37947593db6a96eadd3">operator()</a> (const DocParamSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806029951b075fcd8c430498bd0f2375">operator()</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a> (const DocXRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac51ad3dcaa4b594e4a917c6062e216">operator()</a> (const DocInternalRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d834c86e9800452bd5d86ebe4a475a">operator()</a> (const DocText &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed16c660428cb0d22236e25f0cb5a1f">operator()</a> (const DocHtmlBlockQuote &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1303593cf872dbc274f7d82da5d8c508">operator()</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c8e02e7e2e9e5dbb2bb8a1fe27b37d">operator()</a> (const DocParBlock &amp;)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a> (const T &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a> (const QCString &amp;str, const bool retainNewLine=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool refToTable=false, bool refToSection=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool refToTable=false, bool refToSection=false, SectionType sectionType=SectionType::Anchor)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6e670e04f51e9bb0a163326fe8ffab">escapeMakeIndexChars</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa197e546b10f737e78020b97fdf23cb9">startDotFile</a> (const QCString &amp;fileName, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef2a244f24ea46106204e063fae5273">startMscFile</a> (const QCString &amp;fileName, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddf71d12334619ccd9ed44cec08e258">endMscFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada18505ac90bb92f4ce279d503dba853">writeMscFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe30a1c1a560e4a85206dc7623a17dc4">startDiaFile</a> (const QCString &amp;fileName, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8000cb1d166d1985a8e2b306d2b1c6">endDiaFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168f142f518c0734df4301ca492859d1">writeDiaFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92275d99afc832afc51d7e0deec3afe6">writePlantUMLFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa42bf16168d38b6ac210c3f17bef7510">startPlantUmlFile</a> (const QCString &amp;fileName, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">endPlantUmlFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a> (const DocNodeList &amp;children)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07ff64f82e760b771d8daec21ce731f">getSectionName</a> (int level) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5dab1f77dba06bcffb8898af56f3606">pushTableState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52701ab88ccd1fdf7432e3c689a2a16">popTableState</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a> (size_t col)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0d2ce4dcc1f80ad35725935d062ed6">setNumCols</a> (size_t num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9168d2796d2b37ba82cc27bb4918c6a1">inRowSpan</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1e7a18a592b5ce218b3552b8012d49d">setInRowSpan</a> (bool b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdf9b003ba87f85ee86bddb73602d302">inColSpan</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555cd968fcfe52155db2e225786e99c6">setInColSpan</a> (bool b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3781c16868efac71398e5436f519ee39">firstRow</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d60974e8552037cb12627d282df3392">setFirstRow</a> (bool b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab64e4305bbc1a654dc064dcc253ba005">RowSpanList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ded8946bcb677799616596e18244d4">addRowSpan</a> (ActiveRowSpan &amp;&amp;span)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a> (const DocNodeVariant *n) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">writeStartTableCommand</a> (const DocNodeVariant *n, size_t cols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df0c1870c76f22f1b82744aaeeaf613">writeEndTableCommand</a> (const DocNodeVariant *n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad463a87f9dce2096d73547227047271c">m_t</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/latexcodegenerator">LatexCodeGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad01fc834451929091fe3a94570c5bc9">m_langExt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06dc0a09a39ba955dae7c97895cbe4f7">m_hierarchyLevel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492">TexOrPdf</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">TexOrPdf::NO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::stack&lt; <a href="/web-doxygen/docs/api/structs/latexdocvisitor/tablestate">TableState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab64e4305bbc1a654dc064dcc253ba005">RowSpanList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa73d789e2f5b0c46fbe60b37b2b2a9b">m_emptyRowSpanList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/latexdocvisitor/latexlistiteminfo">LatexListItemInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[maxIndentLevels]</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a> = 13</td>
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

<p>Concrete visitor implementation for LaTeX output.</p>

<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxySectionDef">

## Private Member Typedefs

### RowSpanList {#ab64e4305bbc1a654dc064dcc253ba005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;ActiveRowSpan&gt; LatexDocVisitor::RowSpanList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00131">131</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab64e4305bbc1a654dc064dcc253ba005">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> std::vector&lt;ActiveRowSpan&gt; <a href="#ab64e4305bbc1a654dc064dcc253ba005">RowSpanList</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LatexDocVisitor() {#a7c1f6b996a142fa44583e8f115a00d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatexDocVisitor::LatexDocVisitor (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ci, <a href="/web-doxygen/docs/api/classes/latexcodegenerator">LatexCodeGenerator</a> &amp; lcg, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; langExt, int hierarchyLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00040">40</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00268">268</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c1f6b996a142fa44583e8f115a00d3e">268</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor::LatexDocVisitor</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ci,<a href="/web-doxygen/docs/api/classes/latexcodegenerator">LatexCodeGenerator</a> &amp;lcg,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;langExt, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> hierarchyLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#ad463a87f9dce2096d73547227047271c">m_t</a>(t), <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>(ci), <a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>(lcg), <a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>), <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aad01fc834451929091fe3a94570c5bc9">m_langExt</a>(langExt), <a href="#a06dc0a09a39ba955dae7c97895cbe4f7">m_hierarchyLevel</a>(hierarchyLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7b607b181cfc01d92a707422f92d57da">m&#95;ci</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#a06dc0a09a39ba955dae7c97895cbe4f7">m&#95;hierarchyLevel</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#aff0c5a00a6699c69258af75bb165b504">m&#95;insidePre</a>, <a href="#aad01fc834451929091fe3a94570c5bc9">m&#95;langExt</a>, <a href="#af66c81b21081522e34b6468b4f3c4478">m&#95;lcg</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a4ef9e93a2e68b39e52f7e8ec9595c856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00047">47</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00280">280</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">280</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(w.<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.
</div>
</div>

### operator()() {#a610ca0d0e464f23b2e2c2defbd3bd6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00048">48</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00286">286</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a610ca0d0e464f23b2e2c2defbd3bd6ec">286</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">ref</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">file</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">ref</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">file</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">DocLinkedWord::anchor</a>, <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">DocLinkedWord::file</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">DocLinkedWord::ref</a>, <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a> and <a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">DocLinkedWord::word</a>.
</div>
</div>

### operator()() {#ae8521140810fce270f060a974a5c223e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00049">49</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00294">294</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8521140810fce270f060a974a5c223e">294</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">DocWhiteSpace::chars</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aff0c5a00a6699c69258af75bb165b504">m&#95;insidePre</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

### operator()() {#abfe122c272f139d98332b7630945da0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00050">50</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00307">307</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abfe122c272f139d98332b7630945da0f">307</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperlinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a401769ae867a274591c49695c3a819f0">latex</a>(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (((s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>() == <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa59d844f331ab9ef2ea09969bd1fe49c3">HtmlEntityMapper::Sym_lt</a>) || (s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>() == <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">HtmlEntityMapper::Sym_Less</a>))&amp;&amp; (!<a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\texorpdfstring{$&lt;$}{&lt;}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$&lt;$"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (((s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>() == <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfab130e51b5fae965ad89d2ad2aec5fd55">HtmlEntityMapper::Sym_gt</a>) || (s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>() == <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">HtmlEntityMapper::Sym_Greater</a>)) &amp;&amp; (!<a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\texorpdfstring{$&gt;$}{&gt;}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$&gt;$"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"LaTeX: non supported HTML-entity found: {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().html(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a401769ae867a274591c49695c3a819f0">HtmlEntityMapper::latex</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aff0c5a00a6699c69258af75bb165b504">m&#95;insidePre</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa735e88daf2b0be93495e85e89e06de44">HtmlEntityMapper::Sym&#95;Greater</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfab130e51b5fae965ad89d2ad2aec5fd55">HtmlEntityMapper::Sym&#95;gt</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa1a8b38abfbed7b9cb11b7228b43c4cd0">HtmlEntityMapper::Sym&#95;Less</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa59d844f331ab9ef2ea09969bd1fe49c3">HtmlEntityMapper::Sym&#95;lt</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">DocSymbol::symbol</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### operator()() {#a60686dad3b83395d42770683c5e1e6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00051">51</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00347">347</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60686dad3b83395d42770683c5e1e6a9">347</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> emojiName = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">name</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!emojiName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imageName=emojiName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,emojiName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2); </span><span class="doxyHighlightComment">// strip : at start and end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> != <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxygenemoji{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(emojiName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> != <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight"> &lt;&lt; imageName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">DocEmoji::index</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#a75c523e35f12d34505bac42b4661e621">m&#95;texOrPdf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">DocEmoji::name</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">EmojiEntityMapper::name</a> and <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">PDF</a>.
</div>
</div>

### operator()() {#ae73d9be71f9eba3b4aab19bb46c69fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp; u)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00364">364</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae73d9be71f9eba3b4aab19bb46c69fc8">364</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\href{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (u.<a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">isEmail</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"mailto:"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\texttt{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">DocURL::isEmail</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">DocURL::url</a>.
</div>
</div>

### operator()() {#a5d64467d16ca8ee73bafaf59414cfdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00053">53</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00378">378</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d64467d16ca8ee73bafaf59414cfdd4">378</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"~\\newline\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

### operator()() {#a4d33c93c8ef27f3d559511b25c4e56b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00384">384</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d33c93c8ef27f3d559511b25c4e56b5">384</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\DoxyHorRuler{1}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\DoxyHorRuler{0}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

### operator()() {#a41aaa90a6a3c9ec728048cbdb927c7ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00393">393</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41aaa90a6a3c9ec728048cbdb927c7ae">393</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bfseries{"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\sout{"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\uline{"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\itshape "</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\ttfamily "</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textsubscript{"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textsuperscript{"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{center}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{center} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\footnotesize "</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\normalsize "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\itshape "</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyPre}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyPre}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>:  </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>: </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">DocStyleChange::enable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aff0c5a00a6699c69258af75bb165b504">m&#95;insidePre</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>.
</div>
</div>

### operator()() {#a729fe6d8301bb25f3785b4e4466fccd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00056">56</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00450">450</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a729fe6d8301bb25f3785b4e4466fccd5">450</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang = <a href="#aad01fc834451929091fe3a94570c5bc9">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// explicit language setting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">    lang = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.startCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCode"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(lang).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">context</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">                                      <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(STRIP_CODE_COMMENTS),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">                                      s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">isExample</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.endCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCode"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(), </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\ttfamily "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(), </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyVerb}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyVerb}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* nothing */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dotindex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">        fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d%s"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/inline_dotgraph_"</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">            dotindex++,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">".dot"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">        std::ofstream file = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">          file.write( s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">          file.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aa197e546b10f737e78020b97fdf23cb9">startDotFile</a>(fileName,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mscindex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">        baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/inline_mscgraph_"</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">            mscindex++</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName = baseName+</span><span class="doxyHighlightStringLiteral">".msc"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">        std::ofstream file = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> text = </span><span class="doxyHighlightStringLiteral">"msc {"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">          text+=s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">          text+=</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">          file.write( text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), text.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">          file.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ada18505ac90bb92f4ce279d503dba853">writeMscFile</a>(baseName, s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> latexOutput = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                              latexOutput,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                              s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a9954dcd0a29b9a2ae49f6a41fbc4b3ed">useBitmap</a>() ? <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a> : <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML_EPS</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">                              s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">engine</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a92275d99afc832afc51d7e0deec3afe6">writePlantUMLFile</a>(baseName, s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">DocVerbatim::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>, <a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">DocVerbatim::engine</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">DocVerbatim::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">DocVerbatim::isExample</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">DocVerbatim::language</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a7b607b181cfc01d92a707422f92d57da">m&#95;ci</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aad01fc834451929091fe3a94570c5bc9">m&#95;langExt</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML&#95;BITMAP</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML&#95;EPS</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="#aa197e546b10f737e78020b97fdf23cb9">startDotFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">DocVerbatim::text</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">DocVerbatim::type</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a9954dcd0a29b9a2ae49f6a41fbc4b3ed">DocVerbatim::useBitmap</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a>, <a href="#ada18505ac90bb92f4ce279d503dba853">writeMscFile</a>, <a href="#a92275d99afc832afc51d7e0deec3afe6">writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>.
</div>
</div>

### operator()() {#a81236a6d08e29da34ec95bcc10aea214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp; anc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00057">57</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00564">564</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81236a6d08e29da34ec95bcc10aea214">564</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;anc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\label{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}%\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\Hypertarget{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}%\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">DocAnchor::anchor</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">DocAnchor::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.
</div>
</div>

### operator()() {#ade1c6d00759ad30078d9f5a51cbfc009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp; inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00575">575</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade1c6d00759ad30078d9f5a51cbfc009">575</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;inc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.startCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  fd.get(),    </span><span class="doxyHighlightComment">// fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  -1,    </span><span class="doxyHighlightComment">// start line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  -1,    </span><span class="doxyHighlightComment">// end line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>   </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.endCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.startCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  -1,    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,  </span><span class="doxyHighlightComment">// inlineFragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">                                                 );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.endCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyVerbInclude}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyVerbInclude}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.startCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>().<a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a>(<a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>()==<a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">                                        );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.endCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">DocInclude::blockId</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">DocInclude::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">DocInclude::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">DocInclude::extension</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">DocInclude::file</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">DocInclude::isExample</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>, <a href="#a7b607b181cfc01d92a707422f92d57da">m&#95;ci</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">DocInclude::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">DocInclude::text</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">DocInclude::trimLeft</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">DocInclude::type</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a> and <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>.
</div>
</div>

### operator()() {#a41c844f5b9078d32e11a14b45b6f5c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp; op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00654">654</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41c844f5b9078d32e11a14b45b6f5c2d">654</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;op)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocIncOperator: type=%d first=%d, last=%d text='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    op.type(),op.isFirst(),op.isLast(),qPrint(op.text()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">isFirst</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.startCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locLangExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locLangExt.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) locLangExt = <a href="#aad01fc834451929091fe3a94570c5bc9">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(locLangExt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">type</a>()!=<a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_ptr&lt;FileDef&gt; fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">        fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(locLangExt).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>,op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">context</a>(),op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">isExample</a>(),op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">                                          fd.get(),     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">line</a>(),    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">                                          -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">showLineNo</a>()  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">                                         );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">isLast</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>=<a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) <a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>.endCodeFragment(</span><span class="doxyHighlightStringLiteral">"DoxyCodeInclude"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">DocIncOperator::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">DocIncOperator::exampleFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">DocIncOperator::includeFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">DocIncOperator::isExample</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">DocIncOperator::isFirst</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">DocIncOperator::isLast</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">DocIncOperator::line</a>, <a href="#a7b607b181cfc01d92a707422f92d57da">m&#95;ci</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aad01fc834451929091fe3a94570c5bc9">m&#95;langExt</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">DocVisitor::popHidden</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">DocVisitor::pushHidden</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">DocIncOperator::showLineNo</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">DocIncOperator::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">DocIncOperator::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">DocIncOperator::type</a>.
</div>
</div>

### operator()() {#ac8faec71974f8983332aa0e11a946276}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp; f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00060">60</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00704">704</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8faec71974f8983332aa0e11a946276">704</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s = f.<a href="/web-doxygen/docs/api/classes/docformula/#a4744feabb05063f6019698f2b47a960c">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textnormal{\\textquotesingle}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; c; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/docformula/#a4744feabb05063f6019698f2b47a960c">DocFormula::text</a>.
</div>
</div>

### operator()() {#a718f5fc73955ee4e43228ede93284235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00061">61</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00723">723</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a718f5fc73955ee4e43228ede93284235">723</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\index{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>(i.<a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">entry</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"@{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>(i.<a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">entry</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">DocIndexEntry::entry</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

### operator()() {#a3d7f8b6f817f43e94f39851a2cea219b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00062">62</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00733">733</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d7f8b6f817f43e94f39851a2cea219b">733</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a7da6db1950d1eab0b3aad3535af34d9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp; cite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00063">63</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00737">737</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7da6db1950d1eab0b3aad3535af34d9b">737</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;cite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> opt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">option</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> txt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.noCite())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">      txt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">getText</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">      txt += cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bfseries "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(txt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor = cite.<a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchorPrefix = <a href="/web-doxygen/docs/api/classes/citationmanager/#a4934f7fbd6a387b7cc2ea0a12a2e04b5">CitationManager::instance</a>().<a href="/web-doxygen/docs/api/classes/citationmanager/#a10ba17e783f502c2998a7432c84fd462">anchorPrefix</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">      anchor = anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(anchorPrefix.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()); </span><span class="doxyHighlightComment">// strip prefix</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">      txt = </span><span class="doxyHighlightStringLiteral">"\\DoxyCite{"</span><span class="doxyHighlight"> + anchor + </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.isNumber())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">        txt += </span><span class="doxyHighlightStringLiteral">"{number}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.isShortAuthor())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">        txt += </span><span class="doxyHighlightStringLiteral">"{shortauthor}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.isYear())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">        txt += </span><span class="doxyHighlightStringLiteral">"{year}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"{1}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> txt += </span><span class="doxyHighlightStringLiteral">"{0}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; txt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">      txt += cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bfseries "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(txt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">DocCite::anchor</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a10ba17e783f502c2998a7432c84fd462">CitationManager::anchorPrefix</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">DocCite::file</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">DocCite::getText</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a4934f7fbd6a387b7cc2ea0a12a2e04b5">CitationManager::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">DocCite::option</a> and <a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">DocCite::target</a>.
</div>
</div>

### operator()() {#ad18160e3390b23baf7afb39d4954c928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp; sep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00064">64</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01773">1773</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad18160e3390b23baf7afb39d4954c928">1773</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;sep)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; sep.<a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">chars</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">DocSeparator::chars</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

### operator()() {#a8b9b92e158f2ae2ccccd408ff5201e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00070">70</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00800">800</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b9b92e158f2ae2ccccd408ff5201e50">800</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>&gt;=<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyEnumerate}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[<a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>()].isEnum = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[<a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>()].isEnum = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyItemize}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyEnumerate}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyItemize}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">DocAutoList::isEnumList</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#a1720fe93e9affacc38bdac0cedded094">m&#95;indentLevel</a>, <a href="#aa5ab6acd044e40df6d6450590095dd2b">m&#95;listItemInfo</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a1ce72f4abb11b66d697afdff04056222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00071">71</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00825">825</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ce72f4abb11b66d697afdff04056222">825</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">itemNumber</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a>: </span><span class="doxyHighlightComment">// unchecked</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\item[\\DoxyUnchecked] "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>: </span><span class="doxyHighlightComment">// checked with x</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>: </span><span class="doxyHighlightComment">// checked with X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\item[\\DoxyChecked] "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\item "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(li);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked&#95;X</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked&#95;x</a>, <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">DocAutoListItem::itemNumber</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a28500ffefba81a29ea7a76a60c1f7d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp; p)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00072">72</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00846">846</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28500ffefba81a29ea7a76a60c1f7d1b">846</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!p.<a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">isLast</a>() &amp;&amp;            </span><span class="doxyHighlightComment">// omit &lt;p&gt; for last paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">      !(p.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>() &amp;&amp;           </span><span class="doxyHighlightComment">// and for parameter sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get_if&lt;DocParamSect&gt;(p.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"~\\newline\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">DocPara::isLast</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#adc888f33013fa62f2219d43891d96503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00073">73</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00867">867</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc888f33013fa62f2219d43891d96503">867</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a6f8aff45c8c934cda5be07107de10c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00074">74</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00872">872</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f8aff45c8c934cda5be07107de10c77">872</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxySeeAlso}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSeeAlso());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyReturn}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturns());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyAuthor}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyAuthor}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyVersion}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVersion());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxySince}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSince());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyDate}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDate());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyNote}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNote());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyWarning}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trWarning());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyPrecond}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPrecondition());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyPostcond}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPostcondition());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyCopyright}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCopyright());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyInvariant}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInvariant());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyRemark}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRemarks());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyAttention}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAttention());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyImportant}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trImportant());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyParagraph}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyParagraph}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxySeeAlso}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyReturn}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyAuthor}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyAuthor}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyVersion}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxySince}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyDate}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyNote}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyWarning}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyPrecond}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyPostcond}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyCopyright}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyInvariant}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyRemark}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyAttention}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyImportant}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyParagraph}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyParagraph}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>, <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">DocSimpleSect::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">DocSimpleSect::type</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>.
</div>
</div>

### operator()() {#a57335dd50faa9dc7ee78f420dc35efe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00075">75</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01021">1021</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57335dd50faa9dc7ee78f420dc35efe3">1021</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#ad66d381b7f99cc5e565063f73854573f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00076">76</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01027">1027</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad66d381b7f99cc5e565063f73854573f">1027</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyItemize}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[<a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>()].isEnum = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyItemize}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aa5ab6acd044e40df6d6450590095dd2b">m&#95;listItemInfo</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a09c4ad96f7c5f045fbd0547b623f27bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00077">77</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01036">1036</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09c4ad96f7c5f045fbd0547b623f27bf">1036</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\item "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">    visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">DocSimpleListItem::paragraph</a>.
</div>
</div>

### operator()() {#a0f4bc9b34cb6497194f1adf2e01a1f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01048">1048</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">1048</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperlinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hypertarget{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(s.<a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight"> &lt;&lt; <a href="#ad07ff64f82e760b771d8daec21ce731f">getSectionName</a>(s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\texorpdfstring{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks) <a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">TexOrPdf::TEX</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">TexOrPdf::NO</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks) <a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">TexOrPdf::NO</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\\label{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(s.<a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">DocSection::anchor</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">DocSection::file</a>, <a href="#ad07ff64f82e760b771d8daec21ce731f">getSectionName</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">DocSection::level</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#a75c523e35f12d34505bac42b4661e621">m&#95;texOrPdf</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">NO</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">PDF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">TEX</a>, <a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">DocSection::title</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#aeabfb2614e026a7579c5dadeb5c328c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00079">79</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01082">1082</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeabfb2614e026a7579c5dadeb5c328c3">1082</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>&gt;=<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[<a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>()].isEnum = s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyEnumerate}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; (first ?  </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">: </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label=\\arabic*"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">          first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; (first ?  </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">: </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label=\\enumalphalphcnt*"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">          first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"A"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; (first ?  </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">: </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label=\\enumAlphAlphcnt*"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">          first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"i"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; (first ?  </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">: </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label=\\roman*"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">          first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"I"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; (first ?  </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">: </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"label=\\Roman*"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">          first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"start"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; (first ?  </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">: </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"start="</span><span class="doxyHighlight"> &lt;&lt; val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">        first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyItemize}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>&gt;=<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyEnumerate}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyItemize}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">DocHtmlList::attribs</a>, <a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#a1720fe93e9affacc38bdac0cedded094">m&#95;indentLevel</a>, <a href="#aa5ab6acd044e40df6d6450590095dd2b">m&#95;listItemInfo</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">DocHtmlList::type</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a2a1e6cedc141edf8abf82cfe721eb59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00080">80</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01149">1149</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a1e6cedc141edf8abf82cfe721eb59a">1149</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[<a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>()].isEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : l.<a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\setcounter{DoxyEnumerate"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>(<a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>()+1,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight"> &lt;&lt; (val - 1) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\item "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">DocHtmlListItem::attribs</a>, <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#aa5ab6acd044e40df6d6450590095dd2b">m&#95;listItemInfo</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a4bfb163f58dc53862618450a55e41979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00081">81</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01198">1198</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bfb163f58dc53862618450a55e41979">1198</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> eq = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#abe535965a6e52ac2b1328232b014c0d7">classEqualsReflist</a>(dl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (eq)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyRefList}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#aa069e7d7edbf62f915d7635c7ab5f66e">listIsNested</a>(dl)) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\hfill"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyDescription}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(dl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (eq)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyRefList}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\end{DoxyDescription}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#abe535965a6e52ac2b1328232b014c0d7">classEqualsReflist</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#aa069e7d7edbf62f915d7635c7ab5f66e">listIsNested</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a4336aa37be77360c412335358cd88b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp; dt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00082">82</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01222">1222</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4336aa37be77360c412335358cd88b46">1222</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;dt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\item["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(dt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#af6337e5be9b60d5be63ba2a7f4bd9a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp; dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00083">83</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01232">1232</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">1232</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hfill"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" \\\\\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a678591cbca0c1070b7a8803d3c5541c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00084">84</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01278">1278</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a678591cbca0c1070b7a8803d3c5541c7">1278</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae5dab1f77dba06bcffb8898af56f3606">pushTableState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> *c = t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>() ? &amp;std::get&lt;DocHtmlCaption&gt;(*t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>()) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperLinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!c-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; pdfHyperLinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hypertarget{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(c-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; c-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">anchor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">writeStartTableCommand</a>(t.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>(),t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\caption{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, *t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\label{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(c-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; c-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\\\\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6c0d2ce4dcc1f80ad35725935d062ed6">setNumCols</a>(t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hline\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check if first row is a heading and then render the row already here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// and end it with \endfirsthead (triggered via m_firstRow==TRUE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then repeat the row as normal and end it with \endhead (m_firstRow==FALSE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> *<a href="#a3781c16868efac71398e5436f519ee39">firstRow</a> = std::get_if&lt;DocHtmlRow&gt;(t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#afc50242564e265147b101926f1efce5e">firstRow</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3781c16868efac71398e5436f519ee39">firstRow</a> &amp;&amp; <a href="#a3781c16868efac71398e5436f519ee39">firstRow</a>-&gt;isHeading())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1d60974e8552037cb12627d282df3392">setFirstRow</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>(t.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#afc50242564e265147b101926f1efce5e">firstRow</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1d60974e8552037cb12627d282df3392">setFirstRow</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6df0c1870c76f22f1b82744aaeeaf613">writeEndTableCommand</a>(t.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af52701ab88ccd1fdf7432e3c689a2a16">popTableState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">DocHtmlCaption::anchor</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">DocHtmlTable::caption</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">DocHtmlCaption::file</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#afc50242564e265147b101926f1efce5e">DocHtmlTable::firstRow</a>, <a href="#a3781c16868efac71398e5436f519ee39">firstRow</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">DocHtmlTable::numColumns</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="#af52701ab88ccd1fdf7432e3c689a2a16">popTableState</a>, <a href="#ae5dab1f77dba06bcffb8898af56f3606">pushTableState</a>, <a href="#a1d60974e8552037cb12627d282df3392">setFirstRow</a>, <a href="#a6c0d2ce4dcc1f80ad35725935d062ed6">setNumCols</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>, <a href="#a6df0c1870c76f22f1b82744aaeeaf613">writeEndTableCommand</a> and <a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">writeStartTableCommand</a>.
</div>
</div>

### operator()() {#aed4bd281a17c0748c2b5573eb9f6be86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00085">85</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01326">1326</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed4bd281a17c0748c2b5573eb9f6be86">1326</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#add62a038409ef396c163d584412289cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp; row)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00086">86</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01332">1332</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add62a038409ef396c163d584412289cc">1332</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;row)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(row);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> c=<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (c&lt;=<a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a>()) </span><span class="doxyHighlightComment">// end of row while inside a row span?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;span : <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  found row span: column=%d rs=%d cs=%d rowIdx=%d cell-&gt;rowIdx=%d i=%d c=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    span-&gt;column, span-&gt;rowSpan,span-&gt;colSpan,row.rowIndex(),span-&gt;cell-&gt;rowIndex(),i,c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (span.rowSpan&gt;0 &amp;&amp; span.column==c &amp;&amp;  </span><span class="doxyHighlightComment">// we are at a cell in a row span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">          row.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ad5d8f2862d007316b579b1fcd475136e">rowIndex</a>()&gt;span.cell.rowIndex() </span><span class="doxyHighlightComment">// but not the row that started the span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (span.colSpan&gt;1) </span><span class="doxyHighlightComment">// row span is also part of a column span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\multicolumn{"</span><span class="doxyHighlight"> &lt;&lt; span.colSpan &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt;  </span><span class="doxyHighlightStringLiteral">"}|}{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// solitary row span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\multicolumn{1}{c|}{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">    c++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> col = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;span : <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (span.rowSpan&gt;0) span.rowSpan--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (span.rowSpan&lt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// inactive span</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (span.column&gt;col)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cline{"</span><span class="doxyHighlight"> &lt;&lt; col &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight"> &lt;&lt; (span.column-1) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">      col = span.column+span.colSpan;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">      col = span.column+span.colSpan;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (col &lt;= <a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cline{"</span><span class="doxyHighlight"> &lt;&lt; col &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight"> &lt;&lt; <a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">::parent</a>(row.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (row.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">isHeading</a>() &amp;&amp; row.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ad5d8f2862d007316b579b1fcd475136e">rowIndex</a>()==1 &amp;&amp; !<a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>(n))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3781c16868efac71398e5436f519ee39">firstRow</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\endfirsthead\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hline\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\endfoot\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hline\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\endhead\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>, <a href="#a3781c16868efac71398e5436f519ee39">firstRow</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">DocHtmlRow::isHeading</a>, <a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ad5d8f2862d007316b579b1fcd475136e">DocHtmlRow::rowIndex</a>, <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>, <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#ac11bc06b22732d6e550dc8382badd38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00087">87</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01410">1410</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac11bc06b22732d6e550dc8382badd38f">1410</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> *row = std::get_if&lt;DocHtmlRow&gt;(c.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>(<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//Skip columns that span from above.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;span : <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (span.rowSpan&gt;0 &amp;&amp; span.column==<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (row &amp;&amp; span.colSpan&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\multicolumn{"</span><span class="doxyHighlight"> &lt;&lt; span.colSpan &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>() </span><span class="doxyHighlightComment">/*c.columnIndex()*/</span><span class="doxyHighlight">==1) </span><span class="doxyHighlightComment">// add extra | for first column</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"l|}{"</span><span class="doxyHighlight"> &lt;&lt; (c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ace62c55c933434c4f451847fede71851">isHeading</a>()? </span><span class="doxyHighlightStringLiteral">"\\columncolor{\\tableheadbgcolor}"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// alignment not relevant, empty column</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>(<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>()+span.colSpan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>(<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cs = c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#af34c0918c8bdce594c6039dd64506e7a">colSpan</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> a = c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#abe42707109ca3bbad6ad388f766d8218">alignment</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs&gt;1 &amp;&amp; row)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a555cd968fcfe52155db2e225786e99c6">setInColSpan</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\multicolumn{"</span><span class="doxyHighlight"> &lt;&lt; cs &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a4e028833a3cf77872ac283e2a70560e8">columnIndex</a>()==1) </span><span class="doxyHighlightComment">// add extra | for first column</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (a)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1bfba233eb785db3496ea2a82d9a2136a65214529ecca545b977a6edf61de84c4">DocHtmlCell::Right</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"r|}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1bfba233eb785db3496ea2a82d9a2136a6bf57086c5c581a2d4905ad7cfbec3e0">DocHtmlCell::Center</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"c|}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"l|}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> rs = c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a6c8e5643943bf242271a39a6f679abf6">rowSpan</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> va = c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1afbc68aaf494a718c743d508b394a83">valignment</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rs&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af1e7a18a592b5ce218b3552b8012d49d">setInRowSpan</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\multirow"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(va)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a117087bb36d345bd488208e3c49abc0ba93889b70b0c73a90fcfa7424c9c7a39e">DocHtmlCell::Top</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[t]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a117087bb36d345bd488208e3c49abc0bad4da0c04c710a0275519dc5c2b2ec2bd">DocHtmlCell::Bottom</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[b]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a117087bb36d345bd488208e3c49abc0babae45ea034d0582aeb7a2edd6f93b518">DocHtmlCell::Middle</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// No alignment option needed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("adding row span: cell={r=%d c=%d rs=%d cs=%d} curCol=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//                       c.rowIndex(),c.columnIndex(),c.rowSpan(),c.colSpan(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//                       currentColumn());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a64ded8946bcb677799616596e18244d4">addRowSpan</a>(<a href="/web-doxygen/docs/api/structs/latexdocvisitor/activerowspan">ActiveRowSpan</a>(c,rs,cs,<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; rs &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{*}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (a==<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1bfba233eb785db3496ea2a82d9a2136a6bf57086c5c581a2d4905ad7cfbec3e0">DocHtmlCell::Center</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\PBS\\centering "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (a==<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1bfba233eb785db3496ea2a82d9a2136a65214529ecca545b977a6edf61de84c4">DocHtmlCell::Right</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\PBS\\raggedleft "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ace62c55c933434c4f451847fede71851">isHeading</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cellcolor{\\tableheadbgcolor}\\textbf{ "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cs&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>(<a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>()+cs-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ace62c55c933434c4f451847fede71851">isHeading</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9168d2796d2b37ba82cc27bb4918c6a1">inRowSpan</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af1e7a18a592b5ce218b3552b8012d49d">setInRowSpan</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#abdf9b003ba87f85ee86bddb73602d302">inColSpan</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a555cd968fcfe52155db2e225786e99c6">setInColSpan</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ac61b0f67d380a5ce45f5015e122bc34b">isLast</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a64ded8946bcb677799616596e18244d4">addRowSpan</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#abe42707109ca3bbad6ad388f766d8218">DocHtmlCell::alignment</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a117087bb36d345bd488208e3c49abc0bad4da0c04c710a0275519dc5c2b2ec2bd">DocHtmlCell::Bottom</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1bfba233eb785db3496ea2a82d9a2136a6bf57086c5c581a2d4905ad7cfbec3e0">DocHtmlCell::Center</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af34c0918c8bdce594c6039dd64506e7a">DocHtmlCell::colSpan</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a4e028833a3cf77872ac283e2a70560e8">DocHtmlCell::columnIndex</a>, <a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#abdf9b003ba87f85ee86bddb73602d302">inColSpan</a>, <a href="#a9168d2796d2b37ba82cc27bb4918c6a1">inRowSpan</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ace62c55c933434c4f451847fede71851">DocHtmlCell::isHeading</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ac61b0f67d380a5ce45f5015e122bc34b">DocHtmlCell::isLast</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a117087bb36d345bd488208e3c49abc0babae45ea034d0582aeb7a2edd6f93b518">DocHtmlCell::Middle</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1bfba233eb785db3496ea2a82d9a2136a65214529ecca545b977a6edf61de84c4">DocHtmlCell::Right</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a6c8e5643943bf242271a39a6f679abf6">DocHtmlCell::rowSpan</a>, <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>, <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>, <a href="#a555cd968fcfe52155db2e225786e99c6">setInColSpan</a>, <a href="#af1e7a18a592b5ce218b3552b8012d49d">setInRowSpan</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a117087bb36d345bd488208e3c49abc0ba93889b70b0c73a90fcfa7424c9c7a39e">DocHtmlCell::Top</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a1afbc68aaf494a718c743d508b394a83">DocHtmlCell::valignment</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#adf1a3bedb011096b811a8b1207cc6694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00088">88</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01525">1525</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf1a3bedb011096b811a8b1207cc6694">1525</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a39ce90cc4d05a3748cffe6519957ba59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp; href)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00089">89</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01531">1531</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39ce90cc4d05a3748cffe6519957ba59">1531</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;href)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\href{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>(href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\texttt{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(href);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">DocHRef::url</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a72863fffe73366c27a00f8fdbc6395d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00090">90</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01545">1545</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72863fffe73366c27a00f8fdbc6395d4">1545</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bfseries{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#ad0e9d73e9adb9aac3732cee17a4c67db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00091">91</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01553">1553</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0e9d73e9adb9aac3732cee17a4c67db">1553</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> summary = d.<a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">summary</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*summary);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{adjustwidth}{1em}{0em}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{adjustwidth}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">DocHtmlDetails::summary</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a2f950e3e8499edfa159d43d35ebda0b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp; header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00092">92</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01574">1574</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f950e3e8499edfa159d43d35ebda0b0">1574</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight"> &lt;&lt; <a href="#ad07ff64f82e760b771d8daec21ce731f">getSectionName</a>(header.<a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">level</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"*{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(header);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad07ff64f82e760b771d8daec21ce731f">getSectionName</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">DocHtmlHeader::level</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a28b453c4eabdf03f5d1b690a307d9c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp; img)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00093">93</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01582">1582</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28b453c4eabdf03f5d1b690a307d9c4e">1582</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;img)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (img.<a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>()==<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> gfxName = img.<a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gfxName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">) || gfxName.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".pdf"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">      gfxName=gfxName.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(gfxName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,img.<a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">hasCaption</a>(), gfxName, img.<a href="/web-doxygen/docs/api/classes/docimage/#a79d36f165096668a3d6631efb6e0b4f0">width</a>(),  img.<a href="/web-doxygen/docs/api/classes/docimage/#a434782653279e9f1d823656d48fe3e26">height</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(img);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,img.<a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">hasCaption</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// other format -&gt; skip</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a>, <a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">DocImage::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a434782653279e9f1d823656d48fe3e26">DocImage::height</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">DocImage::isInlineImage</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">DocImage::Latex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">DocImage::name</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">DocImage::type</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docimage/#a79d36f165096668a3d6631efb6e0b4f0">DocImage::width</a>.
</div>
</div>

### operator()() {#a470e988cd5cdc26026424ffc59fec3d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00094">94</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01602">1602</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a470e988cd5cdc26026424ffc59fec3d1">1602</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa197e546b10f737e78020b97fdf23cb9">startDotFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#aa197e546b10f737e78020b97fdf23cb9">startDotFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.
</div>
</div>

### operator()() {#aecc17206d985451fd07d62880158be9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00095">95</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01611">1611</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aecc17206d985451fd07d62880158be9f">1611</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aeef2a244f24ea46106204e063fae5273">startMscFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9ddf71d12334619ccd9ed44cec08e258">endMscFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="#a9ddf71d12334619ccd9ed44cec08e258">endMscFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#aeef2a244f24ea46106204e063fae5273">startMscFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.
</div>
</div>

### operator()() {#af6e9d5dd271f19f872a947b95d88dbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00096">96</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01620">1620</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6e9d5dd271f19f872a947b95d88dbde">1620</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afe30a1c1a560e4a85206dc7623a17dc4">startDiaFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aad8000cb1d166d1985a8e2b306d2b1c6">endDiaFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="#aad8000cb1d166d1985a8e2b306d2b1c6">endDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#afe30a1c1a560e4a85206dc7623a17dc4">startDiaFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.
</div>
</div>

### operator()() {#a6d1352434f601deaf1e191f3db0c3404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00097">97</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01629">1629</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d1352434f601deaf1e191f3db0c3404">1629</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa42bf16168d38b6ac210c3f17bef7510">startPlantUmlFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">endPlantUmlFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">endPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#aa42bf16168d38b6ac210c3f17bef7510">startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.
</div>
</div>

### operator()() {#a59f1ab15f6ef3d9641ae8588f2c717d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp; lnk)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00098">98</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01638">1638</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59f1ab15f6ef3d9641ae8588f2c717d5">1638</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;lnk)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">ref</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">file</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(lnk);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">ref</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">file</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">DocLink::anchor</a>, <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">DocLink::file</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">DocLink::ref</a>, <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a32d07320992840cbb96459bd77cd9608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00099">99</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01646">1646</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32d07320992840cbb96459bd77cd9608">1646</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// when ref.isSubPage()==TRUE we use ref.file() for HTML and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// ref.anchor() for LaTeX/RTF</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">isSubPage</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a7f42be6ae37c6e1cfebab418fe6c50c7">refToTable</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#ae6fd639341aca7aa93aba2d50f0ff874">refToSection</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">hasLinkText</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">targetTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">isSubPage</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a7f42be6ae37c6e1cfebab418fe6c50c7">refToTable</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#ae6fd639341aca7aa93aba2d50f0ff874">refToSection</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a4a7ee966144e3250d175ba9b3f0fe662">sectionType</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">DocRef::anchor</a>, <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">DocRef::file</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">DocRef::hasLinkText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">DocRef::isSubPage</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">DocRef::ref</a>, <a href="/web-doxygen/docs/api/classes/docref/#ae6fd639341aca7aa93aba2d50f0ff874">DocRef::refToSection</a>, <a href="/web-doxygen/docs/api/classes/docref/#a7f42be6ae37c6e1cfebab418fe6c50c7">DocRef::refToTable</a>, <a href="/web-doxygen/docs/api/classes/docref/#a4a7ee966144e3250d175ba9b3f0fe662">DocRef::sectionType</a>, <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">DocRef::targetTitle</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a5a4e5f6aea094c66e6d152fd2962a128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00100">100</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01674">1674</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a4e5f6aea094c66e6d152fd2962a128">1674</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\item \\contentsline{section}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#afe5d43225ef5e2a701c3271da6331e03">isSubPage</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#afc0253a31aeb3962e97246f7a4420f32">ref</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#afc0253a31aeb3962e97246f7a4420f32">ref</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a2b3d15805019c71b6433c53f49aed8f0">refToTable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#afe5d43225ef5e2a701c3271da6331e03">isSubPage</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#afc0253a31aeb3962e97246f7a4420f32">ref</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#afc0253a31aeb3962e97246f7a4420f32">ref</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>(),ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a2b3d15805019c71b6433c53f49aed8f0">refToTable</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{\\ref{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}{}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">DocSecRefItem::anchor</a>, <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">DocSecRefItem::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#afe5d43225ef5e2a701c3271da6331e03">DocSecRefItem::isSubPage</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#afc0253a31aeb3962e97246f7a4420f32">DocSecRefItem::ref</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a2b3d15805019c71b6433c53f49aed8f0">DocSecRefItem::refToTable</a>, <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a1b9a4f0271ea62f929b5072a2ac109b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00101">101</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01705">1705</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b9a4f0271ea62f929b5072a2ac109b0">1705</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\footnotesize\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{multicols}{2}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyCompactList}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyCompactList}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{multicols}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\normalsize\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#aca420728eca4e37947593db6a96eadd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00102">102</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01719">1719</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca420728eca4e37947593db6a96eadd3">1719</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasInOutSpecs = s.<a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasTypeSpecs  = s.<a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>.incUsedTableLevel();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyParams}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (hasInOutSpecs &amp;&amp; hasTypeSpecs) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[2]"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// 2 extra cols</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasInOutSpecs || hasTypeSpecs) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[1]"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// 1 extra col</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trParameters());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyRetVals}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturnValues());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyExceptions}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptions());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\begin{DoxyTemplParams}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trTemplateParameters());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>.decUsedTableLevel();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyParams}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyRetVals}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyExceptions}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyTemplParams}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">DocParamSect::hasInOutSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">DocParamSect::hasTypeSpecifier</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#af66c81b21081522e34b6468b4f3c4478">m&#95;lcg</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a806029951b075fcd8c430498bd0f2375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp; pl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00103">103</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01778">1778</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a806029951b075fcd8c430498bd0f2375">1778</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;pl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a> parentType = <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> *sect = std::get_if&lt;DocParamSect&gt;(pl.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">    parentType = sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useTable = parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">                  parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">                  parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">                  parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\item["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()!=<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\mbox{\\texttt{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in,out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &amp; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;type : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &amp; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\em "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;param : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,param);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &amp; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;par : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,par);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\\\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\hline\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">DocParamList::direction</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">DocParamSect::hasInOutSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">DocParamSect::hasTypeSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">DocParamList::paragraphs</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">DocParamList::parameters</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">DocParamList::paramTypes</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a> and <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>.
</div>
</div>

### operator()() {#a330c52431e7c540fcea7901e74c70da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp; x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00104">104</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01853">1853</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a330c52431e7c540fcea7901e74c70da7">1853</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;x)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperlinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{DoxyRefDesc}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> anonymousEnum = x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>()==</span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\item["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks &amp;&amp; !anonymousEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\mbox{\\hyperlink{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> &lt;&lt; x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textbf{ "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pdfHyperlinks &amp;&amp; !anonymousEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(x);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{DoxyRefDesc}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">DocXRefItem::anchor</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">DocXRefItem::file</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">DocXRefItem::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#aaac51ad3dcaa4b594e4a917c6062e216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00105">105</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01886">1886</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaac51ad3dcaa4b594e4a917c6062e216">1886</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">DocInternalRef::anchor</a>, <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">DocInternalRef::file</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a41d834c86e9800452bd5d86ebe4a475a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00106">106</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01894">1894</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41d834c86e9800452bd5d86ebe4a475a">1894</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a5ed16c660428cb0d22236e25f0cb5a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00107">107</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01900">1900</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5ed16c660428cb0d22236e25f0cb5a1f">1900</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{quote}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{quote}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

### operator()() {#a1303593cf872dbc274f7d82da5d8c508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00108">108</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01910">1910</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1303593cf872dbc274f7d82da5d8c508">1910</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a03c8e02e7e2e9e5dbb2bb8a1fe27b37d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp; pb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00109">109</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01914">1914</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03c8e02e7e2e9e5dbb2bb8a1fe27b37d">1914</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">LatexDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;pb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(pb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a> and <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRowSpan() {#a64ded8946bcb677799616596e18244d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::addRowSpan (<a href="/web-doxygen/docs/api/structs/latexdocvisitor/activerowspan">ActiveRowSpan</a> &amp;&amp; span)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00260">260</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64ded8946bcb677799616596e18244d4">260</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64ded8946bcb677799616596e18244d4">addRowSpan</a>(<a href="/web-doxygen/docs/api/structs/latexdocvisitor/activerowspan">ActiveRowSpan</a> &amp;&amp;span)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty()) <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().rowSpans.push_back(std::move(span));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>.
</div>
</div>

### currentColumn() {#a8d2ed858c16eee5436001b357fb9930c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexDocVisitor::currentColumn ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00216">216</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d2ed858c16eee5436001b357fb9930c">216</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty() ? <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().currentColumn : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a> and <a href="#add62a038409ef396c163d584412289cc">operator()</a>.
</div>
</div>

### decIndentLevel() {#af2255727c9f6bc6589488bbde0d9a007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::decIndentLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00168">168</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02157">2157</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2255727c9f6bc6589488bbde0d9a007">2157</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af2255727c9f6bc6589488bbde0d9a007">LatexDocVisitor::decIndentLevel</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a1720fe93e9affacc38bdac0cedded094">m&#95;indentLevel</a>.

Referenced by <a href="#a1ce72f4abb11b66d697afdff04056222">operator()</a>, <a href="#a5ed16c660428cb0d22236e25f0cb5a1f">operator()</a>, <a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a>, <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>, <a href="#a1b9a4f0271ea62f929b5072a2ac109b0">operator()</a>, <a href="#a09c4ad96f7c5f045fbd0547b623f27bf">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a> and <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>.
</div>
</div>

### endDiaFile() {#aad8000cb1d166d1985a8e2b306d2b1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::endDiaFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00157">157</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02077">2077</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad8000cb1d166d1985a8e2b306d2b1c6">2077</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aad8000cb1d166d1985a8e2b306d2b1c6">LatexDocVisitor::endDiaFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>.

Referenced by <a href="#af6e9d5dd271f19f872a947b95d88dbde">operator()</a>.
</div>
</div>

### endDotFile() {#a44fa6c956b97a5ca373a9c6d361f9658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::endDotFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00146">146</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02021">2021</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44fa6c956b97a5ca373a9c6d361f9658">2021</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a44fa6c956b97a5ca373a9c6d361f9658">LatexDocVisitor::endDotFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>.

Referenced by <a href="#a470e988cd5cdc26026424ffc59fec3d1">operator()</a> and <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>.
</div>
</div>

### endLink() {#a2a7db7045021961de35c39ea7e1deb40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::endLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool refToTable=false, bool refToSection=false, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> sectionType=<a href="/web-doxygen/docs/api/classes/sectiontype/#a017df4547430d10bdd70d7c56efcd78a">SectionType::Anchor</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00140">140</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01980">1980</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a7db7045021961de35c39ea7e1deb40">1980</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2a7db7045021961de35c39ea7e1deb40">LatexDocVisitor::endLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*refToTable*/</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> refToSection, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> sectionType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperLinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !pdfHyperLinks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPageAbbreviation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{"</span><span class="doxyHighlight"> &lt;&lt; file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.isEmpty() &amp;&amp; !anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (refToSection)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; sectionType.<a href="/web-doxygen/docs/api/classes/sectiontype/#a66ac9cce30551011fd940a18848743df">level</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; pdfHyperLinks) </span><span class="doxyHighlightComment">// internal PDF link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (refToSection)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> != <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; sectionType.<a href="/web-doxygen/docs/api/classes/sectiontype/#a66ac9cce30551011fd940a18848743df">level</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a66ac9cce30551011fd940a18848743df">SectionType::level</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#a75c523e35f12d34505bac42b4661e621">m&#95;texOrPdf</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">PDF</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="#aaac51ad3dcaa4b594e4a917c6062e216">operator()</a>, <a href="#a59f1ab15f6ef3d9641ae8588f2c717d5">operator()</a>, <a href="#a610ca0d0e464f23b2e2c2defbd3bd6ec">operator()</a>, <a href="#a32d07320992840cbb96459bd77cd9608">operator()</a> and <a href="#a5a4e5f6aea094c66e6d152fd2962a128">operator()</a>.
</div>
</div>

### endMscFile() {#a9ddf71d12334619ccd9ed44cec08e258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::endMscFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00151">151</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02043">2043</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ddf71d12334619ccd9ed44cec08e258">2043</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ddf71d12334619ccd9ed44cec08e258">LatexDocVisitor::endMscFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>.

Referenced by <a href="#aecc17206d985451fd07d62880158be9f">operator()</a>.
</div>
</div>

### endPlantUmlFile() {#ae69b08d5d7cf891ffcc6ce599b68ed80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::endPlantUmlFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00163">163</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02137">2137</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">2137</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">LatexDocVisitor::endPlantUmlFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m&#95;hide</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>.

Referenced by <a href="#a6d1352434f601deaf1e191f3db0c3404">operator()</a>.
</div>
</div>

### escapeMakeIndexChars() {#a0b6e670e04f51e9bb0a163326fe8ffab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LatexDocVisitor::escapeMakeIndexChars (const char * s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00142">142</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00240">240</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b6e670e04f51e9bb0a163326fe8ffab">240</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0b6e670e04f51e9bb0a163326fe8ffab">LatexDocVisitor::escapeMakeIndexChars</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> str[2]; str[1]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"!"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"@"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\texttt{\"|}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\lcurly{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">: <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\rcurly{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:  str[0]=c; <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>(str); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.
</div>
</div>

### filter() {#a99fd1bd50877a6c36721da21a2a2eb1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::filter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const bool retainNewLine=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00137">137</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01920">1920</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99fd1bd50877a6c36721da21a2a2eb1e">1920</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">LatexDocVisitor::filter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retainNewLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("LatexDocVisitor::filter(%s) m_insideTabbing=%d m_insideTable=%d\n",qPrint(str),m_lcg.insideTabbing(),m_lcg.usedTableLevel()&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,str,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>.insideTabbing(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>.usedTableLevel()&gt;0,  </span><span class="doxyHighlightComment">// insideTable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, </span><span class="doxyHighlightComment">// keepSpaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">                    retainNewLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">                   );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>, <a href="#ad17375904f6fa3f97fedbca5b62a792d">m&#95;insideItem</a>, <a href="#aff0c5a00a6699c69258af75bb165b504">m&#95;insidePre</a>, <a href="#af66c81b21081522e34b6468b4f3c4478">m&#95;lcg</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.

Referenced by <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="#a0b6e670e04f51e9bb0a163326fe8ffab">escapeMakeIndexChars</a>, <a href="#a7da6db1950d1eab0b3aad3535af34d9b">operator()</a>, <a href="#a60686dad3b83395d42770683c5e1e6a9">operator()</a>, <a href="#a610ca0d0e464f23b2e2c2defbd3bd6ec">operator()</a>, <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>, <a href="#a32d07320992840cbb96459bd77cd9608">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a>, <a href="#ae73d9be71f9eba3b4aab19bb46c69fc8">operator()</a>, <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>, <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">operator()</a> and <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>.
</div>
</div>

### firstRow() {#a3781c16868efac71398e5436f519ee39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::firstRow ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00248">248</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3781c16868efac71398e5436f519ee39">248</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3781c16868efac71398e5436f519ee39">firstRow</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty() ? <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().firstRow : <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#add62a038409ef396c163d584412289cc">operator()</a> and <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

### getSectionName() {#ad07ff64f82e760b771d8daec21ce731f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LatexDocVisitor::getSectionName (int level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00170">170</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad07ff64f82e760b771d8daec21ce731f">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ad07ff64f82e760b771d8daec21ce731f">LatexDocVisitor::getSectionName</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> compactLatex = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(COMPACT_LATEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compactLatex) l++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt; <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a53a87b38bd8834f0f9cecd70b3ee0d94">g_maxLevels</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    l += <a href="#a06dc0a09a39ba955dae7c97895cbe4f7">m_hierarchyLevel</a>; </span><span class="doxyHighlightComment">/* May be -1 if generating main page */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Sections get special treatment because they inherit the parent's level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &gt;= <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a53a87b38bd8834f0f9cecd70b3ee0d94">g_maxLevels</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      l = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a53a87b38bd8834f0f9cecd70b3ee0d94">g_maxLevels</a> - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* Should not happen; level is always &gt;= 1 and hierarchyLevel &gt;= -1 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">      l = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a8f1351e365ccc81f1dac1de997eef866">g_secLabels</a>[l];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l == 7)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#abb6979412384989613be283a79b1ee88">g_paragraphLabel</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a530bc6aacffcda759e811ae5db0bed16">g_subparagraphLabel</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a53a87b38bd8834f0f9cecd70b3ee0d94">g&#95;maxLevels</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#abb6979412384989613be283a79b1ee88">g&#95;paragraphLabel</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a8f1351e365ccc81f1dac1de997eef866">g&#95;secLabels</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#a530bc6aacffcda759e811ae5db0bed16">g&#95;subparagraphLabel</a> and <a href="#a06dc0a09a39ba955dae7c97895cbe4f7">m&#95;hierarchyLevel</a>.

Referenced by <a href="#a2f950e3e8499edfa159d43d35ebda0b0">operator()</a> and <a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">operator()</a>.
</div>
</div>

### incIndentLevel() {#a119bb54272cc6a3dbe0c01ee6f60e9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::incIndentLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00167">167</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02148">2148</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">2148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">LatexDocVisitor::incIndentLevel</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>&gt;=<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Maximum indent level ({}) exceeded while generating LaTeX output!\n"</span><span class="doxyHighlight">,<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="#a1720fe93e9affacc38bdac0cedded094">m&#95;indentLevel</a> and <a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>.

Referenced by <a href="#a1ce72f4abb11b66d697afdff04056222">operator()</a>, <a href="#a5ed16c660428cb0d22236e25f0cb5a1f">operator()</a>, <a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a>, <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>, <a href="#a1b9a4f0271ea62f929b5072a2ac109b0">operator()</a>, <a href="#a09c4ad96f7c5f045fbd0547b623f27bf">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a> and <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>.
</div>
</div>

### inColSpan() {#abdf9b003ba87f85ee86bddb73602d302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::inColSpan ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00240">240</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abdf9b003ba87f85ee86bddb73602d302">240</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abdf9b003ba87f85ee86bddb73602d302">inColSpan</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty() ? <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().inColSpan : <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>.
</div>
</div>

### indentLevel() {#a25c6d887a6677aa800a1d928c9455df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LatexDocVisitor::indentLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00169">169</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02143">2143</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25c6d887a6677aa800a1d928c9455df3">2143</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a25c6d887a6677aa800a1d928c9455df3">LatexDocVisitor::indentLevel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::min(<a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a>,<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1720fe93e9affacc38bdac0cedded094">m&#95;indentLevel</a> and <a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>.

Referenced by <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a>, <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a> and <a href="#ad66d381b7f99cc5e565063f73854573f">operator()</a>.
</div>
</div>

### inRowSpan() {#a9168d2796d2b37ba82cc27bb4918c6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::inRowSpan ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00232">232</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9168d2796d2b37ba82cc27bb4918c6a1">232</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9168d2796d2b37ba82cc27bb4918c6a1">inRowSpan</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty() ? <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().inRowSpan : <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>.
</div>
</div>

### insideTable() {#aaa24e4fc93db1df3bcd28753025254d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::insideTable ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00264">264</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa24e4fc93db1df3bcd28753025254d6">264</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#a4d33c93c8ef27f3d559511b25c4e56b5">operator()</a> and <a href="#a28500ffefba81a29ea7a76a60c1f7d1b">operator()</a>.
</div>
</div>

### isTableNested() {#aa2c5d961b9ad326122481acacc033172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::isTableNested (const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00269">269</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01241">1241</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2c5d961b9ad326122481acacc033172">1241</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa2c5d961b9ad326122481acacc033172">LatexDocVisitor::isTableNested</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isNested=<a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>.usedTableLevel()&gt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (n &amp;&amp; !isNested)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">    isNested = <a href="/web-doxygen/docs/api/files/src/docnode-h/#a1c1632e37b281677f09baa3acce082cf">holds_one_of_alternatives&lt;DocHtmlTable,DocParamSect&gt;</a>(*n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">    n = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">::parent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> isNested;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-h/#a1c1632e37b281677f09baa3acce082cf">holds&#95;one&#95;of&#95;alternatives</a>, <a href="#af66c81b21081522e34b6468b4f3c4478">m&#95;lcg</a> and <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>.

Referenced by <a href="#add62a038409ef396c163d584412289cc">operator()</a>, <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>, <a href="#a6df0c1870c76f22f1b82744aaeeaf613">writeEndTableCommand</a> and <a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">writeStartTableCommand</a>.
</div>
</div>

### numCols() {#affb8062141ed5b09ba687d473f2886fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t LatexDocVisitor::numCols ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00224">224</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affb8062141ed5b09ba687d473f2886fe">224</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty() ? <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().numCols : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#add62a038409ef396c163d584412289cc">operator()</a>.
</div>
</div>

### popTableState() {#af52701ab88ccd1fdf7432e3c689a2a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::popTableState ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00212">212</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af52701ab88ccd1fdf7432e3c689a2a16">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af52701ab88ccd1fdf7432e3c689a2a16">popTableState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

### pushTableState() {#ae5dab1f77dba06bcffb8898af56f3606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::pushTableState ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00208">208</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5dab1f77dba06bcffb8898af56f3606">208</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae5dab1f77dba06bcffb8898af56f3606">pushTableState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.emplace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

### rowSpans() {#a1e6bce68fe8f4b6a5e70026aaed88a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RowSpanList &amp; LatexDocVisitor::rowSpans ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00256">256</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">256</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab64e4305bbc1a654dc064dcc253ba005">RowSpanList</a> &amp;<a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty() ? <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().rowSpans : <a href="#aaa73d789e2f5b0c46fbe60b37b2b2a9b">m_emptyRowSpanList</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#aaa73d789e2f5b0c46fbe60b37b2b2a9b">m&#95;emptyRowSpanList</a> and <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a> and <a href="#add62a038409ef396c163d584412289cc">operator()</a>.
</div>
</div>

### setCurrentColumn() {#a24b90355494bec87ba2cabf71e632c16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::setCurrentColumn (size_t col)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00220">220</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24b90355494bec87ba2cabf71e632c16">220</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> col)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty()) <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().currentColumn = col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a> and <a href="#add62a038409ef396c163d584412289cc">operator()</a>.
</div>
</div>

### setFirstRow() {#a1d60974e8552037cb12627d282df3392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::setFirstRow (bool b)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00252">252</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d60974e8552037cb12627d282df3392">252</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d60974e8552037cb12627d282df3392">setFirstRow</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty()) <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().firstRow = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

### setInColSpan() {#a555cd968fcfe52155db2e225786e99c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::setInColSpan (bool b)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00244">244</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a555cd968fcfe52155db2e225786e99c6">244</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a555cd968fcfe52155db2e225786e99c6">setInColSpan</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty()) <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().inColSpan = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>.
</div>
</div>

### setInRowSpan() {#af1e7a18a592b5ce218b3552b8012d49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::setInRowSpan (bool b)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00236">236</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1e7a18a592b5ce218b3552b8012d49d">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af1e7a18a592b5ce218b3552b8012d49d">setInRowSpan</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty()) <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().inRowSpan = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>.
</div>
</div>

### setNumCols() {#a6c0d2ce4dcc1f80ad35725935d062ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::setNumCols (size_t num)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00228">228</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c0d2ce4dcc1f80ad35725935d062ed6">228</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6c0d2ce4dcc1f80ad35725935d062ed6">setNumCols</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> num)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.empty()) <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>.top().numCols = num;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a202aa23a61e3b8e40132aaae748078a0">m&#95;tableStateStack</a>.

Referenced by <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

### startDiaFile() {#afe30a1c1a560e4a85206dc7623a17dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::startDiaFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00154">154</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02061">2061</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe30a1c1a560e4a85206dc7623a17dc4">2061</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afe30a1c1a560e4a85206dc7623a17dc4">LatexDocVisitor::startDiaFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">                                  )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"dia_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>(fileName,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35ac2c027d8c62500300145c3043546d4c6">DiaOutputFormat::EPS</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption, baseName, width, height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>.

Referenced by <a href="#af6e9d5dd271f19f872a947b95d88dbde">operator()</a>.
</div>
</div>

### startDotFile() {#aa197e546b10f737e78020b97fdf23cb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::startDotFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00143">143</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02005">2005</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa197e546b10f737e78020b97fdf23cb9">2005</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa197e546b10f737e78020b97fdf23cb9">LatexDocVisitor::startDotFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">                                  )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"dot_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>(name,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fac2c027d8c62500300145c3043546d4c6">GraphOutputFormat::EPS</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption, baseName, width, height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>.

Referenced by <a href="#a470e988cd5cdc26026424ffc59fec3d1">operator()</a> and <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>.
</div>
</div>

### startLink() {#a7622ffaad8b1168ffc837eae842d6c53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::startLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool refToTable=false, bool refToSection=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00138">138</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01933">1933</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7622ffaad8b1168ffc837eae842d6c53">1933</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7622ffaad8b1168ffc837eae842d6c53">LatexDocVisitor::startLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> refToTable,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> refToSection)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperLinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; pdfHyperLinks) </span><span class="doxyHighlightComment">// internal PDF link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (refToTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxytablelink{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (refToSection)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> == <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">TexOrPdf::TEX</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\protect"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> != <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxysectlink{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> == <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">TexOrPdf::TEX</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\protect"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> != <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxylink{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (refToTable || <a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> != <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">TexOrPdf::PDF</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; refToSection)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxysectref{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; refToTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxytableref{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// internal non-PDF link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\doxyref{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// external link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textbf{ "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="#a75c523e35f12d34505bac42b4661e621">m&#95;texOrPdf</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492abcd1b68617759b1dfcff0403a6b5a8d1">PDF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492a9ed6f50f63c3af102f036468321d142b">TEX</a>.

Referenced by <a href="#aaac51ad3dcaa4b594e4a917c6062e216">operator()</a>, <a href="#a59f1ab15f6ef3d9641ae8588f2c717d5">operator()</a>, <a href="#a610ca0d0e464f23b2e2c2defbd3bd6ec">operator()</a>, <a href="#a32d07320992840cbb96459bd77cd9608">operator()</a> and <a href="#a5a4e5f6aea094c66e6d152fd2962a128">operator()</a>.
</div>
</div>

### startMscFile() {#aeef2a244f24ea46106204e063fae5273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::startMscFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00148">148</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02027">2027</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeef2a244f24ea46106204e063fae5273">2027</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeef2a244f24ea46106204e063fae5273">LatexDocVisitor::startMscFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">                                  )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"msc_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>(fileName,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">MscOutputFormat::EPS</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption, baseName, width, height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>.

Referenced by <a href="#aecc17206d985451fd07d62880158be9f">operator()</a>.
</div>
</div>

### startPlantUmlFile() {#aa42bf16168d38b6ac210c3f17bef7510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::startPlantUmlFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00160">160</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02109">2109</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa42bf16168d38b6ac210c3f17bef7510">2109</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">                                  )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string inBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>(fileName,inBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useBitmap = inBuf.find(</span><span class="doxyHighlightStringLiteral">"@startditaa"</span><span class="doxyHighlight">) != std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">                              outDir,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),inBuf.c_str(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">                              useBitmap ? <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a> : <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML_EPS</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),srcFile,srcLine,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useBitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (shortName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">)==-1) shortName += </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">generatePlantUMLOutput</a>(baseName,outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">                              useBitmap ? <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a> : <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML_EPS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>,hasCaption, shortName, width, height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML&#95;BITMAP</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML&#95;EPS</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>.

Referenced by <a href="#a6d1352434f601deaf1e191f3db0c3404">operator()</a>.
</div>
</div>

### visitCaption() {#a5cdbdc679e7820db4e2ba3c9142f3665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::visitCaption (const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00165">165</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l00232">232</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5cdbdc679e7820db4e2ba3c9142f3665">232</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">LatexDocVisitor::visitCaption</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;n : children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#a168f142f518c0734df4301ca492859d1">writeDiaFile</a>, <a href="#ada18505ac90bb92f4ce279d503dba853">writeMscFile</a> and <a href="#a92275d99afc832afc51d7e0deec3afe6">writePlantUMLFile</a>.
</div>
</div>

### visitChildren() {#af5491b919f553a13e4d244d42c42b78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::visitChildren (const T &amp; t)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00113">113</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5491b919f553a13e4d244d42c42b78e">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af5491b919f553a13e4d244d42c42b78e">visitChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : t.children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Referenced by <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a>, <a href="#a1ce72f4abb11b66d697afdff04056222">operator()</a>, <a href="#af6e9d5dd271f19f872a947b95d88dbde">operator()</a>, <a href="#a470e988cd5cdc26026424ffc59fec3d1">operator()</a>, <a href="#a39ce90cc4d05a3748cffe6519957ba59">operator()</a>, <a href="#a5ed16c660428cb0d22236e25f0cb5a1f">operator()</a>, <a href="#aed4bd281a17c0748c2b5573eb9f6be86">operator()</a>, <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>, <a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">operator()</a>, <a href="#a4bfb163f58dc53862618450a55e41979">operator()</a>, <a href="#a4336aa37be77360c412335358cd88b46">operator()</a>, <a href="#ad0e9d73e9adb9aac3732cee17a4c67db">operator()</a>, <a href="#a2f950e3e8499edfa159d43d35ebda0b0">operator()</a>, <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a>, <a href="#add62a038409ef396c163d584412289cc">operator()</a>, <a href="#a72863fffe73366c27a00f8fdbc6395d4">operator()</a>, <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>, <a href="#a28b453c4eabdf03f5d1b690a307d9c4e">operator()</a>, <a href="#adf1a3bedb011096b811a8b1207cc6694">operator()</a>, <a href="#aaac51ad3dcaa4b594e4a917c6062e216">operator()</a>, <a href="#a59f1ab15f6ef3d9641ae8588f2c717d5">operator()</a>, <a href="#aecc17206d985451fd07d62880158be9f">operator()</a>, <a href="#a28500ffefba81a29ea7a76a60c1f7d1b">operator()</a>, <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>, <a href="#a03c8e02e7e2e9e5dbb2bb8a1fe27b37d">operator()</a>, <a href="#a6d1352434f601deaf1e191f3db0c3404">operator()</a>, <a href="#a32d07320992840cbb96459bd77cd9608">operator()</a>, <a href="#adc888f33013fa62f2219d43891d96503">operator()</a>, <a href="#a5a4e5f6aea094c66e6d152fd2962a128">operator()</a>, <a href="#a1b9a4f0271ea62f929b5072a2ac109b0">operator()</a>, <a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">operator()</a>, <a href="#ad66d381b7f99cc5e565063f73854573f">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a>, <a href="#a41d834c86e9800452bd5d86ebe4a475a">operator()</a>, <a href="#a57335dd50faa9dc7ee78f420dc35efe3">operator()</a>, <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a> and <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>.
</div>
</div>

### writeDiaFile() {#a168f142f518c0734df4301ca492859d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::writeDiaFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00158">158</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02084">2084</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a168f142f518c0734df4301ca492859d1">2084</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a168f142f518c0734df4301ca492859d1">LatexDocVisitor::writeDiaFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>(baseName+</span><span class="doxyHighlightStringLiteral">".dia"</span><span class="doxyHighlight">,outDir,shortName,<a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35ac2c027d8c62500300145c3043546d4c6">DiaOutputFormat::EPS</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), shortName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a> and <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>.
</div>
</div>

### writeEndTableCommand() {#a6df0c1870c76f22f1b82744aaeeaf613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::writeEndTableCommand (const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00271">271</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01265">1265</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6df0c1870c76f22f1b82744aaeeaf613">1265</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6df0c1870c76f22f1b82744aaeeaf613">LatexDocVisitor::writeEndTableCommand</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>(n))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{tabularx}}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{longtabu}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//return isNested ? "TabularNC" : "TabularC";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.

Referenced by <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

### writeMscFile() {#ada18505ac90bb92f4ce279d503dba853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::writeMscFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00152">152</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02050">2050</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada18505ac90bb92f4ce279d503dba853">2050</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ada18505ac90bb92f4ce279d503dba853">LatexDocVisitor::writeMscFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>(baseName+</span><span class="doxyHighlightStringLiteral">".msc"</span><span class="doxyHighlight">,outDir,shortName,<a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">MscOutputFormat::EPS</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), shortName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a> and <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>.

Referenced by <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>.
</div>
</div>

### writePlantUMLFile() {#a92275d99afc832afc51d7e0deec3afe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::writePlantUMLFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00159">159</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l02094">2094</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92275d99afc832afc51d7e0deec3afe6">2094</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a92275d99afc832afc51d7e0deec3afe6">LatexDocVisitor::writePlantUMLFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a9954dcd0a29b9a2ae49f6a41fbc4b3ed">useBitmap</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (shortName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">)==-1) shortName += </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">generatePlantUMLOutput</a>(baseName,outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">                              s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a9954dcd0a29b9a2ae49f6a41fbc4b3ed">useBitmap</a>() ? <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a> : <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML_EPS</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), shortName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML&#95;BITMAP</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5aef367a42db272e040b6fec4c65f52b36">PlantumlManager::PUML&#95;EPS</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a9954dcd0a29b9a2ae49f6a41fbc4b3ed">DocVerbatim::useBitmap</a>, <a href="#a5cdbdc679e7820db4e2ba3c9142f3665">visitCaption</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a>.

Referenced by <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>.
</div>
</div>

### writeStartTableCommand() {#a6de1c60f1310fa0be7c9a16eb2ce760d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LatexDocVisitor::writeStartTableCommand (const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * n, size_t cols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00270">270</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#l01252">1252</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">1252</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">LatexDocVisitor::writeStartTableCommand</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *n,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> cols)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>(n))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\begin{tabularx}{\\linewidth}{|*{"</span><span class="doxyHighlight"> &lt;&lt; cols &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{&gt;{\\raggedright\\arraybackslash}X|}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad463a87f9dce2096d73547227047271c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\tabulinesep=1mm\n\\begin{longtabu}spread 0pt [c]{*{"</span><span class="doxyHighlight"> &lt;&lt; cols &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{|X[-1]}|}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//return isNested ? "TabularNC" : "TabularC";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a> and <a href="#ad463a87f9dce2096d73547227047271c">m&#95;t</a>.

Referenced by <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;ci {#a7b607b181cfc01d92a707422f92d57da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList&amp; LatexDocVisitor::m_ci</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00177">177</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b607b181cfc01d92a707422f92d57da">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#a7b607b181cfc01d92a707422f92d57da">m_ci</a>;</span></span></div>

</div>


Referenced by <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>, <a href="#ade1c6d00759ad30078d9f5a51cbfc009">operator()</a>, <a href="#a41c844f5b9078d32e11a14b45b6f5c2d">operator()</a> and <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>.
</div>
</div>

### m&#95;emptyRowSpanList {#aaa73d789e2f5b0c46fbe60b37b2b2a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RowSpanList LatexDocVisitor::m_emptyRowSpanList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00196">196</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa73d789e2f5b0c46fbe60b37b2b2a9b">196</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab64e4305bbc1a654dc064dcc253ba005">RowSpanList</a> <a href="#aaa73d789e2f5b0c46fbe60b37b2b2a9b">m_emptyRowSpanList</a>;</span></span></div>

</div>


Referenced by <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>.
</div>
</div>

### m&#95;hide {#a6c6a9e04b7e8044f7f34a6b4fb487445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::m_hide</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00181">181</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">181</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6c6a9e04b7e8044f7f34a6b4fb487445">m_hide</a>;</span></span></div>

</div>


Referenced by <a href="#aad8000cb1d166d1985a8e2b306d2b1c6">endDiaFile</a>, <a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a>, <a href="#a9ddf71d12334619ccd9ed44cec08e258">endMscFile</a>, <a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">endPlantUmlFile</a>, <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>, <a href="#a81236a6d08e29da34ec95bcc10aea214">operator()</a>, <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a>, <a href="#a1ce72f4abb11b66d697afdff04056222">operator()</a>, <a href="#a7da6db1950d1eab0b3aad3535af34d9b">operator()</a>, <a href="#af6e9d5dd271f19f872a947b95d88dbde">operator()</a>, <a href="#a470e988cd5cdc26026424ffc59fec3d1">operator()</a>, <a href="#a60686dad3b83395d42770683c5e1e6a9">operator()</a>, <a href="#ac8faec71974f8983332aa0e11a946276">operator()</a>, <a href="#a4d33c93c8ef27f3d559511b25c4e56b5">operator()</a>, <a href="#a39ce90cc4d05a3748cffe6519957ba59">operator()</a>, <a href="#a5ed16c660428cb0d22236e25f0cb5a1f">operator()</a>, <a href="#aed4bd281a17c0748c2b5573eb9f6be86">operator()</a>, <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>, <a href="#a4bfb163f58dc53862618450a55e41979">operator()</a>, <a href="#a4336aa37be77360c412335358cd88b46">operator()</a>, <a href="#ad0e9d73e9adb9aac3732cee17a4c67db">operator()</a>, <a href="#a2f950e3e8499edfa159d43d35ebda0b0">operator()</a>, <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a>, <a href="#add62a038409ef396c163d584412289cc">operator()</a>, <a href="#a72863fffe73366c27a00f8fdbc6395d4">operator()</a>, <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>, <a href="#a28b453c4eabdf03f5d1b690a307d9c4e">operator()</a>, <a href="#ade1c6d00759ad30078d9f5a51cbfc009">operator()</a>, <a href="#a41c844f5b9078d32e11a14b45b6f5c2d">operator()</a>, <a href="#a718f5fc73955ee4e43228ede93284235">operator()</a>, <a href="#adf1a3bedb011096b811a8b1207cc6694">operator()</a>, <a href="#aaac51ad3dcaa4b594e4a917c6062e216">operator()</a>, <a href="#a5d64467d16ca8ee73bafaf59414cfdd4">operator()</a>, <a href="#a59f1ab15f6ef3d9641ae8588f2c717d5">operator()</a>, <a href="#a610ca0d0e464f23b2e2c2defbd3bd6ec">operator()</a>, <a href="#aecc17206d985451fd07d62880158be9f">operator()</a>, <a href="#a28500ffefba81a29ea7a76a60c1f7d1b">operator()</a>, <a href="#a806029951b075fcd8c430498bd0f2375">operator()</a>, <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>, <a href="#a03c8e02e7e2e9e5dbb2bb8a1fe27b37d">operator()</a>, <a href="#a6d1352434f601deaf1e191f3db0c3404">operator()</a>, <a href="#a32d07320992840cbb96459bd77cd9608">operator()</a>, <a href="#a5a4e5f6aea094c66e6d152fd2962a128">operator()</a>, <a href="#a1b9a4f0271ea62f929b5072a2ac109b0">operator()</a>, <a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">operator()</a>, <a href="#ad66d381b7f99cc5e565063f73854573f">operator()</a>, <a href="#a09c4ad96f7c5f045fbd0547b623f27bf">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a>, <a href="#a41aaa90a6a3c9ec728048cbdb927c7ae">operator()</a>, <a href="#abfe122c272f139d98332b7630945da0f">operator()</a>, <a href="#a41d834c86e9800452bd5d86ebe4a475a">operator()</a>, <a href="#a57335dd50faa9dc7ee78f420dc35efe3">operator()</a>, <a href="#ae73d9be71f9eba3b4aab19bb46c69fc8">operator()</a>, <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>, <a href="#ae8521140810fce270f060a974a5c223e">operator()</a>, <a href="#a4ef9e93a2e68b39e52f7e8ec9595c856">operator()</a> and <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>.
</div>
</div>

### m&#95;hierarchyLevel {#a06dc0a09a39ba955dae7c97895cbe4f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LatexDocVisitor::m_hierarchyLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00183">183</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06dc0a09a39ba955dae7c97895cbe4f7">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a06dc0a09a39ba955dae7c97895cbe4f7">m_hierarchyLevel</a>;</span></span></div>

</div>


Referenced by <a href="#ad07ff64f82e760b771d8daec21ce731f">getSectionName</a> and <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>.
</div>
</div>

### m&#95;indentLevel {#a1720fe93e9affacc38bdac0cedded094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LatexDocVisitor::m_indentLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00199">199</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1720fe93e9affacc38bdac0cedded094">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a1720fe93e9affacc38bdac0cedded094">m_indentLevel</a> = 0;</span></span></div>

</div>


Referenced by <a href="#af2255727c9f6bc6589488bbde0d9a007">decIndentLevel</a>, <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>, <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a> and <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>.
</div>
</div>

### m&#95;insideItem {#ad17375904f6fa3f97fedbca5b62a792d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::m_insideItem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00180">180</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad17375904f6fa3f97fedbca5b62a792d">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad17375904f6fa3f97fedbca5b62a792d">m_insideItem</a>;</span></span></div>

</div>


Referenced by <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>, <a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">operator()</a>, <a href="#a4336aa37be77360c412335358cd88b46">operator()</a>, <a href="#a806029951b075fcd8c430498bd0f2375">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a> and <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>.
</div>
</div>

### m&#95;insidePre {#aff0c5a00a6699c69258af75bb165b504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LatexDocVisitor::m_insidePre</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00179">179</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff0c5a00a6699c69258af75bb165b504">179</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aff0c5a00a6699c69258af75bb165b504">m_insidePre</a>;</span></span></div>

</div>


Referenced by <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>, <a href="#a41aaa90a6a3c9ec728048cbdb927c7ae">operator()</a>, <a href="#abfe122c272f139d98332b7630945da0f">operator()</a> and <a href="#ae8521140810fce270f060a974a5c223e">operator()</a>.
</div>
</div>

### m&#95;langExt {#aad01fc834451929091fe3a94570c5bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LatexDocVisitor::m_langExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00182">182</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad01fc834451929091fe3a94570c5bc9">182</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aad01fc834451929091fe3a94570c5bc9">m_langExt</a>;</span></span></div>

</div>


Referenced by <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>, <a href="#a41c844f5b9078d32e11a14b45b6f5c2d">operator()</a> and <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>.
</div>
</div>

### m&#95;lcg {#af66c81b21081522e34b6468b4f3c4478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatexCodeGenerator&amp; LatexDocVisitor::m_lcg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00178">178</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af66c81b21081522e34b6468b4f3c4478">178</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/latexcodegenerator">LatexCodeGenerator</a> &amp;<a href="#af66c81b21081522e34b6468b4f3c4478">m_lcg</a>;</span></span></div>

</div>


Referenced by <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#aa2c5d961b9ad326122481acacc033172">isTableNested</a>, <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a> and <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>.
</div>
</div>

### m&#95;listItemInfo {#aa5ab6acd044e40df6d6450590095dd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatexListItemInfo LatexDocVisitor::m_listItemInfo[maxIndentLevels]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00206">206</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5ab6acd044e40df6d6450590095dd2b">206</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/latexdocvisitor/latexlistiteminfo">LatexListItemInfo</a> <a href="#aa5ab6acd044e40df6d6450590095dd2b">m_listItemInfo</a>[<a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a>];</span></span></div>

</div>


Referenced by <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a>, <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a> and <a href="#ad66d381b7f99cc5e565063f73854573f">operator()</a>.
</div>
</div>

### m&#95;t {#ad463a87f9dce2096d73547227047271c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream&amp; LatexDocVisitor::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00176">176</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad463a87f9dce2096d73547227047271c">176</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#ad463a87f9dce2096d73547227047271c">m_t</a>;</span></span></div>

</div>


Referenced by <a href="#aad8000cb1d166d1985a8e2b306d2b1c6">endDiaFile</a>, <a href="#a44fa6c956b97a5ca373a9c6d361f9658">endDotFile</a>, <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="#a9ddf71d12334619ccd9ed44cec08e258">endMscFile</a>, <a href="#ae69b08d5d7cf891ffcc6ce599b68ed80">endPlantUmlFile</a>, <a href="#a0b6e670e04f51e9bb0a163326fe8ffab">escapeMakeIndexChars</a>, <a href="#a99fd1bd50877a6c36721da21a2a2eb1e">filter</a>, <a href="#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor</a>, <a href="#a81236a6d08e29da34ec95bcc10aea214">operator()</a>, <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a>, <a href="#a1ce72f4abb11b66d697afdff04056222">operator()</a>, <a href="#a7da6db1950d1eab0b3aad3535af34d9b">operator()</a>, <a href="#a60686dad3b83395d42770683c5e1e6a9">operator()</a>, <a href="#ac8faec71974f8983332aa0e11a946276">operator()</a>, <a href="#a4d33c93c8ef27f3d559511b25c4e56b5">operator()</a>, <a href="#a39ce90cc4d05a3748cffe6519957ba59">operator()</a>, <a href="#a5ed16c660428cb0d22236e25f0cb5a1f">operator()</a>, <a href="#ac11bc06b22732d6e550dc8382badd38f">operator()</a>, <a href="#af6337e5be9b60d5be63ba2a7f4bd9a31">operator()</a>, <a href="#a4bfb163f58dc53862618450a55e41979">operator()</a>, <a href="#a4336aa37be77360c412335358cd88b46">operator()</a>, <a href="#ad0e9d73e9adb9aac3732cee17a4c67db">operator()</a>, <a href="#a2f950e3e8499edfa159d43d35ebda0b0">operator()</a>, <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>, <a href="#a2a1e6cedc141edf8abf82cfe721eb59a">operator()</a>, <a href="#add62a038409ef396c163d584412289cc">operator()</a>, <a href="#a72863fffe73366c27a00f8fdbc6395d4">operator()</a>, <a href="#a678591cbca0c1070b7a8803d3c5541c7">operator()</a>, <a href="#a28b453c4eabdf03f5d1b690a307d9c4e">operator()</a>, <a href="#ade1c6d00759ad30078d9f5a51cbfc009">operator()</a>, <a href="#a41c844f5b9078d32e11a14b45b6f5c2d">operator()</a>, <a href="#a718f5fc73955ee4e43228ede93284235">operator()</a>, <a href="#a5d64467d16ca8ee73bafaf59414cfdd4">operator()</a>, <a href="#a28500ffefba81a29ea7a76a60c1f7d1b">operator()</a>, <a href="#a806029951b075fcd8c430498bd0f2375">operator()</a>, <a href="#aca420728eca4e37947593db6a96eadd3">operator()</a>, <a href="#a5a4e5f6aea094c66e6d152fd2962a128">operator()</a>, <a href="#a1b9a4f0271ea62f929b5072a2ac109b0">operator()</a>, <a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">operator()</a>, <a href="#ad18160e3390b23baf7afb39d4954c928">operator()</a>, <a href="#ad66d381b7f99cc5e565063f73854573f">operator()</a>, <a href="#a09c4ad96f7c5f045fbd0547b623f27bf">operator()</a>, <a href="#a6f8aff45c8c934cda5be07107de10c77">operator()</a>, <a href="#a41aaa90a6a3c9ec728048cbdb927c7ae">operator()</a>, <a href="#abfe122c272f139d98332b7630945da0f">operator()</a>, <a href="#ae73d9be71f9eba3b4aab19bb46c69fc8">operator()</a>, <a href="#a729fe6d8301bb25f3785b4e4466fccd5">operator()</a>, <a href="#ae8521140810fce270f060a974a5c223e">operator()</a>, <a href="#a330c52431e7c540fcea7901e74c70da7">operator()</a>, <a href="#afe30a1c1a560e4a85206dc7623a17dc4">startDiaFile</a>, <a href="#aa197e546b10f737e78020b97fdf23cb9">startDotFile</a>, <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>, <a href="#aeef2a244f24ea46106204e063fae5273">startMscFile</a>, <a href="#aa42bf16168d38b6ac210c3f17bef7510">startPlantUmlFile</a>, <a href="#a168f142f518c0734df4301ca492859d1">writeDiaFile</a>, <a href="#a6df0c1870c76f22f1b82744aaeeaf613">writeEndTableCommand</a>, <a href="#ada18505ac90bb92f4ce279d503dba853">writeMscFile</a>, <a href="#a92275d99afc832afc51d7e0deec3afe6">writePlantUMLFile</a> and <a href="#a6de1c60f1310fa0be7c9a16eb2ce760d">writeStartTableCommand</a>.
</div>
</div>

### m&#95;tableStateStack {#a202aa23a61e3b8e40132aaae748078a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::stack&lt;TableState&gt; LatexDocVisitor::m_tableStateStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00195">195</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a202aa23a61e3b8e40132aaae748078a0">195</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::stack&lt;TableState&gt; <a href="#a202aa23a61e3b8e40132aaae748078a0">m_tableStateStack</a>; </span><span class="doxyHighlightComment">// needed for nested tables</span></span></div>

</div>


Referenced by <a href="#a64ded8946bcb677799616596e18244d4">addRowSpan</a>, <a href="#a8d2ed858c16eee5436001b357fb9930c">currentColumn</a>, <a href="#a3781c16868efac71398e5436f519ee39">firstRow</a>, <a href="#abdf9b003ba87f85ee86bddb73602d302">inColSpan</a>, <a href="#a9168d2796d2b37ba82cc27bb4918c6a1">inRowSpan</a>, <a href="#aaa24e4fc93db1df3bcd28753025254d6">insideTable</a>, <a href="#affb8062141ed5b09ba687d473f2886fe">numCols</a>, <a href="#af52701ab88ccd1fdf7432e3c689a2a16">popTableState</a>, <a href="#ae5dab1f77dba06bcffb8898af56f3606">pushTableState</a>, <a href="#a1e6bce68fe8f4b6a5e70026aaed88a81">rowSpans</a>, <a href="#a24b90355494bec87ba2cabf71e632c16">setCurrentColumn</a>, <a href="#a1d60974e8552037cb12627d282df3392">setFirstRow</a>, <a href="#a555cd968fcfe52155db2e225786e99c6">setInColSpan</a>, <a href="#af1e7a18a592b5ce218b3552b8012d49d">setInRowSpan</a> and <a href="#a6c0d2ce4dcc1f80ad35725935d062ed6">setNumCols</a>.
</div>
</div>

### m&#95;texOrPdf {#a75c523e35f12d34505bac42b4661e621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TexOrPdf LatexDocVisitor::m_texOrPdf = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">TexOrPdf::NO</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00184">184</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75c523e35f12d34505bac42b4661e621">184</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492">TexOrPdf</a> <a href="#a75c523e35f12d34505bac42b4661e621">m_texOrPdf</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">TexOrPdf::NO</a>;</span></span></div>

</div>


Referenced by <a href="#a2a7db7045021961de35c39ea7e1deb40">endLink</a>, <a href="#a60686dad3b83395d42770683c5e1e6a9">operator()</a>, <a href="#a0f4bc9b34cb6497194f1adf2e01a1f6a">operator()</a> and <a href="#a7622ffaad8b1168ffc837eae842d6c53">startLink</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### maxIndentLevels {#a2a2cff2081185257e7258819f96fbe4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int LatexDocVisitor::maxIndentLevels = 13</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#l00198">198</a> of file <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a2cff2081185257e7258819f96fbe4b">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a2a2cff2081185257e7258819f96fbe4b">maxIndentLevels</a> = 13;</span></span></div>

</div>


Referenced by <a href="#a119bb54272cc6a3dbe0c01ee6f60e9a3">incIndentLevel</a>, <a href="#a25c6d887a6677aa800a1d928c9455df3">indentLevel</a>, <a href="#a8b9b92e158f2ae2ccccd408ff5201e50">operator()</a> and <a href="#aeabfb2614e026a7579c5dadeb5c328c3">operator()</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp">latexdocvisitor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h">latexdocvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
