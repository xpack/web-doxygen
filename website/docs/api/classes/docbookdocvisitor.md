---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docbookdocvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocbookDocVisitor` Class Reference

<p>Concrete visitor implementation for Docbook output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocbookDocVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">src/docbookvisitor.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8d7feef248a290d19da45c81f0ea26">DocbookDocVisitor</a> (TextStream &amp;t, OutputCodeList &amp;ci, const QCString &amp;langExt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e98d6606eee027d17aebcbe7ad90c85">operator()</a> (const DocWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f23f1bb1c5d9e7c00ca23bae19be54">operator()</a> (const DocLinkedWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab014c099dfdb3ac2e7cda9129c153253">operator()</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30a5c4fe2669a2bdb78dd0c964af909">operator()</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eca51c43b643d592b22070d062a3b77">operator()</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca919f8124510f7e03ef62e8def34408">operator()</a> (const DocURL &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd98eb5e7a8634efc8df1ed1580ac99a">operator()</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391493662c00d8761a7b1817c0c6e6d7">operator()</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5dd013610540bba019aaef10157b416">operator()</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a> (const DocVerbatim &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7fced02c41e630be0ba0d38ec7445e4">operator()</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5826ce8044be2553216f205ef64ead74">operator()</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1abe1e85619493e4e99240d290c3bdd2">operator()</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a633ea27d943ce438a831b1043b37af8c">operator()</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5c051f908207108e9a88c130a79703">operator()</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7020b73e1f3135df92e8becc99fcacb4">operator()</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b206a0c1382df26146e64cde69d1085">operator()</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff7829d4c3cf2759e0eca9b3abbc5173">operator()</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6316cd4b961705e7c3bfee3d7628af09">operator()</a> (const DocAutoList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5fcc77a1bf0ac87ca740473f83ce834">operator()</a> (const DocAutoListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1add073cbb95e81ea333d8528797784">operator()</a> (const DocPara &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f022b87284463cbdd463a89f13d7694">operator()</a> (const DocRoot &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942b617cd956361afbd314539cab5922">operator()</a> (const DocSimpleSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad654cd7e66da83fdf2ff02f9bdcf34fd">operator()</a> (const DocTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c01d6cac8654f0a25efcf25fb783d6">operator()</a> (const DocSimpleList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1246ae30e71d074a6fb40c745494cc">operator()</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad39609386bf77fe37c6e6a3861e92c5">operator()</a> (const DocSection &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ef300f18d17dba697499319c88c8eb7">operator()</a> (const DocHtmlList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3dc4aca49387c2801b733951162e52c">operator()</a> (const DocHtmlListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a24a7573ff52b20b5b852a72eb779a3">operator()</a> (const DocHtmlDescList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52bcad32fdbc97d73c81802524cfce1c">operator()</a> (const DocHtmlDescTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a37d31a03800401baf118ecad9e7d8">operator()</a> (const DocHtmlDescData &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d3c8796370b41a72f6158fa461f5ca">operator()</a> (const DocHtmlTable &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21bc8c6017db61778cf6e60cea89abe">operator()</a> (const DocHtmlRow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ecd666271d67f9e23a18d15f1f259e7">operator()</a> (const DocHtmlCell &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed70425e19b1b76c43d7c2fa497e289">operator()</a> (const DocHtmlCaption &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2df620c0b51848655090f6d5e7ee5c26">operator()</a> (const DocInternal &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db2ddaf8249d9e473d5fd51f106efd8">operator()</a> (const DocHRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f3e3855449c3ee44c7e988e2fc4c38">operator()</a> (const DocHtmlSummary &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9392f6b1374f2be71799e29b52e27c29">operator()</a> (const DocHtmlDetails &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc99d97063bc21b16852e5345a5ff4f0">operator()</a> (const DocHtmlHeader &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab82ef451cf5eff26b1d097aefd8d421">operator()</a> (const DocImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f170949904015a222fd834618f71046">operator()</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa189a4fd5b9a6ff4647ffc13e70978">operator()</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789f7802c80a054fd7ee0d9e5f2fb4dc">operator()</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3af5572195fe68a70f0692dc9ab2ea3">operator()</a> (const DocPlantUmlFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e45c96a087cd77d7c8bd55c7c46a6e">operator()</a> (const DocLink &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1963a24dee9df501c8f65d4cdc02584">operator()</a> (const DocRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01dac5e12f73fbc5dd499dca9b16c946">operator()</a> (const DocSecRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea2df716439077851a238f878500460e">operator()</a> (const DocSecRefList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb18992e55be4c79b5dad6a8b8ae4b7">operator()</a> (const DocParamSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d9cb1979f0d09164d205bfd447b494">operator()</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a4faa0f71f2de7b7d2dad36d9af4e7">operator()</a> (const DocXRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29700a65140a358d78dbb9b46f3e520">operator()</a> (const DocInternalRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9b9df7cb5c9cf603f903416f7b31bca">operator()</a> (const DocText &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c4df795b9cbaacf62f451369d4ed53">operator()</a> (const DocHtmlBlockQuote &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14b0a6b57523bfcdf584ce2b3f14e1fd">operator()</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a986a7c2b2b0094683654ef479b0204ef">operator()</a> (const DocParBlock &amp;)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a> (const T &amp;t)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a> (const QCString &amp;str, const bool retainNewLine=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a> (const QCString &amp;file, const QCString &amp;anchor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2c9442335fc951437fc0cfb466c90c">startMscFile</a> (const QCString &amp;fileName, const QCString &amp;relPath, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const DocNodeList &amp;children, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5fa71d08ee9df28f986474abcf9eaf3">endMscFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">startDiaFile</a> (const QCString &amp;fileName, const QCString &amp;relPath, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const DocNodeList &amp;children, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">endDiaFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db6e8f6eb6422a68ea68af67795231f">writeDiaFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e78b0ed5635b833b739d63dafe452ff">startDotFile</a> (const QCString &amp;fileName, const QCString &amp;relPath, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const DocNodeList &amp;children, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d88687aa2a9c7544925377d4a967fc8">endDotFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a> (const QCString &amp;fileName, const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd00a8643be133e0b0cbef298202eeb">startPlantUmlFile</a> (const QCString &amp;fileName, const QCString &amp;relPath, const QCString &amp;width, const QCString &amp;height, bool hasCaption, const DocNodeList &amp;children, const QCString &amp;srcFile, int srcLine)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e204c832acb152c1909f650536d550">endPlantUmlFile</a> (bool hasCaption)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> (TextStream &amp;t, const DocNodeList &amp;children, bool hasCaption, const QCString &amp;name, const QCString &amp;width, const QCString &amp;height, bool inlineImage=FALSE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a> (TextStream &amp;t, bool hasCaption, bool inlineImage=FALSE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a> (const DocNodeList &amp;children)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24830382b069d6de946df1d470b96b9">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a196a2e77992700eb36c42485adaed6de">BoolStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb5ab6dc99ae7b20888cc7b8af544bf">m_enabled</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a196a2e77992700eb36c42485adaed6de">BoolStack</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a></td>
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

<p>Concrete visitor implementation for Docbook output.</p>

<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocbookDocVisitor() {#ace8d7feef248a290d19da45c81f0ea26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookDocVisitor::DocbookDocVisitor (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ci, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; langExt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace8d7feef248a290d19da45c81f0ea26">179</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ace8d7feef248a290d19da45c81f0ea26">DocbookDocVisitor::DocbookDocVisitor</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ci,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;langExt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>(t), <a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>(ci),<a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>(langExt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// m_t &lt;&lt; "&lt;section&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>, <a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a0e98d6606eee027d17aebcbe7ad90c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 190 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e98d6606eee027d17aebcbe7ad90c85">190</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(w.<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.</p>

</div>
</div>

### operator()() {#a29f23f1bb1c5d9e7c00ca23bae19be54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a29f23f1bb1c5d9e7c00ca23bae19be54">197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">file</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">DocLinkedWord::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">DocLinkedWord::file</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a> and <a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">DocLinkedWord::word</a>.</p>

</div>
</div>

### operator()() {#ab014c099dfdb3ac2e7cda9129c153253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab014c099dfdb3ac2e7cda9129c153253">206</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">DocWhiteSpace::chars</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>

</div>
</div>

### operator()() {#af30a5c4fe2669a2bdb78dd0c964af909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af30a5c4fe2669a2bdb78dd0c964af909">220</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#acfca10f028c7820564bbd80728898a79">docbook</a>(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"DocBook: non supported HTML-entity found: {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().html(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#acfca10f028c7820564bbd80728898a79">HtmlEntityMapper::docbook</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">DocSymbol::symbol</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#a0eca51c43b643d592b22070d062a3b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0eca51c43b643d592b22070d062a3b77">235</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">DocEmoji::index</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">DocEmoji::name</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">EmojiEntityMapper::unicode</a>.</p>

</div>
</div>

### operator()() {#aca919f8124510f7e03ef62e8def34408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp; u)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 250 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca919f8124510f7e03ef62e8def34408">250</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;link xlink:href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (u.<a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">isEmail</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"mailto:"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/link&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">DocURL::isEmail</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">DocURL::url</a>.</p>

</div>
</div>

### operator()() {#abd98eb5e7a8634efc8df1ed1580ac99a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd98eb5e7a8634efc8df1ed1580ac99a">262</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?linebreak?&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// gives nicer results but gives problems as it is not allowed in &lt;pare&gt; and also problems with dblatex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// m_t &lt;&lt; "\n" &lt;&lt; "&lt;sbr/&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>

</div>
</div>

### operator()() {#a391493662c00d8761a7b1817c0c6e6d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 271 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a391493662c00d8761a7b1817c0c6e6d7">271</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;informaltable frame='bottom'&gt;&lt;tgroup cols='1'&gt;&lt;colspec align='center'/&gt;&lt;tbody&gt;&lt;row&gt;&lt;entry align='center'&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;&lt;/row&gt;&lt;/tbody&gt;&lt;/tgroup&gt;&lt;/informaltable&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>

</div>
</div>

### operator()() {#aa5dd013610540bba019aaef10157b416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa5dd013610540bba019aaef10157b416">279</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;emphasis role=\"bold\"&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;emphasis&gt;"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;subscript&gt;"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/subscript&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;superscript&gt;"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/superscript&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;informaltable frame='none'&gt;&lt;tgroup cols='1'&gt;&lt;colspec align='center'/&gt;&lt;tbody&gt;&lt;row&gt;&lt;entry align='center'&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;&lt;/row&gt;&lt;/tbody&gt;&lt;/tgroup&gt;&lt;/informaltable&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* There is no equivalent Docbook tag for rendering Small text */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>: </span><span class="doxyHighlightComment">/* XSLT Stylesheets can be used */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">                                                                   </span><span class="doxyHighlightComment">/* HTML only */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>:        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>:        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>:  </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>: </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">DocStyleChange::enable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>.</p>

</div>
</div>

### operator()() {#a4931bb0ccd2eb4d8aede2a9afb7058d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 332 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">332</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang = <a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// explicit language setting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    lang = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(<a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">                                         s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">                                         langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(STRIP_CODE_COMMENTS),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">                                         s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">                                         s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(), </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(), </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dotindex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> stext = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">        name.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"dot_inline_dotgraph_"</span><span class="doxyHighlight">, dotindex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">        baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/inline_dotgraph_"</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">            dotindex++</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName = baseName+</span><span class="doxyHighlightStringLiteral">".dot"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">        std::ofstream file = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">        file.write( stext.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), stext.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">        file.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a>(baseName, s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mscindex = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName(4096, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> stext = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">        name.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"msc_inline_mscgraph_"</span><span class="doxyHighlight">, mscindex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">        baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%s%d"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">            (<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/inline_mscgraph_"</span><span class="doxyHighlight">).data(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">            mscindex++</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName = baseName+</span><span class="doxyHighlightStringLiteral">".msc"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">        std::ofstream file = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> text = </span><span class="doxyHighlightStringLiteral">"msc {"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">        text+=stext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">        text+=</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">        file.write( text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(), text.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">        file.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a>(baseName,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> docbookOutput = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>(docbookOutput,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">            s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">            s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">engine</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a>(baseName,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">DocVerbatim::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">DocVerbatim::engine</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">DocVerbatim::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">DocVerbatim::isExample</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">DocVerbatim::language</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">DocVerbatim::text</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">DocVerbatim::type</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>, <a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a>, <a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a>, <a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>.</p>

</div>
</div>

### operator()() {#ab7fced02c41e630be0ba0d38ec7445e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp; anc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 448 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7fced02c41e630be0ba0d38ec7445e4">448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;anc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;anchor xml:id=\"_"</span><span class="doxyHighlight"> &lt;&lt;  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>(anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">DocAnchor::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">DocAnchor::file</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.</p>

</div>
</div>

### operator()() {#a5826ce8044be2553216f205ef64ead74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp; inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 455 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5826ce8044be2553216f205ef64ead74">455</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;inc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(), fd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                                                inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                                                langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">                                                inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                                                inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                                                inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>().<a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a>(<a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>()==<a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">                                         );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;&lt;/literallayout&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">DocInclude::blockId</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">DocInclude::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">DocInclude::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">DocInclude::extension</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">DocInclude::file</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">DocInclude::isExample</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>, <a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">DocInclude::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">DocInclude::text</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">DocInclude::trimLeft</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">DocInclude::type</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a> and <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>.</p>

</div>
</div>

### operator()() {#a1abe1e85619493e4e99240d290c3bdd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp; op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 518 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1abe1e85619493e4e99240d290c3bdd2">518</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;op)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">isFirst</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting linenumbering=\"unnumbered\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locLangExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locLangExt.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) locLangExt = <a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(locLangExt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">type</a>()!=<a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_ptr&lt;FileDef&gt; fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">        fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(locLangExt).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>,op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                                        fd.get(),     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">line</a>(),    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">showLineNo</a>()  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">                                       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">isLast</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">DocIncOperator::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">DocIncOperator::exampleFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">DocIncOperator::includeFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">DocIncOperator::isExample</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">DocIncOperator::isFirst</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">DocIncOperator::isLast</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">DocIncOperator::line</a>, <a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">DocVisitor::popHidden</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">DocVisitor::pushHidden</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">DocIncOperator::showLineNo</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">DocIncOperator::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">DocIncOperator::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">DocIncOperator::type</a>.</p>

</div>
</div>

### operator()() {#a633ea27d943ce438a831b1043b37af8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp; f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 572 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a633ea27d943ce438a831b1043b37af8c">572</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.<a href="/web-doxygen/docs/api/classes/docformula/#a6efb81a9620e6fad264a0c896f2ca7cb">isInline</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>  &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;inlinemediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;mediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;imageobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                &lt;imagedata "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"align=\"center\" valign=\"middle\" scalefit=\"0\" fileref=\""</span><span class="doxyHighlight"> &lt;&lt; f.<a href="/web-doxygen/docs/api/classes/docformula/#ae693f78dc76e8caf6060cb26fe3b58aa">relPath</a>() &lt;&lt; f.<a href="/web-doxygen/docs/api/classes/docformula/#a639835af31171584bbf72eab82d7f162">name</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".png\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;/imageobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.<a href="/web-doxygen/docs/api/classes/docformula/#a6efb81a9620e6fad264a0c896f2ca7cb">isInline</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>  &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/inlinemediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/mediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docformula/#a6efb81a9620e6fad264a0c896f2ca7cb">DocFormula::isInline</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docformula/#a639835af31171584bbf72eab82d7f162">DocFormula::name</a> and <a href="/web-doxygen/docs/api/classes/docformula/#ae693f78dc76e8caf6060cb26fe3b58aa">DocFormula::relPath</a>.</p>

</div>
</div>

### operator()() {#a1f5c051f908207108e9a88c130a79703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp; ie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 587 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f5c051f908207108e9a88c130a79703">587</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;ie)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;indexterm&gt;&lt;primary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(ie.<a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">entry</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/primary&gt;&lt;/indexterm&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">DocIndexEntry::entry</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>

</div>
</div>

### operator()() {#a7020b73e1f3135df92e8becc99fcacb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 596 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7020b73e1f3135df92e8becc99fcacb4">596</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// m_t &lt;&lt; "&lt;simplesect/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>.</p>

</div>
</div>

### operator()() {#a5b206a0c1382df26146e64cde69d1085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp; cite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 602 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b206a0c1382df26146e64cde69d1085">602</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;cite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> opt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">option</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noCite()) <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>(),<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">anchor</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">getText</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noCite()) <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(</span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">DocCite::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">DocCite::file</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">DocCite::getText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">DocCite::option</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a> and <a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">DocCite::target</a>.</p>

</div>
</div>

### operator()() {#aff7829d4c3cf2759e0eca9b3abbc5173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp; sep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1392 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff7829d4c3cf2759e0eca9b3abbc5173">1392</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;sep)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; sep.<a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">chars</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">DocSeparator::chars</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>

</div>
</div>

### operator()() {#a6316cd4b961705e7c3bfee3d7628af09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 629 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6316cd4b961705e7c3bfee3d7628af09">629</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">DocAutoList::isEnumList</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae5fcc77a1bf0ac87ca740473f83ce834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 652 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5fcc77a1bf0ac87ca740473f83ce834">652</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">itemNumber</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a>: </span><span class="doxyHighlightComment">// unchecked</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem override=\"unchecked\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>: </span><span class="doxyHighlightComment">// checked with x</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>: </span><span class="doxyHighlightComment">// checked with X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem override=\"checked\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(li);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">DocAutoListItem::itemNumber</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa1add073cbb95e81ea333d8528797784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp; p)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 673 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1add073cbb95e81ea333d8528797784">673</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a7f022b87284463cbdd463a89f13d7694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 684 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7f022b87284463cbdd463a89f13d7694">684</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a942b617cd956361afbd314539cab5922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 690 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a942b617cd956361afbd314539cab5922">690</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSeeAlso() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSeeAlso()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturns()&lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturns()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVersion()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSince() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSince()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDate() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDate()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;note&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNote() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;note&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNote()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;warning&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trWarning() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;warning&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trWarning()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPrecondition() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPrecondition()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPostcondition() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPostcondition()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCopyright() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCopyright()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInvariant() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInvariant()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// &lt;remark&gt; is miising the &lt;title&gt; possibility</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRemarks() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRemarks()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;caution&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAttention() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;caution&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAttention()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;important&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trImportant() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;important&gt;&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trImportant()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#af7bb6fa3996348dc1e211e32eb358f83">hasTitle</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#af7bb6fa3996348dc1e211e32eb358f83">hasTitle</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/formalpara&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/note&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/caution&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/important&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/warning&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/formalpara&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#af7bb6fa3996348dc1e211e32eb358f83">DocSimpleSect::hasTitle</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">DocSimpleSect::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">DocSimpleSect::type</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>, <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>.</p>

</div>
</div>

### operator()() {#ad654cd7e66da83fdf2ff02f9bdcf34fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 901 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad654cd7e66da83fdf2ff02f9bdcf34fd">901</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (t.<a href="/web-doxygen/docs/api/classes/doctitle/#ae27763e0e3579fbd9d2d67e7fbebda47">hasTitle</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (t.<a href="/web-doxygen/docs/api/classes/doctitle/#ae27763e0e3579fbd9d2d67e7fbebda47">hasTitle</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#ae27763e0e3579fbd9d2d67e7fbebda47">DocTitle::hasTitle</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a04c01d6cac8654f0a25efcf25fb783d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 910 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04c01d6cac8654f0a25efcf25fb783d6">910</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a5d1246ae30e71d074a6fb40c745494cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 919 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d1246ae30e71d074a6fb40c745494cc">919</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">    visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">DocSimpleListItem::paragraph</a>.</p>

</div>
</div>

### operator()() {#aad39609386bf77fe37c6e6a3861e92c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 931 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad39609386bf77fe37c6e6a3861e92c5">931</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;section xml:id=\"_"</span><span class="doxyHighlight"> &lt;&lt;  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(s.<a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">file</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/section&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">DocSection::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">DocSection::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">DocSection::title</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a2ef300f18d17dba697499319c88c8eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 946 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ef300f18d17dba697499319c88c8eb7">946</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// opening tag for ordered list will be handled in DocHtmlListItem</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// due to (re-)numbering possibilities</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()!=<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">DocHtmlList::type</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab3dc4aca49387c2801b733951162e52c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 962 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3dc4aca49387c2801b733951162e52c">962</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> *l = std::get_if&lt;DocHtmlList&gt;(s.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l-&gt;<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFirst = &amp;std::get&lt;DocHtmlListItem&gt;(l-&gt;<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#ad097d3d024ed9fa293f9099352309a25">front</a>())==&amp;s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : s.<a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) value = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (value&gt;0 || isFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : l-&gt;<a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"1"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">            type = </span><span class="doxyHighlightStringLiteral">" numeration=\"arabic\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">            type = </span><span class="doxyHighlightStringLiteral">" numeration=\"loweralpha\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"A"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">            type =  </span><span class="doxyHighlightStringLiteral">" numeration=\"upperalpha\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"i"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">            type =  </span><span class="doxyHighlightStringLiteral">" numeration=\"lowerroman\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value==</span><span class="doxyHighlightStringLiteral">"I"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">            type =  </span><span class="doxyHighlightStringLiteral">" numeration=\"upperroman\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (value==0 &amp;&amp; opt.name==</span><span class="doxyHighlightStringLiteral">"start"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) value = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (value&gt;0 &amp;&amp; !isFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (value&gt;0 || isFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;orderedlist"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!type.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; type.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (value&gt;0)         <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" startingnumber=\""</span><span class="doxyHighlight"> &lt;&lt; value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">DocHtmlList::attribs</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">DocHtmlListItem::attribs</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/growvector/#ad097d3d024ed9fa293f9099352309a25">GrowVector&lt; T &gt;::front</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">DocHtmlList::type</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a3a24a7573ff52b20b5b852a72eb779a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1025 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a24a7573ff52b20b5b852a72eb779a3">1025</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;variablelist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/variablelist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a52bcad32fdbc97d73c81802524cfce1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp; dt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1034 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52bcad32fdbc97d73c81802524cfce1c">1034</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;dt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;varlistentry&gt;&lt;term&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(dt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/term&gt;&lt;/varlistentry&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a73a37d31a03800401baf118ecad9e7d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp; dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1043 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73a37d31a03800401baf118ecad9e7d8">1043</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab9d3c8796370b41a72f6158fa461f5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1052 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab9d3c8796370b41a72f6158fa461f5ca">1052</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.push(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;informaltable frame=\"all\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;tgroup cols=\""</span><span class="doxyHighlight"> &lt;&lt; t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" align=\"left\" colsep=\"1\" rowsep=\"1\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint32_t i = 0; i &lt;t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>(); i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// do something with colwidth based of cell width specification (be aware of possible colspan in the header)?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;colspec colname='c"</span><span class="doxyHighlight"> &lt;&lt; i+1 &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.top()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tgroup&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/informaltable&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">DocHtmlTable::caption</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">DocHtmlTable::numColumns</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab21bc8c6017db61778cf6e60cea89abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp; tr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1075 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab21bc8c6017db61778cf6e60cea89abe">1075</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;tr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tr.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">isHeading</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.top()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.top() = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;thead&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.top())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.top() = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;row "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : tr.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ad696d912e61803ae0ffe3b862a92a9f1">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a9e2036260f430686eab1509bb5087359">supportedHtmlAttribute</a>(opt.name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// process supported attributes only</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; opt.name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(opt.value) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(tr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/row&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tr.<a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">isHeading</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/thead&gt;&lt;tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>.top() = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ad696d912e61803ae0ffe3b862a92a9f1">DocHtmlRow::attribs</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">DocHtmlRow::isHeading</a>, <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>, <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a9e2036260f430686eab1509bb5087359">supportedHtmlAttribute</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9ecd666271d67f9e23a18d15f1f259e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1113 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ecd666271d67f9e23a18d15f1f259e7">1113</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ad42711394b311bbb450073c2206da8c8">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"colspan"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" namest='c"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cols = opt.value.toInt();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a> += (cols - 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" nameend='c"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"rowspan"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraRows = opt.value.toInt() - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" morerows='"</span><span class="doxyHighlight"> &lt;&lt; extraRows &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.startsWith(</span><span class="doxyHighlightStringLiteral">"markdownTable"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// handle markdown generated attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.endsWith(</span><span class="doxyHighlightStringLiteral">"Right"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align='right'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.endsWith(</span><span class="doxyHighlightStringLiteral">"Left"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align='left'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.endsWith(</span><span class="doxyHighlightStringLiteral">"Center"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align='center'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip 'markdownTable*' value ending with "None"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" class='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(opt.value) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a9e2036260f430686eab1509bb5087359">supportedHtmlAttribute</a>(opt.name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// process supported attributes only</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; opt.name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(opt.value) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ad42711394b311bbb450073c2206da8c8">DocHtmlCell::attribs</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a9e2036260f430686eab1509bb5087359">supportedHtmlAttribute</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a2ed70425e19b1b76c43d7c2fa497e289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1168 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ed70425e19b1b76c43d7c2fa497e289">1168</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;caption&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;anchor xml:id=\"_"</span><span class="doxyHighlight"> &lt;&lt;  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>(c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">anchor</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/caption&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">DocHtmlCaption::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">DocHtmlCaption::file</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a2df620c0b51848655090f6d5e7ee5c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1181 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2df620c0b51848655090f6d5e7ee5c26">1181</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a3db2ddaf8249d9e473d5fd51f106efd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp; href)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1188 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3db2ddaf8249d9e473d5fd51f106efd8">1188</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;href)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0) != </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;link xlink:href=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(href.<a href="/web-doxygen/docs/api/classes/dochref/#aa4e295c3ed9f05b818f7ae74ee6f34a0">file</a>(),<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>(href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(href);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/link&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/dochref/#aa4e295c3ed9f05b818f7ae74ee6f34a0">DocHRef::file</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">DocHRef::url</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a14f3e3855449c3ee44c7e988e2fc4c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1204 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a14f3e3855449c3ee44c7e988e2fc4c38">1204</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;&lt;emphasis role=\"bold\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;&lt;/para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9392f6b1374f2be71799e29b52e27c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1213 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9392f6b1374f2be71799e29b52e27c29">1213</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> summary = d.<a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">summary</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*summary);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">DocHtmlDetails::summary</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#adc99d97063bc21b16852e5345a5ff4f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp; h)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1229 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc99d97063bc21b16852e5345a5ff4f0">1229</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;h)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formalpara&gt;&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(h);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;&lt;/formalpara&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aab82ef451cf5eff26b1d097aefd8d421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp; img)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1238 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab82ef451cf5eff26b1d097aefd8d421">1238</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;img)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (img.<a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>()==<a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocImage::DocBook</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(img.<a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, img.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">hasCaption</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a>() + baseName, img.<a href="/web-doxygen/docs/api/classes/docimage/#a79d36f165096668a3d6631efb6e0b4f0">width</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#a434782653279e9f1d823656d48fe3e26">height</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(img);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, img.<a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">hasCaption</a>(),img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd=<a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>, baseName, ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">      file=fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(file,<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// skip other formats</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocImage::DocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/docimage/#af627e9312a4cc758736ebaff6619990e">DocImage::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a434782653279e9f1d823656d48fe3e26">DocImage::height</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">DocImage::isInlineImage</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">DocImage::name</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a07a0f3e6897e73d26b36ad4430b885e5">DocImage::relPath</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">DocImage::type</a>, <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>, <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docimage/#a79d36f165096668a3d6631efb6e0b4f0">DocImage::width</a>.</p>

</div>
</div>

### operator()() {#a4f170949904015a222fd834618f71046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1263 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f170949904015a222fd834618f71046">1263</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5e78b0ed5635b833b739d63dafe452ff">startDotFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">relPath</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7d88687aa2a9c7544925377d4a967fc8">endDotFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a7d88687aa2a9c7544925377d4a967fc8">endDotFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">DocDiagramFileBase::relPath</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#a5e78b0ed5635b833b739d63dafe452ff">startDotFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#a5aa189a4fd5b9a6ff4647ffc13e70978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1273 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa189a4fd5b9a6ff4647ffc13e70978">1273</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5b2c9442335fc951437fc0cfb466c90c">startMscFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">relPath</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac5fa71d08ee9df28f986474abcf9eaf3">endMscFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ac5fa71d08ee9df28f986474abcf9eaf3">endMscFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">DocDiagramFileBase::relPath</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#a5b2c9442335fc951437fc0cfb466c90c">startMscFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#a789f7802c80a054fd7ee0d9e5f2fb4dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1283 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a789f7802c80a054fd7ee0d9e5f2fb4dc">1283</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">startDiaFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">relPath</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">endDiaFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">endDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">DocDiagramFileBase::relPath</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">startDiaFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#ac3af5572195fe68a70f0692dc9ab2ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1293 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3af5572195fe68a70f0692dc9ab2ea3">1293</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DOT_CLEANUP)) <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adbd00a8643be133e0b0cbef298202eeb">startPlantUmlFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">relPath</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>(),df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">srcFile</a>(),df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a64e204c832acb152c1909f650536d550">endPlantUmlFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a64e204c832acb152c1909f650536d550">endPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae1cf61673450bd090b7035f44b55d6ac">DocDiagramFileBase::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a1fd78aa1b7bcf4121959bdd285cb659c">DocDiagramFileBase::relPath</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a628b69cdd8bc779ec761f6336f0e6ce3">DocDiagramFileBase::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#abec28a2089907e37e518a3e160a488d5">DocDiagramFileBase::srcLine</a>, <a href="#adbd00a8643be133e0b0cbef298202eeb">startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#ac2e45c96a087cd77d7c8bd55c7c46a6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp; lnk)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1303 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2e45c96a087cd77d7c8bd55c7c46a6e">1303</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;lnk)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">file</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(lnk);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">DocLink::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">DocLink::file</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af1963a24dee9df501c8f65d4cdc02584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1312 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1963a24dee9df501c8f65d4cdc02584">1312</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ref.<a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">isSubPage</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">hasLinkText</a>()) <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">targetTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">DocRef::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">DocRef::file</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">DocRef::hasLinkText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">DocRef::isSubPage</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">DocRef::targetTitle</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a01dac5e12f73fbc5dd499dca9b16c946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1330 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01dac5e12f73fbc5dd499dca9b16c946">1330</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;tocentry xml:idref=\"_" &lt;&lt;  stripPath(ref-&gt;file()) &lt;&lt; "_1" &lt;&lt; ref-&gt;anchor() &lt;&lt; "\"&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tocentry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/tocentry&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aea2df716439077851a238f878500460e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1340 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea2df716439077851a238f878500460e">1340</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;toc&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/toc&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#acfb18992e55be4c79b5dad6a8b8ae4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1349 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfb18992e55be4c79b5dad6a8b8ae4b7">1349</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                &lt;formalpara&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                    &lt;title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>:         <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trParameters();         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>:        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturnValues();       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>:     <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptions();         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>: <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trTemplateParameters(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                    &lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                    &lt;table frame=\"all\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ncols = 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>() == <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasInOutSpecs = s.<a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasTypeSpecs  = s.<a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (hasInOutSpecs &amp;&amp; hasTypeSpecs) ncols += 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasInOutSpecs || hasTypeSpecs) ncols += 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                        &lt;tgroup cols=\""</span><span class="doxyHighlight"> &lt;&lt; ncols &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" align=\"left\" colsep=\"1\" rowsep=\"1\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 1; i &lt;= ncols; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i == ncols) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                        &lt;colspec colwidth=\"4*\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">            <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                        &lt;colspec colwidth=\"1*\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                        &lt;tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                        &lt;/tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                        &lt;/tgroup&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                    &lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                    &lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                &lt;/formalpara&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">DocParamSect::hasInOutSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">DocParamSect::hasTypeSpecifier</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a85d9cb1979f0d09164d205bfd447b494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp; pl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1399 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85d9cb1979f0d09164d205bfd447b494">1399</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;pl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                            &lt;row&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> *sect = std::get_if&lt;DocParamSect&gt;(pl.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()!=<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in,out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect &amp;&amp; sect-&gt;<a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;type : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;&lt;/entry&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cnt = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;param : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cnt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,param);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">      cnt++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;par : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,par);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                            &lt;/row&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">DocParamList::direction</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a7ec7b05c44ebac263741f2983cb4f6b3">DocParamSect::hasInOutSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ae994d0e9cc1d360aaa8d653042c929af">DocParamSect::hasTypeSpecifier</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">DocParamList::paragraphs</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">DocParamList::parameters</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">DocParamList::paramTypes</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>.</p>

</div>
</div>

### operator()() {#aa9a4faa0f71f2de7b7d2dad36d9af4e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp; x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1465 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9a4faa0f71f2de7b7d2dad36d9af4e7">1465</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;x)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;&lt;link linkend=\"_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/link&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(x);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">DocXRefItem::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">DocXRefItem::file</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">DocXRefItem::title</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa29700a65140a358d78dbb9b46f3e520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1481 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa29700a65140a358d78dbb9b46f3e520">1481</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">DocInternalRef::anchor</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">DocInternalRef::file</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab9b9df7cb5c9cf603f903416f7b31bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1491 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab9b9df7cb5c9cf603f903416f7b31bca">1491</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae5c4df795b9cbaacf62f451369d4ed53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1498 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5c4df795b9cbaacf62f451369d4ed53">1498</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;blockquote&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/blockquote&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a14b0a6b57523bfcdf584ce2b3f14e1fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1507 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a14b0a6b57523bfcdf584ce2b3f14e1fd">1507</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// TODO: to be implemented</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>.</p>

</div>
</div>

### operator()() {#a986a7c2b2b0094683654ef479b0204ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp; b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1513 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a986a7c2b2b0094683654ef479b0204ef">1513</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(b);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> and <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitChildren() {#a2cff69b37e830b8dba2fb54085606c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::visitChildren (const T &amp; t)</td>
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



<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2cff69b37e830b8dba2fb54085606c5d">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2cff69b37e830b8dba2fb54085606c5d">visitChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : t.children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Referenced by <a href="#a6316cd4b961705e7c3bfee3d7628af09">operator()</a>, <a href="#ae5fcc77a1bf0ac87ca740473f83ce834">operator()</a>, <a href="#a789f7802c80a054fd7ee0d9e5f2fb4dc">operator()</a>, <a href="#a4f170949904015a222fd834618f71046">operator()</a>, <a href="#a3db2ddaf8249d9e473d5fd51f106efd8">operator()</a>, <a href="#ae5c4df795b9cbaacf62f451369d4ed53">operator()</a>, <a href="#a2ed70425e19b1b76c43d7c2fa497e289">operator()</a>, <a href="#a9ecd666271d67f9e23a18d15f1f259e7">operator()</a>, <a href="#a73a37d31a03800401baf118ecad9e7d8">operator()</a>, <a href="#a3a24a7573ff52b20b5b852a72eb779a3">operator()</a>, <a href="#a52bcad32fdbc97d73c81802524cfce1c">operator()</a>, <a href="#a9392f6b1374f2be71799e29b52e27c29">operator()</a>, <a href="#adc99d97063bc21b16852e5345a5ff4f0">operator()</a>, <a href="#a2ef300f18d17dba697499319c88c8eb7">operator()</a>, <a href="#ab3dc4aca49387c2801b733951162e52c">operator()</a>, <a href="#ab21bc8c6017db61778cf6e60cea89abe">operator()</a>, <a href="#a14f3e3855449c3ee44c7e988e2fc4c38">operator()</a>, <a href="#ab9d3c8796370b41a72f6158fa461f5ca">operator()</a>, <a href="#aab82ef451cf5eff26b1d097aefd8d421">operator()</a>, <a href="#a2df620c0b51848655090f6d5e7ee5c26">operator()</a>, <a href="#aa29700a65140a358d78dbb9b46f3e520">operator()</a>, <a href="#ac2e45c96a087cd77d7c8bd55c7c46a6e">operator()</a>, <a href="#a5aa189a4fd5b9a6ff4647ffc13e70978">operator()</a>, <a href="#aa1add073cbb95e81ea333d8528797784">operator()</a>, <a href="#acfb18992e55be4c79b5dad6a8b8ae4b7">operator()</a>, <a href="#a986a7c2b2b0094683654ef479b0204ef">operator()</a>, <a href="#ac3af5572195fe68a70f0692dc9ab2ea3">operator()</a>, <a href="#af1963a24dee9df501c8f65d4cdc02584">operator()</a>, <a href="#a7f022b87284463cbdd463a89f13d7694">operator()</a>, <a href="#a01dac5e12f73fbc5dd499dca9b16c946">operator()</a>, <a href="#aea2df716439077851a238f878500460e">operator()</a>, <a href="#aad39609386bf77fe37c6e6a3861e92c5">operator()</a>, <a href="#a04c01d6cac8654f0a25efcf25fb783d6">operator()</a>, <a href="#a942b617cd956361afbd314539cab5922">operator()</a>, <a href="#ab9b9df7cb5c9cf603f903416f7b31bca">operator()</a>, <a href="#ad654cd7e66da83fdf2ff02f9bdcf34fd">operator()</a> and <a href="#aa9a4faa0f71f2de7b7d2dad36d9af4e7">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### endDiaFile() {#a0c5e2bcbdfe6dc01259ed748ca1fc0fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::endDiaFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 125 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1654 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">1654</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">DocbookDocVisitor::endDiaFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>.</p>


<p>Referenced by <a href="#a789f7802c80a054fd7ee0d9e5f2fb4dc">operator()</a>.</p>

</div>
</div>

### endDotFile() {#a7d88687aa2a9c7544925377d4a967fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::endDotFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1693 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d88687aa2a9c7544925377d4a967fc8">1693</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7d88687aa2a9c7544925377d4a967fc8">DocbookDocVisitor::endDotFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>.</p>


<p>Referenced by <a href="#a4f170949904015a222fd834618f71046">operator()</a>.</p>

</div>
</div>

### endLink() {#a4e805a87b4b320f63f31b6d29fe8bbd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::endLink ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1539 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">1539</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">DocbookDocVisitor::endLink</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/link&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>


<p>Referenced by <a href="#a5b206a0c1382df26146e64cde69d1085">operator()</a>, <a href="#aa29700a65140a358d78dbb9b46f3e520">operator()</a>, <a href="#ac2e45c96a087cd77d7c8bd55c7c46a6e">operator()</a>, <a href="#a29f23f1bb1c5d9e7c00ca23bae19be54">operator()</a> and <a href="#af1963a24dee9df501c8f65d4cdc02584">operator()</a>.</p>

</div>
</div>

### endMscFile() {#ac5fa71d08ee9df28f986474abcf9eaf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::endMscFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1616 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5fa71d08ee9df28f986474abcf9eaf3">1616</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac5fa71d08ee9df28f986474abcf9eaf3">DocbookDocVisitor::endMscFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>.</p>


<p>Referenced by <a href="#a5aa189a4fd5b9a6ff4647ffc13e70978">operator()</a>.</p>

</div>
</div>

### endPlantUmlFile() {#a64e204c832acb152c1909f650536d550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::endPlantUmlFile (bool hasCaption)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1588 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64e204c832acb152c1909f650536d550">1588</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64e204c832acb152c1909f650536d550">DocbookDocVisitor::endPlantUmlFile</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, hasCaption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>.</p>


<p>Referenced by <a href="#ac3af5572195fe68a70f0692dc9ab2ea3">operator()</a>.</p>

</div>
</div>

### filter() {#a1163472a0d3b1cc3359afdd861966aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::filter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const bool retainNewLine=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1521 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1163472a0d3b1cc3359afdd861966aee">1521</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1163472a0d3b1cc3359afdd861966aee">DocbookDocVisitor::filter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retainNewLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(str, retainNewLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a> and <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>.</p>


<p>Referenced by <a href="#a5b206a0c1382df26146e64cde69d1085">operator()</a>, <a href="#a5826ce8044be2553216f205ef64ead74">operator()</a>, <a href="#a1f5c051f908207108e9a88c130a79703">operator()</a>, <a href="#a29f23f1bb1c5d9e7c00ca23bae19be54">operator()</a>, <a href="#af1963a24dee9df501c8f65d4cdc02584">operator()</a>, <a href="#aca919f8124510f7e03ef62e8def34408">operator()</a>, <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>, <a href="#a0e98d6606eee027d17aebcbe7ad90c85">operator()</a> and <a href="#aa9a4faa0f71f2de7b7d2dad36d9af4e7">operator()</a>.</p>

</div>
</div>

### startDiaFile() {#a3f3e26e49bf3e76bc2b4ab003b2f79f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::startDiaFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1635 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">1635</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">DocbookDocVisitor::startDiaFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName.prepend(</span><span class="doxyHighlightStringLiteral">"dia_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>(fileName,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">DiaOutputFormat::BITMAP</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, children, hasCaption, relPath + baseName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">,  width,  height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> and <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>.</p>


<p>Referenced by <a href="#a789f7802c80a054fd7ee0d9e5f2fb4dc">operator()</a>.</p>

</div>
</div>

### startDotFile() {#a5e78b0ed5635b833b739d63dafe452ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::startDotFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1673 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e78b0ed5635b833b739d63dafe452ff">1673</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e78b0ed5635b833b739d63dafe452ff">DocbookDocVisitor::startDotFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName.prepend(</span><span class="doxyHighlightStringLiteral">"dot_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>(fileName,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, children, hasCaption, relPath + baseName + </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight"> + imgExt,  width,  height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>.</p>


<p>Referenced by <a href="#a4f170949904015a222fd834618f71046">operator()</a>.</p>

</div>
</div>

### startLink() {#a32ae4842f51bff5b91ddb9f00815ddb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::startLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1527 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32ae4842f51bff5b91ddb9f00815ddb0">1527</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">DocbookDocVisitor::startLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;link linkend=\"_"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.</p>


<p>Referenced by <a href="#a5b206a0c1382df26146e64cde69d1085">operator()</a>, <a href="#a3db2ddaf8249d9e473d5fd51f106efd8">operator()</a>, <a href="#aa29700a65140a358d78dbb9b46f3e520">operator()</a>, <a href="#ac2e45c96a087cd77d7c8bd55c7c46a6e">operator()</a>, <a href="#a29f23f1bb1c5d9e7c00ca23bae19be54">operator()</a> and <a href="#af1963a24dee9df501c8f65d4cdc02584">operator()</a>.</p>

</div>
</div>

### startMscFile() {#a5b2c9442335fc951437fc0cfb466c90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::startMscFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1597 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b2c9442335fc951437fc0cfb466c90c">1597</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b2c9442335fc951437fc0cfb466c90c">DocbookDocVisitor::startMscFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName.prepend(</span><span class="doxyHighlightStringLiteral">"msc_"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>(fileName,outDir,baseName,<a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">MscOutputFormat::BITMAP</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, children, hasCaption, relPath + baseName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">,  width,  height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> and <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>.</p>


<p>Referenced by <a href="#a5aa189a4fd5b9a6ff4647ffc13e70978">operator()</a>.</p>

</div>
</div>

### startPlantUmlFile() {#adbd00a8643be133e0b0cbef298202eeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::startPlantUmlFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool hasCaption, const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1566 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbd00a8643be133e0b0cbef298202eeb">1566</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adbd00a8643be133e0b0cbef298202eeb">DocbookDocVisitor::startPlantUmlFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">    )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string inBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>(fileName,inBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName = <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">writePlantUMLSource</a>(outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),inBuf.c_str(),<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),srcFile,srcLine,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">  baseName=<a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">generatePlantUMLOutput</a>(baseName,outDir,<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af24830382b069d6de946df1d470b96b9">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, children, hasCaption, relPath + baseName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">,  width,  height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>.</p>


<p>Referenced by <a href="#ac3af5572195fe68a70f0692dc9ab2ea3">operator()</a>.</p>

</div>
</div>

### visitCaption() {#a66c441845e0df61b24765db6edb18e66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::visitCaption (const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 145 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66c441845e0df61b24765db6edb18e66">110</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a66c441845e0df61b24765db6edb18e66">DocbookDocVisitor::visitCaption</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;n : children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>, <a href="#a6db6e8f6eb6422a68ea68af67795231f">writeDiaFile</a>, <a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a>, <a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a> and <a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a>.</p>

</div>
</div>

### visitPostEnd() {#a967d064892372b073b3a74596cd728bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::visitPostEnd (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool hasCaption, bool inlineImage=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a967d064892372b073b3a74596cd728bc">161</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a967d064892372b073b3a74596cd728bc">DocbookDocVisitor::visitPostEnd</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption &amp;&amp; !inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        --&gt;\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// Needed for general formatting with title for other formats</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/mediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption &amp;&amp; !inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/figure&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/informalfigure&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">endDiaFile</a>, <a href="#a7d88687aa2a9c7544925377d4a967fc8">endDotFile</a>, <a href="#ac5fa71d08ee9df28f986474abcf9eaf3">endMscFile</a>, <a href="#a64e204c832acb152c1909f650536d550">endPlantUmlFile</a>, <a href="#aab82ef451cf5eff26b1d097aefd8d421">operator()</a>, <a href="#a6db6e8f6eb6422a68ea68af67795231f">writeDiaFile</a>, <a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a>, <a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a> and <a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a>.</p>

</div>
</div>

### visitPreStart() {#a0c4f7806424406a4dddeaf5c916abb5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::visitPreStart (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp; children, bool hasCaption, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; width, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; height, bool inlineImage=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c4f7806424406a4dddeaf5c916abb5e">118</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c4f7806424406a4dddeaf5c916abb5e">DocbookDocVisitor::visitPreStart</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;children,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCaption,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;width,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption &amp;&amp; !inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;figure&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>(children);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;informalfigure&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;mediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;imageobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                &lt;imagedata"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!width.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" width=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(width) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!height.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !inlineImage) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" width=\"50%\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!height.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" depth=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(height) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align=\"center\" valign=\"middle\" scalefit=\"0\" fileref=\""</span><span class="doxyHighlight"> &lt;&lt; name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/imagedata&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;/imageobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCaption &amp;&amp; !inlineImage)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;!--\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// Needed for general formatting with title for other formats</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>.</p>


<p>Referenced by <a href="#aab82ef451cf5eff26b1d097aefd8d421">operator()</a>, <a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">startDiaFile</a>, <a href="#a5e78b0ed5635b833b739d63dafe452ff">startDotFile</a>, <a href="#a5b2c9442335fc951437fc0cfb466c90c">startMscFile</a>, <a href="#adbd00a8643be133e0b0cbef298202eeb">startPlantUmlFile</a>, <a href="#a6db6e8f6eb6422a68ea68af67795231f">writeDiaFile</a>, <a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a>, <a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a> and <a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a>.</p>

</div>
</div>

### writeDiaFile() {#a6db6e8f6eb6422a68ea68af67795231f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::writeDiaFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1624 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6db6e8f6eb6422a68ea68af67795231f">1624</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6db6e8f6eb6422a68ea68af67795231f">DocbookDocVisitor::writeDiaFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>(baseName+</span><span class="doxyHighlightStringLiteral">".dia"</span><span class="doxyHighlight">,outDir,shortName,<a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">DiaOutputFormat::BITMAP</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), shortName, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>, <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a> and <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>.</p>

</div>
</div>

### writeDotFile() {#a0bf39b3fd2c1a92324de55df8009ed60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::writeDotFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1662 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0bf39b3fd2c1a92324de55df8009ed60">1662</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0bf39b3fd2c1a92324de55df8009ed60">DocbookDocVisitor::writeDotFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>(baseName+</span><span class="doxyHighlightStringLiteral">".dot"</span><span class="doxyHighlight">,outDir,shortName,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ab9d8c60112cd8bfa12498c07d528b2f6">relPath</a>() + shortName + </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ab9d8c60112cd8bfa12498c07d528b2f6">DocVerbatim::relPath</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>, <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>.</p>


<p>Referenced by <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>.</p>

</div>
</div>

### writeMscFile() {#a370d999e7360a39203535dff006b1bf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::writeMscFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1545 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a370d999e7360a39203535dff006b1bf2">1545</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a370d999e7360a39203535dff006b1bf2">DocbookDocVisitor::writeMscFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>(baseName+</span><span class="doxyHighlightStringLiteral">".msc"</span><span class="doxyHighlight">,outDir,shortName,<a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">MscOutputFormat::BITMAP</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">srcFile</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">srcLine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ab9d8c60112cd8bfa12498c07d528b2f6">relPath</a>() + shortName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/msc-h/#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ab9d8c60112cd8bfa12498c07d528b2f6">DocVerbatim::relPath</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a00d25459191993cb5c8f83322bc24aef">DocVerbatim::srcFile</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1e8e40ae888c52c7623ca29506c54518">DocVerbatim::srcLine</a>, <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>, <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a> and <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>.</p>


<p>Referenced by <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>.</p>

</div>
</div>

### writePlantUMLFile() {#ab259d2b0e06461957346bd3de5bb52e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookDocVisitor::writePlantUMLFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>, definition at line 1556 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab259d2b0e06461957346bd3de5bb52e0">1556</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab259d2b0e06461957346bd3de5bb52e0">DocbookDocVisitor::writePlantUMLFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortName = <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>(baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outDir = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>().<a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">generatePlantUMLOutput</a>(baseName,outDir,<a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ab9d8c60112cd8bfa12498c07d528b2f6">relPath</a>() + shortName + </span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>(<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#af6f1c6249e4127996095d0086442fa0f">PlantumlManager::generatePlantUMLOutput</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#ae264d99d8756b63a55c341b4768ad28b">PlantumlManager::instance</a>, <a href="#af24830382b069d6de946df1d470b96b9">m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a973cf8133612a97554efd32640eef752">makeShortName</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a73ccdfc6400a28af7d9d2f92215b9af5a1414704243dc148d478bed8064a73046">PlantumlManager::PUML_BITMAP</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ab9d8c60112cd8bfa12498c07d528b2f6">DocVerbatim::relPath</a>, <a href="#a66c441845e0df61b24765db6edb18e66">visitCaption</a>, <a href="#a967d064892372b073b3a74596cd728bc">visitPostEnd</a>, <a href="#a0c4f7806424406a4dddeaf5c916abb5e">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a>.</p>


<p>Referenced by <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_bodySet {#a1b8d240d1bf94c09bdca5cea6fce0a9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoolStack DocbookDocVisitor::m_bodySet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#a196a2e77992700eb36c42485adaed6de">BoolStack</a> <a href="#a1b8d240d1bf94c09bdca5cea6fce0a9c">m_bodySet</a>; </span><span class="doxyHighlightComment">// it is possible to have tables without a header, needs to be an array as we can have tables in tables</span></span></div>

</div>


<p>Referenced by <a href="#ab21bc8c6017db61778cf6e60cea89abe">operator()</a> and <a href="#ab9d3c8796370b41a72f6158fa461f5ca">operator()</a>.</p>

</div>
</div>

### m\_ci {#a56f68274053bac20df8dacf4f3b1b0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList&amp; DocbookDocVisitor::m_ci</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56f68274053bac20df8dacf4f3b1b0ff">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#a56f68274053bac20df8dacf4f3b1b0ff">m_ci</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ace8d7feef248a290d19da45c81f0ea26">DocbookDocVisitor</a>, <a href="#a5826ce8044be2553216f205ef64ead74">operator()</a>, <a href="#a1abe1e85619493e4e99240d290c3bdd2">operator()</a> and <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>.</p>

</div>
</div>

### m\_colCnt {#a01aadb154b00bb7962d61a8c016800aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocbookDocVisitor::m_colCnt = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01aadb154b00bb7962d61a8c016800aa">155</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a01aadb154b00bb7962d61a8c016800aa">m_colCnt</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a9ecd666271d67f9e23a18d15f1f259e7">operator()</a> and <a href="#ab21bc8c6017db61778cf6e60cea89abe">operator()</a>.</p>

</div>
</div>

### m\_enabled {#afcb5ab6dc99ae7b20888cc7b8af544bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoolStack DocbookDocVisitor::m_enabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcb5ab6dc99ae7b20888cc7b8af544bf">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#a196a2e77992700eb36c42485adaed6de">BoolStack</a> <a href="#afcb5ab6dc99ae7b20888cc7b8af544bf">m_enabled</a>;</span></span></div>

</div>

</div>
</div>

### m\_hide {#ae883ef6f0124054b0c9bafb1ab5206b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookDocVisitor::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae883ef6f0124054b0c9bafb1ab5206b9">152</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae883ef6f0124054b0c9bafb1ab5206b9">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">endDiaFile</a>, <a href="#a7d88687aa2a9c7544925377d4a967fc8">endDotFile</a>, <a href="#ac5fa71d08ee9df28f986474abcf9eaf3">endMscFile</a>, <a href="#a64e204c832acb152c1909f650536d550">endPlantUmlFile</a>, <a href="#ab7fced02c41e630be0ba0d38ec7445e4">operator()</a>, <a href="#a6316cd4b961705e7c3bfee3d7628af09">operator()</a>, <a href="#ae5fcc77a1bf0ac87ca740473f83ce834">operator()</a>, <a href="#a5b206a0c1382df26146e64cde69d1085">operator()</a>, <a href="#a789f7802c80a054fd7ee0d9e5f2fb4dc">operator()</a>, <a href="#a4f170949904015a222fd834618f71046">operator()</a>, <a href="#a0eca51c43b643d592b22070d062a3b77">operator()</a>, <a href="#a633ea27d943ce438a831b1043b37af8c">operator()</a>, <a href="#a391493662c00d8761a7b1817c0c6e6d7">operator()</a>, <a href="#a3db2ddaf8249d9e473d5fd51f106efd8">operator()</a>, <a href="#ae5c4df795b9cbaacf62f451369d4ed53">operator()</a>, <a href="#a2ed70425e19b1b76c43d7c2fa497e289">operator()</a>, <a href="#a9ecd666271d67f9e23a18d15f1f259e7">operator()</a>, <a href="#a73a37d31a03800401baf118ecad9e7d8">operator()</a>, <a href="#a3a24a7573ff52b20b5b852a72eb779a3">operator()</a>, <a href="#a52bcad32fdbc97d73c81802524cfce1c">operator()</a>, <a href="#a9392f6b1374f2be71799e29b52e27c29">operator()</a>, <a href="#adc99d97063bc21b16852e5345a5ff4f0">operator()</a>, <a href="#a2ef300f18d17dba697499319c88c8eb7">operator()</a>, <a href="#ab3dc4aca49387c2801b733951162e52c">operator()</a>, <a href="#ab21bc8c6017db61778cf6e60cea89abe">operator()</a>, <a href="#a14f3e3855449c3ee44c7e988e2fc4c38">operator()</a>, <a href="#ab9d3c8796370b41a72f6158fa461f5ca">operator()</a>, <a href="#aab82ef451cf5eff26b1d097aefd8d421">operator()</a>, <a href="#a5826ce8044be2553216f205ef64ead74">operator()</a>, <a href="#a1abe1e85619493e4e99240d290c3bdd2">operator()</a>, <a href="#a1f5c051f908207108e9a88c130a79703">operator()</a>, <a href="#a2df620c0b51848655090f6d5e7ee5c26">operator()</a>, <a href="#aa29700a65140a358d78dbb9b46f3e520">operator()</a>, <a href="#abd98eb5e7a8634efc8df1ed1580ac99a">operator()</a>, <a href="#ac2e45c96a087cd77d7c8bd55c7c46a6e">operator()</a>, <a href="#a29f23f1bb1c5d9e7c00ca23bae19be54">operator()</a>, <a href="#a5aa189a4fd5b9a6ff4647ffc13e70978">operator()</a>, <a href="#aa1add073cbb95e81ea333d8528797784">operator()</a>, <a href="#a85d9cb1979f0d09164d205bfd447b494">operator()</a>, <a href="#acfb18992e55be4c79b5dad6a8b8ae4b7">operator()</a>, <a href="#a986a7c2b2b0094683654ef479b0204ef">operator()</a>, <a href="#ac3af5572195fe68a70f0692dc9ab2ea3">operator()</a>, <a href="#af1963a24dee9df501c8f65d4cdc02584">operator()</a>, <a href="#a01dac5e12f73fbc5dd499dca9b16c946">operator()</a>, <a href="#aea2df716439077851a238f878500460e">operator()</a>, <a href="#aad39609386bf77fe37c6e6a3861e92c5">operator()</a>, <a href="#aff7829d4c3cf2759e0eca9b3abbc5173">operator()</a>, <a href="#a04c01d6cac8654f0a25efcf25fb783d6">operator()</a>, <a href="#a5d1246ae30e71d074a6fb40c745494cc">operator()</a>, <a href="#a942b617cd956361afbd314539cab5922">operator()</a>, <a href="#aa5dd013610540bba019aaef10157b416">operator()</a>, <a href="#af30a5c4fe2669a2bdb78dd0c964af909">operator()</a>, <a href="#ad654cd7e66da83fdf2ff02f9bdcf34fd">operator()</a>, <a href="#aca919f8124510f7e03ef62e8def34408">operator()</a>, <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>, <a href="#ab014c099dfdb3ac2e7cda9129c153253">operator()</a>, <a href="#a0e98d6606eee027d17aebcbe7ad90c85">operator()</a> and <a href="#aa9a4faa0f71f2de7b7d2dad36d9af4e7">operator()</a>.</p>

</div>
</div>

### m\_insidePre {#a21cf9cd7915c577d65d4b632f97daeba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookDocVisitor::m_insidePre = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21cf9cd7915c577d65d4b632f97daeba">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a21cf9cd7915c577d65d4b632f97daeba">m_insidePre</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a942b617cd956361afbd314539cab5922">operator()</a>, <a href="#aa5dd013610540bba019aaef10157b416">operator()</a> and <a href="#ab014c099dfdb3ac2e7cda9129c153253">operator()</a>.</p>

</div>
</div>

### m\_langExt {#ae422387d0ce5093fd1cc1cd84666fe0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookDocVisitor::m_langExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae422387d0ce5093fd1cc1cd84666fe0b">154</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae422387d0ce5093fd1cc1cd84666fe0b">m_langExt</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ace8d7feef248a290d19da45c81f0ea26">DocbookDocVisitor</a>, <a href="#a1abe1e85619493e4e99240d290c3bdd2">operator()</a> and <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>.</p>

</div>
</div>

### m\_t {#af24830382b069d6de946df1d470b96b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream&amp; DocbookDocVisitor::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af24830382b069d6de946df1d470b96b9">149</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#af24830382b069d6de946df1d470b96b9">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ace8d7feef248a290d19da45c81f0ea26">DocbookDocVisitor</a>, <a href="#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">endDiaFile</a>, <a href="#a7d88687aa2a9c7544925377d4a967fc8">endDotFile</a>, <a href="#a4e805a87b4b320f63f31b6d29fe8bbd6">endLink</a>, <a href="#ac5fa71d08ee9df28f986474abcf9eaf3">endMscFile</a>, <a href="#a64e204c832acb152c1909f650536d550">endPlantUmlFile</a>, <a href="#a1163472a0d3b1cc3359afdd861966aee">filter</a>, <a href="#ab7fced02c41e630be0ba0d38ec7445e4">operator()</a>, <a href="#a6316cd4b961705e7c3bfee3d7628af09">operator()</a>, <a href="#ae5fcc77a1bf0ac87ca740473f83ce834">operator()</a>, <a href="#a0eca51c43b643d592b22070d062a3b77">operator()</a>, <a href="#a633ea27d943ce438a831b1043b37af8c">operator()</a>, <a href="#a391493662c00d8761a7b1817c0c6e6d7">operator()</a>, <a href="#a3db2ddaf8249d9e473d5fd51f106efd8">operator()</a>, <a href="#ae5c4df795b9cbaacf62f451369d4ed53">operator()</a>, <a href="#a2ed70425e19b1b76c43d7c2fa497e289">operator()</a>, <a href="#a9ecd666271d67f9e23a18d15f1f259e7">operator()</a>, <a href="#a73a37d31a03800401baf118ecad9e7d8">operator()</a>, <a href="#a3a24a7573ff52b20b5b852a72eb779a3">operator()</a>, <a href="#a52bcad32fdbc97d73c81802524cfce1c">operator()</a>, <a href="#a9392f6b1374f2be71799e29b52e27c29">operator()</a>, <a href="#adc99d97063bc21b16852e5345a5ff4f0">operator()</a>, <a href="#a2ef300f18d17dba697499319c88c8eb7">operator()</a>, <a href="#ab3dc4aca49387c2801b733951162e52c">operator()</a>, <a href="#ab21bc8c6017db61778cf6e60cea89abe">operator()</a>, <a href="#a14f3e3855449c3ee44c7e988e2fc4c38">operator()</a>, <a href="#ab9d3c8796370b41a72f6158fa461f5ca">operator()</a>, <a href="#aab82ef451cf5eff26b1d097aefd8d421">operator()</a>, <a href="#a5826ce8044be2553216f205ef64ead74">operator()</a>, <a href="#a1abe1e85619493e4e99240d290c3bdd2">operator()</a>, <a href="#a1f5c051f908207108e9a88c130a79703">operator()</a>, <a href="#aa29700a65140a358d78dbb9b46f3e520">operator()</a>, <a href="#abd98eb5e7a8634efc8df1ed1580ac99a">operator()</a>, <a href="#aa1add073cbb95e81ea333d8528797784">operator()</a>, <a href="#a85d9cb1979f0d09164d205bfd447b494">operator()</a>, <a href="#acfb18992e55be4c79b5dad6a8b8ae4b7">operator()</a>, <a href="#a01dac5e12f73fbc5dd499dca9b16c946">operator()</a>, <a href="#aea2df716439077851a238f878500460e">operator()</a>, <a href="#aad39609386bf77fe37c6e6a3861e92c5">operator()</a>, <a href="#aff7829d4c3cf2759e0eca9b3abbc5173">operator()</a>, <a href="#a04c01d6cac8654f0a25efcf25fb783d6">operator()</a>, <a href="#a5d1246ae30e71d074a6fb40c745494cc">operator()</a>, <a href="#a942b617cd956361afbd314539cab5922">operator()</a>, <a href="#aa5dd013610540bba019aaef10157b416">operator()</a>, <a href="#af30a5c4fe2669a2bdb78dd0c964af909">operator()</a>, <a href="#ad654cd7e66da83fdf2ff02f9bdcf34fd">operator()</a>, <a href="#aca919f8124510f7e03ef62e8def34408">operator()</a>, <a href="#a4931bb0ccd2eb4d8aede2a9afb7058d6">operator()</a>, <a href="#ab014c099dfdb3ac2e7cda9129c153253">operator()</a>, <a href="#aa9a4faa0f71f2de7b7d2dad36d9af4e7">operator()</a>, <a href="#a3f3e26e49bf3e76bc2b4ab003b2f79f4">startDiaFile</a>, <a href="#a5e78b0ed5635b833b739d63dafe452ff">startDotFile</a>, <a href="#a32ae4842f51bff5b91ddb9f00815ddb0">startLink</a>, <a href="#a5b2c9442335fc951437fc0cfb466c90c">startMscFile</a>, <a href="#adbd00a8643be133e0b0cbef298202eeb">startPlantUmlFile</a>, <a href="#a6db6e8f6eb6422a68ea68af67795231f">writeDiaFile</a>, <a href="#a0bf39b3fd2c1a92324de55df8009ed60">writeDotFile</a>, <a href="#a370d999e7360a39203535dff006b1bf2">writeMscFile</a> and <a href="#ab259d2b0e06461957346bd3de5bb52e0">writePlantUMLFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
