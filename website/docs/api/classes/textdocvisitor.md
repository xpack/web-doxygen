---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/textdocvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TextDocVisitor` Class Reference

<p>Concrete visitor implementation for TEXT output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class TextDocVisitor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">src/textdocvisitor.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8871e218557de5dd120f069aa24943e5">TextDocVisitor</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad932c305668398f6c0b4aace1f3f8483">operator()</a> (const DocWord &amp;w)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ad4f6c2986454bef71da208040245d">operator()</a> (const DocLinkedWord &amp;w)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50f1e8ea75600502fc5d9c9e85f2c42d">operator()</a> (const DocWhiteSpace &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3af6b81e834fce376849077c0fa6b565">operator()</a> (const DocSymbol &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c1a244d091ae31fcd8ff2d66747054">operator()</a> (const DocEmoji &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285d9c57869ca5d67f1d0f7cd4e61f4f">operator()</a> (const DocURL &amp;u)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf7ba9afe6d0fdded369e823a576312">operator()</a> (const DocLineBreak &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9512c3aaf835735197cb81dbff4509">operator()</a> (const DocHorRuler &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da13e655f4830fe67573fab682b777c">operator()</a> (const DocStyleChange &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99aa0dd7813f8bd767c48d8f22b34a36">operator()</a> (const DocVerbatim &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad95cb86ee8179d2657dcff6d21b82ec3">operator()</a> (const DocAnchor &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d378fb5a2f82062d71add7299162041">operator()</a> (const DocInclude &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f8a4dda12db29b2c6a552e4d397293">operator()</a> (const DocIncOperator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3402645693d0c046971c63de7b3b88">operator()</a> (const DocFormula &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30da459f4ea599540fe75de89587149e">operator()</a> (const DocIndexEntry &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7e23ebd2a7ac64d90d3e47bd701758">operator()</a> (const DocSimpleSectSep &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88217cd97b6eaa15a8c8f4a8c4757db1">operator()</a> (const DocCite &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c102a60d7e0736462e163ed5ce65985">operator()</a> (const DocSeparator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6596c51428e21b79305826fe801bcdd4">operator()</a> (const DocAutoList &amp;l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23685ceb6a04c2fb3c4c6be68024f306">operator()</a> (const DocAutoListItem &amp;li)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f014ebe48ddfcc5355e240a4fb7705">operator()</a> (const DocPara &amp;p)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4cc82cae14ff8d531ffbf81f943ee4">operator()</a> (const DocRoot &amp;r)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a278389ca9820c7fa26058b5fb5c5a992">operator()</a> (const DocSimpleSect &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8631059d2425e1f6b7630916617fec81">operator()</a> (const DocTitle &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc216d1a18e28c44effe5eb8376406ce">operator()</a> (const DocSimpleList &amp;l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926a69b8e76086fda9ae068d46ff5fbb">operator()</a> (const DocSimpleListItem &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05566775448465866dbb3c63d4779ac">operator()</a> (const DocSection &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746e3166528699c1ddb726789658343a">operator()</a> (const DocHtmlList &amp;l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f90da048f2bbf9661aabf78f1feb92">operator()</a> (const DocHtmlListItem &amp;li)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b20b09948af8e83fa1f9caabb3a9fe">operator()</a> (const DocHtmlDescList &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff707d2dbf9fe8907d88b851cb6967c">operator()</a> (const DocHtmlDescTitle &amp;dt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75b3ce4e09deda54cd0b322207d8b59">operator()</a> (const DocHtmlDescData &amp;dd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0184a5b5bb5139323ea94060b89b471">operator()</a> (const DocHtmlTable &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbe0884bd203117011fccf02423100c">operator()</a> (const DocHtmlRow &amp;r)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf478a242c096d2e0d3e4507a092c4d">operator()</a> (const DocHtmlCell &amp;c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffc5ada9a7d440ecbe0806a375bc10b">operator()</a> (const DocHtmlCaption &amp;c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71287f4e8ce55ad65cd979b5953e4c85">operator()</a> (const DocInternal &amp;i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae094469f57f2b537316aea706573cdab">operator()</a> (const DocHRef &amp;h)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad8b3823415a16dfaa51630c0677cc4">operator()</a> (const DocHtmlSummary &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc46761fac33da87e160f3a78ecbcae">operator()</a> (const DocHtmlDetails &amp;d)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b77a7ccc8480a9bd10c29ad36578183">operator()</a> (const DocHtmlHeader &amp;h)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8453da1335c0e51d78860f4510b4b5">operator()</a> (const DocImage &amp;i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5235f87bc1fdc978b22e9998730cb35e">operator()</a> (const DocDotFile &amp;df)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab334af6b81322d7d437384debe04da5b">operator()</a> (const DocMscFile &amp;df)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd289832895043986162a1d6c7e86f2a">operator()</a> (const DocDiaFile &amp;df)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21c8c2c9297498622e99be29f6da36e7">operator()</a> (const DocPlantUmlFile &amp;df)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38f4afee39d980f80a4dc378cf53ac69">operator()</a> (const DocLink &amp;l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac075dcb801cf9b1897ca5afd81be8889">operator()</a> (const DocRef &amp;r)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c16bf106d1bb53850a5565b21da550">operator()</a> (const DocSecRefItem &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d74fee058c638cb165e029e5c6bd609">operator()</a> (const DocSecRefList &amp;l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7d70310bc619b4f5e08685e7d61de0">operator()</a> (const DocParamSect &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a9b3e21db66831dc25f1a32082ed38">operator()</a> (const DocParamList &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f9378c24ab5d72579c39330caa7aed">operator()</a> (const DocXRefItem &amp;x)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36490b641f0a71682679955d9ebb297">operator()</a> (const DocInternalRef &amp;r)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32e2794207e6411e95fdb14745ac0ba">operator()</a> (const DocText &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059976e67597727de9e20b56bc3d31c5">operator()</a> (const DocHtmlBlockQuote &amp;q)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93fa293c26400b3fc8ab880c0f1b4ec">operator()</a> (const DocVhdlFlow &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b6cd5ab6bb3326e7be15df2bb7d5c3">operator()</a> (const DocParBlock &amp;pb)</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a> (const T &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a> (const QCString &amp;str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a></td>
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

<p>Concrete visitor implementation for TEXT output.</p>

<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextDocVisitor() {#a8871e218557de5dd120f069aa24943e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextDocVisitor::TextDocVisitor (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8871e218557de5dd120f069aa24943e5">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8871e218557de5dd120f069aa24943e5">TextDocVisitor</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t) : <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>(t) {}</span></span></div>

</div>


<p>Reference <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#ad932c305668398f6c0b4aace1f3f8483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp; w)</td>
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



<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad932c305668398f6c0b4aace1f3f8483">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad932c305668398f6c0b4aace1f3f8483">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docword">DocWord</a> &amp;w)        { <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>(w.<a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">word</a>()); }</span></span></div>

</div>


<p>References <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a> and <a href="/web-doxygen/docs/api/classes/docword/#af9ecbc2daa4fb051a07c510ab0a7d461">DocWord::word</a>.</p>

</div>
</div>

### operator()() {#ae3ad4f6c2986454bef71da208040245d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp; w)</td>
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



<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3ad4f6c2986454bef71da208040245d">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3ad4f6c2986454bef71da208040245d">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinkedword">DocLinkedWord</a> &amp;w)  { <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>(w.<a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">word</a>()); }</span></span></div>

</div>


<p>References <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a> and <a href="/web-doxygen/docs/api/classes/doclinkedword/#a99a9908a9068fadb25871975cc41a507">DocLinkedWord::word</a>.</p>

</div>
</div>

### operator()() {#a50f1e8ea75600502fc5d9c9e85f2c42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;)</td>
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



<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a50f1e8ea75600502fc5d9c9e85f2c42d">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a50f1e8ea75600502fc5d9c9e85f2c42d">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docwhitespace">DocWhiteSpace</a> &amp;)   { <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;       }</span></span></div>

</div>


<p>Reference <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>.</p>

</div>
</div>

### operator()() {#a3af6b81e834fce376849077c0fa6b565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>, definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-cpp">textdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3af6b81e834fce376849077c0fa6b565">28</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad932c305668398f6c0b4aace1f3f8483">TextDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsymbol">DocSymbol</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#aea40dae4575be9010f2ea950206a6f57">html</a>(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"text: non supported HTML-entity found: {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().html(s.<a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">symbol</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#aea40dae4575be9010f2ea950206a6f57">HtmlEntityMapper::html</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>, <a href="/web-doxygen/docs/api/classes/docsymbol/#a904ef70c86c562216950a0fbfc423f84">DocSymbol::symbol</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### operator()() {#a23c1a244d091ae31fcd8ff2d66747054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>, definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-cpp">textdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23c1a244d091ae31fcd8ff2d66747054">41</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad932c305668398f6c0b4aace1f3f8483">TextDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docemoji">DocEmoji</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// the TextDocVisitor is only invoked for the JS part of the HTML output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *res = <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">unicode</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">index</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'x'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\u{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; *p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a07de0cec2007bc102188a656a354b8b9">DocEmoji::index</a>, <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a6b4ebc91738fb8f8af7459346a86f49b">EmojiEntityMapper::instance</a>, <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>, <a href="/web-doxygen/docs/api/classes/docemoji/#a5c754f3d5f362c43008fe6bf6d11147a">DocEmoji::name</a> and <a href="/web-doxygen/docs/api/classes/emojientitymapper/#a1b6d7e3d1f82adf44c46fdd82d11b2f8">EmojiEntityMapper::unicode</a>.</p>

</div>
</div>

### operator()() {#a285d9c57869ca5d67f1d0f7cd4e61f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp; u)</td>
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



<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a285d9c57869ca5d67f1d0f7cd4e61f4f">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a285d9c57869ca5d67f1d0f7cd4e61f4f">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docurl">DocURL</a> &amp;u)         { <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>(u.<a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">url</a>());  }</span></span></div>

</div>


<p>References <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a> and <a href="/web-doxygen/docs/api/classes/docurl/#a06354fa0923e369dc58da474622528a0">DocURL::url</a>.</p>

</div>
</div>

### operator()() {#a5bf7ba9afe6d0fdded369e823a576312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)</td>
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



<p>Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5bf7ba9afe6d0fdded369e823a576312">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5bf7ba9afe6d0fdded369e823a576312">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclinebreak">DocLineBreak</a> &amp;)    { <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;       }</span></span></div>

</div>


<p>Reference <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>.</p>

</div>
</div>

### operator()() {#acb9512c3aaf835735197cb81dbff4509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)</td>
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



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb9512c3aaf835735197cb81dbff4509">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acb9512c3aaf835735197cb81dbff4509">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochorruler">DocHorRuler</a> &amp;)     {}</span></span></div>

</div>

</div>
</div>

### operator()() {#a4da13e655f4830fe67573fab682b777c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;)</td>
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



<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4da13e655f4830fe67573fab682b777c">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4da13e655f4830fe67573fab682b777c">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docstylechange">DocStyleChange</a> &amp;)  {}</span></span></div>

</div>

</div>
</div>

### operator()() {#a99aa0dd7813f8bd767c48d8f22b34a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp; s)</td>
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



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99aa0dd7813f8bd767c48d8f22b34a36">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a99aa0dd7813f8bd767c48d8f22b34a36">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docverbatim">DocVerbatim</a> &amp;s)    { <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>(s.<a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">text</a>()); }</span></span></div>

</div>


<p>References <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a> and <a href="/web-doxygen/docs/api/classes/docverbatim/#a7570e40ac3f0b1bb946c81aa1f384d2f">DocVerbatim::text</a>.</p>

</div>
</div>

### operator()() {#ad95cb86ee8179d2657dcff6d21b82ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;)</td>
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



<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad95cb86ee8179d2657dcff6d21b82ec3">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad95cb86ee8179d2657dcff6d21b82ec3">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docanchor">DocAnchor</a> &amp;)       {}</span></span></div>

</div>

</div>
</div>

### operator()() {#a1d378fb5a2f82062d71add7299162041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;)</td>
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



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d378fb5a2f82062d71add7299162041">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d378fb5a2f82062d71add7299162041">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinclude">DocInclude</a> &amp;)      {}</span></span></div>

</div>

</div>
</div>

### operator()() {#a75f8a4dda12db29b2c6a552e4d397293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;)</td>
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



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75f8a4dda12db29b2c6a552e4d397293">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a75f8a4dda12db29b2c6a552e4d397293">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docincoperator">DocIncOperator</a> &amp;)  {}</span></span></div>

</div>

</div>
</div>

### operator()() {#a7e3402645693d0c046971c63de7b3b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;)</td>
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



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e3402645693d0c046971c63de7b3b88">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7e3402645693d0c046971c63de7b3b88">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docformula">DocFormula</a> &amp;)      {}</span></span></div>

</div>

</div>
</div>

### operator()() {#a30da459f4ea599540fe75de89587149e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;)</td>
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



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a30da459f4ea599540fe75de89587149e">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a30da459f4ea599540fe75de89587149e">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docindexentry">DocIndexEntry</a> &amp;)   {}</span></span></div>

</div>

</div>
</div>

### operator()() {#ade7e23ebd2a7ac64d90d3e47bd701758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;)</td>
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



<p>Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade7e23ebd2a7ac64d90d3e47bd701758">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ade7e23ebd2a7ac64d90d3e47bd701758">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a> &amp;){}</span></span></div>

</div>

</div>
</div>

### operator()() {#a88217cd97b6eaa15a8c8f4a8c4757db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp; cite)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>, definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-cpp">textdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88217cd97b6eaa15a8c8f4a8c4757db1">73</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad932c305668398f6c0b4aace1f3f8483">TextDocVisitor::operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccite">DocCite</a> &amp;cite)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cite.<a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">file</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor = cite.<a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchorPrefix = <a href="/web-doxygen/docs/api/classes/citationmanager/#a4934f7fbd6a387b7cc2ea0a12a2e04b5">CitationManager::instance</a>().<a href="/web-doxygen/docs/api/classes/citationmanager/#a10ba17e783f502c2998a7432c84fd462">anchorPrefix</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    anchor = anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(anchorPrefix.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()); </span><span class="doxyHighlightComment">// strip prefix</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>(cite.<a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">target</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccite/#acb79082b3765794abb193fcef75b1b2e">DocCite::anchor</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a10ba17e783f502c2998a7432c84fd462">CitationManager::anchorPrefix</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ae842d125098f64d7ee7bb1b955f2f6ba">DocCite::file</a>, <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#a4934f7fbd6a387b7cc2ea0a12a2e04b5">CitationManager::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="/web-doxygen/docs/api/classes/doccite/#aba1e595baf53edff52edf749074abce8">DocCite::target</a>.</p>

</div>
</div>

### operator()() {#a6c102a60d7e0736462e163ed5ce65985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;)</td>
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



<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c102a60d7e0736462e163ed5ce65985">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6c102a60d7e0736462e163ed5ce65985">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docseparator">DocSeparator</a> &amp;)    { <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">; }</span></span></div>

</div>


<p>Reference <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>.</p>

</div>
</div>

### operator()() {#a6596c51428e21b79305826fe801bcdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp; l)</td>
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



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6596c51428e21b79305826fe801bcdd4">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6596c51428e21b79305826fe801bcdd4">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolist">DocAutoList</a> &amp;l)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(l);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a23685ceb6a04c2fb3c4c6be68024f306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp; li)</td>
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



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23685ceb6a04c2fb3c4c6be68024f306">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a23685ceb6a04c2fb3c4c6be68024f306">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docautolistitem">DocAutoListItem</a> &amp;li)   { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(li); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a21f014ebe48ddfcc5355e240a4fb7705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp; p)</td>
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



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21f014ebe48ddfcc5355e240a4fb7705">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a21f014ebe48ddfcc5355e240a4fb7705">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> &amp;p)            { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(p);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ade4cc82cae14ff8d531ffbf81f943ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp; r)</td>
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



<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade4cc82cae14ff8d531ffbf81f943ee4">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ade4cc82cae14ff8d531ffbf81f943ee4">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a> &amp;r)            { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(r);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a278389ca9820c7fa26058b5fb5c5a992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp; s)</td>
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



<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a278389ca9820c7fa26058b5fb5c5a992">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a278389ca9820c7fa26058b5fb5c5a992">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplesect">DocSimpleSect</a> &amp;s)      { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(s);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a8631059d2425e1f6b7630916617fec81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp; t)</td>
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



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8631059d2425e1f6b7630916617fec81">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8631059d2425e1f6b7630916617fec81">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> &amp;t)           { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(t);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#acc216d1a18e28c44effe5eb8376406ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp; l)</td>
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



<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc216d1a18e28c44effe5eb8376406ce">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acc216d1a18e28c44effe5eb8376406ce">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelist">DocSimpleList</a> &amp;l)      { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(l);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a926a69b8e76086fda9ae068d46ff5fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;)</td>
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



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a926a69b8e76086fda9ae068d46ff5fbb">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a926a69b8e76086fda9ae068d46ff5fbb">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsimplelistitem">DocSimpleListItem</a> &amp;)   {                    }</span></span></div>

</div>

</div>
</div>

### operator()() {#ab05566775448465866dbb3c63d4779ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp; s)</td>
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



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab05566775448465866dbb3c63d4779ac">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab05566775448465866dbb3c63d4779ac">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsection">DocSection</a> &amp;s)         { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(s);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a746e3166528699c1ddb726789658343a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp; l)</td>
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



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a746e3166528699c1ddb726789658343a">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a746e3166528699c1ddb726789658343a">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllist">DocHtmlList</a> &amp;l)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(l);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab6f90da048f2bbf9661aabf78f1feb92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp; li)</td>
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



<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6f90da048f2bbf9661aabf78f1feb92">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab6f90da048f2bbf9661aabf78f1feb92">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmllistitem">DocHtmlListItem</a> &amp;li)   { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(li); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af0b20b09948af8e83fa1f9caabb3a9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp; dl)</td>
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



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0b20b09948af8e83fa1f9caabb3a9fe">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af0b20b09948af8e83fa1f9caabb3a9fe">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesclist">DocHtmlDescList</a> &amp;dl)   { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(dl); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a0ff707d2dbf9fe8907d88b851cb6967c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp; dt)</td>
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



<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ff707d2dbf9fe8907d88b851cb6967c">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0ff707d2dbf9fe8907d88b851cb6967c">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldesctitle">DocHtmlDescTitle</a> &amp;dt)  { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(dt); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ad75b3ce4e09deda54cd0b322207d8b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp; dd)</td>
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



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad75b3ce4e09deda54cd0b322207d8b59">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad75b3ce4e09deda54cd0b322207d8b59">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldescdata">DocHtmlDescData</a> &amp;dd)   { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(dd); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af0184a5b5bb5139323ea94060b89b471}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp; t)</td>
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



<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0184a5b5bb5139323ea94060b89b471">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af0184a5b5bb5139323ea94060b89b471">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmltable">DocHtmlTable</a> &amp;t)       { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(t);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9fbe0884bd203117011fccf02423100c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp; r)</td>
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



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9fbe0884bd203117011fccf02423100c">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9fbe0884bd203117011fccf02423100c">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> &amp;r)         { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(r);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a2bf478a242c096d2e0d3e4507a092c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp; c)</td>
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



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2bf478a242c096d2e0d3e4507a092c4d">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2bf478a242c096d2e0d3e4507a092c4d">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> &amp;c)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(c);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#acffc5ada9a7d440ecbe0806a375bc10b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp; c)</td>
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



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acffc5ada9a7d440ecbe0806a375bc10b">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acffc5ada9a7d440ecbe0806a375bc10b">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlcaption">DocHtmlCaption</a> &amp;c)     { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(c);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a71287f4e8ce55ad65cd979b5953e4c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp; i)</td>
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



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71287f4e8ce55ad65cd979b5953e4c85">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a71287f4e8ce55ad65cd979b5953e4c85">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternal">DocInternal</a> &amp;i)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(i);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae094469f57f2b537316aea706573cdab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp; h)</td>
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



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae094469f57f2b537316aea706573cdab">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae094469f57f2b537316aea706573cdab">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochref">DocHRef</a> &amp;h)            { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(h);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a3ad8b3823415a16dfaa51630c0677cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp; s)</td>
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



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ad8b3823415a16dfaa51630c0677cc4">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3ad8b3823415a16dfaa51630c0677cc4">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlsummary">DocHtmlSummary</a> &amp;s)     { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(s);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a1dc46761fac33da87e160f3a78ecbcae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp; d)</td>
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



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1dc46761fac33da87e160f3a78ecbcae">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1dc46761fac33da87e160f3a78ecbcae">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmldetails">DocHtmlDetails</a> &amp;d)     { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(d);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9b77a7ccc8480a9bd10c29ad36578183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp; h)</td>
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



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b77a7ccc8480a9bd10c29ad36578183">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9b77a7ccc8480a9bd10c29ad36578183">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlheader">DocHtmlHeader</a> &amp;h)      { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(h);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#aff8453da1335c0e51d78860f4510b4b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp; i)</td>
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



<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff8453da1335c0e51d78860f4510b4b5">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aff8453da1335c0e51d78860f4510b4b5">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docimage">DocImage</a> &amp;i)           { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(i);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a5235f87bc1fdc978b22e9998730cb35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp; df)</td>
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



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5235f87bc1fdc978b22e9998730cb35e">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5235f87bc1fdc978b22e9998730cb35e">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdotfile">DocDotFile</a> &amp;df)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(df); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab334af6b81322d7d437384debe04da5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp; df)</td>
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



<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab334af6b81322d7d437384debe04da5b">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab334af6b81322d7d437384debe04da5b">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docmscfile">DocMscFile</a> &amp;df)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(df); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#abd289832895043986162a1d6c7e86f2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp; df)</td>
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



<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd289832895043986162a1d6c7e86f2a">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd289832895043986162a1d6c7e86f2a">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docdiafile">DocDiaFile</a> &amp;df)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(df); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a21c8c2c9297498622e99be29f6da36e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp; df)</td>
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



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21c8c2c9297498622e99be29f6da36e7">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a21c8c2c9297498622e99be29f6da36e7">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docplantumlfile">DocPlantUmlFile</a> &amp;df)   { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(df); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a38f4afee39d980f80a4dc378cf53ac69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp; l)</td>
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



<p>Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38f4afee39d980f80a4dc378cf53ac69">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a38f4afee39d980f80a4dc378cf53ac69">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doclink">DocLink</a> &amp;l)            { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(l);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ac075dcb801cf9b1897ca5afd81be8889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp; r)</td>
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



<p>Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac075dcb801cf9b1897ca5afd81be8889">97</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac075dcb801cf9b1897ca5afd81be8889">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docref">DocRef</a> &amp;r)             { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(r);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#af5c16bf106d1bb53850a5565b21da550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp; s)</td>
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



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5c16bf106d1bb53850a5565b21da550">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af5c16bf106d1bb53850a5565b21da550">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecrefitem">DocSecRefItem</a> &amp;s)      { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(s);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a9d74fee058c638cb165e029e5c6bd609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp; l)</td>
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



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9d74fee058c638cb165e029e5c6bd609">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9d74fee058c638cb165e029e5c6bd609">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docsecreflist">DocSecRefList</a> &amp;l)      { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(l);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a1c7d70310bc619b4f5e08685e7d61de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp; s)</td>
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



<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c7d70310bc619b4f5e08685e7d61de0">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c7d70310bc619b4f5e08685e7d61de0">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamsect">DocParamSect</a> &amp;s)       { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(s);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a74a9b3e21db66831dc25f1a32082ed38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;)</td>
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



<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74a9b3e21db66831dc25f1a32082ed38">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a74a9b3e21db66831dc25f1a32082ed38">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a> &amp;)        {                    }</span></span></div>

</div>

</div>
</div>

### operator()() {#a49f9378c24ab5d72579c39330caa7aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp; x)</td>
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



<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49f9378c24ab5d72579c39330caa7aed">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a49f9378c24ab5d72579c39330caa7aed">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docxrefitem">DocXRefItem</a> &amp;x)        { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(x);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ab36490b641f0a71682679955d9ebb297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp; r)</td>
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



<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab36490b641f0a71682679955d9ebb297">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab36490b641f0a71682679955d9ebb297">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docinternalref">DocInternalRef</a> &amp;r)     { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(r);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ae32e2794207e6411e95fdb14745ac0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp; t)</td>
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



<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae32e2794207e6411e95fdb14745ac0ba">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae32e2794207e6411e95fdb14745ac0ba">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doctext">DocText</a> &amp;t)            { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(t);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#a059976e67597727de9e20b56bc3d31c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp; q)</td>
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



<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a059976e67597727de9e20b56bc3d31c5">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a059976e67597727de9e20b56bc3d31c5">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dochtmlblockquote">DocHtmlBlockQuote</a> &amp;q)  { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(q);  }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

### operator()() {#ad93fa293c26400b3fc8ab880c0f1b4ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)</td>
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



<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad93fa293c26400b3fc8ab880c0f1b4ec">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad93fa293c26400b3fc8ab880c0f1b4ec">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docvhdlflow">DocVhdlFlow</a> &amp;)         {                    }</span></span></div>

</div>

</div>
</div>

### operator()() {#ad5b6cd5ab6bb3326e7be15df2bb7d5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::operator() (const <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp; pb)</td>
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



<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5b6cd5ab6bb3326e7be15df2bb7d5c3">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad5b6cd5ab6bb3326e7be15df2bb7d5c3">operator()</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docparblock">DocParBlock</a> &amp;pb)       { <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(pb); }</span></span></div>

</div>


<p>Reference <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitChildren() {#a98bd21fc501edeca01045c90c07a4aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::visitChildren (const T &amp; t)</td>
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



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98bd21fc501edeca01045c90c07a4aad">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98bd21fc501edeca01045c90c07a4aad">visitChildren</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> T &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;child : t.children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">        std::visit(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, child);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Referenced by <a href="#a6596c51428e21b79305826fe801bcdd4">operator()</a>, <a href="#a23685ceb6a04c2fb3c4c6be68024f306">operator()</a>, <a href="#abd289832895043986162a1d6c7e86f2a">operator()</a>, <a href="#a5235f87bc1fdc978b22e9998730cb35e">operator()</a>, <a href="#ae094469f57f2b537316aea706573cdab">operator()</a>, <a href="#a059976e67597727de9e20b56bc3d31c5">operator()</a>, <a href="#acffc5ada9a7d440ecbe0806a375bc10b">operator()</a>, <a href="#a2bf478a242c096d2e0d3e4507a092c4d">operator()</a>, <a href="#ad75b3ce4e09deda54cd0b322207d8b59">operator()</a>, <a href="#af0b20b09948af8e83fa1f9caabb3a9fe">operator()</a>, <a href="#a0ff707d2dbf9fe8907d88b851cb6967c">operator()</a>, <a href="#a1dc46761fac33da87e160f3a78ecbcae">operator()</a>, <a href="#a9b77a7ccc8480a9bd10c29ad36578183">operator()</a>, <a href="#a746e3166528699c1ddb726789658343a">operator()</a>, <a href="#ab6f90da048f2bbf9661aabf78f1feb92">operator()</a>, <a href="#a9fbe0884bd203117011fccf02423100c">operator()</a>, <a href="#a3ad8b3823415a16dfaa51630c0677cc4">operator()</a>, <a href="#af0184a5b5bb5139323ea94060b89b471">operator()</a>, <a href="#aff8453da1335c0e51d78860f4510b4b5">operator()</a>, <a href="#a71287f4e8ce55ad65cd979b5953e4c85">operator()</a>, <a href="#ab36490b641f0a71682679955d9ebb297">operator()</a>, <a href="#a38f4afee39d980f80a4dc378cf53ac69">operator()</a>, <a href="#ab334af6b81322d7d437384debe04da5b">operator()</a>, <a href="#a21f014ebe48ddfcc5355e240a4fb7705">operator()</a>, <a href="#a1c7d70310bc619b4f5e08685e7d61de0">operator()</a>, <a href="#ad5b6cd5ab6bb3326e7be15df2bb7d5c3">operator()</a>, <a href="#a21c8c2c9297498622e99be29f6da36e7">operator()</a>, <a href="#ac075dcb801cf9b1897ca5afd81be8889">operator()</a>, <a href="#ade4cc82cae14ff8d531ffbf81f943ee4">operator()</a>, <a href="#af5c16bf106d1bb53850a5565b21da550">operator()</a>, <a href="#a9d74fee058c638cb165e029e5c6bd609">operator()</a>, <a href="#ab05566775448465866dbb3c63d4779ac">operator()</a>, <a href="#acc216d1a18e28c44effe5eb8376406ce">operator()</a>, <a href="#a278389ca9820c7fa26058b5fb5c5a992">operator()</a>, <a href="#ae32e2794207e6411e95fdb14745ac0ba">operator()</a>, <a href="#a8631059d2425e1f6b7630916617fec81">operator()</a> and <a href="#a49f9378c24ab5d72579c39330caa7aed">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### filter() {#a41b5f683e302b49a51ffc8f4199e6d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextDocVisitor::filter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>, definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-cpp">textdocvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41b5f683e302b49a51ffc8f4199e6d38">88</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41b5f683e302b49a51ffc8f4199e6d38">TextDocVisitor::filter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("TextDocVisitor::filter(%s)\n",str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = *p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) c=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a> &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>.</p>


<p>Referenced by <a href="#a88217cd97b6eaa15a8c8f4a8c4757db1">operator()</a>, <a href="#a23c1a244d091ae31fcd8ff2d66747054">operator()</a>, <a href="#ae3ad4f6c2986454bef71da208040245d">operator()</a>, <a href="#a285d9c57869ca5d67f1d0f7cd4e61f4f">operator()</a>, <a href="#a99aa0dd7813f8bd767c48d8f22b34a36">operator()</a> and <a href="#ad932c305668398f6c0b4aace1f3f8483">operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_t {#a80ad669a6389b88ced6163d3fd19f14f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream&amp; TextDocVisitor::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80ad669a6389b88ced6163d3fd19f14f">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#a80ad669a6389b88ced6163d3fd19f14f">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a41b5f683e302b49a51ffc8f4199e6d38">filter</a>, <a href="#a88217cd97b6eaa15a8c8f4a8c4757db1">operator()</a>, <a href="#a23c1a244d091ae31fcd8ff2d66747054">operator()</a>, <a href="#a5bf7ba9afe6d0fdded369e823a576312">operator()</a>, <a href="#a6c102a60d7e0736462e163ed5ce65985">operator()</a>, <a href="#a3af6b81e834fce376849077c0fa6b565">operator()</a>, <a href="#a50f1e8ea75600502fc5d9c9e85f2c42d">operator()</a> and <a href="#a8871e218557de5dd120f069aa24943e5">TextDocVisitor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/textdocvisitor-cpp">textdocvisitor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/textdocvisitor-h">textdocvisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
