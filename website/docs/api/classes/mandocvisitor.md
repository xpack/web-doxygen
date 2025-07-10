---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/mandocvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ManDocVisitor` Class Reference

<p>Concrete visitor implementation for LaTeX output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ManDocVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">src/mandocvisitor.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a> (TextStream &amp;t, OutputCodeList &amp;ci, const QCString &amp;langExt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717055210b0bdcd869a71a36a62690cc">operator()</a> (const DocWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1385e8fb9c9effec554143178bd5f5ac">operator()</a> (const DocLinkedWord &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315f64205ff8e9d75ddd63e31f068269">operator()</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb7a0185345e8311efd7d18827dbe43b">operator()</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae151cc7686cf768f2e7e91002bac8dcc">operator()</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff22dba562419dc8b2498e0a3864df37">operator()</a> (const DocURL &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1ae1428205bcf6e4cdebb9ae20ede4">operator()</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2df84b2d5419625e00bd41061f2444d">operator()</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3135258f772ad9dcb6c936b55f913543">operator()</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a> (const DocVerbatim &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41ae44e9b06650ea54caa0eec86c147">operator()</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a103c34bd91c4bf67cadfca22f2b61466">operator()</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a611ec420e06726e8061f4fe83c3f8a6f">operator()</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36acbaa3b88d11ce458d0987ce393685">operator()</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6442170525a21620514d3a30339d738b">operator()</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7972f852beb0baaac4f5dbf54a620b3">operator()</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a718bc15298af2003de3afb45ee5a9794">operator()</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48f89c9aade30cdf2894a4e0aa69f1a">operator()</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f090ff971f194f7e0f26eccc6dc3e35">operator()</a> (const DocAutoList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5beb634b87459054e96cfa6e07717a">operator()</a> (const DocAutoListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541113c556c1afc2e6107999d3e18bd4">operator()</a> (const DocPara &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5f9f27f1b4dd3ff3135a1faaa6ddd0">operator()</a> (const DocRoot &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf41fa80034e1477e1017f19f89d4de">operator()</a> (const DocSimpleSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713081a0d41c7dec260ddf2b0b7566b3">operator()</a> (const DocTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9077004871b7326c313f59f59942b81">operator()</a> (const DocSimpleList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad902c41e3df81277b2bf6f1e95f466d">operator()</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1c588d1549ecec64db696b44247951">operator()</a> (const DocSection &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a> (const DocHtmlList &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a> (const DocHtmlListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe102e24c2324f00273af856a3577c60">operator()</a> (const DocHtmlDescList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc07bea7c5f6f69559f84793b9193a9">operator()</a> (const DocHtmlDescTitle &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f3fdd3602427ba34e23a0e79ffcf64">operator()</a> (const DocHtmlDescData &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020f68cb0200ee90447176b9a176195e">operator()</a> (const DocHtmlTable &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a846f20e5b255bd0f0cb15a519618c810">operator()</a> (const DocHtmlCaption &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a33acdda18c57a81a33a31883b6b51">operator()</a> (const DocHtmlRow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54571770faa432eca6b9f45798e5c270">operator()</a> (const DocHtmlCell &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffe8b8d83060eca96b20ba5f5a87e4b">operator()</a> (const DocInternal &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c6dea7aa28aac1737579ae55868059c">operator()</a> (const DocHRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de17f04f63f6e2ce8b0d362a023d90c">operator()</a> (const DocHtmlSummary &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7989c5d873c1601edf487ddd90daec">operator()</a> (const DocHtmlDetails &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa515f7b48fa75a22c9e1173511e8cb88">operator()</a> (const DocHtmlHeader &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d073a9742c34c51135478391c2eb352">operator()</a> (const DocImage &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a1e75b842a266130f48e661f7c6b4a">operator()</a> (const DocDotFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b845abd7c638ffca47d5f6cba1e2f82">operator()</a> (const DocMscFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b8d9fc88bce9474268018f81239419">operator()</a> (const DocDiaFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8ace0ec0eba0fabafd2d6ca0e4a189">operator()</a> (const DocPlantUmlFile &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65162a3a4705ffa6dc6315ca0b785db4">operator()</a> (const DocLink &amp;lnk)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfc3d202bc44676a3830b4ec33a35f0">operator()</a> (const DocRef &amp;ref)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6d88a7940699bbb17fa4648d6007a9">operator()</a> (const DocSecRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a9717a4dd573bbfeda26508bda3491">operator()</a> (const DocSecRefList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21bb817afa0823ea94983a1d86aea4b">operator()</a> (const DocParamSect &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9becdb1d4b3096f9081710f0c6c14e80">operator()</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70abcda93ed50a2ffbdacf0f1d973c39">operator()</a> (const DocXRefItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a157978a326c9f3952142064c0bc0f22c">operator()</a> (const DocInternalRef &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd8b41c0d97340deb2646fb6e3bc981">operator()</a> (const DocText &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f911cbb8030ff42a96e838476e249f">operator()</a> (const DocHtmlBlockQuote &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e0c71c14d7e9083ae670e0219f3ce06">operator()</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01005dd006d8e9cb51497b43e2c2db0b">operator()</a> (const DocParBlock &amp;)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a> (const T &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72964fa569229687454f00fe4dc4ab45">filter</a> (const QCString &amp;str, const bool retainNewline=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-doxygen/docs/api/structs/mandocvisitor/manlistiteminfo">ManListItemInfo</a>, <a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a> = 13</td>
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

<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ManDocVisitor() {#ae196a1929c47ffea2e32ab8d321943d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManDocVisitor::ManDocVisitor (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ci, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; langExt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae196a1929c47ffea2e32ab8d321943d5">33</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor::ManDocVisitor</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ci,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;langExt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>(t), <a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>(ci), <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>), <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>), <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>(0), <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a>(langExt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>, <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a> and <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a717055210b0bdcd869a71a36a62690cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a717055210b0bdcd869a71a36a62690cc">44</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(w.<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.</p>

</div>
</div>

### operator()() {#a1385e8fb9c9effec554143178bd5f5ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1385e8fb9c9effec554143178bd5f5ac">51</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">word</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">DocLinkedWord::word</a>.</p>

</div>
</div>

### operator()() {#a315f64205ff8e9d75ddd63e31f068269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp; w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a315f64205ff8e9d75ddd63e31f068269">60</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(w.<a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">chars</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/docwhitespace/#a9e8fbf6c6ca3efa8f4e7d9fce2352023">DocWhiteSpace::chars</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a> and <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>.</p>

</div>
</div>

### operator()() {#afb7a0185345e8311efd7d18827dbe43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb7a0185345e8311efd7d18827dbe43b">75</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#ae69bb690ab38e84854b912b68e71cf79">man</a>(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// no error or warning to be supplied</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// err("man: non supported HTML-entity found: &amp;{};\n",get_symbol_item(s-&gt;symbol()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#ae69bb690ab38e84854b912b68e71cf79">HtmlEntityMapper::man</a> and <a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">DocSymbol::symbol</a>.</p>

</div>
</div>

### operator()() {#ae151cc7686cf768f2e7e91002bac8dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae151cc7686cf768f2e7e91002bac8dcc">91</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">name</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">DocEmoji::index</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">DocEmoji::name</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a33137ef11c5d63f6f7d7a27c01db943e">EmojiEntityMapper::name</a>.</p>

</div>
</div>

### operator()() {#aff22dba562419dc8b2498e0a3864df37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp; u)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff22dba562419dc8b2498e0a3864df37">106</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">DocURL::url</a>.</p>

</div>
</div>

### operator()() {#a2e1ae1428205bcf6e4cdebb9ae20ede4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e1ae1428205bcf6e4cdebb9ae20ede4">113</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n.br\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#aa2df84b2d5419625e00bd41061f2444d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2df84b2d5419625e00bd41061f2444d">120</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#a3135258f772ad9dcb6c936b55f913543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3135258f772ad9dcb6c936b55f913543">128</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">style</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* not supported */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>: </span><span class="doxyHighlightComment">//underline is shown as emphasis</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fI"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fI"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fR"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\*&lt;"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\*&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\*{"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\*} "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* not supported */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* not supported */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* not supported */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">enable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>:  </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>: </span><span class="doxyHighlightComment">/* HTML only */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#ac8a8c808b962cc17665ab52937b8bd78">DocStyleChange::enable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a56d079390f264e34af453a015bd2e2c9">DocStyleChange::style</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a> and <a href="/web-doxygen/docs/api/classes/docstylechange/#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>.</p>

</div>
</div>

### operator()() {#aff3cb0ea5dd2ee90d238e8689a34e0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">196</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lang = <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// explicit language setting</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    lang = s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">language</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(lang).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>,s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">context</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">                                        langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(STRIP_CODE_COMMENTS),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">                                        s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">isExample</a>(),s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">exampleFile</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fR\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* nothing */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a5237d98c668e1c746648c77e62e18fe4">DocVerbatim::Code</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a58a8316261706c1b74b8396742bf86b8">DocVerbatim::context</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a18bd2b8d2df70a8423919cf6dd4d33e1">DocVerbatim::DocbookOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a792fd26984aba5cab5b5bc235d705bd1">DocVerbatim::Dot</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a77801c92a718d54461dd551f0c5ed235">DocVerbatim::exampleFile</a>, <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6d584858761afb81c76d1c85e19438e9">getLanguageFromCodeLang</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a8abc5ca69c3762e97cffaacc244457f1">DocVerbatim::HtmlOnly</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a56e82d369d1af07c80e299d33a5836ea">DocVerbatim::isExample</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a2b815ee5bcc8575d0bd8f2eec2eff302">DocVerbatim::JavaDocCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac7616766260c93e27d7490271ef110a4">DocVerbatim::JavaDocLiteral</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a330cfad3caad6395b0afe3ebbf7d3dcf">DocVerbatim::language</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ac5a4818987c756de7d336c3d7ad04173">DocVerbatim::LatexOnly</a>, <a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a578f19d38fb29903c3f55aea4f76bccb">DocVerbatim::ManOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36aa841d77afafe62444561766f255fda8b">DocVerbatim::Msc</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a3291e7fae70d3ccc1ee0e306d7150012">DocVerbatim::PlantUML</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a53b96b0c5ba74d8884669c178eb88bf9">DocVerbatim::RtfOnly</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">DocVerbatim::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#a643407838e6684602459062da9f9d2ec">DocVerbatim::type</a>, <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36a6c1b77a564f7f47346627a07de09c251">DocVerbatim::Verbatim</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#ad8c770dcf2e62369b95f4e34fb11fa36ad30f4dea69d46825ffdf21d1748e3715">DocVerbatim::XmlOnly</a>.</p>

</div>
</div>

### operator()() {#af41ae44e9b06650ea54caa0eec86c147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 254 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af41ae44e9b06650ea54caa0eec86c147">254</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* no support for anchors in man pages */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a103c34bd91c4bf67cadfca22f2b61466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp; inc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a103c34bd91c4bf67cadfca22f2b61466">259</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;inc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">                                           langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">                                           inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">                                           fd.get(), </span><span class="doxyHighlightComment">// fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">                                           -1,    </span><span class="doxyHighlightComment">// start line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">                                           -1,    </span><span class="doxyHighlightComment">// end line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">                                           <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">                                           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">extension</a>()).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>,inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">                                        langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">isExample</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">                                        inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,  </span><span class="doxyHighlightComment">// inlineFragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">                                       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>().<a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a>(<a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">file</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">type</a>()==<a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">                                          inc.<a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">                                         );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docinclude/#a0a32ad9c12a12a6664dd90ba2c141c26">DocInclude::blockId</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#afe43ae68ec1e5cb184ab7a3e63b40556">DocInclude::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DocInclude::DontInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DocInclude::DontIncWithLines</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a9541ad25c955f690e228a07e6d1c0093">DocInclude::exampleFile</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a1201f943eb5e45821291843810df8a51">DocInclude::extension</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ad2dce3078cd4a33bf3923066b2c79957">DocInclude::file</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">DocInclude::HtmlInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">DocInclude::Include</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">DocInclude::IncWithLines</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#af001e0f412f5189fc3f7105b402996d6">DocInclude::isExample</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">DocInclude::LatexInclude</a>, <a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">DocInclude::Snippet</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">DocInclude::SnippetWithLines</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a6d2679020b534464d254f0dea85cded1">DocInclude::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ab2a402fcaf6d3c4ecce0cd7647c0e339">DocInclude::text</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#ae9583c0c22fe5031fc50b95cbabef0c0">DocInclude::trimLeft</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a8e9f5167c504937dedc7ffac6a454514">DocInclude::type</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">DocInclude::VerbInclude</a> and <a href="/web-doxygen/docs/api/classes/docinclude/#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>.</p>

</div>
</div>

### operator()() {#a611ec420e06726e8061f4fe83c3f8a6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp; op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 352 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a611ec420e06726e8061f4fe83c3f8a6f">352</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;op)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> locLangExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (locLangExt.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) locLangExt = <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(locLangExt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocIncOperator: type=%d first=%d, last=%d text='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    op.type(),op.isFirst(),op.isLast(),qPrint(op.text()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">isFirst</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".nf\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">type</a>()!=<a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_ptr&lt;FileDef&gt; fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">includeFileName</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">        fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">getCodeParser</a>(locLangExt).<a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">parseCode</a>(<a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>,op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">context</a>(),op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">text</a>(),langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">stripCodeComments</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">isExample</a>(),op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">exampleFile</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">                                        fd.get(),     </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">line</a>(),    </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">                                        -1,    </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, </span><span class="doxyHighlightComment">// inline fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,     </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">                                        op.<a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">showLineNo</a>()  </span><span class="doxyHighlightComment">// show line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">                                       );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">pushHidden</a>(<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op.<a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">isLast</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a> = <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">popHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docincoperator/#ab59377a5d6002c488ebfaeff4c8f2e64">DocIncOperator::context</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab5e78827022d8466df9e7bfb189bc8e8">DocIncOperator::exampleFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a1ec90584b36968b4eef801a5becb0522">DocVisitor::getCodeParser</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a7c06a4a5f871ce72f41d72f7b1452736">DocIncOperator::includeFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aff7da518608143cfc4d53bee4be28ecb">DocIncOperator::isExample</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ad5fc63c8a8ab2ebb0359443aba890802">DocIncOperator::isFirst</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3aa61fa6f30b556886cf8460ed9e0a3c">DocIncOperator::isLast</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ab9499d4c8335483abbface712143d69f">DocIncOperator::line</a>, <a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#afaec23aad7de1e76aab6a441d70c9119">DocVisitor::popHidden</a>, <a href="/web-doxygen/docs/api/classes/docvisitor/#a54bb9f229fa8660eb70dd68e87fdfd9d">DocVisitor::pushHidden</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aea2218e2b49020af7c643b1b6b9204ac">DocIncOperator::showLineNo</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ae7a155da5a206f51e93edc166bd64970a170db94965a90854526b0be5273d59b8">DocIncOperator::Skip</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a3948f96579d9147908c2a1c06207e270">DocIncOperator::stripCodeComments</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a91b44df290fd25ebcc9125227b593ece">DocIncOperator::text</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/docincoperator/#ad22086824c941ff3099faa8c45f3a02a">DocIncOperator::type</a>.</p>

</div>
</div>

### operator()() {#a36acbaa3b88d11ce458d0987ce393685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp; f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 413 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36acbaa3b88d11ce458d0987ce393685">413</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; f.<a href="/web-doxygen/docs/api/classes/docformula/#a4744feabb05063f6019698f2b47a960c">text</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="/web-doxygen/docs/api/classes/docformula/#a4744feabb05063f6019698f2b47a960c">DocFormula::text</a>.</p>

</div>
</div>

### operator()() {#a6442170525a21620514d3a30339d738b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 419 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6442170525a21620514d3a30339d738b">419</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#ab7972f852beb0baaac4f5dbf54a620b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 423 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7972f852beb0baaac4f5dbf54a620b3">423</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a718bc15298af2003de3afb45ee5a9794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp; cite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 427 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a718bc15298af2003de3afb45ee5a9794">427</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;cite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> opt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">option</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> txt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">    txt = cite.<a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">getText</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    txt += cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!opt.noPar()) txt += </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(txt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">DocCite::file</a>, <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="/web-doxygen/docs/api/classes/doccite/#a294548216265b2291dfb8654750d4920">DocCite::getText</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/doccite/#aafaea054e0d069a474232f1cb3a5092e">DocCite::option</a> and <a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">DocCite::target</a>.</p>

</div>
</div>

### operator()() {#aa48f89c9aade30cdf2894a4e0aa69f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 447 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa48f89c9aade30cdf2894a4e0aa69f1a">447</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">chars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docseparator/#a7de00e3032b756cfd4653d4e4f676f5d">DocSeparator::chars</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a> and <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>.</p>

</div>
</div>

### operator()() {#a0f090ff971f194f7e0f26eccc6dc3e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 458 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f090ff971f194f7e0f26eccc6dc3e35">458</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4c5beb634b87459054e96cfa6e07717a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 467 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c5beb634b87459054e96cfa6e07717a">467</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ws;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>&gt;0) ws.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,2*(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".IP \""</span><span class="doxyHighlight"> &lt;&lt; ws;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> *list = std::get_if&lt;DocAutoList&gt;(li.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (list &amp;&amp; list-&gt;<a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">isEnumList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; li.<a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">itemNumber</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".\" "</span><span class="doxyHighlight"> &lt;&lt; (2*(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>+1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// bullet list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">itemNumber</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a>: </span><span class="doxyHighlightComment">// unchecked</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[ ]\" "</span><span class="doxyHighlight"> &lt;&lt; (2*<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>) + 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>: </span><span class="doxyHighlightComment">// checked with x</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[x]\" "</span><span class="doxyHighlight"> &lt;&lt; (2*<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>) + 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>: </span><span class="doxyHighlightComment">// checked with X</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"[X]\" "</span><span class="doxyHighlight"> &lt;&lt; (2*<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>) + 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\(bu\" "</span><span class="doxyHighlight"> &lt;&lt; (2*<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(li);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a97c36a5afc2ae0435319e9b203befe53">DocAutoList::Checked_X</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a4dc2d6867c4a095b4e80a4d81522a9b8">DocAutoList::Checked_x</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">QCString::fill</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a479dfc09c9f638c9bdead57868c5a3b8">DocAutoList::isEnumList</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a2d307e9d399d0209c30a717f07d81ee2">DocAutoListItem::itemNumber</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docautolist/#a6c707b00eeb9280c20474f5a6fbcb145a93580c9edb988c5c77a1897aa31e0721">DocAutoList::Unchecked</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a541113c556c1afc2e6107999d3e18bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp; p)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 504 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a541113c556c1afc2e6107999d3e18bd4">504</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!p.<a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">isLast</a>() &amp;&amp;            </span><span class="doxyHighlightComment">// omit &lt;p&gt; for last paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">      !(p.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>() &amp;&amp;           </span><span class="doxyHighlightComment">// and for parameter sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">        std::get_if&lt;DocParamSect&gt;(p.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n.PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docpara/#a32a474477c8d44117a82964eeac50e53">DocPara::isLast</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a1c5f9f27f1b4dd3ff3135a1faaa6ddd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 520 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c5f9f27f1b4dd3ff3135a1faaa6ddd0">520</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a8bf41fa80034e1477e1017f19f89d4de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 525 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8bf41fa80034e1477e1017f19f89d4de">525</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSeeAlso(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturns(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAuthor(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trVersion(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSince(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDate(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNote(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trWarning(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPrecondition(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPostcondition(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCopyright(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInvariant(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRemarks(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trAttention(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trImportant(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>:  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// special case 1: user defined title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RS 4\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RE\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">DocSimpleSect::Attention</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">DocSimpleSect::Author</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">DocSimpleSect::Authors</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">DocSimpleSect::Copyright</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">DocSimpleSect::Date</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">DocSimpleSect::Important</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">DocSimpleSect::Invar</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">DocSimpleSect::Note</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">DocSimpleSect::Post</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">DocSimpleSect::Pre</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">DocSimpleSect::Rcs</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">DocSimpleSect::Remark</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">DocSimpleSect::Return</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">DocSimpleSect::See</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">DocSimpleSect::Since</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#abbbcd2151b9e3b29fea64118e99b0b61">DocSimpleSect::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a1ea4e7672816ad91cf567b2000f1a65c">DocSimpleSect::type</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">DocSimpleSect::Unknown</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">DocSimpleSect::User</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">DocSimpleSect::Version</a>, <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a> and <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">DocSimpleSect::Warning</a>.</p>

</div>
</div>

### operator()() {#a713081a0d41c7dec260ddf2b0b7566b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 587 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a713081a0d41c7dec260ddf2b0b7566b3">587</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa9077004871b7326c313f59f59942b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 593 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9077004871b7326c313f59f59942b81">593</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PD 0\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aad902c41e3df81277b2bf6f1e95f466d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 605 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad902c41e3df81277b2bf6f1e95f466d">605</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ws;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>&gt;0) ws.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,2*(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".IP \""</span><span class="doxyHighlight"> &lt;&lt; ws &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\(bu\" "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">    visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*li.<a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">paragraph</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">QCString::fill</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsimplelistitem/#a5cf88bdd86a58c836a938a20e13cf5c8">DocSimpleListItem::paragraph</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#aaa1c588d1549ecec64db696b44247951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 621 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa1c588d1549ecec64db696b44247951">621</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>()==1) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".SH"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".SS"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*s.<a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">level</a>()==1) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docsection/#a86d69300a2a90eeacd2d1422bccc2e2b">DocSection::level</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsection/#ac1429596005eb07ca96d2a0f832e4019">DocSection::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aef0c0f7241f4095ca450dc4b56554a86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 637 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef0c0f7241f4095ca450dc4b56554a86">637</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PD 0\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indent = std::min(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>,<a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].type   = </span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : l.<a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].type = opt.value[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"start"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllist/#a5bd8c9fdf0acc981eb3207a150f6781f">DocHtmlList::attribs</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4ce763b29a44b5b477602993c33842b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp; li)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 666 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ce763b29a44b5b477602993c33842b9">666</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;li)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ws;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>&gt;0) ws.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,2*(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".IP \""</span><span class="doxyHighlight"> &lt;&lt; ws;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> *list = std::get_if&lt;DocHtmlList&gt;(li.<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (list &amp;&amp; list-&gt;<a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">type</a>()==<a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indent = std::min(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>,<a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : li.<a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">attribs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt.name==</span><span class="doxyHighlightStringLiteral">"value"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = opt.value.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok) <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number = val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'1'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6e984969913a70c9b67da588f68b8a14">integerToAlpha</a>(<a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6e984969913a70c9b67da588f68b8a14">integerToAlpha</a>(<a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'i'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>(<a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'I'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>(<a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".\" "</span><span class="doxyHighlight"> &lt;&lt; ((<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>+1)*2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>[indent].number++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// bullet list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\(bu\" "</span><span class="doxyHighlight"> &lt;&lt; (<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>*2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(li);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a2c0badd651aa4cebd3711ee5a0aaa7a7">DocHtmlListItem::attribs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">QCString::fill</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6e984969913a70c9b67da588f68b8a14">integerToAlpha</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3603e3a5f6710fd96b6c634f9e2de708">integerToRoman</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#af05523650adffbefb14392d8f9f23487a8642714056eb3abfd3972a5dec674042">DocHtmlList::Ordered</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab92254aca59f20ebb04f85b0ffd92020">DocHtmlList::type</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#abe102e24c2324f00273af856a3577c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp; dl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 721 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe102e24c2324f00273af856a3577c60">721</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(dl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>-=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n.PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9dc07bea7c5f6f69559f84793b9193a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp; dt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 732 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9dc07bea7c5f6f69559f84793b9193a9">732</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;dt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n.PP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n.IP \"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(dt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae9f3fdd3602427ba34e23a0e79ffcf64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp; dd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 742 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9f3fdd3602427ba34e23a0e79ffcf64">742</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".IP \"\" 1c\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a020f68cb0200ee90447176b9a176195e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 750 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a020f68cb0200ee90447176b9a176195e">750</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a846f20e5b255bd0f0cb15a519618c810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 755 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a846f20e5b255bd0f0cb15a519618c810">755</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a36a33acdda18c57a81a33a31883b6b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp; r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 760 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36a33acdda18c57a81a33a31883b6b51">760</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a54571770faa432eca6b9f45798e5c270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 765 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54571770faa432eca6b9f45798e5c270">765</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aeffe8b8d83060eca96b20ba5f5a87e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp; i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 770 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeffe8b8d83060eca96b20ba5f5a87e4b">770</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a5c6dea7aa28aac1737579ae55868059c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp; href)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 775 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c6dea7aa28aac1737579ae55868059c">775</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;href)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fR"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(href);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a0de17f04f63f6e2ce8b0d362a023d90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 783 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0de17f04f63f6e2ce8b0d362a023d90c">783</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP\n.PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ade7989c5d873c1601edf487ddd90daec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp; d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 790 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade7989c5d873c1601edf487ddd90daec">790</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> summary = d.<a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">summary</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,*summary);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RS 4\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (summary)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RE\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#ab353fa87425d140b051dea0fdbfded23">DocHtmlDetails::summary</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aa515f7b48fa75a22c9e1173511e8cb88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp; header)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 815 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa515f7b48fa75a22c9e1173511e8cb88">815</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (header.<a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">level</a>()==1) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".SH"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".SS"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(header);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (header.<a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">level</a>()==1) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dochtmlheader/#af8e82a4c504c1d6acd6838fa21404263">DocHtmlHeader::level</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a7d073a9742c34c51135478391c2eb352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 827 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d073a9742c34c51135478391c2eb352">827</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a61a1e75b842a266130f48e661f7c6b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 831 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a61a1e75b842a266130f48e661f7c6b4a">831</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a6b845abd7c638ffca47d5f6cba1e2f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 835 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b845abd7c638ffca47d5f6cba1e2f82">835</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a55b8d9fc88bce9474268018f81239419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 839 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55b8d9fc88bce9474268018f81239419">839</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#add8ace0ec0eba0fabafd2d6ca0e4a189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 843 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add8ace0ec0eba0fabafd2d6ca0e4a189">843</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a65162a3a4705ffa6dc6315ca0b785db4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp; lnk)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 847 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a65162a3a4705ffa6dc6315ca0b785db4">847</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;dl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(dl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a4cfc3d202bc44676a3830b4ec33a35f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 855 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cfc3d202bc44676a3830b4ec33a35f0">855</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">hasLinkText</a>()) <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(ref.<a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">targetTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="/web-doxygen/docs/api/classes/docref/#af54b6d5c031b011dd3877d68bce47455">DocRef::hasLinkText</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docref/#a5c24ebdffb560b02af49504d3d5b8eb1">DocRef::targetTitle</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aad6d88a7940699bbb17fa4648d6007a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 864 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad6d88a7940699bbb17fa4648d6007a9">864</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ws;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>&gt;0) ws.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,2*(<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>-1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".IP \""</span><span class="doxyHighlight"> &lt;&lt; ws &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\(bu\" "</span><span class="doxyHighlight"> &lt;&lt; (2*<a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">QCString::fill</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab9a9717a4dd573bbfeda26508bda3491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp; l)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 877 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab9a9717a4dd573bbfeda26508bda3491">877</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af21bb817afa0823ea94983a1d86aea4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 887 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af21bb817afa0823ea94983a1d86aea4b">887</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">type</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trParameters(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trReturnValues(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptions(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trTemplateParameters(); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RS 4\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RE\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">DocParamSect::Exception</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">DocParamSect::TemplateParam</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#afcb0666a1b93ac69a56ab22179827d8a">DocParamSect::type</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9becdb1d4b3096f9081710f0c6c14e80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp; pl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 918 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9becdb1d4b3096f9081710f0c6c14e80">918</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;pl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fI"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;param : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,param);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;par : pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,par);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a96270035f29eb07f50ed8c0c2acda9d3">isLast</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".br\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a96270035f29eb07f50ed8c0c2acda9d3">DocParamList::isLast</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#aea61e6129350589c862ceb0f75d5f9a9">DocParamList::paragraphs</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a543cac8da19b4edaa5eb0c7deeba2455">DocParamList::parameters</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#a70abcda93ed50a2ffbdacf0f1d973c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp; x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 940 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70abcda93ed50a2ffbdacf0f1d973c39">940</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;x)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>(x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RS 4\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(x);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (x.<a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">title</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RE\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#af174176c1e034a106469af615e09854e">DocXRefItem::title</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a157978a326c9f3952142064c0bc0f22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp; ref)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 961 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a157978a326c9f3952142064c0bc0f22c">961</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fB"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a2cd8b41c0d97340deb2646fb6e3bc981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 969 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2cd8b41c0d97340deb2646fb6e3bc981">969</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae2f911cbb8030ff42a96e838476e249f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 974 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2f911cbb8030ff42a96e838476e249f">974</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RS 4\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// TODO: add support for nested block quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(q);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".RE\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".PP\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>, <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>, <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a5e0c71c14d7e9083ae670e0219f3ce06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 990 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e0c71c14d7e9083ae670e0219f3ce06">990</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### operator()() {#a01005dd006d8e9cb51497b43e2c2db0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp; pb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 994 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01005dd006d8e9cb51497b43e2c2db0b">994</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;pb)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(pb);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### filter() {#a72964fa569229687454f00fe4dc4ab45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::filter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const bool retainNewline=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>, definition at line 999 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72964fa569229687454f00fe4dc4ab45">999</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a72964fa569229687454f00fe4dc4ab45">ManDocVisitor::filter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retainNewline)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideDoubleQuote = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">:  <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;."</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// see  bug652277</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\"'</span><span class="doxyHighlight">: <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">; insideDoubleQuote = !insideDoubleQuote; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retainNewline || !insideDoubleQuote) <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; c; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a> &lt;&lt; c; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>.</p>


<p>Referenced by <a href="#a718bc15298af2003de3afb45ee5a9794">operator()</a>, <a href="#a1385e8fb9c9effec554143178bd5f5ac">operator()</a>, <a href="#a4cfc3d202bc44676a3830b4ec33a35f0">operator()</a>, <a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a>, <a href="#a717055210b0bdcd869a71a36a62690cc">operator()</a> and <a href="#a70abcda93ed50a2ffbdacf0f1d973c39">operator()</a>.</p>

</div>
</div>

### visitChildren() {#adf00e7b84564cbfef3e73f19ed470d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ManDocVisitor::visitChildren (const T &amp; t)</td>
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



<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf00e7b84564cbfef3e73f19ed470d63">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adf00e7b84564cbfef3e73f19ed470d63">visitChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : t.children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Referenced by <a href="#a0f090ff971f194f7e0f26eccc6dc3e35">operator()</a>, <a href="#a4c5beb634b87459054e96cfa6e07717a">operator()</a>, <a href="#a5c6dea7aa28aac1737579ae55868059c">operator()</a>, <a href="#ae2f911cbb8030ff42a96e838476e249f">operator()</a>, <a href="#a846f20e5b255bd0f0cb15a519618c810">operator()</a>, <a href="#a54571770faa432eca6b9f45798e5c270">operator()</a>, <a href="#ae9f3fdd3602427ba34e23a0e79ffcf64">operator()</a>, <a href="#abe102e24c2324f00273af856a3577c60">operator()</a>, <a href="#a9dc07bea7c5f6f69559f84793b9193a9">operator()</a>, <a href="#ade7989c5d873c1601edf487ddd90daec">operator()</a>, <a href="#aa515f7b48fa75a22c9e1173511e8cb88">operator()</a>, <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a>, <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>, <a href="#a36a33acdda18c57a81a33a31883b6b51">operator()</a>, <a href="#a0de17f04f63f6e2ce8b0d362a023d90c">operator()</a>, <a href="#a020f68cb0200ee90447176b9a176195e">operator()</a>, <a href="#aeffe8b8d83060eca96b20ba5f5a87e4b">operator()</a>, <a href="#a157978a326c9f3952142064c0bc0f22c">operator()</a>, <a href="#a65162a3a4705ffa6dc6315ca0b785db4">operator()</a>, <a href="#a541113c556c1afc2e6107999d3e18bd4">operator()</a>, <a href="#af21bb817afa0823ea94983a1d86aea4b">operator()</a>, <a href="#a01005dd006d8e9cb51497b43e2c2db0b">operator()</a>, <a href="#a4cfc3d202bc44676a3830b4ec33a35f0">operator()</a>, <a href="#a1c5f9f27f1b4dd3ff3135a1faaa6ddd0">operator()</a>, <a href="#aad6d88a7940699bbb17fa4648d6007a9">operator()</a>, <a href="#ab9a9717a4dd573bbfeda26508bda3491">operator()</a>, <a href="#aaa1c588d1549ecec64db696b44247951">operator()</a>, <a href="#aa9077004871b7326c313f59f59942b81">operator()</a>, <a href="#a8bf41fa80034e1477e1017f19f89d4de">operator()</a>, <a href="#a2cd8b41c0d97340deb2646fb6e3bc981">operator()</a>, <a href="#a713081a0d41c7dec260ddf2b0b7566b3">operator()</a> and <a href="#a70abcda93ed50a2ffbdacf0f1d973c39">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_ci {#aa76a7b803ad442dc3748062f0db1c869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList&amp; ManDocVisitor::m_ci</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa76a7b803ad442dc3748062f0db1c869">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#aa76a7b803ad442dc3748062f0db1c869">m_ci</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a103c34bd91c4bf67cadfca22f2b61466">operator()</a>, <a href="#a611ec420e06726e8061f4fe83c3f8a6f">operator()</a> and <a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a>.</p>

</div>
</div>

### m\_firstCol {#a7c4d50d6aca1907932aa2102deed79de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ManDocVisitor::m_firstCol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c4d50d6aca1907932aa2102deed79de">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7c4d50d6aca1907932aa2102deed79de">m_firstCol</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a4c5beb634b87459054e96cfa6e07717a">operator()</a>, <a href="#ae151cc7686cf768f2e7e91002bac8dcc">operator()</a>, <a href="#aa2df84b2d5419625e00bd41061f2444d">operator()</a>, <a href="#ae2f911cbb8030ff42a96e838476e249f">operator()</a>, <a href="#ae9f3fdd3602427ba34e23a0e79ffcf64">operator()</a>, <a href="#abe102e24c2324f00273af856a3577c60">operator()</a>, <a href="#a9dc07bea7c5f6f69559f84793b9193a9">operator()</a>, <a href="#ade7989c5d873c1601edf487ddd90daec">operator()</a>, <a href="#aa515f7b48fa75a22c9e1173511e8cb88">operator()</a>, <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a>, <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>, <a href="#a103c34bd91c4bf67cadfca22f2b61466">operator()</a>, <a href="#a611ec420e06726e8061f4fe83c3f8a6f">operator()</a>, <a href="#a2e1ae1428205bcf6e4cdebb9ae20ede4">operator()</a>, <a href="#a1385e8fb9c9effec554143178bd5f5ac">operator()</a>, <a href="#a541113c556c1afc2e6107999d3e18bd4">operator()</a>, <a href="#a9becdb1d4b3096f9081710f0c6c14e80">operator()</a>, <a href="#af21bb817afa0823ea94983a1d86aea4b">operator()</a>, <a href="#aad6d88a7940699bbb17fa4648d6007a9">operator()</a>, <a href="#ab9a9717a4dd573bbfeda26508bda3491">operator()</a>, <a href="#aaa1c588d1549ecec64db696b44247951">operator()</a>, <a href="#aa9077004871b7326c313f59f59942b81">operator()</a>, <a href="#aad902c41e3df81277b2bf6f1e95f466d">operator()</a>, <a href="#a8bf41fa80034e1477e1017f19f89d4de">operator()</a>, <a href="#a3135258f772ad9dcb6c936b55f913543">operator()</a>, <a href="#afb7a0185345e8311efd7d18827dbe43b">operator()</a>, <a href="#aff22dba562419dc8b2498e0a3864df37">operator()</a>, <a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a>, <a href="#a315f64205ff8e9d75ddd63e31f068269">operator()</a>, <a href="#a717055210b0bdcd869a71a36a62690cc">operator()</a> and <a href="#a70abcda93ed50a2ffbdacf0f1d973c39">operator()</a>.</p>

</div>
</div>

### m\_hide {#a19093acb1d57b5023cc26ebf81986862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ManDocVisitor::m_hide</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19093acb1d57b5023cc26ebf81986862">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a19093acb1d57b5023cc26ebf81986862">m_hide</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a0f090ff971f194f7e0f26eccc6dc3e35">operator()</a>, <a href="#a4c5beb634b87459054e96cfa6e07717a">operator()</a>, <a href="#a718bc15298af2003de3afb45ee5a9794">operator()</a>, <a href="#ae151cc7686cf768f2e7e91002bac8dcc">operator()</a>, <a href="#a36acbaa3b88d11ce458d0987ce393685">operator()</a>, <a href="#aa2df84b2d5419625e00bd41061f2444d">operator()</a>, <a href="#a5c6dea7aa28aac1737579ae55868059c">operator()</a>, <a href="#ae2f911cbb8030ff42a96e838476e249f">operator()</a>, <a href="#abe102e24c2324f00273af856a3577c60">operator()</a>, <a href="#a9dc07bea7c5f6f69559f84793b9193a9">operator()</a>, <a href="#ade7989c5d873c1601edf487ddd90daec">operator()</a>, <a href="#aa515f7b48fa75a22c9e1173511e8cb88">operator()</a>, <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a>, <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>, <a href="#a103c34bd91c4bf67cadfca22f2b61466">operator()</a>, <a href="#a611ec420e06726e8061f4fe83c3f8a6f">operator()</a>, <a href="#a157978a326c9f3952142064c0bc0f22c">operator()</a>, <a href="#a2e1ae1428205bcf6e4cdebb9ae20ede4">operator()</a>, <a href="#a65162a3a4705ffa6dc6315ca0b785db4">operator()</a>, <a href="#a1385e8fb9c9effec554143178bd5f5ac">operator()</a>, <a href="#a541113c556c1afc2e6107999d3e18bd4">operator()</a>, <a href="#a9becdb1d4b3096f9081710f0c6c14e80">operator()</a>, <a href="#af21bb817afa0823ea94983a1d86aea4b">operator()</a>, <a href="#a4cfc3d202bc44676a3830b4ec33a35f0">operator()</a>, <a href="#aad6d88a7940699bbb17fa4648d6007a9">operator()</a>, <a href="#ab9a9717a4dd573bbfeda26508bda3491">operator()</a>, <a href="#aaa1c588d1549ecec64db696b44247951">operator()</a>, <a href="#aa48f89c9aade30cdf2894a4e0aa69f1a">operator()</a>, <a href="#aa9077004871b7326c313f59f59942b81">operator()</a>, <a href="#aad902c41e3df81277b2bf6f1e95f466d">operator()</a>, <a href="#a8bf41fa80034e1477e1017f19f89d4de">operator()</a>, <a href="#a3135258f772ad9dcb6c936b55f913543">operator()</a>, <a href="#afb7a0185345e8311efd7d18827dbe43b">operator()</a>, <a href="#a713081a0d41c7dec260ddf2b0b7566b3">operator()</a>, <a href="#aff22dba562419dc8b2498e0a3864df37">operator()</a>, <a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a>, <a href="#a315f64205ff8e9d75ddd63e31f068269">operator()</a>, <a href="#a717055210b0bdcd869a71a36a62690cc">operator()</a> and <a href="#a70abcda93ed50a2ffbdacf0f1d973c39">operator()</a>.</p>

</div>
</div>

### m\_indent {#a14c58a82f8994fede554dc42d6efd1ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ManDocVisitor::m_indent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a14c58a82f8994fede554dc42d6efd1ce">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">  <a href="#a14c58a82f8994fede554dc42d6efd1ce">m_indent</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a0f090ff971f194f7e0f26eccc6dc3e35">operator()</a>, <a href="#a4c5beb634b87459054e96cfa6e07717a">operator()</a>, <a href="#abe102e24c2324f00273af856a3577c60">operator()</a>, <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a>, <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>, <a href="#aad6d88a7940699bbb17fa4648d6007a9">operator()</a>, <a href="#ab9a9717a4dd573bbfeda26508bda3491">operator()</a>, <a href="#aa9077004871b7326c313f59f59942b81">operator()</a> and <a href="#aad902c41e3df81277b2bf6f1e95f466d">operator()</a>.</p>

</div>
</div>

### m\_insidePre {#a9f8f69bc7068b52c3a58c132226d8dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ManDocVisitor::m_insidePre</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f8f69bc7068b52c3a58c132226d8dd1">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9f8f69bc7068b52c3a58c132226d8dd1">m_insidePre</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a3135258f772ad9dcb6c936b55f913543">operator()</a> and <a href="#a315f64205ff8e9d75ddd63e31f068269">operator()</a>.</p>

</div>
</div>

### m\_langExt {#aaa9bec6cb0fa3914b92e7b17d989acd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ManDocVisitor::m_langExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aaa9bec6cb0fa3914b92e7b17d989acd4">m_langExt</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a611ec420e06726e8061f4fe83c3f8a6f">operator()</a> and <a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a>.</p>

</div>
</div>

### m\_listItemInfo {#a315b274dea4ad591fa35bf486b251f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;ManListItemInfo,maxIndentLevels&gt; ManDocVisitor::m_listItemInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a315b274dea4ad591fa35bf486b251f55">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::array&lt;ManListItemInfo,maxIndentLevels&gt; <a href="#a315b274dea4ad591fa35bf486b251f55">m_listItemInfo</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a> and <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>.</p>

</div>
</div>

### m\_t {#a5f6a193c724ec88ff68967702b73ca7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream&amp; ManDocVisitor::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f6a193c724ec88ff68967702b73ca7d">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#a5f6a193c724ec88ff68967702b73ca7d">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a72964fa569229687454f00fe4dc4ab45">filter</a>, <a href="#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor</a>, <a href="#a0f090ff971f194f7e0f26eccc6dc3e35">operator()</a>, <a href="#a4c5beb634b87459054e96cfa6e07717a">operator()</a>, <a href="#a718bc15298af2003de3afb45ee5a9794">operator()</a>, <a href="#ae151cc7686cf768f2e7e91002bac8dcc">operator()</a>, <a href="#a36acbaa3b88d11ce458d0987ce393685">operator()</a>, <a href="#aa2df84b2d5419625e00bd41061f2444d">operator()</a>, <a href="#a5c6dea7aa28aac1737579ae55868059c">operator()</a>, <a href="#ae2f911cbb8030ff42a96e838476e249f">operator()</a>, <a href="#ae9f3fdd3602427ba34e23a0e79ffcf64">operator()</a>, <a href="#abe102e24c2324f00273af856a3577c60">operator()</a>, <a href="#a9dc07bea7c5f6f69559f84793b9193a9">operator()</a>, <a href="#ade7989c5d873c1601edf487ddd90daec">operator()</a>, <a href="#aa515f7b48fa75a22c9e1173511e8cb88">operator()</a>, <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a>, <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>, <a href="#a0de17f04f63f6e2ce8b0d362a023d90c">operator()</a>, <a href="#a103c34bd91c4bf67cadfca22f2b61466">operator()</a>, <a href="#a611ec420e06726e8061f4fe83c3f8a6f">operator()</a>, <a href="#a157978a326c9f3952142064c0bc0f22c">operator()</a>, <a href="#a2e1ae1428205bcf6e4cdebb9ae20ede4">operator()</a>, <a href="#a65162a3a4705ffa6dc6315ca0b785db4">operator()</a>, <a href="#a1385e8fb9c9effec554143178bd5f5ac">operator()</a>, <a href="#a541113c556c1afc2e6107999d3e18bd4">operator()</a>, <a href="#a9becdb1d4b3096f9081710f0c6c14e80">operator()</a>, <a href="#af21bb817afa0823ea94983a1d86aea4b">operator()</a>, <a href="#a4cfc3d202bc44676a3830b4ec33a35f0">operator()</a>, <a href="#aad6d88a7940699bbb17fa4648d6007a9">operator()</a>, <a href="#ab9a9717a4dd573bbfeda26508bda3491">operator()</a>, <a href="#aaa1c588d1549ecec64db696b44247951">operator()</a>, <a href="#aa48f89c9aade30cdf2894a4e0aa69f1a">operator()</a>, <a href="#aa9077004871b7326c313f59f59942b81">operator()</a>, <a href="#aad902c41e3df81277b2bf6f1e95f466d">operator()</a>, <a href="#a8bf41fa80034e1477e1017f19f89d4de">operator()</a>, <a href="#a3135258f772ad9dcb6c936b55f913543">operator()</a>, <a href="#afb7a0185345e8311efd7d18827dbe43b">operator()</a>, <a href="#aff22dba562419dc8b2498e0a3864df37">operator()</a>, <a href="#aff3cb0ea5dd2ee90d238e8689a34e0da">operator()</a>, <a href="#a315f64205ff8e9d75ddd63e31f068269">operator()</a> and <a href="#a70abcda93ed50a2ffbdacf0f1d973c39">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### maxIndentLevels {#aaca268157a9ae4dba58321631aafaf66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int ManDocVisitor::maxIndentLevels = 13</td>
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



<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaca268157a9ae4dba58321631aafaf66">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aaca268157a9ae4dba58321631aafaf66">maxIndentLevels</a> = 13;</span></span></div>

</div>


<p>Referenced by <a href="#aef0c0f7241f4095ca450dc4b56554a86">operator()</a> and <a href="#a4ce763b29a44b5b477602993c33842b9">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/mandocvisitor-cpp">mandocvisitor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/mandocvisitor-h">mandocvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
