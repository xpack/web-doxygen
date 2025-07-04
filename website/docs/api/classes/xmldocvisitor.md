---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/xmldocvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XmlDocVisitor` Class Reference

<p>Concrete visitor implementation for XML output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class XmlDocVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">src/xmldocvisitor.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a> (TextStream &amp;t, OutputCodeList &amp;ci, const QCString &amp;langExt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafdda01946f77377d8007cb92e156df">operator()</a> (const DocWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38f30197ee604df5323ed695d9e4bfc1">operator()</a> (const DocLinkedWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1580dc76cff9388253fc5f0214b8bf">operator()</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f36acc2f17b5a95a12d047ed0f4d08">operator()</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac090b55ba575d25794fb3cdce0e02967">operator()</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6530d993517830bcb20a2ccc86e4fa3e">operator()</a> (const DocURL &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6279ee10c3fb05d9c6410106f90f2c1">operator()</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a894a0ee995fa505268bd52cb4b50be01">operator()</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3356483b754f0dab670ad4a1407f98">operator()</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">operator()</a> (const DocVerbatim &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac971dec0f2cd21a3975be1cbd00b34a8">operator()</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32d2017f02e0835ea865360773ac1eda">operator()</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac219ce4773970158e118d1d3b57ebd78">operator()</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7074792ea780e43a5ed6f1b3b8bae2eb">operator()</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3337e1132c6c023a23199cd93cb1fa18">operator()</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888662f4192f8c5d448e84b9faa1cbf0">operator()</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31e19a340fe2392303f138f3d0d046f0">operator()</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff89169f10e0104095bba0d9029d6ba6">operator()</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0130a36f03912eae004a687497d280e2">operator()</a> (const DocAutoList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086d9184f4174d34a09c85ae729a6326">operator()</a> (const DocAutoListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab90634212dbc2f235c0e2d6093b3c4b0">operator()</a> (const DocPara &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0303c24c19d33c6ec4bac50efc43b9b3">operator()</a> (const DocRoot &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8592f34797e03f25475a23b9ee7f9e29">operator()</a> (const DocSimpleSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a558e9807cce6b45e0a8b87d8355a97f1">operator()</a> (const DocTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707992f9ca42c2d8b5d322e61fda8ad9">operator()</a> (const DocSimpleList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fc08e18c0395ca5855cbb69d9cde19">operator()</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11012240cba58c78041715a6c963b350">operator()</a> (const DocSection &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5522b266c9dcf8df929ec4b4ca1d5e5">operator()</a> (const DocHtmlList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa429846d5df9551f2226db222c3cb0">operator()</a> (const DocHtmlListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c24501c95550ca20853061c65621c3">operator()</a> (const DocHtmlDescList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4dea55a84e8249cd292b760e1469e7">operator()</a> (const DocHtmlDescTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc801c44d435c860eb0c4e72b7687d9">operator()</a> (const DocHtmlDescData &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0655fab12e9ffece836f11b46a8c44">operator()</a> (const DocHtmlTable &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b8a51b96265ea51fcf3b68eb7a22be4">operator()</a> (const DocHtmlRow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123cf8763db886cf114983b68532e034">operator()</a> (const DocHtmlCell &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55bc41271c5cfa6920f32fd8142ce31">operator()</a> (const DocHtmlCaption &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c7fbf7fd8d248ccedcc9c42edb7ea4">operator()</a> (const DocInternal &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9d445166ed91d40a7ff249c8f262d21">operator()</a> (const DocHRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5bd33699c39b682c2f8628da1ce5e9">operator()</a> (const DocHtmlSummary &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de7175b4fed07fac30cb69f45bd9d71">operator()</a> (const DocHtmlDetails &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73746a7f0fbddc7813a141f7700a72e5">operator()</a> (const DocHtmlHeader &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608907da6a8263ac7cff6caae01673c9">operator()</a> (const DocImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c8677143c5ae39bcfedcdac6b518a4">operator()</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2acf19e70d566ecbaec05b214a437d">operator()</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59ea834b25f5117addb171ba0ec6259">operator()</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71b99c9086e5c3e82c7947cd9f256eb9">operator()</a> (const DocPlantUmlFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99f84e51bf6f28fbcd36d90b1c1e34c">operator()</a> (const DocLink &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">operator()</a> (const DocRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8bc2ce89c9b20a8b9879393aa6108f">operator()</a> (const DocSecRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a484adec7f67b66fe540d1d227ac92fa5">operator()</a> (const DocSecRefList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8613537dce42682e941104234d73477c">operator()</a> (const DocParamSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff7d5a66db3412ce103eeb44fee565c">operator()</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd694108a8abefd6d6d7be9c7bba21cc">operator()</a> (const DocXRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">operator()</a> (const DocInternalRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c1c416a453b6eefd45bc560c2c86aa7">operator()</a> (const DocText &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e60bb1a2c3b9aa23335cde3cc022019">operator()</a> (const DocHtmlBlockQuote &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38fa85a8ee30ae6262d53581787f63b7">operator()</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf510cbb1888d94cc76a20782985c02">operator()</a> (const DocParBlock &amp;)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a> (const T &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a> (const QCString &amp;str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa013b821ca9681befa4786b6877709">startLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a></td>
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

<p>Concrete visitor implementation for XML output.</p>

<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### XmlDocVisitor() {#a7c793fb726834b10d3a13071c6279374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XmlDocVisitor::XmlDocVisitor (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ci, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; langExt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c793fb726834b10d3a13071c6279374">151</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor::XmlDocVisitor</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ci,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;langExt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>(t), <a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>(ci), <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>), <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>(langExt), <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>(0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a>, <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>, <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#acafdda01946f77377d8007cb92e156df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 161 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acafdda01946f77377d8007cb92e156df">161</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(w.<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.</p>

</div>
</div>

### operator()() {#a38f30197ee604df5323ed695d9e4bfc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38f30197ee604df5323ed695d9e4bfc1">167</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">ref</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">file</a>(),w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doclinkedword/#aa660e6600aa99dc591e1c7cc915f6d7c">DocLinkedWord::anchor</a>, <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a87a6514222a5dc65f0fe4420c916d3be">DocLinkedWord::file</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="/web-doxygen/docs/api/classes/doclinkedword/#a956ecf12c5e819f4cb3d1d742e0779c2">DocLinkedWord::ref</a>, <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a> and <a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">DocLinkedWord::word</a>.</p>

</div>
</div>

### operator()() {#a5a1580dc76cff9388253fc5f0214b8bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a1580dc76cff9388253fc5f0214b8bf">175</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">DocWhiteSpace::chars</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

### operator()() {#ad9f36acc2f17b5a95a12d047ed0f4d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9f36acc2f17b5a95a12d047ed0f4d08">188</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a6359802a6779aa5f0245357d974c3bd1">xml</a>(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"XML: non supported HTML-entity found: {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().html(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">DocSymbol::symbol</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a6359802a6779aa5f0245357d974c3bd1">HtmlEntityMapper::xml</a>.</p>

</div>
</div>

### operator()() {#ac090b55ba575d25794fb3cdce0e02967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac090b55ba575d25794fb3cdce0e02967">202</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">name</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    name = name.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;emoji name=\""</span><span class="doxyHighlight"> &lt;&lt; name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" unicode=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().unicode(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">DocEmoji::index</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">DocEmoji::name</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">EmojiEntityMapper::name</a>.</p>

</div>
</div>

### operator()() {#a6530d993517830bcb20a2ccc86e4fa3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp; u)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6530d993517830bcb20a2ccc86e4fa3e">220</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;ulink url=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (u.<a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">isEmail</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"mailto:"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/ulink&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/docurl/#ac2e7983ca9569098860da2ce21fa25f6">DocURL::isEmail</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">DocURL::url</a>.</p>

</div>
</div>

### operator()() {#aa6279ee10c3fb05d9c6410106f90f2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6279ee10c3fb05d9c6410106f90f2c1">231</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;linebreak/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a894a0ee995fa505268bd52cb4b50be01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a894a0ee995fa505268bd52cb4b50be01">237</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;hruler/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

### operator()() {#aac3356483b754f0dab670ad4a1407f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3356483b754f0dab670ad4a1407f98">243</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;bold&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/bold&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;s&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/s&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;strike&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/strike&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;del&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/del&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;underline&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/underline&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;ins&gt;"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/ins&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;emphasis&gt;"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;subscript&gt;"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/subscript&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;superscript&gt;"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/superscript&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;center&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/center&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;small&gt;"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/small&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;cite&gt;"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/cite&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;preformatted&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/preformatted&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>:  </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>: </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">DocStyleChange::enable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>.</p>

</div>
</div>

### operator()() {#ae2f1f49b8496f09377c4e7de91e2f3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 306 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">306</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang = <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// explicit language setting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    lang = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" filename=\""</span><span class="doxyHighlight"> &lt;&lt; lang &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(lang).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">context</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">                                    <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(STRIP_CODE_COMMENTS),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">                                    s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">isExample</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;javadocliteral&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/javadocliteral&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;javadoccode&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/javadoccode&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;verbatim&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/verbatim&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a52966dec2b3158261a05706d39516e98">isBlock</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;htmlonly block=\"yes\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;htmlonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/htmlonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;rtfonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/rtfonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;manonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/manonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;latexonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/latexonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;docbookonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/docbookonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"dot"</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(), <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"dot"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"msc"</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(),  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"msc"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"plantuml"</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">hasCaption</a>(), *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">children</a>(),  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, s.<a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">width</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">height</a>(), s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">engine</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"plantuml"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docverbatim/#a3cd10cfddf4f4d971fe573226ca4f522">DocVerbatim::children</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">DocVerbatim::context</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a8b8656dd3666ad17f4bf5a7e3690cfcd">DocVerbatim::engine</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">DocVerbatim::exampleFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a2f48fffda3a45f9f6127aa1cc1642cf0">DocVerbatim::hasCaption</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a1fd8c264ec55a734efd2f2ab890ef5d4">DocVerbatim::height</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a52966dec2b3158261a05706d39516e98">DocVerbatim::isBlock</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">DocVerbatim::isExample</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">DocVerbatim::language</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>, <a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">DocVerbatim::text</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">DocVerbatim::type</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ae68d4f3d6bdd5787627a0b7f4e44d3c2">DocVerbatim::width</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>.</p>

</div>
</div>

### operator()() {#ac971dec0f2cd21a3975be1cbd00b34a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp; anc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 396 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac971dec0f2cd21a3975be1cbd00b34a8">396</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;anc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;anchor id=\""</span><span class="doxyHighlight"> &lt;&lt; anc.<a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">file</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; anc.<a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docanchor/#aa2b10316da4800824d00ed52d8eee959">DocAnchor::anchor</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#ae8a62d8e80af9d1cf04561fcbe07c343">DocAnchor::file</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a32d2017f02e0835ea865360773ac1eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp; inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 402 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32d2017f02e0835ea865360773ac1eda">402</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;inc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("XMLDocVisitor: DocInclude type=%d trimleft=%d\n",inc.type(),inc.trimLeft());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting filename=\""</span><span class="doxyHighlight"> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">                                           langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">                                           fd.get(), </span><span class="doxyHighlightComment">// fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">                                           -1,    </span><span class="doxyHighlightComment">// start line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">                                           -1,    </span><span class="doxyHighlightComment">// end line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>   </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                                           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting filename=\""</span><span class="doxyHighlight"> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">                                        langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,  </span><span class="doxyHighlightComment">// inlineFragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">                                       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a135bf24f61094b5ccd0f11184a689105">isBlock</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;htmlonly block=\"yes\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;htmlonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/htmlonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;latexonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/latexonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;rtfonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/rtfonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;manonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/manonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;docbookonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/docbookonly&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;verbatim&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/verbatim&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting filename=\""</span><span class="doxyHighlight"> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>().<a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a>(<a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                                       inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">                                       inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">                                       inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">                                       inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>()==<a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">                                       inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">                                       inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">                                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">DocInclude::blockId</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">DocInclude::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">DocInclude::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">DocInclude::extension</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">DocInclude::file</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a135bf24f61094b5ccd0f11184a689105">DocInclude::isBlock</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">DocInclude::isExample</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>, <a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">DocInclude::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">DocInclude::text</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">DocInclude::trimLeft</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">DocInclude::type</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a> and <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>.</p>

</div>
</div>

### operator()() {#ac219ce4773970158e118d1d3b57ebd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp; op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 506 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac219ce4773970158e118d1d3b57ebd78">506</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;op)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocIncOperator: type=%d first=%d, last=%d text='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    op.type(),op.isFirst(),op.isLast(),qPrint(op.text()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">isFirst</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting filename=\""</span><span class="doxyHighlight"> &lt;&lt; op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locLangExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locLangExt.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) locLangExt = <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(locLangExt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">type</a>()!=<a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_ptr&lt;FileDef&gt; fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">        fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(locLangExt).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>,op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">                                          fd.get(),     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">line</a>(),    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                                          -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                                          op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">showLineNo</a>()  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">                                         );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">isLast</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">DocIncOperator::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">DocIncOperator::exampleFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">DocIncOperator::includeFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">DocIncOperator::isExample</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">DocIncOperator::isFirst</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">DocIncOperator::isLast</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">DocIncOperator::line</a>, <a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">DocVisitor::popHidden</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">DocVisitor::pushHidden</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">DocIncOperator::showLineNo</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">DocIncOperator::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">DocIncOperator::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">DocIncOperator::type</a>.</p>

</div>
</div>

### operator()() {#a7074792ea780e43a5ed6f1b3b8bae2eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp; f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 561 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7074792ea780e43a5ed6f1b3b8bae2eb">561</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;formula id=\""</span><span class="doxyHighlight"> &lt;&lt; f.<a href="/web-doxygen/docs/api/classes/docformula/#ad34d6903f1f038579b131efa2efc2a06">id</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(f.<a href="/web-doxygen/docs/api/classes/docformula/#a4744feabb05063f6019698f2b47a960c">text</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/formula&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/docformula/#ad34d6903f1f038579b131efa2efc2a06">DocFormula::id</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="/web-doxygen/docs/api/classes/docformula/#a4744feabb05063f6019698f2b47a960c">DocFormula::text</a>.</p>

</div>
</div>

### operator()() {#a3337e1132c6c023a23199cd93cb1fa18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp; ie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 569 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3337e1132c6c023a23199cd93cb1fa18">569</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;ie)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;indexentry&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"&lt;primaryie&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(ie.<a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">entry</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/primaryie&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightStringLiteral">"&lt;secondaryie&gt;&lt;/secondaryie&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;/indexentry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docindexentry/#ac267b515c9df901ab1505e070931996c">DocIndexEntry::entry</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a888662f4192f8c5d448e84b9faa1cbf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp; sep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 580 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a888662f4192f8c5d448e84b9faa1cbf0">580</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;sep)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> *sect = std::get_if&lt;DocSimpleSect&gt;(sep.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sect)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a36411b9bf1cb632973d4d0bc7e1add8f">endSimpleSect</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>,*sect);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a8edfee8e77103bfc38b103b93dd4f90e">startSimpleSect</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>,*sect);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a36411b9bf1cb632973d4d0bc7e1add8f">endSimpleSect</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a8edfee8e77103bfc38b103b93dd4f90e">startSimpleSect</a>.</p>

</div>
</div>

### operator()() {#a31e19a340fe2392303f138f3d0d046f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp; cite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 590 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31e19a340fe2392303f138f3d0d046f0">590</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;cite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> opt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">option</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noCite()) <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae5f235deff96cbae64d906842654abea">ref</a>(),cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>(),cite.<a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">getText</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noCite()) <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;b&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(</span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">DocCite::anchor</a>, <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">DocCite::file</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">DocCite::getText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">DocCite::option</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae5f235deff96cbae64d906842654abea">DocCite::ref</a>, <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a> and <a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">DocCite::target</a>.</p>

</div>
</div>

### operator()() {#aff89169f10e0104095bba0d9029d6ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1075 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff89169f10e0104095bba0d9029d6ba6">1075</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parametertype&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parametertype&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>

</div>
</div>

### operator()() {#a0130a36f03912eae004a687497d280e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 616 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0130a36f03912eae004a687497d280e2">616</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l.<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">DocAutoList::isEnumList</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a086d9184f4174d34a09c85ae729a6326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 638 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a086d9184f4174d34a09c85ae729a6326">638</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">itemNumber</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a>: </span><span class="doxyHighlightComment">// unchecked</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem override=\"unchecked\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>: </span><span class="doxyHighlightComment">// checked with x</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>: </span><span class="doxyHighlightComment">// checked with X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem override=\"checked\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(li);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">DocAutoListItem::itemNumber</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab90634212dbc2f235c0e2d6093b3c4b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp; p)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 658 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab90634212dbc2f235c0e2d6093b3c4b0">658</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a0303c24c19d33c6ec4bac50efc43b9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 666 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0303c24c19d33c6ec4bac50efc43b9b3">666</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a8592f34797e03f25475a23b9ee7f9e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 671 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8592f34797e03f25475a23b9ee7f9e29">671</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a8edfee8e77103bfc38b103b93dd4f90e">startSimpleSect</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a36411b9bf1cb632973d4d0bc7e1add8f">endSimpleSect</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a36411b9bf1cb632973d4d0bc7e1add8f">endSimpleSect</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a8edfee8e77103bfc38b103b93dd4f90e">startSimpleSect</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">DocSimpleSect::title</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a558e9807cce6b45e0a8b87d8355a97f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 683 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a558e9807cce6b45e0a8b87d8355a97f1">683</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a707992f9ca42c2d8b5d322e61fda8ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 691 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a707992f9ca42c2d8b5d322e61fda8ad9">691</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a69fc08e18c0395ca5855cbb69d9cde19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 699 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a69fc08e18c0395ca5855cbb69d9cde19">699</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">DocSimpleListItem::paragraph</a>.</p>

</div>
</div>

### operator()() {#a11012240cba58c78041715a6c963b350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 710 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a11012240cba58c78041715a6c963b350">710</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> orgSectionLevel = <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sectId = s.<a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">file</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) sectId += </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">+s.<a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>+1&lt;s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>()) </span><span class="doxyHighlightComment">// fix missing intermediate levels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;sect"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" id=\""</span><span class="doxyHighlight"> &lt;&lt; sectId &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1s"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;sect"</span><span class="doxyHighlight"> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" id=\""</span><span class="doxyHighlight"> &lt;&lt; sectId &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/sect"</span><span class="doxyHighlight"> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (orgSectionLevel&lt;<a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>) </span><span class="doxyHighlightComment">// fix missing intermediate levels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/sect"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsection/#abcd4b7aefb6d755c6c7eb310e225f1a9">DocSection::anchor</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a455df233c8ff5617d235a6d63908ab7b">DocSection::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">DocSection::level</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">DocSection::title</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae5522b266c9dcf8df929ec4b4ca1d5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 738 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5522b266c9dcf8df929ec4b4ca1d5e5">738</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;orderedlist"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; opt.name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/orderedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">DocHtmlList::attribs</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">DocHtmlList::type</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#abaa429846d5df9551f2226db222c3cb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 765 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abaa429846d5df9551f2226db222c3cb0">765</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : l.<a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; opt.name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">DocHtmlListItem::attribs</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae5c24501c95550ca20853061c65621c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 781 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5c24501c95550ca20853061c65621c3">781</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;variablelist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(dl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/variablelist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#afa4dea55a84e8249cd292b760e1469e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp; dt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 789 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa4dea55a84e8249cd292b760e1469e7">789</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;dt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;varlistentry&gt;&lt;term&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(dt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/term&gt;&lt;/varlistentry&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a7cc801c44d435c860eb0c4e72b7687d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp; dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 797 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cc801c44d435c860eb0c4e72b7687d9">797</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;listitem&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a0c0655fab12e9ffece836f11b46a8c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 805 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c0655fab12e9ffece836f11b46a8c44">805</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table rows=\""</span><span class="doxyHighlight"> &lt;&lt; t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a197727d94413c8a39461bb9008d57390">numRows</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" cols=\""</span><span class="doxyHighlight"> &lt;&lt; t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight"> ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#aa067a7324dc0d06431ead1202b669e18">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"width"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; opt.name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*t.<a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmltable/#aa067a7324dc0d06431ead1202b669e18">DocHtmlTable::attribs</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a93e3d4a5878ef927d4b4a32ffa2ec17d">DocHtmlTable::caption</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a8885013add9c26d1ddf36d1412bbd6f9">DocHtmlTable::numColumns</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a197727d94413c8a39461bb9008d57390">DocHtmlTable::numRows</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a7b8a51b96265ea51fcf3b68eb7a22be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 826 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b8a51b96265ea51fcf3b68eb7a22be4">826</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;row&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/row&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a123cf8763db886cf114983b68532e034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 834 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a123cf8763db886cf114983b68532e034">834</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ace62c55c933434c4f451847fede71851">isHeading</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry thead=\"yes\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry thead=\"no\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : c.<a href="/web-doxygen/docs/api/classes/dochtmlcell/#ad42711394b311bbb450073c2206da8c8">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"colspan"</span><span class="doxyHighlight"> || opt.name==</span><span class="doxyHighlightStringLiteral">"rowspan"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; opt.name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value.toInt() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"align"</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">             (opt.value==</span><span class="doxyHighlightStringLiteral">"right"</span><span class="doxyHighlight"> || opt.value==</span><span class="doxyHighlightStringLiteral">"left"</span><span class="doxyHighlight"> || opt.value==</span><span class="doxyHighlightStringLiteral">"center"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"valign"</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">      (opt.value == </span><span class="doxyHighlightStringLiteral">"bottom"</span><span class="doxyHighlight"> || opt.value == </span><span class="doxyHighlightStringLiteral">"top"</span><span class="doxyHighlight"> || opt.value == </span><span class="doxyHighlightStringLiteral">"middle"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" valign=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"width"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" width=\""</span><span class="doxyHighlight"> &lt;&lt; opt.value &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// handle markdown generated attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.startsWith(</span><span class="doxyHighlightStringLiteral">"markdownTable"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// handle markdown generated attributes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.endsWith(</span><span class="doxyHighlightStringLiteral">"Right"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align='right'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.endsWith(</span><span class="doxyHighlightStringLiteral">"Left"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align='left'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.value.endsWith(</span><span class="doxyHighlightStringLiteral">"Center"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" align='center'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip 'markdownTable*' value ending with "None"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.value.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" class=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(opt.value) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ad42711394b311bbb450073c2206da8c8">DocHtmlCell::attribs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ace62c55c933434c4f451847fede71851">DocHtmlCell::isHeading</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ad55bc41271c5cfa6920f32fd8142ce31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 887 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad55bc41271c5cfa6920f32fd8142ce31">887</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;caption"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" id=\""</span><span class="doxyHighlight">  &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">file</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; c.<a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">anchor</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/caption&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#ad71b7d8e7cff7bfb530c36f5a8eda34b">DocHtmlCaption::anchor</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#adbd4124543e897c5e2bf6120c99e83be">DocHtmlCaption::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a16c7fbf7fd8d248ccedcc9c42edb7ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 900 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16c7fbf7fd8d248ccedcc9c42edb7ea4">900</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;internal&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/internal&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af9d445166ed91d40a7ff249c8f262d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp; href)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 908 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9d445166ed91d40a7ff249c8f262d21">908</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;href)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;ulink url=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(href.<a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">url</a>(), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(href);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/ulink&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a5413d17bd302ad2e43057488bdd96175">DocHRef::url</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aed5bd33699c39b682c2f8628da1ce5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 916 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed5bd33699c39b682c2f8628da1ce5e9">916</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;summary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/summary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4de7175b4fed07fac30cb69f45bd9d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 924 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4de7175b4fed07fac30cb69f45bd9d71">924</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;details&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> summary = d.<a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">summary</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*summary);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/details&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">DocHtmlDetails::summary</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a73746a7f0fbddc7813a141f7700a72e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp; header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 937 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73746a7f0fbddc7813a141f7700a72e5">937</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;heading level=\""</span><span class="doxyHighlight"> &lt;&lt; header.<a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">level</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(header);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/heading&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">DocHtmlHeader::level</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a608907da6a8263ac7cff6caae01673c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp; img)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 945 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a608907da6a8263ac7cff6caae01673c9">945</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;img)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = img.<a href="/web-doxygen/docs/api/classes/docimage/#a0e32f1e888da6279104a2fb515c620de">url</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (url.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName = img.<a href="/web-doxygen/docs/api/classes/docimage/#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a>()+img.<a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3a775021310e25718452bfe250b2f999">correctURL</a>(url,img.<a href="/web-doxygen/docs/api/classes/docimage/#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> attribs = img.<a href="/web-doxygen/docs/api/classes/docimage/#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find_if(attribs.begin(),attribs.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">                         [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;att) { return att.name==</span><span class="doxyHighlightStringLiteral">"alt"</span><span class="doxyHighlight">; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> altValue = it!=attribs.end() ? it-&gt;value : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"image"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, img.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(), baseName, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">                img.<a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#a79d36f165096668a3d6631efb6e0b4f0">width</a>(), img.<a href="/web-doxygen/docs/api/classes/docimage/#a434782653279e9f1d823656d48fe3e26">height</a>(), <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">                altValue, img.<a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// copy the image to the output dir</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (url.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; (fd=<a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>,img.<a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">name</a>(),ambig)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(img);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"image"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a05ea2b5c8166be879cc96e30fa487fb7">DocImage::attribs</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3a775021310e25718452bfe250b2f999">correctURL</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a434782653279e9f1d823656d48fe3e26">DocImage::height</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a7062fae1e1507b5c093fe5b71a866371">Doxygen::imageNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docimage/#ae52199cbb5da4e10ccb3a9b53c4978ac">DocImage::isInlineImage</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a0c62b3e12569fac905243b891a62d81a">DocImage::name</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a07a0f3e6897e73d26b36ad4430b885e5">DocImage::relPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a4a7abc635cfbbb0824b1a482b6cb42e9">DocImage::type</a>, <a href="/web-doxygen/docs/api/classes/docimage/#a0e32f1e888da6279104a2fb515c620de">DocImage::url</a>, <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docimage/#a79d36f165096668a3d6631efb6e0b4f0">DocImage::width</a>.</p>

</div>
</div>

### operator()() {#ac9c8677143c5ae39bcfedcdac6b518a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 978 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac9c8677143c5ae39bcfedcdac6b518a4">978</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"dotfile"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(), <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"dotfile"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#a3a2acf19e70d566ecbaec05b214a437d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 987 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a2acf19e70d566ecbaec05b214a437d">987</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"mscfile"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(), <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"mscfile"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#ad59ea834b25f5117addb171ba0ec6259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 996 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad59ea834b25f5117addb171ba0ec6259">996</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"diafile"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(), <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"diafile"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#a71b99c9086e5c3e82c7947cd9f256eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp; df)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1005 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71b99c9086e5c3e82c7947cd9f256eb9">1005</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;df)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>(),<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"plantumlfile"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, df.<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(), <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">file</a>()), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">width</a>(), df.<a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">height</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(df);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>(<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, </span><span class="doxyHighlightStringLiteral">"plantumlfile"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a7c838cdd33e3371ec3e6d9449d33a140">DocDiagramFileBase::file</a>, <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#a5b3819d1a267752459d04c3dc9b19390">DocDiagramFileBase::height</a>, <a href="/web-doxygen/docs/api/classes/docimage/#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">DocImage::Html</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a> and <a href="/web-doxygen/docs/api/classes/docdiagramfilebase/#ae3c17a53045f44ddecd0c2991ec64169">DocDiagramFileBase::width</a>.</p>

</div>
</div>

### operator()() {#aa99f84e51bf6f28fbcd36d90b1c1e34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp; lnk)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1014 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa99f84e51bf6f28fbcd36d90b1c1e34c">1014</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;lnk)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a>(lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">ref</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">file</a>(),lnk.<a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(lnk);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doclink/#a12c7fd0cd735e1fb53216fc9fa26bf61">DocLink::anchor</a>, <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a39a863f3f56d0247210911c2381e39f2">DocLink::file</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="/web-doxygen/docs/api/classes/doclink/#a927a404f81961d4545e5ad41e0c4d35a">DocLink::ref</a>, <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4f27cdc13bc0c7d51bbc657f000b29f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1022 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">1022</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">ref</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">isSubPage</a>() ? <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>() : ref.<a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">hasLinkText</a>()) <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">targetTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docref/#a020050a7e2b6bd6438db4835b5d7130a">DocRef::anchor</a>, <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a83619a74c9fc8be97545a13521d5a126">DocRef::file</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">DocRef::hasLinkText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docref/#a722c091f3305523016b5608a5bb9ccdf">DocRef::isSubPage</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="/web-doxygen/docs/api/classes/docref/#ab1f49243161d41850208e8fde53bd9a5">DocRef::ref</a>, <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a>, <a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">DocRef::targetTitle</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a0e8bc2ce89c9b20a8b9879393aa6108f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1034 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e8bc2ce89c9b20a8b9879393aa6108f">1034</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tocitem id=\""</span><span class="doxyHighlight"> &lt;&lt; ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">file</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; ref.<a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/tocitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsecrefitem/#ab9aa2458393645fd08a33ea58c4b4cca">DocSecRefItem::anchor</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a751e1df43138d68817a38c68e5e066fc">DocSecRefItem::file</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a484adec7f67b66fe540d1d227ac92fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1045 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a484adec7f67b66fe540d1d227ac92fa5">1045</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;toclist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/toclist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a8613537dce42682e941104234d73477c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1053 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8613537dce42682e941104234d73477c">1053</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parameterlist kind=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"param"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"retval"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"exception"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"templateparam"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parameterlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4ff7d5a66db3412ce103eeb44fee565c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp; pl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1081 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ff7d5a66db3412ce103eeb44fee565c">1081</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;pl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parameteritem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parameternamelist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;param : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parametertype&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;type : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parametertype&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parametername"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()!=<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" direction=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"in"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"out"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()==<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"inout"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,param);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parametername&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parameternamelist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parameterdescription&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;par : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,par);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parameterdescription&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parameteritem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docparamlist/#ac45275b55efab9d6a60049f6d6dc7679">DocParamList::direction</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">DocParamSect::In</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">DocParamSect::InOut</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">DocParamSect::Out</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">DocParamList::paragraphs</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">DocParamList::parameters</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a66138e258fb9547bd85e0b9227c48ebf">DocParamList::paramTypes</a> and <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>.</p>

</div>
</div>

### operator()() {#acd694108a8abefd6d6d7be9c7bba21cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp; x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1129 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd694108a8abefd6d6d7be9c7bba21cc">1129</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;x)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;xrefsect id=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">file</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;xreftitle&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/xreftitle&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;xrefdescription&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(x);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/xrefdescription&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/xrefsect&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docxrefitem/#a60de194481baf1f130d2b3a3cee3e4b5">DocXRefItem::anchor</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#ab4fe34f455483d8db30c22030115bfdf">DocXRefItem::file</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">DocXRefItem::title</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aeb414a8b798eb7fe8b6a96ff7990fc5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1146 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">1146</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">file</a>(),ref.<a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">anchor</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinternalref/#ae0ccb4c91d73cda323769f8ee3aa7957">DocInternalRef::anchor</a>, <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#a770f32c338d58af80aa1db5eee306138">DocInternalRef::file</a>, <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>, <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4c1c416a453b6eefd45bc560c2c86aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1155 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c1c416a453b6eefd45bc560c2c86aa7">1155</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a7e60bb1a2c3b9aa23335cde3cc022019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1160 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e60bb1a2c3b9aa23335cde3cc022019">1160</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;blockquote&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/blockquote&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a38fa85a8ee30ae6262d53581787f63b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1168 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38fa85a8ee30ae6262d53581787f63b7">1168</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a0bf510cbb1888d94cc76a20782985c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp; pb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1172 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0bf510cbb1888d94cc76a20782985c02">1172</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acafdda01946f77377d8007cb92e156df">XmlDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;pb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;parblock&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(pb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/parblock&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a>, <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> and <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### endLink() {#ac5ee6a7eb44019dd88204ef3e54765a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::endLink ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 123 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1198 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5ee6a7eb44019dd88204ef3e54765a7">1198</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">XmlDocVisitor::endLink</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/ref&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>


<p>Referenced by <a href="#a31e19a340fe2392303f138f3d0d046f0">operator()</a>, <a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">operator()</a>, <a href="#aa99f84e51bf6f28fbcd36d90b1c1e34c">operator()</a>, <a href="#a38f30197ee604df5323ed695d9e4bfc1">operator()</a> and <a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">operator()</a>.</p>

</div>
</div>

### filter() {#a4a0b1cce6594e65ae0d43c46dfcf52d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::filter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1181 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">1181</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">XmlDocVisitor::filter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>


<p>Referenced by <a href="#a31e19a340fe2392303f138f3d0d046f0">operator()</a>, <a href="#ac090b55ba575d25794fb3cdce0e02967">operator()</a>, <a href="#a7074792ea780e43a5ed6f1b3b8bae2eb">operator()</a>, <a href="#a32d2017f02e0835ea865360773ac1eda">operator()</a>, <a href="#a3337e1132c6c023a23199cd93cb1fa18">operator()</a>, <a href="#a38f30197ee604df5323ed695d9e4bfc1">operator()</a>, <a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">operator()</a>, <a href="#a6530d993517830bcb20a2ccc86e4fa3e">operator()</a>, <a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">operator()</a>, <a href="#acafdda01946f77377d8007cb92e156df">operator()</a> and <a href="#acd694108a8abefd6d6d7be9c7bba21cc">operator()</a>.</p>

</div>
</div>

### startLink() {#a5fa013b821ca9681befa4786b6877709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::startLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 121 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>, definition at line 1186 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa013b821ca9681befa4786b6877709">1186</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5fa013b821ca9681befa4786b6877709">XmlDocVisitor::startLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("XmlDocVisitor: file=%s anchor=%s\n",qPrint(file),qPrint(anchor));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;ref refid=\""</span><span class="doxyHighlight"> &lt;&lt; file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" kindref=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"member"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"compound"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" external=\""</span><span class="doxyHighlight"> &lt;&lt; ref &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>.</p>


<p>Referenced by <a href="#a31e19a340fe2392303f138f3d0d046f0">operator()</a>, <a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">operator()</a>, <a href="#aa99f84e51bf6f28fbcd36d90b1c1e34c">operator()</a>, <a href="#a38f30197ee604df5323ed695d9e4bfc1">operator()</a> and <a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">operator()</a>.</p>

</div>
</div>

### visitChildren() {#a29cc174e4c321c6cbdf5ef4ffa64b22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XmlDocVisitor::visitChildren (const T &amp; t)</td>
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



<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a29cc174e4c321c6cbdf5ef4ffa64b22c">visitChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : t.children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Referenced by <a href="#a0130a36f03912eae004a687497d280e2">operator()</a>, <a href="#a086d9184f4174d34a09c85ae729a6326">operator()</a>, <a href="#ad59ea834b25f5117addb171ba0ec6259">operator()</a>, <a href="#ac9c8677143c5ae39bcfedcdac6b518a4">operator()</a>, <a href="#af9d445166ed91d40a7ff249c8f262d21">operator()</a>, <a href="#a7e60bb1a2c3b9aa23335cde3cc022019">operator()</a>, <a href="#ad55bc41271c5cfa6920f32fd8142ce31">operator()</a>, <a href="#a123cf8763db886cf114983b68532e034">operator()</a>, <a href="#a7cc801c44d435c860eb0c4e72b7687d9">operator()</a>, <a href="#ae5c24501c95550ca20853061c65621c3">operator()</a>, <a href="#afa4dea55a84e8249cd292b760e1469e7">operator()</a>, <a href="#a4de7175b4fed07fac30cb69f45bd9d71">operator()</a>, <a href="#a73746a7f0fbddc7813a141f7700a72e5">operator()</a>, <a href="#ae5522b266c9dcf8df929ec4b4ca1d5e5">operator()</a>, <a href="#abaa429846d5df9551f2226db222c3cb0">operator()</a>, <a href="#a7b8a51b96265ea51fcf3b68eb7a22be4">operator()</a>, <a href="#aed5bd33699c39b682c2f8628da1ce5e9">operator()</a>, <a href="#a0c0655fab12e9ffece836f11b46a8c44">operator()</a>, <a href="#a608907da6a8263ac7cff6caae01673c9">operator()</a>, <a href="#a16c7fbf7fd8d248ccedcc9c42edb7ea4">operator()</a>, <a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">operator()</a>, <a href="#aa99f84e51bf6f28fbcd36d90b1c1e34c">operator()</a>, <a href="#a3a2acf19e70d566ecbaec05b214a437d">operator()</a>, <a href="#ab90634212dbc2f235c0e2d6093b3c4b0">operator()</a>, <a href="#a8613537dce42682e941104234d73477c">operator()</a>, <a href="#a0bf510cbb1888d94cc76a20782985c02">operator()</a>, <a href="#a71b99c9086e5c3e82c7947cd9f256eb9">operator()</a>, <a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">operator()</a>, <a href="#a0303c24c19d33c6ec4bac50efc43b9b3">operator()</a>, <a href="#a0e8bc2ce89c9b20a8b9879393aa6108f">operator()</a>, <a href="#a484adec7f67b66fe540d1d227ac92fa5">operator()</a>, <a href="#a11012240cba58c78041715a6c963b350">operator()</a>, <a href="#a707992f9ca42c2d8b5d322e61fda8ad9">operator()</a>, <a href="#a8592f34797e03f25475a23b9ee7f9e29">operator()</a>, <a href="#a4c1c416a453b6eefd45bc560c2c86aa7">operator()</a>, <a href="#a558e9807cce6b45e0a8b87d8355a97f1">operator()</a> and <a href="#acd694108a8abefd6d6d7be9c7bba21cc">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_ci {#a1317518664d2d196ec25409c3c1b1594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList&amp; XmlDocVisitor::m_ci</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1317518664d2d196ec25409c3c1b1594">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#a1317518664d2d196ec25409c3c1b1594">m_ci</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a32d2017f02e0835ea865360773ac1eda">operator()</a>, <a href="#ac219ce4773970158e118d1d3b57ebd78">operator()</a>, <a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">operator()</a> and <a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a>.</p>

</div>
</div>

### m\_hide {#a324135bddac33bb920baba94345f7d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XmlDocVisitor::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a324135bddac33bb920baba94345f7d25">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a324135bddac33bb920baba94345f7d25">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#ac971dec0f2cd21a3975be1cbd00b34a8">operator()</a>, <a href="#a0130a36f03912eae004a687497d280e2">operator()</a>, <a href="#a086d9184f4174d34a09c85ae729a6326">operator()</a>, <a href="#a31e19a340fe2392303f138f3d0d046f0">operator()</a>, <a href="#ad59ea834b25f5117addb171ba0ec6259">operator()</a>, <a href="#ac9c8677143c5ae39bcfedcdac6b518a4">operator()</a>, <a href="#ac090b55ba575d25794fb3cdce0e02967">operator()</a>, <a href="#a7074792ea780e43a5ed6f1b3b8bae2eb">operator()</a>, <a href="#a894a0ee995fa505268bd52cb4b50be01">operator()</a>, <a href="#af9d445166ed91d40a7ff249c8f262d21">operator()</a>, <a href="#a7e60bb1a2c3b9aa23335cde3cc022019">operator()</a>, <a href="#ad55bc41271c5cfa6920f32fd8142ce31">operator()</a>, <a href="#a123cf8763db886cf114983b68532e034">operator()</a>, <a href="#a7cc801c44d435c860eb0c4e72b7687d9">operator()</a>, <a href="#ae5c24501c95550ca20853061c65621c3">operator()</a>, <a href="#afa4dea55a84e8249cd292b760e1469e7">operator()</a>, <a href="#a4de7175b4fed07fac30cb69f45bd9d71">operator()</a>, <a href="#a73746a7f0fbddc7813a141f7700a72e5">operator()</a>, <a href="#ae5522b266c9dcf8df929ec4b4ca1d5e5">operator()</a>, <a href="#abaa429846d5df9551f2226db222c3cb0">operator()</a>, <a href="#a7b8a51b96265ea51fcf3b68eb7a22be4">operator()</a>, <a href="#aed5bd33699c39b682c2f8628da1ce5e9">operator()</a>, <a href="#a0c0655fab12e9ffece836f11b46a8c44">operator()</a>, <a href="#a608907da6a8263ac7cff6caae01673c9">operator()</a>, <a href="#a32d2017f02e0835ea865360773ac1eda">operator()</a>, <a href="#ac219ce4773970158e118d1d3b57ebd78">operator()</a>, <a href="#a3337e1132c6c023a23199cd93cb1fa18">operator()</a>, <a href="#a16c7fbf7fd8d248ccedcc9c42edb7ea4">operator()</a>, <a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">operator()</a>, <a href="#aa6279ee10c3fb05d9c6410106f90f2c1">operator()</a>, <a href="#aa99f84e51bf6f28fbcd36d90b1c1e34c">operator()</a>, <a href="#a38f30197ee604df5323ed695d9e4bfc1">operator()</a>, <a href="#a3a2acf19e70d566ecbaec05b214a437d">operator()</a>, <a href="#ab90634212dbc2f235c0e2d6093b3c4b0">operator()</a>, <a href="#a4ff7d5a66db3412ce103eeb44fee565c">operator()</a>, <a href="#a8613537dce42682e941104234d73477c">operator()</a>, <a href="#a0bf510cbb1888d94cc76a20782985c02">operator()</a>, <a href="#a71b99c9086e5c3e82c7947cd9f256eb9">operator()</a>, <a href="#a4f27cdc13bc0c7d51bbc657f000b29f4">operator()</a>, <a href="#a0e8bc2ce89c9b20a8b9879393aa6108f">operator()</a>, <a href="#a484adec7f67b66fe540d1d227ac92fa5">operator()</a>, <a href="#a11012240cba58c78041715a6c963b350">operator()</a>, <a href="#a707992f9ca42c2d8b5d322e61fda8ad9">operator()</a>, <a href="#a69fc08e18c0395ca5855cbb69d9cde19">operator()</a>, <a href="#a8592f34797e03f25475a23b9ee7f9e29">operator()</a>, <a href="#aac3356483b754f0dab670ad4a1407f98">operator()</a>, <a href="#ad9f36acc2f17b5a95a12d047ed0f4d08">operator()</a>, <a href="#a558e9807cce6b45e0a8b87d8355a97f1">operator()</a>, <a href="#a6530d993517830bcb20a2ccc86e4fa3e">operator()</a>, <a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">operator()</a>, <a href="#a5a1580dc76cff9388253fc5f0214b8bf">operator()</a>, <a href="#acafdda01946f77377d8007cb92e156df">operator()</a>, <a href="#acd694108a8abefd6d6d7be9c7bba21cc">operator()</a> and <a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a>.</p>

</div>
</div>

### m\_insidePre {#a48ac7a76821c488eb48b95378d783b9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XmlDocVisitor::m_insidePre = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48ac7a76821c488eb48b95378d783b9f">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a48ac7a76821c488eb48b95378d783b9f">m_insidePre</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#aac3356483b754f0dab670ad4a1407f98">operator()</a>, <a href="#a5a1580dc76cff9388253fc5f0214b8bf">operator()</a> and <a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a>.</p>

</div>
</div>

### m\_langExt {#adaa97b8389a3089ca4c94973d76d35e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString XmlDocVisitor::m_langExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adaa97b8389a3089ca4c94973d76d35e7">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#adaa97b8389a3089ca4c94973d76d35e7">m_langExt</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac219ce4773970158e118d1d3b57ebd78">operator()</a>, <a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">operator()</a> and <a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a>.</p>

</div>
</div>

### m\_sectionLevel {#a37ec5798084261eddc263e54d45bd3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int XmlDocVisitor::m_sectionLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37ec5798084261eddc263e54d45bd3d6">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a37ec5798084261eddc263e54d45bd3d6">m_sectionLevel</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a11012240cba58c78041715a6c963b350">operator()</a> and <a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a>.</p>

</div>
</div>

### m\_t {#a4239c11c359f3e7b30a6ba5c107445ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream&amp; XmlDocVisitor::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4239c11c359f3e7b30a6ba5c107445ab">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#a4239c11c359f3e7b30a6ba5c107445ab">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac5ee6a7eb44019dd88204ef3e54765a7">endLink</a>, <a href="#a4a0b1cce6594e65ae0d43c46dfcf52d5">filter</a>, <a href="#ac971dec0f2cd21a3975be1cbd00b34a8">operator()</a>, <a href="#a0130a36f03912eae004a687497d280e2">operator()</a>, <a href="#a086d9184f4174d34a09c85ae729a6326">operator()</a>, <a href="#a31e19a340fe2392303f138f3d0d046f0">operator()</a>, <a href="#ad59ea834b25f5117addb171ba0ec6259">operator()</a>, <a href="#ac9c8677143c5ae39bcfedcdac6b518a4">operator()</a>, <a href="#ac090b55ba575d25794fb3cdce0e02967">operator()</a>, <a href="#a7074792ea780e43a5ed6f1b3b8bae2eb">operator()</a>, <a href="#a894a0ee995fa505268bd52cb4b50be01">operator()</a>, <a href="#af9d445166ed91d40a7ff249c8f262d21">operator()</a>, <a href="#a7e60bb1a2c3b9aa23335cde3cc022019">operator()</a>, <a href="#ad55bc41271c5cfa6920f32fd8142ce31">operator()</a>, <a href="#a123cf8763db886cf114983b68532e034">operator()</a>, <a href="#a7cc801c44d435c860eb0c4e72b7687d9">operator()</a>, <a href="#ae5c24501c95550ca20853061c65621c3">operator()</a>, <a href="#afa4dea55a84e8249cd292b760e1469e7">operator()</a>, <a href="#a4de7175b4fed07fac30cb69f45bd9d71">operator()</a>, <a href="#a73746a7f0fbddc7813a141f7700a72e5">operator()</a>, <a href="#ae5522b266c9dcf8df929ec4b4ca1d5e5">operator()</a>, <a href="#abaa429846d5df9551f2226db222c3cb0">operator()</a>, <a href="#a7b8a51b96265ea51fcf3b68eb7a22be4">operator()</a>, <a href="#aed5bd33699c39b682c2f8628da1ce5e9">operator()</a>, <a href="#a0c0655fab12e9ffece836f11b46a8c44">operator()</a>, <a href="#a608907da6a8263ac7cff6caae01673c9">operator()</a>, <a href="#a32d2017f02e0835ea865360773ac1eda">operator()</a>, <a href="#ac219ce4773970158e118d1d3b57ebd78">operator()</a>, <a href="#a3337e1132c6c023a23199cd93cb1fa18">operator()</a>, <a href="#a16c7fbf7fd8d248ccedcc9c42edb7ea4">operator()</a>, <a href="#aeb414a8b798eb7fe8b6a96ff7990fc5d">operator()</a>, <a href="#aa6279ee10c3fb05d9c6410106f90f2c1">operator()</a>, <a href="#a3a2acf19e70d566ecbaec05b214a437d">operator()</a>, <a href="#ab90634212dbc2f235c0e2d6093b3c4b0">operator()</a>, <a href="#a4ff7d5a66db3412ce103eeb44fee565c">operator()</a>, <a href="#a8613537dce42682e941104234d73477c">operator()</a>, <a href="#a0bf510cbb1888d94cc76a20782985c02">operator()</a>, <a href="#a71b99c9086e5c3e82c7947cd9f256eb9">operator()</a>, <a href="#a0e8bc2ce89c9b20a8b9879393aa6108f">operator()</a>, <a href="#a484adec7f67b66fe540d1d227ac92fa5">operator()</a>, <a href="#a11012240cba58c78041715a6c963b350">operator()</a>, <a href="#aff89169f10e0104095bba0d9029d6ba6">operator()</a>, <a href="#a707992f9ca42c2d8b5d322e61fda8ad9">operator()</a>, <a href="#a69fc08e18c0395ca5855cbb69d9cde19">operator()</a>, <a href="#a8592f34797e03f25475a23b9ee7f9e29">operator()</a>, <a href="#a888662f4192f8c5d448e84b9faa1cbf0">operator()</a>, <a href="#aac3356483b754f0dab670ad4a1407f98">operator()</a>, <a href="#ad9f36acc2f17b5a95a12d047ed0f4d08">operator()</a>, <a href="#a558e9807cce6b45e0a8b87d8355a97f1">operator()</a>, <a href="#a6530d993517830bcb20a2ccc86e4fa3e">operator()</a>, <a href="#ae2f1f49b8496f09377c4e7de91e2f3d6">operator()</a>, <a href="#a5a1580dc76cff9388253fc5f0214b8bf">operator()</a>, <a href="#acd694108a8abefd6d6d7be9c7bba21cc">operator()</a>, <a href="#a5fa013b821ca9681befa4786b6877709">startLink</a> and <a href="#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp">xmldocvisitor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/xmldocvisitor-h">xmldocvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
