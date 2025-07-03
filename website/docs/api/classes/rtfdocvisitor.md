---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/rtfdocvisitor
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `RTFDocVisitor` Class Reference

<p>Concrete visitor implementation for RTF output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class RTFDocVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">src/rtfdocvisitor.h</a>&gt;
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b0a4193b8ba939843a29f3d67acaa9">RTFDocVisitor</a> (TextStream &amp;t, OutputCodeList &amp;ci, const QCString &amp;langExt, int hierarchyLevel=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af039aed5400d69cb1776431f44f90360">operator()</a> (const DocWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23778040c53c76ac927398e0e728ffb5">operator()</a> (const DocLinkedWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af154c4b8688beaef882211c40763fec3">operator()</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8123582499bf0458dc938ff66c4724e7">operator()</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc374c79a2895d83e349ffc76358209e">operator()</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f1097897a6deaeffd0ca3ca9e5c811">operator()</a> (const DocURL &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561b27cc775aaa5f6db73f1d33099176">operator()</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a485c2a5796bb5e12497c7ab9d65d1f8c">operator()</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3beab942bf46b1f903ac30ac39a10d2">operator()</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> (const DocVerbatim &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2993bfecac33a60da6408f79586b7da2">operator()</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af0a6415a019a1051dda0dd4d56dbef">operator()</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6822c7504330f96cc764e333589e7a">operator()</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bbffb38b5bccd84b4c291c4af27591f">operator()</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">operator()</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bd1ead75c76578b08ef7a5c49a4d70">operator()</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74283afcc3656534bef009b917a9f525">operator()</a> (const DocAutoList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a> (const DocAutoListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ff0afe39093628cd96d42dfce7515f">operator()</a> (const DocPara &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a> (const DocRoot &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a> (const DocSimpleSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac06a6ad599b271d16500b483b5912679">operator()</a> (const DocTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a> (const DocSimpleList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add264d5a56e09e76ec274af99af747d2">operator()</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b1ef4b308483fcf725cef8081e5849">operator()</a> (const DocSection &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a> (const DocHtmlList &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a> (const DocHtmlListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4eb63da29c3a07a95f240dcd9a143e">operator()</a> (const DocHtmlDescList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c5c194fc2579df52204eb00134c6bf">operator()</a> (const DocHtmlDescTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a> (const DocHtmlDescData &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c72fc623be48174c003bb47c523d6c1">operator()</a> (const DocHtmlTable &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f9db74256f38af950876f6863a1dd4">operator()</a> (const DocHtmlCaption &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5ce880ef222be6eeb6eea7e12b78b8">operator()</a> (const DocHtmlRow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c61ff58fa9f747fc2b971c689a09ff">operator()</a> (const DocHtmlCell &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1d0bebcd0570b99692349a8268122d9">operator()</a> (const DocInternal &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af199af5695c344c4730378ecfce43079">operator()</a> (const DocHRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02dc45654c7f54372b2306e37d8cd3f">operator()</a> (const DocHtmlSummary &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a> (const DocHtmlDetails &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae81723bf98cc11856ec916852cf089">operator()</a> (const DocHtmlHeader &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247c4506996a3a6d71827322614efb30">operator()</a> (const DocImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33dd9566336e1d3c40ea2dadff6d8676">operator()</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732b1d92dfc620e4cb221bbb32fade22">operator()</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8991833ac99826e07a993af4b58b0c4b">operator()</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3ac1fc0fb8cb8218beb807d0a820d1">operator()</a> (const DocPlantUmlFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4d703a5dab4d351818ffdf686dccd1">operator()</a> (const DocLink &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa547c49d64497e4774d3405b9cdcf7f1">operator()</a> (const DocRef &amp;ref)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ccfb63934cef53d78e3e6641be084b5">operator()</a> (const DocSecRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a> (const DocSecRefList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a> (const DocParamSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb7edc62cad5a541849845d2bfe030e9">operator()</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a> (const DocXRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db5842a73ae3417854ddcd60b0e1d12">operator()</a> (const DocInternalRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc9aeca576eb153d222793bc3227d07">operator()</a> (const DocText &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a> (const DocHtmlBlockQuote &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc08a91c8127a3befd90c2f5f01ca4b">operator()</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d70bea0fa796acb266fcfda801cfbb9">operator()</a> (const DocParBlock &amp;)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a> (const T &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02ac65b43b4122de86989aed6d356df1">filter</a> (const QCString &amp;str, bool verbatim=FALSE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a> (const QCString &amp;ref)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a> (const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9b164379ca75fc12d225af36eac95aa">getListTable</a> (const int id)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a> (const QCString &amp;name, bool isTypeRTF, bool hasCaption, bool inlineImage=FALSE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a> (bool isTypeRTF, bool hasCaption, bool inlineImage=FALSE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a> (const QCString &amp;fileName, bool hasCaption, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ea7715bb9b143ed6ae91770903188b">writeDotFile</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a> (const QCString &amp;fileName, bool hasCaption, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47dad14278a28560cae8ec1a900fda24">writeMscFile</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37a4b0291dcc41a9b1072757d344b546">writeDiaFile</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aaf0de986f15251aaa6221d226ab55a">writePlantUMLFile</a> (const QCString &amp;fileName, bool hasCaption)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4948ccf2a491663a91479243554243cd">m_ci</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/rtfdocvisitor/rtflistiteminfo">RTFListItemInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[maxIndentLevels]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a> = 13</td>
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

<p>Concrete visitor implementation for RTF output.</p>

<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RTFDocVisitor() {#a67b0a4193b8ba939843a29f3d67acaa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTFDocVisitor::RTFDocVisitor (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ci, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; langExt, int hierarchyLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67b0a4193b8ba939843a29f3d67acaa9">70</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a67b0a4193b8ba939843a29f3d67acaa9">RTFDocVisitor::RTFDocVisitor</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ci,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;langExt, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> hierarchyLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>(t), <a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>(ci), <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a>(langExt), <a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a>(hierarchyLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>, <a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a>, <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a> and <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#af039aed5400d69cb1776431f44f90360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af039aed5400d69cb1776431f44f90360">119</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocWord)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(w.<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.</p>

</div>
</div>

### operator()() {#a23778040c53c76ac927398e0e728ffb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23778040c53c76ac927398e0e728ffb5">127</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocLinkedWord)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">ref</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">file</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">ref</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">DocLinkedWord::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">DocLinkedWord::file</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">DocLinkedWord::ref</a>, <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a> and <a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">DocLinkedWord::word</a>.</p>

</div>
</div>

### operator()() {#af154c4b8688beaef882211c40763fec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af154c4b8688beaef882211c40763fec3">137</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocWhiteSpace)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">DocWhiteSpace::chars</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> and <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a8123582499bf0458dc938ff66c4724e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8123582499bf0458dc938ff66c4724e7">152</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocSymbol)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9e02cf0591dcb069b71e93f3e827a36c">rtf</a>(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"RTF: non supported HTML-entity found: {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().html(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9e02cf0591dcb069b71e93f3e827a36c">HtmlEntityMapper::rtf</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">DocSymbol::symbol</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#adc374c79a2895d83e349ffc76358209e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc374c79a2895d83e349ffc76358209e">168</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocEmoji)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val1 = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'x'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">          val1 = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">          val = 55296 + ( ( val1 - 65536 ) &amp; 1047552 ) / 1024 - 0x10000;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\u"</span><span class="doxyHighlight"> &lt;&lt; val &lt;&lt; </span><span class="doxyHighlightStringLiteral">"?"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">          val = 56320 + ( ( val1 - 65536 ) &amp; 1023 ) - 65536 ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\u"</span><span class="doxyHighlight"> &lt;&lt; val &lt;&lt; </span><span class="doxyHighlightStringLiteral">"?"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">          val = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'2'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'3'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'4'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'5'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'6'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'7'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'8'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">          val = val * 16 + *p - </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'b'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'c'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'d'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'e'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'f'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">          val = val * 16 + *p - </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> + 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">DocEmoji::index</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">DocEmoji::name</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">EmojiEntityMapper::unicode</a>.</p>

</div>
</div>

### operator()() {#a74f1097897a6deaeffd0ca3ca9e5c811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp; u)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 210 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74f1097897a6deaeffd0ca3ca9e5c811">210</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocURL)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RTF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\field "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"{\\*\\fldinst "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{ HYPERLINK \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (u.<a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">isEmail</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"mailto:"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt;  </span><span class="doxyHighlightStringLiteral">"\" }"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt;   </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"{\\fldrslt "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{\\cs37\\ul\\cf2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt;     </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\f2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">DocURL::isEmail</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">DocURL::url</a>.</p>

</div>
</div>

### operator()() {#a561b27cc775aaa5f6db73f1d33099176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a561b27cc775aaa5f6db73f1d33099176">240</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocLineBreak)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#a485c2a5796bb5e12497c7ab9d65d1f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a485c2a5796bb5e12497c7ab9d65d1f8c">248</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocHorRuler)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\pard\\widctlpar\\brdrb\\brdrs\\brdrw5\\brsp20 \\adjustright \\par}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#af3beab942bf46b1f903ac30ac39a10d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 256 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3beab942bf46b1f903ac30ac39a10d2">256</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocStyleChange)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\b "</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\strike "</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\ul "</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\i "</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\f2 "</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\sub "</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\super "</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\qc "</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\sub "</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\i "</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>:  </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>: </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">DocStyleChange::enable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>.</p>

</div>
</div>

### operator()() {#a101e1d1d08453e6a606f9f8652a6cc73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 319 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a101e1d1d08453e6a606f9f8652a6cc73">319</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocVerbatim)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang = <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// explicit language setting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    lang = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(lang).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">context</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">                                    <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(STRIP_CODE_COMMENTS),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">                                    s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">isExample</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "\\par\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\f2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "\\par\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* nothing */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dotindex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">        fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d%s"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/inline_dotgraph_"</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">            dotindex++,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">".dot"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">        std::ofstream file = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> stext = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">          file.write( stext.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), stext.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">          file.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>(fileName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mscindex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">        baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d%s"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/inline_mscgraph_"</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">            mscindex++,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">".msc"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">        std::ofstream file = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(baseName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> text = </span><span class="doxyHighlightStringLiteral">"msc {"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">        text+=s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">        text+=</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">        file.write( text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), text.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">        file.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a>(baseName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> rtfOutput = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">                       rtfOutput,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">                       s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">engine</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a8aaf0de986f15251aaa6221d226ab55a">writePlantUMLFile</a>(baseName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">DocVerbatim::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">DocVerbatim::engine</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">DocVerbatim::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">DocVerbatim::isExample</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">DocVerbatim::language</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">DocVerbatim::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">DocVerbatim::type</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>, <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>, <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>, <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a>, <a href="#a8aaf0de986f15251aaa6221d226ab55a">writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>.</p>

</div>
</div>

### operator()() {#a2993bfecac33a60da6408f79586b7da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp; anc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 442 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2993bfecac33a60da6408f79586b7da2">442</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;anc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocAnchor)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">    anchor+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    anchor+=</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">    anchor+=anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bkmkstart "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(anchor) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bkmkend "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(anchor) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">DocAnchor::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">DocAnchor::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.</p>

</div>
</div>

### operator()() {#ac315ddf81b73a005764278a3c190d1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp; inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 464 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac315ddf81b73a005764278a3c190d1a4">464</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;inc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocInclude)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                                           langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">                                           fd.get(),   </span><span class="doxyHighlightComment">// fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">                                           -1,    </span><span class="doxyHighlightComment">// start line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">                                           -1,    </span><span class="doxyHighlightComment">// end line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>   </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">                                           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,  </span><span class="doxyHighlightComment">// inlineFragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">                                       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>().<a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a>(<a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>()==<a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                                         inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">                                        );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">DocInclude::blockId</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">DocInclude::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">DocInclude::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">DocInclude::extension</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">DocInclude::file</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">DocInclude::isExample</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>, <a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">DocInclude::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">DocInclude::text</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">DocInclude::trimLeft</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">DocInclude::type</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a> and <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>.</p>

</div>
</div>

### operator()() {#a75e708a4ea1b27587678f424211b8b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp; op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 552 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75e708a4ea1b27587678f424211b8b62">552</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;op)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocIncOperator: type=%d first=%d, last=%d text='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    op.type(),op.isFirst(),op.isLast(),qPrint(op.text()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocIncOperator)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locLangExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locLangExt.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) locLangExt = <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(locLangExt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">isFirst</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"CodeExample"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">type</a>()!=<a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_ptr&lt;FileDef&gt; fd = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">        fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(locLangExt).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>,op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">context</a>(),op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">isExample</a>(),op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">                                        fd.get(),     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">line</a>(),    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">showLineNo</a>()  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">                                       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">isLast</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">DocIncOperator::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">DocIncOperator::exampleFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">DocIncOperator::includeFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">DocIncOperator::isExample</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">DocIncOperator::isFirst</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">DocIncOperator::isLast</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">DocIncOperator::line</a>, <a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">DocVisitor::popHidden</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">DocVisitor::pushHidden</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">DocIncOperator::showLineNo</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">DocIncOperator::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">DocIncOperator::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">DocIncOperator::type</a>.</p>

</div>
</div>

### operator()() {#a4af0a6415a019a1051dda0dd4d56dbef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp; f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 614 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4af0a6415a019a1051dda0dd4d56dbef">614</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocFormula)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bDisplay = !f.<a href="/web-doxygen/docs/api/classes/docformula/#a6efb81a9620e6fad264a0c896f2ca7cb">isInline</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bDisplay)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard\\plain"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\qc"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{ \\field\\flddirty {\\*\\fldinst  INCLUDEPICTURE \""</span><span class="doxyHighlight"> &lt;&lt; f.<a href="/web-doxygen/docs/api/classes/docformula/#ae693f78dc76e8caf6060cb26fe3b58aa">relPath</a>() &lt;&lt; f.<a href="/web-doxygen/docs/api/classes/docformula/#a639835af31171584bbf72eab82d7f162">name</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".png\" \\\\d \\\\*MERGEFORMAT}{\\fldrslt Image}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bDisplay)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docformula/#a6efb81a9620e6fad264a0c896f2ca7cb">DocFormula::isInline</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docformula/#a639835af31171584bbf72eab82d7f162">DocFormula::name</a> and <a href="/web-doxygen/docs/api/classes/docformula/#ae693f78dc76e8caf6060cb26fe3b58aa">DocFormula::relPath</a>.</p>

</div>
</div>

### operator()() {#aed6822c7504330f96cc764e333589e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 635 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed6822c7504330f96cc764e333589e7a">635</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visit(DocIndexEntry)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\xe \\v "</span><span class="doxyHighlight"> &lt;&lt; i.<a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">entry</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">DocIndexEntry::entry</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> and <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a6bbffb38b5bccd84b4c291c4af27591f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 643 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bbffb38b5bccd84b4c291c4af27591f">643</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a8b41cc5c80471d8cbb6fb7a8bbd55bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp; cite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 647 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">647</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;cite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocCite &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> opt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">option</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noCite()) <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae5f235deff96cbae64d906842654abea">ref</a>(),cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>(),cite.<a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">getText</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noCite()) <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae5f235deff96cbae64d906842654abea">ref</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\b"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(</span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">DocCite::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">DocCite::file</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">DocCite::getText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">DocCite::option</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae5f235deff96cbae64d906842654abea">DocCite::ref</a>, <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a> and <a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">DocCite::target</a>.</p>

</div>
</div>

### operator()() {#a96bd1ead75c76578b08ef7a5c49a4d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp; sep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1425 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96bd1ead75c76578b08ef7a5c49a4d70">1425</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;sep)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; sep.<a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">chars</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">DocSeparator::chars</a> and <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a74283afcc3656534bef009b917a9f525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 675 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74283afcc3656534bef009b917a9f525">675</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocAutoList &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isEnum = l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isCheck = l.<a href="/web-doxygen/docs/api/classes/docautolist/#a1adff5a3fa53eb8bf20d4a1e89851d85">isCheckedList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].type   = </span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!l.<a href="/web-doxygen/docs/api/classes/docautolist/#a1adff5a3fa53eb8bf20d4a1e89851d85">isCheckedList</a>() &amp;&amp; <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>()==0) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a1adff5a3fa53eb8bf20d4a1e89851d85">DocAutoList::isCheckedList</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">DocAutoList::isEnumList</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a39a5bf02292d858e211a2cb3ee3f62c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 693 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a39a5bf02292d858e211a2cb3ee3f62c1">693</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> prevLevel = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocAutoListItem &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((level != prevLevel-1) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      (!(level==prevLevel &amp;&amp; level != 0 &amp;&amp; <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isCheck)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">      (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">  prevLevel= level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"ListEnum"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number &lt;&lt; </span><span class="doxyHighlightStringLiteral">".\\tab "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">itemNumber</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a>: </span><span class="doxyHighlightComment">// unchecked</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#ac9b164379ca75fc12d225af36eac95aa">getListTable</a>(2) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>: </span><span class="doxyHighlightComment">// checked with x</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>: </span><span class="doxyHighlightComment">// checked with X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#ac9b164379ca75fc12d225af36eac95aa">getListTable</a>(3) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#ac9b164379ca75fc12d225af36eac95aa">getListTable</a>(1) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(li);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#ac9b164379ca75fc12d225af36eac95aa">getListTable</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">DocAutoListItem::itemNumber</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af6ff0afe39093628cd96d42dfce7515f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp; p)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 733 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6ff0afe39093628cd96d42dfce7515f">733</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocPara &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">      !p.<a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">isLast</a>() &amp;&amp;            </span><span class="doxyHighlightComment">// omit &lt;p&gt; for last paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">      !(p.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>() &amp;&amp;           </span><span class="doxyHighlightComment">// and for parameters &amp; sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get_if&lt;DocParamSect&gt;(p.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">DocPara::isLast</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a07acb7803948c3811f88d4efa00587a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 750 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07acb7803948c3811f88d4efa00587a4">750</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocRoot &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (r.<a href="/web-doxygen/docs/api/classes/docroot/#a65e7fbdda6784c769c6333adc1fe629c">indent</a>()) <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[</span><span class="doxyHighlightStringLiteral">"BodyText"</span><span class="doxyHighlight">].reference() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> &amp;&amp; !r.<a href="/web-doxygen/docs/api/classes/docroot/#a32e7c733315cae51633409dfaaf6020f">singleLine</a>()) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (r.<a href="/web-doxygen/docs/api/classes/docroot/#a65e7fbdda6784c769c6333adc1fe629c">indent</a>()) <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a65e7fbdda6784c769c6333adc1fe629c">DocRoot::indent</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a32e7c733315cae51633409dfaaf6020f">DocRoot::singleLine</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa17fa64bc141c519b0b24e0a475ab1e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 763 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa17fa64bc141c519b0b24e0a475ab1e1">763</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocSimpleSect &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// start desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "{\\b "; // start bold</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[</span><span class="doxyHighlightStringLiteral">"Heading5"</span><span class="doxyHighlight">].reference() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSeeAlso(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturns(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVersion(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSince(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDate(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNote(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trWarning(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPrecondition(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPostcondition(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCopyright(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInvariant(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRemarks(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAttention(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trImportant(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>()!=<a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a> &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>()!=<a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end bold</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\s17 \\sa60 \\sb30\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end bold</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>()!=<a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a> &amp;&amp; s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>()!=<a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end DescContinue</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">DocSimpleSect::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">DocSimpleSect::type</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>, <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>.</p>

</div>
</div>

### operator()() {#ac06a6ad599b271d16500b483b5912679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 840 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac06a6ad599b271d16500b483b5912679">840</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocTitle &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9bc7acec72efe2239cb6c798855ed08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 847 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9bc7acec72efe2239cb6c798855ed08a">847</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocSimpleSect &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[<a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>()].isEnum = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[<a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>()].isCheck = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#add264d5a56e09e76ec274af99af747d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 861 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add264d5a56e09e76ec274af99af747d2">861</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocSimpleListItem &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"ListBullet"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visitPost(DocSimpleListItem)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">DocSimpleListItem::paragraph</a> and <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>.</p>

</div>
</div>

### operator()() {#a89b1ef4b308483fcf725cef8081e5849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 876 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89b1ef4b308483fcf725cef8081e5849">876</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocSection &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bkmkstart "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(s.<a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">file</a>())+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bkmkend "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(s.<a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">file</a>())+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{{"</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// start section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> heading;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = std::min(s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>()+2+<a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a>,4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (level &lt;= 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">    level = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  heading.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"Heading%d"</span><span class="doxyHighlight">,level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set style</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[heading.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].reference() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// make table of contents entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\par"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\tc\\tcl"</span><span class="doxyHighlight"> &lt;&lt; level &lt;&lt; </span><span class="doxyHighlightStringLiteral">" \\v "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par}\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">DocSection::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">DocSection::file</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">DocSection::level</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">DocSection::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a2851bbf082cd6f2a85d6c9fc7a1050c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 910 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">910</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlList &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isEnum = l.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isCheck = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].type   = </span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : l.<a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].type = opt.value[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"start"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">DocHtmlList::attribs</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">DocHtmlList::type</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a63f63207a160e4e99a4c2dd5b55734c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 939 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63f63207a160e4e99a4c2dd5b55734c8">939</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlListItem &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].isEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : l.<a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"ListEnum"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6e984969913a70c9b67da588f68b8a14">integerToAlpha</a>(<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6e984969913a70c9b67da588f68b8a14">integerToAlpha</a>(<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'i'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>(<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'I'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>(<a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".\\tab "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[level].number++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"ListBullet"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visitPost(DocHtmlListItem)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">DocHtmlListItem::attribs</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6e984969913a70c9b67da588f68b8a14">integerToAlpha</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a8d4eb63da29c3a07a95f240dcd9a143e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 993 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d4eb63da29c3a07a95f240dcd9a143e">993</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlDescList &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "{\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; rtf_Style_Reset &lt;&lt; getStyle("ListContinue");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_lastIsPara=FALSE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(dl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "}\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "\\par\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_lastIsPara=TRUE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae0c5c194fc2579df52204eb00134c6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp; dt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1006 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0c5c194fc2579df52204eb00134c6bf">1006</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;dt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlDescTitle &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "\\par\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "{\\b ";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[</span><span class="doxyHighlightStringLiteral">"Heading5"</span><span class="doxyHighlight">].reference() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(dt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a85db1985a82081ef9ab2e5a25c450f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp; dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1020 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85db1985a82081ef9ab2e5a25c450f28">1020</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlDescData &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a3c72fc623be48174c003bb47c523d6c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1033 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c72fc623be48174c003bb47c523d6c1">1033</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlTable &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c = std::get&lt;DocHtmlCaption&gt;(*t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard \\qc \\b"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bkmkstart "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>())+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\bkmkend "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>())+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{Table \\field\\flddirty{\\*\\fldinst { SEQ Table \\\\*Arabic }}{\\fldrslt {\\noproof 1}} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard\\plain\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">DocHtmlCaption::anchor</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">DocHtmlTable::caption</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">DocHtmlCaption::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a44f9db74256f38af950876f6863a1dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1057 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44f9db74256f38af950876f6863a1dd4">1057</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlCaption &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a7a5ce880ef222be6eeb6eea7e12b78b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1064 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a5ce880ef222be6eeb6eea7e12b78b8">1064</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlRow &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> columnWidth=r.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac8411351d60c38dd457f0d118b1a3ab3">numCells</a>()&gt;0 ? <a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a6329c1ef4afd935bc3ef8065583fed30">rtf_pageWidth</a>/r.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac8411351d60c38dd457f0d118b1a3ab3">numCells</a>() : 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\trowd \\trgaph108\\trleft-108"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrt\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrl\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrb\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrr\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrh\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrv\\brdrs\\brdrw10 \n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;r.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac8411351d60c38dd457f0d118b1a3ab3">numCells</a>();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (r.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">isHeading</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\clcbpat16"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// set cell shading to light grey (color 16 in the clut)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\clvertalt\\clbrdrt\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\clbrdrl\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\clbrdrb\\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\clbrdrr \\brdrs\\brdrw10 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\cltxlrtb "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\cellx"</span><span class="doxyHighlight"> &lt;&lt; ((i+1)*columnWidth) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard \\widctlpar\\intbl\\adjustright\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard \\widctlpar\\intbl\\adjustright\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\row }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">DocHtmlRow::isHeading</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac8411351d60c38dd457f0d118b1a3ab3">DocHtmlRow::numCells</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a6329c1ef4afd935bc3ef8065583fed30">rtf_pageWidth</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a70c61ff58fa9f747fc2b971c689a09ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1098 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70c61ff58fa9f747fc2b971c689a09ff">1098</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlCell &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cell }"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa1d0bebcd0570b99692349a8268122d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1109 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1d0bebcd0570b99692349a8268122d9">1109</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af199af5695c344c4730378ecfce43079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp; href)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1115 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af199af5695c344c4730378ecfce43079">1115</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;href)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHRef &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RTF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// when starting with # so a local link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cite;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">      cite = href.<a href="/web-doxygen/docs/api/classes/dochref/#aa4e295c3ed9f05b818f7ae74ee6f34a0">file</a>() + </span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight"> + href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\field "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{\\*\\fldinst "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"{ HYPERLINK \\\\l \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(cite) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"}{}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{\\fldrslt "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"{\\cs37\\ul\\cf2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\field "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"{\\*\\fldinst "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"{ HYPERLINK \""</span><span class="doxyHighlight"> &lt;&lt; href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"}{}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{\\fldrslt "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"{\\cs37\\ul\\cf2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\f2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(href);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RTF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt;     </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dochref/#aa4e295c3ed9f05b818f7ae74ee6f34a0">DocHRef::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">DocHRef::url</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae02dc45654c7f54372b2306e37d8cd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1164 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae02dc45654c7f54372b2306e37d8cd3f">1164</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\b "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\\par "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#acc6c497f52cf55d67723f21ec2a97c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1172 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc6c497f52cf55d67723f21ec2a97c6b">1172</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlDetails &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> summary = d.<a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">summary</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*summary);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// start desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">DocHtmlDetails::summary</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#adae81723bf98cc11856ec916852cf089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp; header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1195 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adae81723bf98cc11856ec916852cf089">1195</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlHeader &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// start section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> heading;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level = std::clamp(header.<a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">level</a>()+<a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a>,<a href="/web-doxygen/docs/api/classes/sectiontype/#ab44dce28d2b68c6514acbe2415a8a4d7">SectionType::MinLevel</a>,<a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">  heading.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"Heading%d"</span><span class="doxyHighlight">,level);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set style</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[heading.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()].reference();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// make open table of contents entry that will be closed in visitPost method</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\tc\\tcl"</span><span class="doxyHighlight"> &lt;&lt; level &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(header);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// close open table of contents entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} \\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">DocHtmlHeader::level</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#ab44dce28d2b68c6514acbe2415a8a4d7">SectionType::MinLevel</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a247c4506996a3a6d71827322614efb30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp; img)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1281 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a247c4506996a3a6d71827322614efb30">1281</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;img)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocImage &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>(img.<a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">name</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>()==<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>, img.<a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">hasCaption</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(img);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(img.<a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>()==<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>, img.<a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">hasCaption</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">DocImage::hasCaption</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">DocImage::isInlineImage</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">DocImage::name</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">DocImage::Rtf</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">DocImage::type</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a33dd9566336e1d3c40ea2dadff6d8676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1290 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33dd9566336e1d3c40ea2dadff6d8676">1290</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocDotFile &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a> and <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>.</p>

</div>
</div>

### operator()() {#a732b1d92dfc620e4cb221bbb32fade22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1298 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a732b1d92dfc620e4cb221bbb32fade22">1298</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocMscFile &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a> and <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a>.</p>

</div>
</div>

### operator()() {#a8991833ac99826e07a993af4b58b0c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1307 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8991833ac99826e07a993af4b58b0c4b">1307</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocDiaFile &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a37a4b0291dcc41a9b1072757d344b546">writeDiaFile</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a> and <a href="#a37a4b0291dcc41a9b1072757d344b546">writeDiaFile</a>.</p>

</div>
</div>

### operator()() {#a4f3ac1fc0fb8cb8218beb807d0a820d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1316 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f3ac1fc0fb8cb8218beb807d0a820d1">1316</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocPlantUmlFile &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> rtfOutput = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string inBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),inBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">                       rtfOutput,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),inBuf.c_str(),<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8aaf0de986f15251aaa6221d226ab55a">writePlantUMLFile</a>(baseName, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>, <a href="#a8aaf0de986f15251aaa6221d226ab55a">writePlantUMLFile</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>.</p>

</div>
</div>

### operator()() {#a9a4d703a5dab4d351818ffdf686dccd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp; lnk)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1331 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a4d703a5dab4d351818ffdf686dccd1">1331</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;lnk)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocLink &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>(lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">ref</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">file</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(lnk);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>(lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">ref</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">DocLink::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">DocLink::file</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">DocLink::ref</a>, <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa547c49d64497e4774d3405b9cdcf7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1340 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa547c49d64497e4774d3405b9cdcf7f1">1340</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocRef &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// when ref.isSubPage()==TRUE we use ref.file() for HTML and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// ref.anchor() for LaTeX/RTF</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">isSubPage</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">hasLinkText</a>()) <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">targetTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; " ";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">DocRef::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">DocRef::file</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">DocRef::hasLinkText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">DocRef::isSubPage</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">DocRef::ref</a>, <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">DocRef::targetTitle</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a3ccfb63934cef53d78e3e6641be084b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1361 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ccfb63934cef53d78e3e6641be084b5">1361</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocSecRefItem &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4fcb960f7e5b593e8e6c51ea43f66a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1367 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">1367</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocSecRefList &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"LatexTOC"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a6f4df2c3160f09e662393e6a23b2add0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1383 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f4df2c3160f09e662393e6a23b2add0">1383</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocParamSect &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// start param list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "{\\b "; // start bold</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[</span><span class="doxyHighlightStringLiteral">"Heading5"</span><span class="doxyHighlight">].reference() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trParameters(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturnValues(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptions(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trTemplateParameters(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useTable = s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">                  s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">                  s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">                  s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "\\par\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aeb7edc62cad5a541849845d2bfe030e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp; pl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1430 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb7edc62cad5a541849845d2bfe030e9">1430</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;pl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> columnPos[4][5] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">  { { 2, 25, 100, 100, 100 }, </span><span class="doxyHighlightComment">// no inout, no type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">    { 3, 14,  35, 100, 100 }, </span><span class="doxyHighlightComment">// inout, no type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">    { 3, 25,  50, 100, 100 }, </span><span class="doxyHighlightComment">// no inout, type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">    { 4, 14,  35, 55,  100 }, </span><span class="doxyHighlightComment">// inout, type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> config=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocParamList &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a> parentType = <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> *sect = std::get_if&lt;DocParamSect&gt;(pl.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    parentType = sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useTable = parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">                  parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">                  parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">                  parentType==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>()) config+=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>())  config+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\trowd \\trgaph108\\trleft426\\tblind426"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrt\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrl\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrb\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrr\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrh\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\trbrdrv\\brdrs\\brdrw10\\brdrcf15 "</span><span class="doxyHighlight">&lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;columnPos[config][0];i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\clvertalt\\clbrdrt\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\clbrdrl\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\clbrdrb\\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\clbrdrr \\brdrs\\brdrw10\\brdrcf15 "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\cltxlrtb "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"\\cellx"</span><span class="doxyHighlight"> &lt;&lt; (<a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a6329c1ef4afd935bc3ef8065583fed30">rtf_pageWidth</a>*columnPos[config][i+1]/100) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard \\widctlpar\\intbl\\adjustright\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Put in the direction: in/out/in,out if specified.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()!=<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in,out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cell }"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;type : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cell }"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\i "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;param : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,param);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cell }{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;par : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,par);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useTable)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\cell }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//m_t &lt;&lt; "\\pard \\widctlpar\\intbl\\adjustright\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\row }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">DocParamList::direction</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">DocParamSect::hasInOutSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">DocParamSect::hasTypeSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">DocParamList::paragraphs</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">DocParamList::parameters</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">DocParamList::paramTypes</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a6329c1ef4afd935bc3ef8065583fed30">rtf_pageWidth</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a> and <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>.</p>

</div>
</div>

### operator()() {#a7f10a43fc0a35475e9078305d745951f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp; x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1561 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7f10a43fc0a35475e9078305d745951f">1561</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;x)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> anonymousEnum = x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>()==</span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocXRefItem &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// start param list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "{\\b "; // start bold</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[</span><span class="doxyHighlightStringLiteral">"Heading5"</span><span class="doxyHighlight">].reference() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RTF_HYPERLINKS) &amp;&amp; !anonymousEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> refName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">      refName+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">      refName+=</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">      refName+=x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\field "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"{\\*\\fldinst "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{ HYPERLINK  \\\\l \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(refName) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"}{}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"{\\fldrslt "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"{\\cs37\\ul\\cf2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt;     </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">"}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end bold</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(x);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::visitPost(DocXRefItem)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end xref item</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">DocXRefItem::anchor</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">DocXRefItem::file</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">DocXRefItem::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a3db5842a73ae3417854ddcd60b0e1d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1622 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3db5842a73ae3417854ddcd60b0e1d12">1622</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocInternalRef &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">DocInternalRef::anchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">DocInternalRef::file</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9dc9aeca576eb153d222793bc3227d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1632 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9dc9aeca576eb153d222793bc3227d07">1632</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocText &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a022f6eb89bc55b752aeff008e9c9037d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1639 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a022f6eb89bc55b752aeff008e9c9037d">1639</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>(</span><span class="doxyHighlightStringLiteral">"{\\comment RTFDocVisitor::operator()(const DocHtmlBlockQuote &amp;)}\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// start desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>(</span><span class="doxyHighlightStringLiteral">"DescContinue"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// end desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a8e937453cd49cd7e753fa4e9d77d3c38">DBG_RTF</a>, <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a>, <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a0dc08a91c8127a3befd90c2f5f01ca4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1654 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0dc08a91c8127a3befd90c2f5f01ca4b">1654</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a0d70bea0fa796acb266fcfda801cfbb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp; pb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1658 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d70bea0fa796acb266fcfda801cfbb9">1658</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;pb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(pb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> and <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### decIndentLevel() {#a7a1c80a721716cb64c2a82e80cbff047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::decIndentLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a1c80a721716cb64c2a82e80cbff047">110</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7a1c80a721716cb64c2a82e80cbff047">RTFDocVisitor::decIndentLevel</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a>&gt;0) <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a>.</p>


<p>Referenced by <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#add264d5a56e09e76ec274af99af747d2">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a> and <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>.</p>

</div>
</div>

### endLink() {#adc9cf36e3e61b81df2b0ada024366806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::endLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1730 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc9cf36e3e61b81df2b0ada024366806">1730</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adc9cf36e3e61b81df2b0ada024366806">RTFDocVisitor::endLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RTF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}}}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> and <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>.</p>


<p>Referenced by <a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">operator()</a>, <a href="#a3db5842a73ae3417854ddcd60b0e1d12">operator()</a>, <a href="#a9a4d703a5dab4d351818ffdf686dccd1">operator()</a>, <a href="#a23778040c53c76ac927398e0e728ffb5">operator()</a> and <a href="#aa547c49d64497e4774d3405b9cdcf7f1">operator()</a>.</p>

</div>
</div>

### filter() {#a02ac65b43b4122de86989aed6d356df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::filter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, bool verbatim=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1672 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02ac65b43b4122de86989aed6d356df1">1672</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a02ac65b43b4122de86989aed6d356df1">RTFDocVisitor::filter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> verbatim)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=*p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">:  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\{"</span><span class="doxyHighlight">;            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">:  <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\}"</span><span class="doxyHighlight">;            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (verbatim)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:   <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>.</p>


<p>Referenced by <a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">operator()</a>, <a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a>, <a href="#a23778040c53c76ac927398e0e728ffb5">operator()</a>, <a href="#aa547c49d64497e4774d3405b9cdcf7f1">operator()</a>, <a href="#a74f1097897a6deaeffd0ca3ca9e5c811">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a>, <a href="#af039aed5400d69cb1776431f44f90360">operator()</a> and <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>.</p>

</div>
</div>

### getListTable() {#ac9b164379ca75fc12d225af36eac95aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RTFDocVisitor::getListTable (const int id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac9b164379ca75fc12d225af36eac95aa">83</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac9b164379ca75fc12d225af36eac95aa">RTFDocVisitor::getListTable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0 ; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>[i].definition ; i++ )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> == <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>[i].</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">) &amp;&amp; (<a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a> == <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>[i].lvl))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>[i].place;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a> and <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>.</p>


<p>Referenced by <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>.</p>

</div>
</div>

### getStyle() {#a7467e3f0f800ca5303ce1e6e473cdcfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RTFDocVisitor::getStyle (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">76</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">RTFDocVisitor::getStyle</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> n = name + <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(<a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/styledata">StyleData</a> &amp;sd = <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>[n.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> sd.<a href="/web-doxygen/docs/api/structs/styledata/#af5bfe4b887b11e7daba3c3648697e031">reference</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>, <a href="/web-doxygen/docs/api/structs/styledata/#af5bfe4b887b11e7daba3c3648697e031">StyleData::reference</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a>, <a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#add264d5a56e09e76ec274af99af747d2">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a>, <a href="#af3beab942bf46b1f903ac30ac39a10d2">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> and <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>.</p>

</div>
</div>

### incIndentLevel() {#a346f4b14ce5276df49857a01b0c501c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::incIndentLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a346f4b14ce5276df49857a01b0c501c8">101</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a346f4b14ce5276df49857a01b0c501c8">RTFDocVisitor::incIndentLevel</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a>&gt;=<a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Maximum indent level ({}) exceeded while generating RTF output!\n"</span><span class="doxyHighlight">,<a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a> and <a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a>.</p>


<p>Referenced by <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#add264d5a56e09e76ec274af99af747d2">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a> and <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>.</p>

</div>
</div>

### includePicturePostRTF() {#a489cc0ae371a7749b2bb9736ead27a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::includePicturePostRTF (bool isTypeRTF, bool hasCaption, bool inlineImage=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1253 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a489cc0ae371a7749b2bb9736ead27a19">1253</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a489cc0ae371a7749b2bb9736ead27a19">RTFDocVisitor::includePicturePostRTF</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isTypeRTF, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isTypeRTF)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" }"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> and <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">DocVisitor::popHidden</a>.</p>


<p>Referenced by <a href="#a8991833ac99826e07a993af4b58b0c4b">operator()</a>, <a href="#a33dd9566336e1d3c40ea2dadff6d8676">operator()</a>, <a href="#a247c4506996a3a6d71827322614efb30">operator()</a>, <a href="#a732b1d92dfc620e4cb221bbb32fade22">operator()</a>, <a href="#a4f3ac1fc0fb8cb8218beb807d0a820d1">operator()</a> and <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a>.</p>

</div>
</div>

### includePicturePreRTF() {#a2e791b200dd11ec24ff27a9aab0f8940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::includePicturePreRTF (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool isTypeRTF, bool hasCaption, bool inlineImage=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1216 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e791b200dd11ec24ff27a9aab0f8940">1216</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2e791b200dd11ec24ff27a9aab0f8940">RTFDocVisitor::includePicturePreRTF</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isTypeRTF, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isTypeRTF)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption || <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard \\qc "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{ \\field\\flddirty {\\*\\fldinst  INCLUDEPICTURE \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" \\\\d \\\\*MERGEFORMAT}{\\fldrslt Image}}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\par\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pard \\qc \\b"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{Image \\field\\flddirty{\\*\\fldinst { SEQ Image \\\\*Arabic }}{\\fldrslt {\\noproof 1}} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption) <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\comment "</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// to prevent caption to be shown</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// other format -&gt; skip</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">DocVisitor::pushHidden</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a247c4506996a3a6d71827322614efb30">operator()</a>, <a href="#a37a4b0291dcc41a9b1072757d344b546">writeDiaFile</a>, <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>, <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a> and <a href="#a8aaf0de986f15251aaa6221d226ab55a">writePlantUMLFile</a>.</p>

</div>
</div>

### indentLevel() {#a05c7c66aca435bbdb1fef9133159876f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int RTFDocVisitor::indentLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05c7c66aca435bbdb1fef9133159876f">96</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a05c7c66aca435bbdb1fef9133159876f">RTFDocVisitor::indentLevel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::min(<a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a>,<a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a> and <a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a>.</p>


<p>Referenced by <a href="#a7467e3f0f800ca5303ce1e6e473cdcfe">getStyle</a>, <a href="#a74283afcc3656534bef009b917a9f525">operator()</a>, <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a> and <a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a>.</p>

</div>
</div>

### startLink() {#a02328f0a76dfca6a9e0d24167905289e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::startLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1700 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02328f0a76dfca6a9e0d24167905289e">1700</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a02328f0a76dfca6a9e0d24167905289e">RTFDocVisitor::startLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(RTF_HYPERLINKS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> refName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">      refName+=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">      refName+=</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">      refName+=anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\field {\\*\\fldinst { HYPERLINK  \\\\l \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(refName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" }{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{\\fldrslt {\\cs37\\ul\\cf2 "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\b "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a>, <a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.</p>


<p>Referenced by <a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">operator()</a>, <a href="#a3db5842a73ae3417854ddcd60b0e1d12">operator()</a>, <a href="#a9a4d703a5dab4d351818ffdf686dccd1">operator()</a>, <a href="#a23778040c53c76ac927398e0e728ffb5">operator()</a> and <a href="#aa547c49d64497e4774d3405b9cdcf7f1">operator()</a>.</p>

</div>
</div>

### visitChildren() {#a23f7a489312340750c32e797addf90dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::visitChildren (const T &amp; t)</td>
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



<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23f7a489312340750c32e797addf90dd">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a23f7a489312340750c32e797addf90dd">visitChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : t.children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Referenced by <a href="#a74283afcc3656534bef009b917a9f525">operator()</a>, <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a8991833ac99826e07a993af4b58b0c4b">operator()</a>, <a href="#a33dd9566336e1d3c40ea2dadff6d8676">operator()</a>, <a href="#af199af5695c344c4730378ecfce43079">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a44f9db74256f38af950876f6863a1dd4">operator()</a>, <a href="#a70c61ff58fa9f747fc2b971c689a09ff">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#a8d4eb63da29c3a07a95f240dcd9a143e">operator()</a>, <a href="#ae0c5c194fc2579df52204eb00134c6bf">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#adae81723bf98cc11856ec916852cf089">operator()</a>, <a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#a7a5ce880ef222be6eeb6eea7e12b78b8">operator()</a>, <a href="#ae02dc45654c7f54372b2306e37d8cd3f">operator()</a>, <a href="#a3c72fc623be48174c003bb47c523d6c1">operator()</a>, <a href="#a247c4506996a3a6d71827322614efb30">operator()</a>, <a href="#aa1d0bebcd0570b99692349a8268122d9">operator()</a>, <a href="#a3db5842a73ae3417854ddcd60b0e1d12">operator()</a>, <a href="#a9a4d703a5dab4d351818ffdf686dccd1">operator()</a>, <a href="#a732b1d92dfc620e4cb221bbb32fade22">operator()</a>, <a href="#af6ff0afe39093628cd96d42dfce7515f">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a0d70bea0fa796acb266fcfda801cfbb9">operator()</a>, <a href="#a4f3ac1fc0fb8cb8218beb807d0a820d1">operator()</a>, <a href="#aa547c49d64497e4774d3405b9cdcf7f1">operator()</a>, <a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a>, <a href="#a3ccfb63934cef53d78e3e6641be084b5">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#a89b1ef4b308483fcf725cef8081e5849">operator()</a>, <a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a>, <a href="#a9dc9aeca576eb153d222793bc3227d07">operator()</a>, <a href="#ac06a6ad599b271d16500b483b5912679">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> and <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>.</p>

</div>
</div>

### writeDiaFile() {#a37a4b0291dcc41a9b1072757d344b546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::writeDiaFile (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1770 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37a4b0291dcc41a9b1072757d344b546">1770</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a37a4b0291dcc41a9b1072757d344b546">RTFDocVisitor::writeDiaFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),outDir,baseName,<a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">DiaOutputFormat::BITMAP</a>,df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>(baseName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a> and <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>.</p>


<p>Referenced by <a href="#a8991833ac99826e07a993af4b58b0c4b">operator()</a>.</p>

</div>
</div>

### writeDotFile() {#a286a80b0680a1b0defb947466bea6762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::writeDotFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1747 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a286a80b0680a1b0defb947466bea6762">1747</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a286a80b0680a1b0defb947466bea6762">RTFDocVisitor::writeDotFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;filename, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(filename);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>(filename,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>(baseName + </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight"> + imgExt, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>.</p>


<p>Referenced by <a href="#a33dd9566336e1d3c40ea2dadff6d8676">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> and <a href="#a94ea7715bb9b143ed6ae91770903188b">writeDotFile</a>.</p>

</div>
</div>

### writeDotFile() {#a94ea7715bb9b143ed6ae91770903188b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::writeDotFile (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1743 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a94ea7715bb9b143ed6ae91770903188b">1743</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a286a80b0680a1b0defb947466bea6762">RTFDocVisitor::writeDotFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a> and <a href="#a286a80b0680a1b0defb947466bea6762">writeDotFile</a>.</p>

</div>
</div>

### writeMscFile() {#ab70c2bad1c74761849c430861ec0d2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::writeMscFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1761 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab70c2bad1c74761849c430861ec0d2da">1761</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab70c2bad1c74761849c430861ec0d2da">RTFDocVisitor::writeMscFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>(fileName,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">MscOutputFormat::BITMAP</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>(baseName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a> and <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>.</p>


<p>Referenced by <a href="#a732b1d92dfc620e4cb221bbb32fade22">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> and <a href="#a47dad14278a28560cae8ec1a900fda24">writeMscFile</a>.</p>

</div>
</div>

### writeMscFile() {#a47dad14278a28560cae8ec1a900fda24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::writeMscFile (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 134 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1757 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47dad14278a28560cae8ec1a900fda24">1757</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab70c2bad1c74761849c430861ec0d2da">RTFDocVisitor::writeMscFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a> and <a href="#ab70c2bad1c74761849c430861ec0d2da">writeMscFile</a>.</p>

</div>
</div>

### writePlantUMLFile() {#a8aaf0de986f15251aaa6221d226ab55a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RTFDocVisitor::writePlantUMLFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>, definition at line 1778 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8aaf0de986f15251aaa6221d226ab55a">1778</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8aaf0de986f15251aaa6221d226ab55a">RTFDocVisitor::writePlantUMLFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(RTF_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">generatePlantUMLOutput</a>(fileName,outDir,<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>(baseName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>.</p>


<p>Referenced by <a href="#a4f3ac1fc0fb8cb8218beb807d0a820d1">operator()</a> and <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_ci {#a4948ccf2a491663a91479243554243cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList&amp; RTFDocVisitor::m_ci</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4948ccf2a491663a91479243554243cd">143</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#a4948ccf2a491663a91479243554243cd">m_ci</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a>, <a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> and <a href="#a67b0a4193b8ba939843a29f3d67acaa9">RTFDocVisitor</a>.</p>

</div>
</div>

### m\_hide {#a8adcc63dc189a8e625ff27867dedbe25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RTFDocVisitor::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8adcc63dc189a8e625ff27867dedbe25">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8adcc63dc189a8e625ff27867dedbe25">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="#a2993bfecac33a60da6408f79586b7da2">operator()</a>, <a href="#a74283afcc3656534bef009b917a9f525">operator()</a>, <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">operator()</a>, <a href="#adc374c79a2895d83e349ffc76358209e">operator()</a>, <a href="#a4af0a6415a019a1051dda0dd4d56dbef">operator()</a>, <a href="#a485c2a5796bb5e12497c7ab9d65d1f8c">operator()</a>, <a href="#af199af5695c344c4730378ecfce43079">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a70c61ff58fa9f747fc2b971c689a09ff">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#a8d4eb63da29c3a07a95f240dcd9a143e">operator()</a>, <a href="#ae0c5c194fc2579df52204eb00134c6bf">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#adae81723bf98cc11856ec916852cf089">operator()</a>, <a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#a7a5ce880ef222be6eeb6eea7e12b78b8">operator()</a>, <a href="#ae02dc45654c7f54372b2306e37d8cd3f">operator()</a>, <a href="#a3c72fc623be48174c003bb47c523d6c1">operator()</a>, <a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a>, <a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a>, <a href="#aed6822c7504330f96cc764e333589e7a">operator()</a>, <a href="#aa1d0bebcd0570b99692349a8268122d9">operator()</a>, <a href="#a3db5842a73ae3417854ddcd60b0e1d12">operator()</a>, <a href="#a561b27cc775aaa5f6db73f1d33099176">operator()</a>, <a href="#a9a4d703a5dab4d351818ffdf686dccd1">operator()</a>, <a href="#a23778040c53c76ac927398e0e728ffb5">operator()</a>, <a href="#af6ff0afe39093628cd96d42dfce7515f">operator()</a>, <a href="#aeb7edc62cad5a541849845d2bfe030e9">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a0d70bea0fa796acb266fcfda801cfbb9">operator()</a>, <a href="#aa547c49d64497e4774d3405b9cdcf7f1">operator()</a>, <a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#a89b1ef4b308483fcf725cef8081e5849">operator()</a>, <a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a>, <a href="#add264d5a56e09e76ec274af99af747d2">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a>, <a href="#af3beab942bf46b1f903ac30ac39a10d2">operator()</a>, <a href="#a8123582499bf0458dc938ff66c4724e7">operator()</a>, <a href="#a9dc9aeca576eb153d222793bc3227d07">operator()</a>, <a href="#ac06a6ad599b271d16500b483b5912679">operator()</a>, <a href="#a74f1097897a6deaeffd0ca3ca9e5c811">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a>, <a href="#af154c4b8688beaef882211c40763fec3">operator()</a>, <a href="#af039aed5400d69cb1776431f44f90360">operator()</a> and <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>.</p>

</div>
</div>

### m\_hierarchyLevel {#a36079b40823fcb3c2f0473dbf124d032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int RTFDocVisitor::m_hierarchyLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36079b40823fcb3c2f0473dbf124d032">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a36079b40823fcb3c2f0473dbf124d032">m_hierarchyLevel</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#adae81723bf98cc11856ec916852cf089">operator()</a>, <a href="#a89b1ef4b308483fcf725cef8081e5849">operator()</a> and <a href="#a67b0a4193b8ba939843a29f3d67acaa9">RTFDocVisitor</a>.</p>

</div>
</div>

### m\_indentLevel {#a7750d512b4ea14d7547669387849d45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int RTFDocVisitor::m_indentLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7750d512b4ea14d7547669387849d45b">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7750d512b4ea14d7547669387849d45b">m_indentLevel</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a7a1c80a721716cb64c2a82e80cbff047">decIndentLevel</a>, <a href="#ac9b164379ca75fc12d225af36eac95aa">getListTable</a>, <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a> and <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>.</p>

</div>
</div>

### m\_insidePre {#a5aa7831854cde6046dc35731447cd982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RTFDocVisitor::m_insidePre = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa7831854cde6046dc35731447cd982">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5aa7831854cde6046dc35731447cd982">m_insidePre</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#af3beab942bf46b1f903ac30ac39a10d2">operator()</a> and <a href="#af154c4b8688beaef882211c40763fec3">operator()</a>.</p>

</div>
</div>

### m\_langExt {#a303074f18eaca30ccd8faf73917255ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RTFDocVisitor::m_langExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a303074f18eaca30ccd8faf73917255ad">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a303074f18eaca30ccd8faf73917255ad">m_langExt</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a> and <a href="#a67b0a4193b8ba939843a29f3d67acaa9">RTFDocVisitor</a>.</p>

</div>
</div>

### m\_lastIsPara {#a477396568e5d3d9fdba5e77538d6c373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RTFDocVisitor::m_lastIsPara = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a477396568e5d3d9fdba5e77538d6c373">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a477396568e5d3d9fdba5e77538d6c373">m_lastIsPara</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="#a2993bfecac33a60da6408f79586b7da2">operator()</a>, <a href="#a74283afcc3656534bef009b917a9f525">operator()</a>, <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#adc374c79a2895d83e349ffc76358209e">operator()</a>, <a href="#a4af0a6415a019a1051dda0dd4d56dbef">operator()</a>, <a href="#a485c2a5796bb5e12497c7ab9d65d1f8c">operator()</a>, <a href="#af199af5695c344c4730378ecfce43079">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a70c61ff58fa9f747fc2b971c689a09ff">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#ae0c5c194fc2579df52204eb00134c6bf">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#adae81723bf98cc11856ec916852cf089">operator()</a>, <a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#a7a5ce880ef222be6eeb6eea7e12b78b8">operator()</a>, <a href="#a3c72fc623be48174c003bb47c523d6c1">operator()</a>, <a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a>, <a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a>, <a href="#aed6822c7504330f96cc764e333589e7a">operator()</a>, <a href="#a561b27cc775aaa5f6db73f1d33099176">operator()</a>, <a href="#a23778040c53c76ac927398e0e728ffb5">operator()</a>, <a href="#af6ff0afe39093628cd96d42dfce7515f">operator()</a>, <a href="#aeb7edc62cad5a541849845d2bfe030e9">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#a89b1ef4b308483fcf725cef8081e5849">operator()</a>, <a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a>, <a href="#add264d5a56e09e76ec274af99af747d2">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a>, <a href="#af3beab942bf46b1f903ac30ac39a10d2">operator()</a>, <a href="#a8123582499bf0458dc938ff66c4724e7">operator()</a>, <a href="#a74f1097897a6deaeffd0ca3ca9e5c811">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a>, <a href="#af154c4b8688beaef882211c40763fec3">operator()</a>, <a href="#af039aed5400d69cb1776431f44f90360">operator()</a>, <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a> and <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>.</p>

</div>
</div>

### m\_listItemInfo {#aedd538d88fdeb63ad937e4be8d9931d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTFListItemInfo RTFDocVisitor::m_listItemInfo[maxIndentLevels]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aedd538d88fdeb63ad937e4be8d9931d5">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/rtfdocvisitor/rtflistiteminfo">RTFListItemInfo</a> <a href="#aedd538d88fdeb63ad937e4be8d9931d5">m_listItemInfo</a>[<a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a>];</span></span></div>

</div>


<p>Referenced by <a href="#a74283afcc3656534bef009b917a9f525">operator()</a>, <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a> and <a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a>.</p>

</div>
</div>

### m\_t {#aba1d89b083d64bd4d9865bd2e191b0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream&amp; RTFDocVisitor::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba1d89b083d64bd4d9865bd2e191b0ab">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#aba1d89b083d64bd4d9865bd2e191b0ab">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adc9cf36e3e61b81df2b0ada024366806">endLink</a>, <a href="#a02ac65b43b4122de86989aed6d356df1">filter</a>, <a href="#a489cc0ae371a7749b2bb9736ead27a19">includePicturePostRTF</a>, <a href="#a2e791b200dd11ec24ff27a9aab0f8940">includePicturePreRTF</a>, <a href="#a2993bfecac33a60da6408f79586b7da2">operator()</a>, <a href="#a74283afcc3656534bef009b917a9f525">operator()</a>, <a href="#a39a5bf02292d858e211a2cb3ee3f62c1">operator()</a>, <a href="#a8b41cc5c80471d8cbb6fb7a8bbd55bf2">operator()</a>, <a href="#adc374c79a2895d83e349ffc76358209e">operator()</a>, <a href="#a4af0a6415a019a1051dda0dd4d56dbef">operator()</a>, <a href="#a485c2a5796bb5e12497c7ab9d65d1f8c">operator()</a>, <a href="#af199af5695c344c4730378ecfce43079">operator()</a>, <a href="#a022f6eb89bc55b752aeff008e9c9037d">operator()</a>, <a href="#a44f9db74256f38af950876f6863a1dd4">operator()</a>, <a href="#a70c61ff58fa9f747fc2b971c689a09ff">operator()</a>, <a href="#a85db1985a82081ef9ab2e5a25c450f28">operator()</a>, <a href="#ae0c5c194fc2579df52204eb00134c6bf">operator()</a>, <a href="#acc6c497f52cf55d67723f21ec2a97c6b">operator()</a>, <a href="#adae81723bf98cc11856ec916852cf089">operator()</a>, <a href="#a2851bbf082cd6f2a85d6c9fc7a1050c0">operator()</a>, <a href="#a63f63207a160e4e99a4c2dd5b55734c8">operator()</a>, <a href="#a7a5ce880ef222be6eeb6eea7e12b78b8">operator()</a>, <a href="#ae02dc45654c7f54372b2306e37d8cd3f">operator()</a>, <a href="#a3c72fc623be48174c003bb47c523d6c1">operator()</a>, <a href="#ac315ddf81b73a005764278a3c190d1a4">operator()</a>, <a href="#a75e708a4ea1b27587678f424211b8b62">operator()</a>, <a href="#aed6822c7504330f96cc764e333589e7a">operator()</a>, <a href="#a3db5842a73ae3417854ddcd60b0e1d12">operator()</a>, <a href="#a561b27cc775aaa5f6db73f1d33099176">operator()</a>, <a href="#af6ff0afe39093628cd96d42dfce7515f">operator()</a>, <a href="#aeb7edc62cad5a541849845d2bfe030e9">operator()</a>, <a href="#a6f4df2c3160f09e662393e6a23b2add0">operator()</a>, <a href="#a07acb7803948c3811f88d4efa00587a4">operator()</a>, <a href="#a4fcb960f7e5b593e8e6c51ea43f66a9a">operator()</a>, <a href="#a89b1ef4b308483fcf725cef8081e5849">operator()</a>, <a href="#a96bd1ead75c76578b08ef7a5c49a4d70">operator()</a>, <a href="#a9bc7acec72efe2239cb6c798855ed08a">operator()</a>, <a href="#add264d5a56e09e76ec274af99af747d2">operator()</a>, <a href="#aa17fa64bc141c519b0b24e0a475ab1e1">operator()</a>, <a href="#af3beab942bf46b1f903ac30ac39a10d2">operator()</a>, <a href="#a8123582499bf0458dc938ff66c4724e7">operator()</a>, <a href="#a74f1097897a6deaeffd0ca3ca9e5c811">operator()</a>, <a href="#a101e1d1d08453e6a606f9f8652a6cc73">operator()</a>, <a href="#af154c4b8688beaef882211c40763fec3">operator()</a>, <a href="#a7f10a43fc0a35475e9078305d745951f">operator()</a>, <a href="#a67b0a4193b8ba939843a29f3d67acaa9">RTFDocVisitor</a> and <a href="#a02328f0a76dfca6a9e0d24167905289e">startLink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### maxIndentLevels {#aa0f6416af4eadfbe1375e94e9c64383c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int RTFDocVisitor::maxIndentLevels = 13</td>
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



<p>Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0f6416af4eadfbe1375e94e9c64383c">149</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa0f6416af4eadfbe1375e94e9c64383c">maxIndentLevels</a> = 13;</span></span></div>

</div>


<p>Referenced by <a href="#a346f4b14ce5276df49857a01b0c501c8">incIndentLevel</a> and <a href="#a05c7c66aca435bbdb1fef9133159876f">indentLevel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp">rtfdocvisitor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-h">rtfdocvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
