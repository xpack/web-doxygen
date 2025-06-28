---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/htmlgenerator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `HtmlGenerator` Class Reference

<p>Generator for HTML output. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class HtmlGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/htmlgen-h">src/htmlgen.h</a>&gt;
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputgenerator">OutputGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for shared implementation for all output generators. <a href="/web-doxygen/docs/api/classes/outputgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for output generators. <a href="/web-doxygen/docs/api/classes/outputgenintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a> (const HtmlGenerator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d0647721017cb789265f3ef0308349">HtmlGenerator</a> (HtmlGenerator &amp;&amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d3c67df991a213ef94780d91367a12">~HtmlGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a> (const HtmlGenerator &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6344452ddcb80e7dc2000c6186121cb">operator=</a> (HtmlGenerator &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0be36300dc3636e212df095e2b31397">clearBuffer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8164db5b0eaa9499cf02083114cff358">type</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5b6f9593880ec7974154024672dab72">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7780b856bce0c4e0ea29e92fec08dce">addCodeGen</a> (OutputCodeList &amp;list) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bec825c1c10f337c697e790f6cac8d6">cleanup</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4baf32d6d76de7c48ea865fe47496612">writeDoc</a> (const IDocNodeAST *node, const Definition *, const MemberDef *, int id) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a> (const QCString &amp;name, const QCString &amp;manName, const QCString &amp;title, int id, int hierarchyLevel) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d89564f75789d7f452bd01b6bfa14b">endFile</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c585c2b2bb740380ac384da86ae8477">writeFooter</a> (const QCString &amp;navPath) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b34fac2db4cc617332b082a1a087095">writeSearchInfo</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cdd8741ce148e10f53fca1b9f47f866">startIndexSection</a> (IndexSection) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf3fd95d2b2c10d8e84da5adaab1dce">endIndexSection</a> (IndexSection) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefbbae5ae8945e7c52e4a33daa40e9b7">writePageLink</a> (const QCString &amp;, bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce5f3aec5a887f33e47443fbc071d64">startProjectNumber</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4d79122d4f9001e93365e5274dc5cc">endProjectNumber</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86eb94b45459e81c896e184152dd7176">writeStyleInfo</a> (int part) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab529153ad002aa294643ef13adbf351a">startTitleHead</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe66b78ec5e7be56c1d8e4d5c6f2b2e">endTitleHead</a> (const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3877e4dc1ec9c0f9e0c0c8ae8c9ec6a9">startParagraph</a> (const QCString &amp;classDef) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b830c30201e8b2ba3a2103acceff7cd">endParagraph</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a2e0e20f56eb2256b9b8741ec8b33f">writeString</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7e7bf073a75a8377e6031d8b798063">startIndexListItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2997268cba31448fe3ec43d3e980c78">endIndexListItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642f7c83fd60f3acc6820127e0d0fa9d">startIndexList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38b18ddbb0822f71d8c56db9f6798fc4">endIndexList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad19095c7e9f02127aa3be21956d915">startIndexKey</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753d63e17acc0010e76b8cd441741180">endIndexKey</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac077b0913733fb9701b7759c44ffbd">startIndexValue</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab71ffb2e8886e91089d788647c74e3c6">endIndexValue</a> (const QCString &amp;, bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6ed316d237d1da4b7c3b8d4f822d68">startItemList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7f3aba96e41a1525db5bd833d48067">endItemList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80da85d198868bc3351b1a6a90f32a75">startIndexItem</a> (const QCString &amp;ref, const QCString &amp;file) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea7b80127d86e6971ff8933e3e8ae42d">endIndexItem</a> (const QCString &amp;ref, const QCString &amp;file) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e18e094779f6af393deafc4b64d454">writeObjectLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1099f1315ce5240b9165563e30471124">startTextLink</a> (const QCString &amp;file, const QCString &amp;anchor) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb9a151291ddcd9b1e6eee2b228b754">endTextLink</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455cc2ac7c3f27ea0348c24c2f8a0f62">startTypewriter</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ea951201d8b37278044a38c4be9949">endTypewriter</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac590d2ce8474c9bd7c2abbc9679fb11d">startGroupHeader</a> (const QCString &amp;, int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44799df53d0705c6a8f1611bf0c686f2">endGroupHeader</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0cac82069348e3bea2d7912feb3d87">startItemListItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6432012a68a21dc44897857bb774f76f">endItemListItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e8e67b9d4140660537473a3c98c3d4">startMemberSections</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9261c777bbdaa1882cbd9186c6b08fb6">endMemberSections</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d710dda637c39d769e433ea953bb1b3">startHeaderSection</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835dc606cb69304a10a5af081585ff78">endHeaderSection</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea90b1337254e9c10ceaefcff8b9c825">startMemberHeader</a> (const QCString &amp;, int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2b7702acdf9b41c6b78cee0177820b">endMemberHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287320869b27536a66d09bd7f545507a">startMemberSubtitle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f7f3498ff3870052db84b11e20eec4">endMemberSubtitle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53aef5bc2dc01700784de5269730cb46">startMemberDocList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9300885ee109900582e9a2c8dc298c21">endMemberDocList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b26359bf24a0cac681e048110451dda">startMemberList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3839bea77bec5697144e8fc0d6ebea15">endMemberList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed122d098bf970698797293cabd09b21">startInlineHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e4b1850daaf19be1cc41dc34e69979">endInlineHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c325207af03cb2116d59d5b1b7a84c">startAnonTypeScope</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb928846109209685c293abf118c62c">endAnonTypeScope</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec800447787c1eada0c828c6d3bb374">startMemberItem</a> (const QCString &amp;anchor, MemberItemType, const QCString &amp;inheritId) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6ff44b008a49f08afd2347655b3831a">endMemberItem</a> (MemberItemType) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f7ada93721d02805a695d80cb4ca0fe">startMemberTemplateParams</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb252c9c1a9af617ee975f211f3da598">endMemberTemplateParams</a> (const QCString &amp;anchor, const QCString &amp;inheritId) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42347ea9872571c56ab5127514370b8e">startCompoundTemplateParams</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940ab965d6b42f7a8a8e3f26f926ff42">endCompoundTemplateParams</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac80db5c4ebf34e1aefa117b542507a">startMemberGroupHeader</a> (const QCString &amp;, bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e033353bdec24873c922894b8a36d4">endMemberGroupHeader</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e40997271cb08e164b46ad72459d12c">startMemberGroupDocs</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a842c61286aea39f627c46ae95210a9">endMemberGroupDocs</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8271b410ef99182f6229857ab18f56f">startMemberGroup</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64cca65695d73978bf4ce3c0aa7051d7">endMemberGroup</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6116e3f64dcba6a1b4152afdf91fa1">insertMemberAlign</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2260389b86a386811fc344bb6ec9273d">insertMemberAlignLeft</a> (MemberItemType, bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477b9bf180d9c7a57edcd11c408cdb5b">startMemberDescription</a> (const QCString &amp;anchor, const QCString &amp;inheritId, bool typ) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca9bf50e7dc80e39b2e9264b3c916ad">endMemberDescription</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292546e2f380d75990bfec88cc579a06">startMemberDeclaration</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21d10473a4e983501ec2e97e738a682">endMemberDeclaration</a> (const QCString &amp;anchor, const QCString &amp;inheritId) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af012e45f04c5da89f11d17770dad1b00">writeInheritedSectionTitle</a> (const QCString &amp;id, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;title, const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3ba3fa4795d6f4130c6430252a099e">writeRuler</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fc309a5382d6beb8f919fc436709e2">writeAnchor</a> (const QCString &amp;, const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a160471f9e3f531fa16ba15bcc467392f">startEmphasis</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ad044610596fe6a022162ca73bd2f3">endEmphasis</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ad780056d93e93a6d630b5f0f025df">startBold</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd13d8dc0cfe6f4167da3ea51041eeaa">endBold</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062324c12b32fa04ce3ed878590769a7">startDescForItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e3f7fb6b7c623adb98082a237f28bb">endDescForItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1afec505ae6d03e654d11f3b6010a36d">lineBreak</a> (const QCString &amp;style) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a70bf7faba5c41a9fe61307f15ce0d3">writeChar</a> (char c) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e27be79946300ecc5d82289192fb691">startMemberDoc</a> (const QCString &amp;clName, const QCString &amp;memName, const QCString &amp;anchor, const QCString &amp;title, int memCount, int memTotal, bool showInline) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84d2a7b716a16fa142c0fdb0f8c338c">endMemberDoc</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c7cd661ef071ac37a0fb4efcf31574">startDoxyAnchor</a> (const QCString &amp;fName, const QCString &amp;manName, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;args) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f00bc90c73109a50bf3c9b94358e13f">endDoxyAnchor</a> (const QCString &amp;fName, const QCString &amp;anchor) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ce30a94ffb23fbc28c653e994ba794">addLabel</a> (const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504ef77641d52aea691b99b67a12445f">writeLatexSpacing</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af437de0126be35d936123ca8eff51a">writeStartAnnoItem</a> (const QCString &amp;type, const QCString &amp;file, const QCString &amp;path, const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bd1c0fe5fa8cc53924bbd8639674840">startCenter</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a425a35b6459f9e9faef4647e374592">endCenter</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8fff599224cb05f307e07f60fd06c1d">startSmall</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60dde525b35f9f620a51070aab5e87f4">endSmall</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad122021b54713f1bfb7058d4723af613">startExamples</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a0d7bb0cbbb2dd55182ea054b50176">endExamples</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3bbc191d41c6566b7bafe7a063dd1ac">startSection</a> (const QCString &amp;, const QCString &amp;, SectionType) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec484816eb09040f49038c4b0a999f23">endSection</a> (const QCString &amp;, SectionType) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87854052ee77c122ec7cbe42a7089113">addIndexItem</a> (const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848866b2ca1f5ded259c90a391a7abc4">startIndent</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5068d044d959a849cf7fd9743d07c012">endIndent</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a658e00cd4c2a6a97fa1f6746739c3984">writeSynopsis</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a005f1a46f9808e8a719ba756407259ec">startClassDiagram</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e132b23d93e17c4e30b815977a5c865">endClassDiagram</a> (const ClassDiagram &amp;, const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcccf18ee3dacb0315c80dd8010a2fa1">startPageRef</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3ba521b2573cc57e3e0685124e00ed">endPageRef</a> (const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5788d7e519223edb196aa42008c475d9">startQuickIndices</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6c0960d638ac86281ecefc1213d8d1">endQuickIndices</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add51830ca796373d40b216621b6d4b8e">writeSplitBar</a> (const QCString &amp;name, const QCString &amp;allMembersFile) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4546e1dafb6db9b26352c6c0aca8f0dd">writeNavigationPath</a> (const QCString &amp;s) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049734b4a24f5f4c365cc8352a9e9e39">writeLogo</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23778fa833bc3d55e61c2cb13d39c090">writeQuickLinks</a> (HighlightedItem hli, const QCString &amp;file, bool extraTabs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf222cd6347aaf899d714dae6ddeb52f">writeSummaryLink</a> (const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;title, bool first) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715a0d36fadb1999b1e2d0162aa03825">writePageOutline</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4a211b9f17df0484bcc2658d5abdaf">startContents</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c1a1a311c32a34c735413521d117a3e">endContents</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e345b8b54d35f3900d6b5a53aad546">startPageDoc</a> (const QCString &amp;pageTitle) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a7c461a41d487efe3c90a5ed69caf4">endPageDoc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f723ce20e5ff505a49cac90da7e2d3d">writeNonBreakableSpace</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea8da6d66244a87fe3141b1165e084c">startDescTable</a> (const QCString &amp;title, const bool hasInits) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ca46b12db83276b90fc5e706c24682">endDescTable</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a401d1ec435f24eb9c4ef50f983e37af7">startDescTableRow</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55ba92a674ec09dfd13ff7f6811d78e6">endDescTableRow</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2229e11153da2bf67e59928d250783">startDescTableTitle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac18fa9a0f9c3de7c8969e1fb1d669c13">endDescTableTitle</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578dfeee8598b1dbb0910e7d42e46ee9">startDescTableInit</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed12b681f9ef106d1b9a245c720b2d9">endDescTableInit</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a58ad6a53095540f4abafb003fc47a1">startDescTableData</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fcd1422de24ca62489159681167573">endDescTableData</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cacd7e83fff3a670a66073686c882a8">startDotGraph</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bf91873a8da583cfbb47b15806c0ae4">endDotGraph</a> (DotClassGraph &amp;g) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20449975cf6595d7c2cb353f1c26534f">startInclDepGraph</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78029628ccb4f7aef7ca0c4cbce0ae3">endInclDepGraph</a> (DotInclDepGraph &amp;g) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d892ee256e9a34db8cf761569bb2c9c">startGroupCollaboration</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf59d930dff9f6aa46e3e5674678a35">endGroupCollaboration</a> (DotGroupCollaboration &amp;g) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d21b07f7218dcc1161ed797dc8a74a">startCallGraph</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add957a1f68cc9b99a4c57caa58b33a9b">endCallGraph</a> (DotCallGraph &amp;g) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41dc42e70634afb2a68fd1c45dd16f91">startDirDepGraph</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603fd2d86e322ea4018747febe523edf">endDirDepGraph</a> (DotDirDeps &amp;g) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05e0b9d1baf567428af8a4e6b96b0ca">writeGraphicalHierarchy</a> (DotGfxHierarchyTable &amp;g) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8a36f69c16ce253b2fb173f7f36674">startTextBlock</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad907561a88520aac4253dd94cccfb73f">endTextBlock</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab871f28ae2928638adde578fe1514aca">lastIndexPage</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f67237c29b8499dae33d2462cef68a">startMemberDocPrefixItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac007b8ceaed1b6260def8b681ec1e1da">endMemberDocPrefixItem</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30b47346a71e1216fb4083c64675bf4e">startMemberDocName</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ad614730d5b184f8d98b4d3ca6e6dcd">endMemberDocName</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a566f2060c7d674363ec9f009e47430ac">startParameterType</a> (bool first, const QCString &amp;key) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3462109af2644ffeb87b40975d7fb7bd">endParameterType</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc2066cc3b3716a98dfb95d756fa838">startParameterName</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535f67c3665549f6f93202fd19ec46da">endParameterName</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8133798f73d8a88098f57559170a0f0">startParameterExtra</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad8dcc25a41bc905e649e12b0302a3d">endParameterExtra</a> (bool last, bool emptyList, bool closeBracket) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18891cddc72601d23dc617fd045911d8">startParameterDefVal</a> (const char *sep) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64513a369c8c8c75dcac36ba1e9341f1">endParameterDefVal</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af453192b313a5d9bcc31360b15c7feaa">startParameterList</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a76953ad9eafdccdad1bc536fd9a097">endParameterList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726c53bd6e118a6ab62e6022c7dd80e6">exceptionEntry</a> (const QCString &amp;, bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e492ea8c1e1d299d8ab6af19fd52c9a">startConstraintList</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4239a94a42b77210e64e042cfee7f726">startConstraintParam</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2448ccd6f13a29e9517e5a0cdb8db73">endConstraintParam</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab07067c23edb49e8b251e963a480e5c5">startConstraintType</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04149859c738f4615b722c17a3c643f">endConstraintType</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79bdcce95772f1eb1c314a2da602097">startConstraintDocs</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eba93d3b17a8449d5be024af4eb22d4">endConstraintDocs</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a75abb12be07ae3d3ae71ad65fd97f6">endConstraintList</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5dae7d567cd940f9dab8408272e8cd">startMemberDocSimple</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedce042225aecc4a3d499d675251bd6b">endMemberDocSimple</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12aa643326c720f1a8f80610c1bc82fc">startInlineMemberType</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de90155aebd5eacbbca903687f8e5f5">endInlineMemberType</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d47d7645dc5b280ff77706469a7dd87">startInlineMemberName</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5d2db9d4bdda1b0ae0c6824bfbe415">endInlineMemberName</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a719fede306ded713d46b9551eec66cf7">startInlineMemberDoc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcdb6177d9281921c6d2aa6893b1b5c9">endInlineMemberDoc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34bd3e5c72c259091f2546327ac84868">startLabels</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ebfa2100dc76714c34b65372f8ce867">writeLabel</a> (const QCString &amp;l, bool isLast) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11aa8c21a8b7eb4af49fc708e43e909">endLabels</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5af845a03a3c0c16a3855d88034dfa70">startLocalToc</a> (int level) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb64fea3c5e96e1c48b5caba59681fb">endLocalToc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c8a6327e1ce58e1d01bc05a1770e94b">startTocEntry</a> (const SectionInfo *si) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5a12bcaed78c969eac8b73cb19d798f">endTocEntry</a> (const SectionInfo *si) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a> (const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd5a2e848ea16b025b1fb07b4b307fc">startTitle</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1337adbb5ad6cea03fcee0d5a7cdfce">endTitle</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a894bfecdbda01b83760c93a6a6947b9d">docify_</a> (const QCString &amp;text, bool inHtmlComment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlcodegenerator">HtmlCodeGenerator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8830ad77ec53a2c66f11d161cedf292c">m_pageOutlineIndent</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/htmlgenerator/tocstate">TocState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4c6cd48e43f74bf258851f8b109faf">init</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0dc4a7197da8f8aa16b96d1c958ab2">writeStyleSheetFile</a> (TextStream &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00e0c98e1c833ae27198d1e10c9c22e">writeHeaderFile</a> (TextStream &amp;t, const QCString &amp;cssname)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1132096e93e030970694a61ea6c65f">writeFooterFile</a> (TextStream &amp;t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7306ef9abbceafd6074b4d883a59f033">writeTabData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Additional initialization after indices have been created. <a href="#a7306ef9abbceafd6074b4d883a59f033">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6341c32bafc4883a531b50502dfcd9">writeSearchInfoStatic</a> (TextStream &amp;t, const QCString &amp;relPath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9114c68d96141e80c08efdd497fc010e">writeSearchData</a> (const QCString &amp;dir)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd6971ba73b744d9ceb90478194d61d">writeSearchPage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9588784ebebaad9cb24e153c07aeb662">writeExternalSearchPage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">writeLogoAsString</a> (const QCString &amp;path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a> (const QCString &amp;name, const QCString &amp;relpath, const QCString &amp;allMembersFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ae2deb6a25b4b0307edd25ad66896f">getMathJaxMacros</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3874b75d86f996ce7d7ca32bea785c56">getNavTreeCss</a> ()</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a> (TextStream &amp;t, const QCString &amp;, const QCString &amp;, const QCString &amp;)</td>
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

<p>Generator for HTML output.</p>

<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### HtmlGenerator() {#a0dc05bee31f886b2b5d5318d0c0213a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlGenerator::HtmlGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1090 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0dc05bee31f886b2b5d5318d0c0213a4">1090</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator::HtmlGenerator</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:HtmlGenerator()\n",(void*)this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a> = <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>-&gt;add&lt;<a href="/web-doxygen/docs/api/classes/htmlcodegenerator">HtmlCodeGenerator</a>&gt;(&amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m&#95;codeGen</a>, <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m&#95;codeList</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator::OutputGenerator</a>.

Referenced by <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a79d0647721017cb789265f3ef0308349">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a> and <a href="#aa6344452ddcb80e7dc2000c6186121cb">operator=</a>.
</div>
</div>

### HtmlGenerator() {#ad04eea6ce6f560d620aa10365466ba44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlGenerator::HtmlGenerator (const <a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> &amp; og)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1098 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad04eea6ce6f560d620aa10365466ba44">1098</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator::HtmlGenerator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a> &amp;og) : <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a>(og.<a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>), <a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:HtmlGenerator(copy %p)\n",(void*)this,(void*)&amp;og);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>     = std::make_unique&lt;OutputCodeList&gt;(*og.<a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>      = <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>-&gt;get&lt;<a href="/web-doxygen/docs/api/classes/htmlcodegenerator">HtmlCodeGenerator</a>&gt;(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>-&gt;setTextStream(&amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>    = og.<a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a>     = og.<a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>      = og.<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a> = og.<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a> = og.<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a>, <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m&#95;codeGen</a>, <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m&#95;codeList</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">OutputGenerator::m&#95;dir</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a>, <a href="#a453969afc6bce23453c23dbc81bc0996">m&#95;lastFile</a>, <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m&#95;lastTitle</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator::OutputGenerator</a>.
</div>
</div>

### HtmlGenerator() {#a79d0647721017cb789265f3ef0308349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlGenerator::HtmlGenerator (<a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

Reference <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~HtmlGenerator() {#a11d3c67df991a213ef94780d91367a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlGenerator::~HtmlGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a2a179f3313aad4e67a77b536a25a101b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlGenerator &amp; HtmlGenerator::operator= (const <a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> &amp; og)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 100 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1111 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a179f3313aad4e67a77b536a25a101b">1111</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a> &amp;<a href="#a2a179f3313aad4e67a77b536a25a101b">HtmlGenerator::operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a> &amp;og)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:HtmlGenerator(copy assign %p)\n",(void*)this,(void*)&amp;og);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">!=&amp;og)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>          = og.<a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>     = std::make_unique&lt;OutputCodeList&gt;(*og.<a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>      = <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>-&gt;get&lt;<a href="/web-doxygen/docs/api/classes/htmlcodegenerator">HtmlCodeGenerator</a>&gt;(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>-&gt;setTextStream(&amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>    = og.<a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a>     = og.<a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>      = og.<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a> = og.<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a> = og.<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a>, <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m&#95;codeGen</a>, <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m&#95;codeList</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">OutputGenerator::m&#95;dir</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a>, <a href="#a453969afc6bce23453c23dbc81bc0996">m&#95;lastFile</a>, <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m&#95;lastTitle</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### operator=() {#aa6344452ddcb80e7dc2000c6186121cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlGenerator &amp; HtmlGenerator::operator= (<a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

Reference <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGen() {#ab7780b856bce0c4e0ea29e92fec08dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::addCodeGen (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; list)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 124 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1131 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7780b856bce0c4e0ea29e92fec08dce">1131</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab7780b856bce0c4e0ea29e92fec08dce">HtmlGenerator::addCodeGen</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;list)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">  list.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">add</a>&lt;<a href="/web-doxygen/docs/api/files/src/outputlist-h/#a6bfa5e817e6c7a7250c6ad815f2e192a">HtmlCodeGeneratorDefer</a>&gt;(<a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">OutputCodeList::add</a> and <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m&#95;codeGen</a>.
</div>
</div>

### addIndexItem() {#a87854052ee77c122ec7cbe42a7089113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::addIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 242 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2548 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87854052ee77c122ec7cbe42a7089113">2548</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a87854052ee77c122ec7cbe42a7089113">HtmlGenerator::addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2550</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### addLabel() {#ac3ce30a94ffb23fbc28c653e994ba794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::addLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 230 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1658 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3ce30a94ffb23fbc28c653e994ba794">1658</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac3ce30a94ffb23fbc28c653e994ba794">HtmlGenerator::addLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### cleanup() {#a8bec825c1c10f337c697e790f6cac8d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::cleanup ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 125 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1275 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8bec825c1c10f337c697e790f6cac8d6">1275</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8bec825c1c10f337c697e790f6cac8d6">HtmlGenerator::cleanup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dname = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(dname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### clearBuffer() {#af0be36300dc3636e212df095e2b31397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::clearBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>
</div>
</div>

### clone() {#ad5b6f9593880ec7974154024672dab72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputGenIntf &gt; HtmlGenerator::clone ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5b6f9593880ec7974154024672dab72">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputGenIntf&gt; <a href="#ad5b6f9593880ec7974154024672dab72">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;HtmlGenerator&gt;(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">); }</span></span></div>

</div>

</div>
</div>

### docify() {#ad8c12afa5b7d84e2e403af4c3ed30cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::docify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 157 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1854 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">1854</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">HtmlGenerator::docify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a894bfecdbda01b83760c93a6a6947b9d">docify_</a>(str,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a894bfecdbda01b83760c93a6a6947b9d">docify&#95;</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.

Referenced by <a href="#ad122021b54713f1bfb7058d4723af613">startExamples</a>, <a href="#a3e27be79946300ecc5d82289192fb691">startMemberDoc</a>, <a href="#a18891cddc72601d23dc617fd045911d8">startParameterDefVal</a>, <a href="#a4a70bf7faba5c41a9fe61307f15ce0d3">writeChar</a>, <a href="#a46e18e094779f6af393deafc4b64d454">writeObjectLink</a> and <a href="#a9af437de0126be35d936123ca8eff51a">writeStartAnnoItem</a>.
</div>
</div>

### endAnonTypeScope() {#a2eb928846109209685c293abf118c62c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endAnonTypeScope (int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2eb928846109209685c293abf118c62c">186</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2eb928846109209685c293abf118c62c">endAnonTypeScope</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### endBold() {#abd13d8dc0cfe6f4167da3ea51041eeaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endBold ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd13d8dc0cfe6f4167da3ea51041eeaa">217</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd13d8dc0cfe6f4167da3ea51041eeaa">endBold</a>()</span><span class="doxyHighlightKeyword"> override       </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endCallGraph() {#add957a1f68cc9b99a4c57caa58b33a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endCallGraph (<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp; g)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 282 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2471 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add957a1f68cc9b99a4c57caa58b33a9b">2471</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>(<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2472</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2478</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotcallgraph/#ad59c94658b83032817c03c0d59c7e5da">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotcallgraph/#ad59c94658b83032817c03c0d59c7e5da">DotCallGraph::writeGraph</a>.
</div>
</div>

### endCenter() {#a9a425a35b6459f9e9faef4647e374592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endCenter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a425a35b6459f9e9faef4647e374592">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a425a35b6459f9e9faef4647e374592">endCenter</a>()</span><span class="doxyHighlightKeyword"> override          </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/center&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endClassDiagram() {#a6e132b23d93e17c4e30b815977a5c865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endClassDiagram (const <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp; d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 247 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1978 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e132b23d93e17c4e30b815977a5c865">1978</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp;d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> tt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">  d.<a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">writeImage</a>(tt,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tt.<a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;div class=\"center\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;img src=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a> &lt;&lt; <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".png\" usemap=\"#"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_map\" alt=\"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;map id=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_map\" name=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_map\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; tt.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/map&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;div class=\"center\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;img src=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a> &lt;&lt; <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".png\" alt=\"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">TextStream::empty</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a> and <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

### endCompoundTemplateParams() {#a940ab965d6b42f7a8a8e3f26f926ff42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endCompoundTemplateParams ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 192 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2077 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a940ab965d6b42f7a8a8e3f26f926ff42">2077</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a940ab965d6b42f7a8a8e3f26f926ff42">HtmlGenerator::endCompoundTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endConstraintDocs() {#a6eba93d3b17a8449d5be024af4eb22d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endConstraintDocs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 313 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3306 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6eba93d3b17a8449d5be024af4eb22d4">3306</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6eba93d3b17a8449d5be024af4eb22d4">HtmlGenerator::endConstraintDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3307</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3308</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3309</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endConstraintList() {#a4a75abb12be07ae3d3ae71ad65fd97f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endConstraintList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 314 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3311 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a75abb12be07ae3d3ae71ad65fd97f6">3311</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a75abb12be07ae3d3ae71ad65fd97f6">HtmlGenerator::endConstraintList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3312</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3313</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3314</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/dd&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3315</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/dl&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3316</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3317</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endConstraintParam() {#ab2448ccd6f13a29e9517e5a0cdb8db73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endConstraintParam ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 309 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3286 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2448ccd6f13a29e9517e5a0cdb8db73">3286</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab2448ccd6f13a29e9517e5a0cdb8db73">HtmlGenerator::endConstraintParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3287</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3288</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/em&gt;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3289</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endConstraintType() {#ae04149859c738f4615b722c17a3c643f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endConstraintType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 311 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3296 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae04149859c738f4615b722c17a3c643f">3296</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae04149859c738f4615b722c17a3c643f">HtmlGenerator::endConstraintType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3297</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/em&gt;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3299</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endContents() {#a7c1a1a311c32a34c735413521d117a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endContents ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 259 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3048 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c1a1a311c32a34c735413521d117a3e">3048</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c1a1a311c32a34c735413521d117a3e">HtmlGenerator::endContents</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3049</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3050</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- contents --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3051</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDescForItem() {#a80e3f7fb6b7c623adb98082a237f28bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDescForItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80e3f7fb6b7c623adb98082a237f28bb">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a80e3f7fb6b7c623adb98082a237f28bb">endDescForItem</a>()</span><span class="doxyHighlightKeyword"> override   </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/dd&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDescTable() {#a15ca46b12db83276b90fc5e706c24682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDescTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 265 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2565 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15ca46b12db83276b90fc5e706c24682">2565</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a15ca46b12db83276b90fc5e706c24682">HtmlGenerator::endDescTable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2567</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2568</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDescTableData() {#a97fcd1422de24ca62489159681167573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDescTableData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 273 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2605 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97fcd1422de24ca62489159681167573">2605</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a97fcd1422de24ca62489159681167573">HtmlGenerator::endDescTableData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDescTableInit() {#a0ed12b681f9ef106d1b9a245c720b2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDescTableInit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 271 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2595 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ed12b681f9ef106d1b9a245c720b2d9">2595</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0ed12b681f9ef106d1b9a245c720b2d9">HtmlGenerator::endDescTableInit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2596</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2597</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2598</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDescTableRow() {#a55ba92a674ec09dfd13ff7f6811d78e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDescTableRow ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 267 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2575 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55ba92a674ec09dfd13ff7f6811d78e6">2575</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a55ba92a674ec09dfd13ff7f6811d78e6">HtmlGenerator::endDescTableRow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDescTableTitle() {#ac18fa9a0f9c3de7c8969e1fb1d669c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDescTableTitle ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 269 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2585 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac18fa9a0f9c3de7c8969e1fb1d669c13">2585</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac18fa9a0f9c3de7c8969e1fb1d669c13">HtmlGenerator::endDescTableTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endDirDepGraph() {#a603fd2d86e322ea4018747febe523edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDirDepGraph (<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp; g)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 284 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2489 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a603fd2d86e322ea4018747febe523edf">2489</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>(<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotdirdeps/#a636d65d1b7097eca39e1dc431e8a7b32">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotdirdeps/#a636d65d1b7097eca39e1dc431e8a7b32">DotDirDeps::writeGraph</a>.
</div>
</div>

### endDotGraph() {#a8bf91873a8da583cfbb47b15806c0ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDotGraph (<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp; g)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 276 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2401 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8bf91873a8da583cfbb47b15806c0ae4">2401</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>(<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateLegend = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_LEGEND);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> umlLook = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(UML_LOOK);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#a0273e4e9adfbbe1f601a986636ef79dc">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateLegend &amp;&amp; !umlLook)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>+</span><span class="doxyHighlightStringLiteral">"graph_legend"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;center&gt;&lt;span class=\"legend\"&gt;["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"target=\"top\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!url.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trLegend();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]&lt;/span&gt;&lt;/center&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a0273e4e9adfbbe1f601a986636ef79dc">DotClassGraph::writeGraph</a>.
</div>
</div>

### endDoxyAnchor() {#a9f00bc90c73109a50bf3c9b94358e13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 229 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1654 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f00bc90c73109a50bf3c9b94358e13f">1654</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9f00bc90c73109a50bf3c9b94358e13f">HtmlGenerator::endDoxyAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endEmphasis() {#a47ad044610596fe6a022162ca73bd2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endEmphasis ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47ad044610596fe6a022162ca73bd2f3">215</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a47ad044610596fe6a022162ca73bd2f3">endEmphasis</a>()</span><span class="doxyHighlightKeyword"> override   </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/em&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endExamples() {#a73a0d7bb0cbbb2dd55182ea054b50176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endExamples ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 239 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2617 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73a0d7bb0cbbb2dd55182ea054b50176">2617</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a73a0d7bb0cbbb2dd55182ea054b50176">HtmlGenerator::endExamples</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/dl&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endFile() {#a05d89564f75789d7f452bd01b6bfa14b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endFile ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 128 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1561 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05d89564f75789d7f452bd01b6bfa14b">1561</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a05d89564f75789d7f452bd01b6bfa14b">HtmlGenerator::endFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a>.
</div>
</div>

### endGroupCollaboration() {#aabf59d930dff9f6aa46e3e5674678a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endGroupCollaboration (<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp; g)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 280 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2453 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabf59d930dff9f6aa46e3e5674678a35">2453</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a>(<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a1e26ce5a2563ee5144ef66ff9cf88461">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a1e26ce5a2563ee5144ef66ff9cf88461">DotGroupCollaboration::writeGraph</a>.
</div>
</div>

### endGroupHeader() {#a44799df53d0705c6a8f1611bf0c686f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endGroupHeader (int extraIndentLevel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 167 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1807 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44799df53d0705c6a8f1611bf0c686f2">1807</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a44799df53d0705c6a8f1611bf0c686f2">HtmlGenerator::endGroupHeader</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraIndentLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extraIndentLevel==2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h4&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extraIndentLevel==1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h3&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h2&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endHeaderSection() {#a835dc606cb69304a10a5af081585ff78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endHeaderSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 174 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3348 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a835dc606cb69304a10a5af081585ff78">3348</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a835dc606cb69304a10a5af081585ff78">HtmlGenerator::endHeaderSection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3349</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3350</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!--header--&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3351</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endInclDepGraph() {#ac78029628ccb4f7aef7ca0c4cbce0ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endInclDepGraph (<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp; g)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 278 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2435 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac78029628ccb4f7aef7ca0c4cbce0ae3">2435</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>(<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2441</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a197a7b8e9b068d122b062c80b21784e4">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a95a7a96e259bc6213901ea61ae4ca431">endSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae2e58dbdf23ed7a1c24f10c4c81ec544">endSectionHeader</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ae5b4dc7827454fb9508e9a7ee4e663e8">endSectionSummary</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a34e1ea8704b315e66086811539bd1a5f">startSectionContent</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5de92e3118bc2a62d1f43598d1cb2028">startSectionSummary</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a197a7b8e9b068d122b062c80b21784e4">DotInclDepGraph::writeGraph</a>.
</div>
</div>

### endIndent() {#a5068d044d959a849cf7fd9743d07c012}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 244 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2542 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5068d044d959a849cf7fd9743d07c012">2542</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5068d044d959a849cf7fd9743d07c012">HtmlGenerator::endIndent</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2543</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endIndent --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2545</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n&lt;/div&gt;\n"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2546</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endIndexItem() {#aea7b80127d86e6971ff8933e3e8ae42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 156 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1720 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea7b80127d86e6971ff8933e3e8ae42d">1720</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aea7b80127d86e6971ff8933e3e8ae42d">HtmlGenerator::endIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("HtmlGenerator::endIndexItem(%s,%s,%s)\n",ref,f,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || !f.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endIndexKey() {#a753d63e17acc0010e76b8cd441741180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndexKey ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 150 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2205 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a753d63e17acc0010e76b8cd441741180">2205</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a753d63e17acc0010e76b8cd441741180">HtmlGenerator::endIndexKey</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/td&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endIndexList() {#a38b18ddbb0822f71d8c56db9f6798fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndexList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 148 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2195 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38b18ddbb0822f71d8c56db9f6798fc4">2195</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a38b18ddbb0822f71d8c56db9f6798fc4">HtmlGenerator::endIndexList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endIndexListItem() {#af2997268cba31448fe3ec43d3e980c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndexListItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 146 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1685 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2997268cba31448fe3ec43d3e980c78">1685</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af2997268cba31448fe3ec43d3e980c78">HtmlGenerator::endIndexListItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endIndexSection() {#acdf3fd95d2b2c10d8e84da5adaab1dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acdf3fd95d2b2c10d8e84da5adaab1dce">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acdf3fd95d2b2c10d8e84da5adaab1dce">endIndexSection</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a>)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### endIndexValue() {#ab71ffb2e8886e91089d788647c74e3c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endIndexValue (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 152 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2215 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab71ffb2e8886e91089d788647c74e3c6">2215</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab71ffb2e8886e91089d788647c74e3c6">HtmlGenerator::endIndexValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/td&gt;&lt;/tr&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endInlineHeader() {#a64e4b1850daaf19be1cc41dc34e69979}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endInlineHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 184 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3363 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64e4b1850daaf19be1cc41dc34e69979">3363</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64e4b1850daaf19be1cc41dc34e69979">HtmlGenerator::endInlineHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3364</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3365</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h3&gt;&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3366</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endInlineMemberDoc() {#adcdb6177d9281921c6d2aa6893b1b5c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endInlineMemberDoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 323 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3413 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adcdb6177d9281921c6d2aa6893b1b5c9">3413</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adcdb6177d9281921c6d2aa6893b1b5c9">HtmlGenerator::endInlineMemberDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3414</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3415</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endInlineMemberDoc --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3417</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endInlineMemberName() {#aed5d2db9d4bdda1b0ae0c6824bfbe415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endInlineMemberName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 321 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3401 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed5d2db9d4bdda1b0ae0c6824bfbe415">3401</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aed5d2db9d4bdda1b0ae0c6824bfbe415">HtmlGenerator::endInlineMemberName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3402</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3403</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endInlineMemberName --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3404</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3405</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endInlineMemberType() {#a7de90155aebd5eacbbca903687f8e5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endInlineMemberType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 319 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3389 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7de90155aebd5eacbbca903687f8e5f5">3389</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7de90155aebd5eacbbca903687f8e5f5">HtmlGenerator::endInlineMemberType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3390</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3391</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endInlineMemberType --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3392</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3393</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endItemList() {#afc7f3aba96e41a1525db5bd833d48067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endItemList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc7f3aba96e41a1525db5bd833d48067">154</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc7f3aba96e41a1525db5bd833d48067">endItemList</a>()</span><span class="doxyHighlightKeyword"> override    </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/ul&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endItemListItem() {#a6432012a68a21dc44897857bb774f76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endItemListItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6432012a68a21dc44897857bb774f76f">169</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6432012a68a21dc44897857bb774f76f">endItemListItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endLabels() {#aa11aa8c21a8b7eb4af49fc708e43e909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endLabels ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 327 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3465 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa11aa8c21a8b7eb4af49fc708e43e909">3465</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa11aa8c21a8b7eb4af49fc708e43e909">HtmlGenerator::endLabels</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3466</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3467</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endLabels --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3468</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3469</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endLocalToc() {#aafb64fea3c5e96e1c48b5caba59681fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endLocalToc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 330 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3565 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aafb64fea3c5e96e1c48b5caba59681fb">3565</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aafb64fea3c5e96e1c48b5caba59681fb">HtmlGenerator::endLocalToc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3566</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3567</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level &gt; <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel) <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level = <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3568</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3569</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3570</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.decIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3571</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.decIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;/ul&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3572</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3573</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3574</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3575</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#a3742f232f4e229f51178530f132dfc3a">m&#95;tocState</a>.
</div>
</div>

### endMemberDeclaration() {#aa21d10473a4e983501ec2e97e738a682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDeclaration (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 206 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3540 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa21d10473a4e983501ec2e97e738a682">3540</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa21d10473a4e983501ec2e97e738a682">HtmlGenerator::endMemberDeclaration</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3541</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3542</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endMemberDescription() {#a6ca9bf50e7dc80e39b2e9264b3c916ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDescription ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 204 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2119 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ca9bf50e7dc80e39b2e9264b3c916ad">2119</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6ca9bf50e7dc80e39b2e9264b3c916ad">HtmlGenerator::endMemberDescription</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberDescription --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;br /&gt;&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberDoc() {#ae84d2a7b716a16fa142c0fdb0f8c338c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDoc (bool hasArgs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 225 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2385 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae84d2a7b716a16fa142c0fdb0f8c338c">2385</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae84d2a7b716a16fa142c0fdb0f8c338c">HtmlGenerator::endMemberDoc</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasArgs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2387</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberDoc --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2388</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!hasArgs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2389</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2390</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2391</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2392</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2393</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// m_t &lt;&lt; "&lt;/div&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberDocList() {#a9300885ee109900582e9a2c8dc298c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDocList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 180 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2225 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9300885ee109900582e9a2c8dc298c21">2225</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9300885ee109900582e9a2c8dc298c21">HtmlGenerator::endMemberDocList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberDocList --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberDocName() {#a7ad614730d5b184f8d98b4d3ca6e6dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDocName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 294 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2269 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ad614730d5b184f8d98b4d3ca6e6dcd">2269</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7ad614730d5b184f8d98b4d3ca6e6dcd">HtmlGenerator::endMemberDocName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberDocName --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberDocPrefixItem() {#ac007b8ceaed1b6260def8b681ec1e1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDocPrefixItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 292 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2253 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac007b8ceaed1b6260def8b681ec1e1da">2253</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac007b8ceaed1b6260def8b681ec1e1da">HtmlGenerator::endMemberDocPrefixItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberDocPrefixItem --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberDocSimple() {#aedce042225aecc4a3d499d675251bd6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberDocSimple (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 317 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3377 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aedce042225aecc4a3d499d675251bd6b">3377</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aedce042225aecc4a3d499d675251bd6b">HtmlGenerator::endMemberDocSimple</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3378</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3379</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberDocSimple --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3380</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3381</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberGroup() {#a64cca65695d73978bf4ce3c0aa7051d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberGroup (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 199 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2531 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64cca65695d73978bf4ce3c0aa7051d7">2531</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64cca65695d73978bf4ce3c0aa7051d7">HtmlGenerator::endMemberGroup</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2532</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2533</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endMemberGroupDocs() {#a8a842c61286aea39f627c46ae95210a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberGroupDocs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 197 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2522 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a842c61286aea39f627c46ae95210a9">2522</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8a842c61286aea39f627c46ae95210a9">HtmlGenerator::endMemberGroupDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2524</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2525</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberGroupHeader() {#a18e033353bdec24873c922894b8a36d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberGroupHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 195 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2512 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18e033353bdec24873c922894b8a36d4">2512</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a18e033353bdec24873c922894b8a36d4">HtmlGenerator::endMemberGroupHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberHeader() {#a8d2b7702acdf9b41c6b78cee0177820b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 176 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2167 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d2b7702acdf9b41c6b78cee0177820b">2167</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8d2b7702acdf9b41c6b78cee0177820b">HtmlGenerator::endMemberHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberHeader --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h2&gt;&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberItem() {#ae6ff44b008a49f08afd2347655b3831a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberItem (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 188 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2048 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6ff44b008a49f08afd2347655b3831a">2048</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae6ff44b008a49f08afd2347655b3831a">HtmlGenerator::endMemberItem</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>==<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">MemberItemType::AnonymousStart</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9c6116e3f64dcba6a1b4152afdf91fa1">insertMemberAlign</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">OutputGenerator::AnonymousStart</a>, <a href="#a9c6116e3f64dcba6a1b4152afdf91fa1">insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.
</div>
</div>

### endMemberList() {#a3839bea77bec5697144e8fc0d6ebea15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 182 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2017 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3839bea77bec5697144e8fc0d6ebea15">2017</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3839bea77bec5697144e8fc0d6ebea15">HtmlGenerator::endMemberList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberList --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberSections() {#a9261c777bbdaa1882cbd9186c6b08fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberSections ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 172 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2133 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9261c777bbdaa1882cbd9186c6b08fb6">2133</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9261c777bbdaa1882cbd9186c6b08fb6">HtmlGenerator::endMemberSections</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberSections --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberSubtitle() {#ae0f7f3498ff3870052db84b11e20eec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberSubtitle ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 178 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2184 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0f7f3498ff3870052db84b11e20eec4">2184</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae0f7f3498ff3870052db84b11e20eec4">HtmlGenerator::endMemberSubtitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endMemberSubtitle --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endMemberTemplateParams() {#abb252c9c1a9af617ee975f211f3da598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endMemberTemplateParams (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 190 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2061 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb252c9c1a9af617ee975f211f3da598">2061</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abb252c9c1a9af617ee975f211f3da598">HtmlGenerator::endMemberTemplateParams</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"memitem:"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inheritId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" inherit "</span><span class="doxyHighlight"> &lt;&lt; inheritId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" template\"&gt;&lt;td class=\"memItemLeft\" align=\"right\" valign=\"top\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endPageDoc() {#a53a7c461a41d487efe3c90a5ed69caf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endPageDoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 261 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3058 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53a7c461a41d487efe3c90a5ed69caf4">3058</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a53a7c461a41d487efe3c90a5ed69caf4">HtmlGenerator::endPageDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3059</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3060</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- PageDoc --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3061</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endPageRef() {#acc3ba521b2573cc57e3e0685124e00ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endPageRef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc3ba521b2573cc57e3e0685124e00ed">249</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acc3ba521b2573cc57e3e0685124e00ed">endPageRef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### endParagraph() {#a9b830c30201e8b2ba3a2103acceff7cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endParagraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 143 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1670 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b830c30201e8b2ba3a2103acceff7cd">1670</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9b830c30201e8b2ba3a2103acceff7cd">HtmlGenerator::endParagraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/p&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endParameterDefVal() {#a64513a369c8c8c75dcac36ba1e9341f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endParameterDefVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 302 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2354 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64513a369c8c8c75dcac36ba1e9341f1">2354</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64513a369c8c8c75dcac36ba1e9341f1">HtmlGenerator::endParameterDefVal</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endParameterExtra() {#a0ad8dcc25a41bc905e649e12b0302a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endParameterExtra (bool last, bool emptyList, bool closeBracket)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 300 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2323 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ad8dcc25a41bc905e649e12b0302a3d">2323</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0ad8dcc25a41bc905e649e12b0302a3d">HtmlGenerator::endParameterExtra</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> last,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> emptyList, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endParameterExtra --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (last)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (emptyList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (closeBracket) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;td&gt;)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (closeBracket) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endParameterList() {#a4a76953ad9eafdccdad1bc536fd9a097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endParameterList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 304 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2359 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a76953ad9eafdccdad1bc536fd9a097">2359</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a76953ad9eafdccdad1bc536fd9a097">HtmlGenerator::endParameterList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endParameterList --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endParameterName() {#a535f67c3665549f6f93202fd19ec46da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endParameterName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 298 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2312 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a535f67c3665549f6f93202fd19ec46da">2312</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a535f67c3665549f6f93202fd19ec46da">HtmlGenerator::endParameterName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endParameterName --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/em&gt;&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endParameterType() {#a3462109af2644ffeb87b40975d7fb7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endParameterType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 296 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2300 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3462109af2644ffeb87b40975d7fb7bd">2300</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3462109af2644ffeb87b40975d7fb7bd">HtmlGenerator::endParameterType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- endParameterType --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endPlainFile() {#abb4a012326a0991e0f7cf339b21eafa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endPlainFile ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 335 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb4a012326a0991e0f7cf339b21eafa5">335</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaacf2b4efc09a2c06b9dd8cc2af69046">OutputGenerator::endPlainFile</a>(); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaacf2b4efc09a2c06b9dd8cc2af69046">OutputGenerator::endPlainFile</a>.

Referenced by <a href="#a05d89564f75789d7f452bd01b6bfa14b">endFile</a> and <a href="#a86eb94b45459e81c896e184152dd7176">writeStyleInfo</a>.
</div>
</div>

### endProjectNumber() {#abc4d79122d4f9001e93365e5274dc5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endProjectNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1571 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc4d79122d4f9001e93365e5274dc5cc">1571</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abc4d79122d4f9001e93365e5274dc5cc">HtmlGenerator::endProjectNumber</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h3&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endQuickIndices() {#a5d6c0960d638ac86281ecefc1213d8d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endQuickIndices ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 251 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2988 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d6c0960d638ac86281ecefc1213d8d1">2988</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5d6c0960d638ac86281ecefc1213d8d1">HtmlGenerator::endQuickIndices</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2989</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2990</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2991</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- top --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2992</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2993</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2994</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"doc-content\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2995</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2996</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endSection() {#aec484816eb09040f49038c4b0a999f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 241 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1839 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec484816eb09040f49038c4b0a999f23">1839</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aec484816eb09040f49038c4b0a999f23">HtmlGenerator::endSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,<a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.level())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a840604fef79fdbb4e2d3e44f6fb25be1">SectionType::Page</a>:             <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h1&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a16a0139dc8140f1c1626f46db559dac6">SectionType::Section</a>:          <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h2&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a53adf06c99d78c4fcf4a8e4a1366c401">SectionType::Subsection</a>:       <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h3&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a5f6dc2a0df2c922d077db4211dcec9d1">SectionType::Subsubsection</a>:    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h4&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#ae77523c9ecd298b11cdcdc8fae693a33">SectionType::Paragraph</a>:        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h5&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#afe5ca7520c54e7d647adb55a910b53cd">SectionType::Subparagraph</a>:     <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h6&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#afc5a4c3df18d1ff4855525a78069b63b">SectionType::Subsubparagraph</a>:  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h6&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a840604fef79fdbb4e2d3e44f6fb25be1">SectionType::Page</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#ae77523c9ecd298b11cdcdc8fae693a33">SectionType::Paragraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a16a0139dc8140f1c1626f46db559dac6">SectionType::Section</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#afe5ca7520c54e7d647adb55a910b53cd">SectionType::Subparagraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a53adf06c99d78c4fcf4a8e4a1366c401">SectionType::Subsection</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#afc5a4c3df18d1ff4855525a78069b63b">SectionType::Subsubparagraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a5f6dc2a0df2c922d077db4211dcec9d1">SectionType::Subsubsection</a> and <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.
</div>
</div>

### endSmall() {#a60dde525b35f9f620a51070aab5e87f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endSmall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60dde525b35f9f620a51070aab5e87f4">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a60dde525b35f9f620a51070aab5e87f4">endSmall</a>()</span><span class="doxyHighlightKeyword"> override           </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/small&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endTextBlock() {#ad907561a88520aac4253dd94cccfb73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endTextBlock (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 288 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad907561a88520aac4253dd94cccfb73f">288</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad907561a88520aac4253dd94cccfb73f">endTextBlock</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endTextLink() {#a8eb9a151291ddcd9b1e6eee2b228b754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endTextLink ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 163 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1781 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8eb9a151291ddcd9b1e6eee2b228b754">1781</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8eb9a151291ddcd9b1e6eee2b228b754">HtmlGenerator::endTextLink</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endTitleHead() {#aebe66b78ec5e7be56c1d8e4d5c6f2b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 140 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3342 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebe66b78ec5e7be56c1d8e4d5c6f2b2e">3342</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aebe66b78ec5e7be56c1d8e4d5c6f2b2e">HtmlGenerator::endTitleHead</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3343</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3344</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae1337adbb5ad6cea03fcee0d5a7cdfce">endTitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3345</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3346</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ae1337adbb5ad6cea03fcee0d5a7cdfce">endTitle</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### endTocEntry() {#ae5a12bcaed78c969eac8b73cb19d798f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 332 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3621 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5a12bcaed78c969eac8b73cb19d798f">3621</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae5a12bcaed78c969eac8b73cb19d798f">HtmlGenerator::endTocEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3622</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3623</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a> = si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">type</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nextLevel = <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.level();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.isSection() &amp;&amp; nextLevel&lt;=<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3626</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3627</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3628</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.inLi[nextLevel]=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3629</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level = nextLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3630</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3631</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="#a3742f232f4e229f51178530f132dfc3a">m&#95;tocState</a>, <a href="#a8164db5b0eaa9499cf02083114cff358">type</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">SectionInfo::type</a>.
</div>
</div>

### endTypewriter() {#af6ea951201d8b37278044a38c4be9949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endTypewriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6ea951201d8b37278044a38c4be9949">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af6ea951201d8b37278044a38c4be9949">endTypewriter</a>()</span><span class="doxyHighlightKeyword"> override   </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/code&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### exceptionEntry() {#a726c53bd6e118a6ab62e6022c7dd80e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::exceptionEntry (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix, bool closeBracket)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 305 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2366 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a726c53bd6e118a6ab62e6022c7dd80e6">2366</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a726c53bd6e118a6ab62e6022c7dd80e6">HtmlGenerator::exceptionEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- exceptionEntry --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td align=\"right\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// colspan 2 so it gets both parameter type and parameter name columns</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;td&gt;(&lt;/td&gt;&lt;td colspan=\"2\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;)&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;td colspan=\"2\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.
</div>
</div>

### insertMemberAlign() {#a9c6116e3f64dcba6a1b4152afdf91fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::insertMemberAlign (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 201 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2082 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c6116e3f64dcba6a1b4152afdf91fa1">2082</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9c6116e3f64dcba6a1b4152afdf91fa1">HtmlGenerator::insertMemberAlign</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- insertMemberAlign --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;&lt;/td&gt;&lt;td class=\"memItemRight\" valign=\"bottom\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.

Referenced by <a href="#ae6ff44b008a49f08afd2347655b3831a">endMemberItem</a>.
</div>
</div>

### insertMemberAlignLeft() {#a2260389b86a386811fc344bb6ec9273d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::insertMemberAlignLeft (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> type, bool initTag)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 202 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2088 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2260389b86a386811fc344bb6ec9273d">2088</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2260389b86a386811fc344bb6ec9273d">HtmlGenerator::insertMemberAlignLeft</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> initTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!initTag) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">MemberItemType::Normal</a>:         <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"memItemLeft\" align=\"right\" valign=\"top\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">MemberItemType::AnonymousStart</a>: <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"memItemLeft anon\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba8475427fd01aab02bf1bb0f3d280af17">MemberItemType::AnonymousEnd</a>:   <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"memItemLeft anonEnd\" valign=\"top\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbaf756dbefd44dd9270c676f74fb8d3708">MemberItemType::Templated</a>:      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"memTemplParams\" colspan=\"2\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba8475427fd01aab02bf1bb0f3d280af17">OutputGenerator::AnonymousEnd</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">OutputGenerator::AnonymousStart</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::Normal</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcbaf756dbefd44dd9270c676f74fb8d3708">OutputGenerator::Templated</a> and <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.

Referenced by <a href="#a1ec800447787c1eada0c828c6d3bb374">startMemberItem</a>.
</div>
</div>

### lastIndexPage() {#ab871f28ae2928638adde578fe1514aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::lastIndexPage ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 289 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab871f28ae2928638adde578fe1514aca">289</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab871f28ae2928638adde578fe1514aca">lastIndexPage</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### lineBreak() {#a1afec505ae6d03e654d11f3b6010a36d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::lineBreak (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 220 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3319 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1afec505ae6d03e654d11f3b6010a36d">3319</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1afec505ae6d03e654d11f3b6010a36d">HtmlGenerator::lineBreak</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3320</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!style.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3322</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3323</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;br class=\""</span><span class="doxyHighlight"> &lt;&lt; style &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" /&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3324</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3326</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3327</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;br /&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3328</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3329</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startAnonTypeScope() {#ad6c325207af03cb2116d59d5b1b7a84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startAnonTypeScope (int)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6c325207af03cb2116d59d5b1b7a84c">185</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6c325207af03cb2116d59d5b1b7a84c">startAnonTypeScope</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startBold() {#a41ad780056d93e93a6d630b5f0f025df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startBold ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 216 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41ad780056d93e93a6d630b5f0f025df">216</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41ad780056d93e93a6d630b5f0f025df">startBold</a>()</span><span class="doxyHighlightKeyword"> override     </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;b&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startCallGraph() {#a34d21b07f7218dcc1161ed797dc8a74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startCallGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 281 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2466 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34d21b07f7218dcc1161ed797dc8a74a">2466</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34d21b07f7218dcc1161ed797dc8a74a">HtmlGenerator::startCallGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2467</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2468</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>.
</div>
</div>

### startCenter() {#a3bd1c0fe5fa8cc53924bbd8639674840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startCenter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3bd1c0fe5fa8cc53924bbd8639674840">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3bd1c0fe5fa8cc53924bbd8639674840">startCenter</a>()</span><span class="doxyHighlightKeyword"> override        </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;center&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startClassDiagram() {#a005f1a46f9808e8a719ba756407259ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startClassDiagram ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 246 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1973 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a005f1a46f9808e8a719ba756407259ec">1973</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a005f1a46f9808e8a719ba756407259ec">HtmlGenerator::startClassDiagram</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>.
</div>
</div>

### startCompoundTemplateParams() {#a42347ea9872571c56ab5127514370b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startCompoundTemplateParams ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 191 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2072 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42347ea9872571c56ab5127514370b8e">2072</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a42347ea9872571c56ab5127514370b8e">HtmlGenerator::startCompoundTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"compoundTemplParams\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startConstraintDocs() {#ab79bdcce95772f1eb1c314a2da602097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startConstraintDocs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 312 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3301 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab79bdcce95772f1eb1c314a2da602097">3301</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab79bdcce95772f1eb1c314a2da602097">HtmlGenerator::startConstraintDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3302</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3303</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td&gt;&amp;#160;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3304</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startConstraintList() {#a6e492ea8c1e1d299d8ab6af19fd52c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startConstraintList (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 307 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3274 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e492ea8c1e1d299d8ab6af19fd52c9a">3274</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e492ea8c1e1d299d8ab6af19fd52c9a">HtmlGenerator::startConstraintList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3275</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3276</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"typeconstraint\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3277</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;dl&gt;&lt;dt&gt;&lt;b&gt;"</span><span class="doxyHighlight"> &lt;&lt; header &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt;&lt;/dt&gt;&lt;dd&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3278</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table border=\"0\" cellspacing=\"2\" cellpadding=\"0\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3279</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startConstraintParam() {#a4239a94a42b77210e64e042cfee7f726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startConstraintParam ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 308 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3281 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4239a94a42b77210e64e042cfee7f726">3281</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4239a94a42b77210e64e042cfee7f726">HtmlGenerator::startConstraintParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3282</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3283</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;td valign=\"top\"&gt;&lt;em&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3284</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startConstraintType() {#ab07067c23edb49e8b251e963a480e5c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startConstraintType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 310 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3291 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab07067c23edb49e8b251e963a480e5c5">3291</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab07067c23edb49e8b251e963a480e5c5">HtmlGenerator::startConstraintType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3292</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3293</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td&gt;&amp;#160;:&lt;/td&gt;&lt;td valign=\"top\"&gt;&lt;em&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3294</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startContents() {#a3d4a211b9f17df0484bcc2658d5abdaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startContents ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 258 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3043 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d4a211b9f17df0484bcc2658d5abdaf">3043</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3d4a211b9f17df0484bcc2658d5abdaf">HtmlGenerator::startContents</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3044</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3045</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"contents\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3046</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDescForItem() {#a062324c12b32fa04ce3ed878590769a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDescForItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a062324c12b32fa04ce3ed878590769a7">218</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a062324c12b32fa04ce3ed878590769a7">startDescForItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;dd&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDescTable() {#a6ea8da6d66244a87fe3141b1165e084c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDescTable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const bool hasInits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 264 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2560 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ea8da6d66244a87fe3141b1165e084c">2560</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6ea8da6d66244a87fe3141b1165e084c">HtmlGenerator::startDescTable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasInits)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"fieldtable\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;th colspan=\""</span><span class="doxyHighlight"> &lt;&lt; (hasInits?3:2) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; title &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/th&gt;&lt;/tr&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDescTableData() {#a9a58ad6a53095540f4abafb003fc47a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDescTableData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 272 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2600 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a58ad6a53095540f4abafb003fc47a1">2600</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a58ad6a53095540f4abafb003fc47a1">HtmlGenerator::startDescTableData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"fielddoc\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDescTableInit() {#a578dfeee8598b1dbb0910e7d42e46ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDescTableInit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 270 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2590 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a578dfeee8598b1dbb0910e7d42e46ee9">2590</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a578dfeee8598b1dbb0910e7d42e46ee9">HtmlGenerator::startDescTableInit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"fieldinit\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDescTableRow() {#a401d1ec435f24eb9c4ef50f983e37af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDescTableRow ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 266 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2570 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a401d1ec435f24eb9c4ef50f983e37af7">2570</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a401d1ec435f24eb9c4ef50f983e37af7">HtmlGenerator::startDescTableRow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2571</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDescTableTitle() {#a5e2229e11153da2bf67e59928d250783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDescTableTitle ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 268 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2580 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e2229e11153da2bf67e59928d250783">2580</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e2229e11153da2bf67e59928d250783">HtmlGenerator::startDescTableTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"fieldname\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startDirDepGraph() {#a41dc42e70634afb2a68fd1c45dd16f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDirDepGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 283 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2484 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41dc42e70634afb2a68fd1c45dd16f91">2484</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41dc42e70634afb2a68fd1c45dd16f91">HtmlGenerator::startDirDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>.
</div>
</div>

### startDotGraph() {#a4cacd7e83fff3a670a66073686c882a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDotGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 275 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2396 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cacd7e83fff3a670a66073686c882a8">2396</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4cacd7e83fff3a670a66073686c882a8">HtmlGenerator::startDotGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>.
</div>
</div>

### startDoxyAnchor() {#a41c7cd661ef071ac37a0fb4efcf31574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 226 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1647 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41c7cd661ef071ac37a0fb4efcf31574">1647</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41c7cd661ef071ac37a0fb4efcf31574">HtmlGenerator::startDoxyAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a id=\""</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" name=\""</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startEmphasis() {#a160471f9e3f531fa16ba15bcc467392f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startEmphasis ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a160471f9e3f531fa16ba15bcc467392f">214</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a160471f9e3f531fa16ba15bcc467392f">startEmphasis</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;em&gt;"</span><span class="doxyHighlight">;  }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startExamples() {#ad122021b54713f1bfb7058d4723af613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startExamples ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 238 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2610 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad122021b54713f1bfb7058d4723af613">2610</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad122021b54713f1bfb7058d4723af613">HtmlGenerator::startExamples</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;dl class=\"section examples\"&gt;&lt;dt&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExamples());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/dt&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.
</div>
</div>

### startFile() {#ab59c183ba1429ec58b88fd83ea686d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int id, int hierarchyLevel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 127 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1448 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab59c183ba1429ec58b88fd83ea686d6c">1448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*id*/</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*hierarchyLevel*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("HtmlGenerator::startFile(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>=title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>-&gt;setFileName(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a>-&gt;setRelativePath(<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ad2a13506b949e3ae461c03411a8ff36b">g_indexLock</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addIndexFile(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1464</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1465</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a> = <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a>,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>(title)),<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedBy() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" Doxygen "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> searchEngine = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (searchEngine </span><span class="doxyHighlightComment">/*&amp;&amp; !generateTreeView*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var searchBox = new SearchBox(\"searchBox\", \""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>&lt;&lt; </span><span class="doxyHighlightStringLiteral">"search/\",'"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"');\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_CODE_FOLDING))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$(function() { codefold.init(); });\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g&#95;header</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g&#95;header&#95;file</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ad2a13506b949e3ae461c03411a8ff36b">g&#95;indexLock</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="#aa32061e00ef95a2b936ab97ea46b0cad">m&#95;codeGen</a>, <a href="#a453969afc6bce23453c23dbc81bc0996">m&#95;lastFile</a>, <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m&#95;lastTitle</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>, <a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.
</div>
</div>

### startGroupCollaboration() {#a6d892ee256e9a34db8cf761569bb2c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startGroupCollaboration ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 279 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2448 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d892ee256e9a34db8cf761569bb2c9c">2448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d892ee256e9a34db8cf761569bb2c9c">HtmlGenerator::startGroupCollaboration</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>.
</div>
</div>

### startGroupHeader() {#ac590d2ce8474c9bd7c2abbc9679fb11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, int extraIndentLevel)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 166 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1786 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac590d2ce8474c9bd7c2abbc9679fb11d">1786</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac590d2ce8474c9bd7c2abbc9679fb11d">HtmlGenerator::startGroupHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraIndentLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extraIndentLevel==2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;h4"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extraIndentLevel==1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;h3"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// extraIndentLevel==0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;h2"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt;</span><span class="doxyHighlightStringLiteral">" id=\"header-"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)+</span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" class=\"groupheader\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startHeaderSection() {#a5d710dda637c39d769e433ea953bb1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startHeaderSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 173 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3331 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d710dda637c39d769e433ea953bb1b3">3331</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5d710dda637c39d769e433ea953bb1b3">HtmlGenerator::startHeaderSection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3332</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3333</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"header\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3334</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startInclDepGraph() {#a20449975cf6595d7c2cb353f1c26534f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startInclDepGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 277 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2430 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20449975cf6595d7c2cb353f1c26534f">2430</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a20449975cf6595d7c2cb353f1c26534f">HtmlGenerator::startInclDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,<a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="#a306ac96cc0bd258bec437951ca315dcd">m&#95;sectionCount</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac5f89137286ceb01d9c5a1a14a36d8e1">startSectionHeader</a>.
</div>
</div>

### startIndent() {#a848866b2ca1f5ded259c90a391a7abc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 243 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2535 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a848866b2ca1f5ded259c90a391a7abc4">2535</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a848866b2ca1f5ded259c90a391a7abc4">HtmlGenerator::startIndent</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2536</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2537</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startIndent --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"memdoc\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startIndexItem() {#a80da85d198868bc3351b1a6a90f32a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 155 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1690 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80da85d198868bc3351b1a6a90f32a75">1690</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a80da85d198868bc3351b1a6a90f32a75">HtmlGenerator::startIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("HtmlGenerator::startIndexItem(%s,%s)\n",ref,f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || !f.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\"elRef\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\"el\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>(<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,ref,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn=f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; fn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;b&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### startIndexKey() {#a1ad19095c7e9f02127aa3be21956d915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndexKey ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 149 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2200 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ad19095c7e9f02127aa3be21956d915">2200</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1ad19095c7e9f02127aa3be21956d915">HtmlGenerator::startIndexKey</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "  &lt;tr&gt;&lt;td class=\"indexkey\"&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### startIndexList() {#a642f7c83fd60f3acc6820127e0d0fa9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndexList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 147 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2190 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a642f7c83fd60f3acc6820127e0d0fa9d">2190</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a642f7c83fd60f3acc6820127e0d0fa9d">HtmlGenerator::startIndexList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startIndexListItem() {#abb7e7bf073a75a8377e6031d8b798063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndexListItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 145 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1680 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abb7e7bf073a75a8377e6031d8b798063">1680</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abb7e7bf073a75a8377e6031d8b798063">HtmlGenerator::startIndexListItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;li&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startIndexSection() {#a8cdd8741ce148e10f53fca1b9f47f866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8cdd8741ce148e10f53fca1b9f47f866">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8cdd8741ce148e10f53fca1b9f47f866">startIndexSection</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a>)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startIndexValue() {#aaac077b0913733fb9701b7759c44ffbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startIndexValue (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 151 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2210 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaac077b0913733fb9701b7759c44ffbd">2210</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaac077b0913733fb9701b7759c44ffbd">HtmlGenerator::startIndexValue</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;td class=\"indexvalue\"&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### startInlineHeader() {#aed122d098bf970698797293cabd09b21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startInlineHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 183 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3353 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed122d098bf970698797293cabd09b21">3353</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aed122d098bf970698797293cabd09b21">HtmlGenerator::startInlineHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3354</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3356</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3357</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"memberdecls\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3358</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3359</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3360</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;td colspan=\"2\"&gt;&lt;h3&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3361</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startInlineMemberDoc() {#a719fede306ded713d46b9551eec66cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startInlineMemberDoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 322 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3407 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a719fede306ded713d46b9551eec66cf7">3407</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a719fede306ded713d46b9551eec66cf7">HtmlGenerator::startInlineMemberDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3408</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3409</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startInlineMemberDoc --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3410</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"fielddoc\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3411</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startInlineMemberName() {#a0d47d7645dc5b280ff77706469a7dd87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startInlineMemberName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 320 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3395 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d47d7645dc5b280ff77706469a7dd87">3395</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0d47d7645dc5b280ff77706469a7dd87">HtmlGenerator::startInlineMemberName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3396</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3397</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startInlineMemberName --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3398</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"fieldname\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3399</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startInlineMemberType() {#a12aa643326c720f1a8f80610c1bc82fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startInlineMemberType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 318 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3383 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12aa643326c720f1a8f80610c1bc82fc">3383</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a12aa643326c720f1a8f80610c1bc82fc">HtmlGenerator::startInlineMemberType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3384</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3385</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startInlineMemberType --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3386</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;td class=\"fieldtype\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3387</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startItemList() {#afc6ed316d237d1da4b7c3b8d4f822d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startItemList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc6ed316d237d1da4b7c3b8d4f822d68">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc6ed316d237d1da4b7c3b8d4f822d68">startItemList</a>()</span><span class="doxyHighlightKeyword"> override  </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;ul&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startItemListItem() {#a2e0cac82069348e3bea2d7912feb3d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startItemListItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e0cac82069348e3bea2d7912feb3d87">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2e0cac82069348e3bea2d7912feb3d87">startItemListItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;li&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startLabels() {#a34bd3e5c72c259091f2546327ac84868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startLabels ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 325 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3419 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34bd3e5c72c259091f2546327ac84868">3419</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34bd3e5c72c259091f2546327ac84868">HtmlGenerator::startLabels</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3420</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3421</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startLabels --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3422</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"mlabels\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3423</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startLocalToc() {#a5af845a03a3c0c16a3855d88034dfa70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startLocalToc (int level)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 329 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3555 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5af845a03a3c0c16a3855d88034dfa70">3555</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5af845a03a3c0c16a3855d88034dfa70">HtmlGenerator::startLocalToc</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3556</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3557</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3558</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.indent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3559</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel=level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3560</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.inLi = <a href="/web-doxygen/docs/api/files/src/containers-h/#af473e8b17774fe44ba6746b9e7bff90a">BoolVector</a>(level+1,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3561</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"toc\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3562</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;h3&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRTFTableOfContents() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h3&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3563</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="#a3742f232f4e229f51178530f132dfc3a">m&#95;tocState</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.
</div>
</div>

### startMemberDeclaration() {#a292546e2f380d75990bfec88cc579a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDeclaration ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a292546e2f380d75990bfec88cc579a06">205</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a292546e2f380d75990bfec88cc579a06">startMemberDeclaration</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startMemberDescription() {#a477b9bf180d9c7a57edcd11c408cdb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDescription (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId, bool typ)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 203 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2100 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a477b9bf180d9c7a57edcd11c408cdb5b">2100</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a477b9bf180d9c7a57edcd11c408cdb5b">HtmlGenerator::startMemberDescription</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> typ)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberDescription --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"memberdecls\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"memdesc:"</span><span class="doxyHighlight"> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inheritId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" inherit "</span><span class="doxyHighlight"> &lt;&lt; inheritId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"mdescLeft\"&gt;&amp;#160;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typ) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"mdescLeft\"&gt;&amp;#160;&lt;/td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td class=\"mdescRight\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberDoc() {#a3e27be79946300ecc5d82289192fb691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; clName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int memCount, int memTotal, bool showInline)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 222 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2230 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e27be79946300ecc5d82289192fb691">2230</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3e27be79946300ecc5d82289192fb691">HtmlGenerator::startMemberDoc</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* clName */</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* memName */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memCount, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memTotal, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* showInline */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberDoc --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n&lt;h2 class=\"memtitle\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"permalink\"&gt;&lt;a href=\"#"</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&amp;#9670;&amp;#160;&lt;/a&gt;&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memTotal&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &lt;span class=\"overload\"&gt;["</span><span class="doxyHighlight"> &lt;&lt; memCount &lt;&lt; </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> &lt;&lt; memTotal &lt;&lt;</span><span class="doxyHighlightStringLiteral">"]&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/h2&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n&lt;div class=\"memitem\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"memproto\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberDocList() {#a53aef5bc2dc01700784de5269730cb46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDocList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 179 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2220 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53aef5bc2dc01700784de5269730cb46">2220</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a53aef5bc2dc01700784de5269730cb46">HtmlGenerator::startMemberDocList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberDocList --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberDocName() {#a30b47346a71e1216fb4083c64675bf4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDocName (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 293 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2259 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a30b47346a71e1216fb4083c64675bf4e">2259</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a30b47346a71e1216fb4083c64675bf4e">HtmlGenerator::startMemberDocName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*align*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberDocName --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;table class=\"memname\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td class=\"memname\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberDocPrefixItem() {#ae2f67237c29b8499dae33d2462cef68a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDocPrefixItem ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 291 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2247 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2f67237c29b8499dae33d2462cef68a">2247</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae2f67237c29b8499dae33d2462cef68a">HtmlGenerator::startMemberDocPrefixItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberDocPrefixItem --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"memtemplate\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberDocSimple() {#a7f5dae7d567cd940f9dab8408272e8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberDocSimple (bool isEnum)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 316 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3368 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7f5dae7d567cd940f9dab8408272e8cd">3368</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7f5dae7d567cd940f9dab8408272e8cd">HtmlGenerator::startMemberDocSimple</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3369</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3370</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberDocSimple --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3371</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"fieldtable\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;th colspan=\""</span><span class="doxyHighlight"> &lt;&lt; (isEnum?</span><span class="doxyHighlightStringLiteral">"2"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"3"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3373</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; (isEnum? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trEnumerationValues() :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3374</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundMembers()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/th&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3375</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.
</div>
</div>

### startMemberGroup() {#ae8271b410ef99182f6229857ab18f56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberGroup ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 198 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2527 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8271b410ef99182f6229857ab18f56f">2527</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae8271b410ef99182f6229857ab18f56f">HtmlGenerator::startMemberGroup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2528</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### startMemberGroupDocs() {#a7e40997271cb08e164b46ad72459d12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberGroupDocs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 196 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2517 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e40997271cb08e164b46ad72459d12c">2517</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7e40997271cb08e164b46ad72459d12c">HtmlGenerator::startMemberGroupDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2518</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2519</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;td colspan=\"2\" class=\"ititle\"&gt;&lt;div class=\"groupText\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberGroupHeader() {#a4ac80db5c4ebf34e1aefa117b542507a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 194 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2507 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ac80db5c4ebf34e1aefa117b542507a">2507</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ac80db5c4ebf34e1aefa117b542507a">HtmlGenerator::startMemberGroupHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr id=\""</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" class=\"groupHeader\"&gt;&lt;td colspan=\"2\"&gt;&lt;div class=\"groupHeader\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberHeader() {#aea90b1337254e9c10ceaefcff8b9c825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int typ)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 175 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2142 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea90b1337254e9c10ceaefcff8b9c825">2142</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aea90b1337254e9c10ceaefcff8b9c825">HtmlGenerator::startMemberHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> typ)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberHeader --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"memberdecls\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"heading\"&gt;&lt;td colspan=\""</span><span class="doxyHighlight"> &lt;&lt; typ &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;h2"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" id=\"header-"</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" class=\"groupheader\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a id=\""</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" name=\""</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;/a&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### startMemberItem() {#a1ec800447787c1eada0c828c6d3bb374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 187 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2026 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ec800447787c1eada0c828c6d3bb374">2026</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1ec800447787c1eada0c828c6d3bb374">HtmlGenerator::startMemberItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberItem() --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"memberdecls\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"memitem:"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inheritId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" inherit "</span><span class="doxyHighlight"> &lt;&lt; inheritId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" id=\"r_"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>(anchor) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2260389b86a386811fc344bb6ec9273d">insertMemberAlignLeft</a>(<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a2260389b86a386811fc344bb6ec9273d">insertMemberAlignLeft</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.
</div>
</div>

### startMemberList() {#a5b26359bf24a0cac681e048110451dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 181 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2012 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b26359bf24a0cac681e048110451dda">2012</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b26359bf24a0cac681e048110451dda">HtmlGenerator::startMemberList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberList --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberSections() {#a90e8e67b9d4140660537473a3c98c3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberSections ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 171 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2125 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90e8e67b9d4140660537473a3c98c3d4">2125</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a90e8e67b9d4140660537473a3c98c3d4">HtmlGenerator::startMemberSections</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberSections --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// we postpone writing &lt;table&gt; until we actually</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">// write a row to prevent empty tables, which</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">// are not valid XHTML!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### startMemberSubtitle() {#a287320869b27536a66d09bd7f545507a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberSubtitle ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 177 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2173 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a287320869b27536a66d09bd7f545507a">2173</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a287320869b27536a66d09bd7f545507a">HtmlGenerator::startMemberSubtitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startMemberSubtitle --&gt;\n"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table class=\"memberdecls\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;td class=\"ititle\" colspan=\"2\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m&#95;emptySection</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startMemberTemplateParams() {#a9f7ada93721d02805a695d80cb4ca0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startMemberTemplateParams ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 189 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2057 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f7ada93721d02805a695d80cb4ca0fe">2057</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9f7ada93721d02805a695d80cb4ca0fe">HtmlGenerator::startMemberTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### startPageDoc() {#aa1e345b8b54d35f3900d6b5a53aad546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startPageDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; pageTitle)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 260 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3053 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1e345b8b54d35f3900d6b5a53aad546">3053</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa1e345b8b54d35f3900d6b5a53aad546">HtmlGenerator::startPageDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* pageTitle */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3054</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3055</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3056</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startPageRef() {#abcccf18ee3dacb0315c80dd8010a2fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startPageRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcccf18ee3dacb0315c80dd8010a2fa1">248</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abcccf18ee3dacb0315c80dd8010a2fa1">startPageRef</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startParagraph() {#a3877e4dc1ec9c0f9e0c0c8ae8c9ec6a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startParagraph (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; classDef)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 142 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1662 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3877e4dc1ec9c0f9e0c0c8ae8c9ec6a9">1662</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3877e4dc1ec9c0f9e0c0c8ae8c9ec6a9">HtmlGenerator::startParagraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;classDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!classDef.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n&lt;p class=\""</span><span class="doxyHighlight"> &lt;&lt; classDef &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n&lt;p&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startParameterDefVal() {#a18891cddc72601d23dc617fd045911d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startParameterDefVal (const char * sep)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 301 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2347 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18891cddc72601d23dc617fd045911d8">2347</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a18891cddc72601d23dc617fd045911d8">HtmlGenerator::startParameterDefVal</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"paramdefsep\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;&lt;span class=\"paramdefval\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startParameterExtra() {#ac8133798f73d8a88098f57559170a0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startParameterExtra ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 299 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2318 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8133798f73d8a88098f57559170a0f0">2318</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac8133798f73d8a88098f57559170a0f0">HtmlGenerator::startParameterExtra</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startParameterExtra --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startParameterList() {#af453192b313a5d9bcc31360b15c7feaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startParameterList (bool openBracket)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 303 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2275 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af453192b313a5d9bcc31360b15c7feaa">2275</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af453192b313a5d9bcc31360b15c7feaa">HtmlGenerator::startParameterList</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> openBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startParameterList --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (openBracket) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startParameterName() {#a1cc2066cc3b3716a98dfb95d756fa838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startParameterName (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 297 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2306 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cc2066cc3b3716a98dfb95d756fa838">2306</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1cc2066cc3b3716a98dfb95d756fa838">HtmlGenerator::startParameterName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*oneArgOnly*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startParameterName --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td class=\"paramname\"&gt;&lt;span class=\"paramname\"&gt;&lt;em&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startParameterType() {#a566f2060c7d674363ec9f009e47430ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startParameterType (bool first, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 295 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2283 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a566f2060c7d674363ec9f009e47430ac">2283</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a566f2060c7d674363ec9f009e47430ac">HtmlGenerator::startParameterType</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startFirstParameterType --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td class=\"paramtype\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- startParameterType --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td class=\"paramkey\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; key &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td&gt;&lt;/td&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"          &lt;td class=\"paramtype\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startPlainFile() {#afcbb993451628a18541fe8323e2dbf13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startPlainFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 334 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcbb993451628a18541fe8323e2dbf13">334</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6d2b81663565fee4440ef02fe9b3a197">OutputGenerator::startPlainFile</a>(name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6d2b81663565fee4440ef02fe9b3a197">OutputGenerator::startPlainFile</a>.

Referenced by <a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a> and <a href="#a86eb94b45459e81c896e184152dd7176">writeStyleInfo</a>.
</div>
</div>

### startProjectNumber() {#acce5f3aec5a887f33e47443fbc071d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startProjectNumber ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1566 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acce5f3aec5a887f33e47443fbc071d64">1566</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acce5f3aec5a887f33e47443fbc071d64">HtmlGenerator::startProjectNumber</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;h3 class=\"version\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startQuickIndices() {#a5788d7e519223edb196aa42008c475d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startQuickIndices ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 250 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5788d7e519223edb196aa42008c475d9">250</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5788d7e519223edb196aa42008c475d9">startQuickIndices</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startSection() {#ae3bbc191d41c6566b7bafe7a063dd1ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 240 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1823 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3bbc191d41c6566b7bafe7a063dd1ac">1823</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3bbc191d41c6566b7bafe7a063dd1ac">HtmlGenerator::startSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lab,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,<a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.level())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a840604fef79fdbb4e2d3e44f6fb25be1">SectionType::Page</a>:             <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h1 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a16a0139dc8140f1c1626f46db559dac6">SectionType::Section</a>:          <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h2 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a53adf06c99d78c4fcf4a8e4a1366c401">SectionType::Subsection</a>:       <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h3 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#a5f6dc2a0df2c922d077db4211dcec9d1">SectionType::Subsubsection</a>:    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h4 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#ae77523c9ecd298b11cdcdc8fae693a33">SectionType::Paragraph</a>:        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h5 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#afe5ca7520c54e7d647adb55a910b53cd">SectionType::Subparagraph</a>:     <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h6 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectiontype/#afc5a4c3df18d1ff4855525a78069b63b">SectionType::Subsubparagraph</a>:  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n&lt;h6 class=\"doxsection\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">: <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(0); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a id=\""</span><span class="doxyHighlight"> &lt;&lt; lab &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" name=\""</span><span class="doxyHighlight"> &lt;&lt; lab &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a840604fef79fdbb4e2d3e44f6fb25be1">SectionType::Page</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#ae77523c9ecd298b11cdcdc8fae693a33">SectionType::Paragraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a16a0139dc8140f1c1626f46db559dac6">SectionType::Section</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#afe5ca7520c54e7d647adb55a910b53cd">SectionType::Subparagraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a53adf06c99d78c4fcf4a8e4a1366c401">SectionType::Subsection</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#afc5a4c3df18d1ff4855525a78069b63b">SectionType::Subsubparagraph</a>, <a href="/web-doxygen/docs/api/classes/sectiontype/#a5f6dc2a0df2c922d077db4211dcec9d1">SectionType::Subsubsection</a> and <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.
</div>
</div>

### startSmall() {#af8fff599224cb05f307e07f60fd06c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startSmall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8fff599224cb05f307e07f60fd06c1d">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af8fff599224cb05f307e07f60fd06c1d">startSmall</a>()</span><span class="doxyHighlightKeyword"> override         </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;small&gt;\n"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startTextBlock() {#ada8a36f69c16ce253b2fb173f7f36674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startTextBlock (bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada8a36f69c16ce253b2fb173f7f36674">287</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ada8a36f69c16ce253b2fb173f7f36674">startTextBlock</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"textblock\"&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startTextLink() {#a1099f1315ce5240b9165563e30471124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startTextLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 162 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1769 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1099f1315ce5240b9165563e30471124">1769</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1099f1315ce5240b9165563e30471124">HtmlGenerator::startTextLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>(<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>() == <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+fn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">                       fn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">                       anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### startTitleHead() {#ab529153ad002aa294643ef13adbf351a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 139 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3336 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab529153ad002aa294643ef13adbf351a">3336</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab529153ad002aa294643ef13adbf351a">HtmlGenerator::startTitleHead</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3337</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3338</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;div class=\"headertitle\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3339</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0fd5a2e848ea16b025b1fb07b4b307fc">startTitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3340</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#a0fd5a2e848ea16b025b1fb07b4b307fc">startTitle</a>.
</div>
</div>

### startTocEntry() {#a0c8a6327e1ce58e1d01bc05a1770e94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 331 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3577 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c8a6327e1ce58e1d01bc05a1770e94b">3577</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c8a6327e1ce58e1d01bc05a1770e94b">HtmlGenerator::startTocEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3578</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3579</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a> = si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">type</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3580</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.isSection())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3581</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  level=%d title=%s maxLevel=%d\n",level,qPrint(si-&gt;title()),maxLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3583</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nextLevel = <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>.level();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3584</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nextLevel&gt;<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3585</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3586</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level;l&lt;nextLevel;l++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3587</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3588</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt; <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3589</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3590</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.incIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;ul&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3591</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2] = { </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">+l+1), 0 };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3592</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *empty = (l!=nextLevel-1) ? </span><span class="doxyHighlightStringLiteral">" empty"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3593</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.incIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;li class=\"level"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(cs) + empty + </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3594</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3595</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3596</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3597</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nextLevel&lt;<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3598</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3599</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level;l&gt;nextLevel;l--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3600</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3601</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt;= <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel) <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.decIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3602</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.inLi[l] = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3603</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt;= <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel) <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.decIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;/ul&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3604</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3605</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3606</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nextLevel &lt;= <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.maxLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3607</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3608</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.inLi[nextLevel] || <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.level&gt;nextLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3609</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3610</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.decIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;/li&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3611</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2] = { </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight">+nextLevel), 0 };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3612</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.incIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,</span><span class="doxyHighlightStringLiteral">"&lt;li class=\"level"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(cs) + </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3613</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3614</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> label = si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">label</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3615</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>.writeIndent(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3616</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>  &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\"#"</span><span class="doxyHighlight">+label+</span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3617</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3618</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3619</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">SectionInfo::label</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="#a3742f232f4e229f51178530f132dfc3a">m&#95;tocState</a>, <a href="#a8164db5b0eaa9499cf02083114cff358">type</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">SectionInfo::type</a>.
</div>
</div>

### startTypewriter() {#a455cc2ac7c3f27ea0348c24c2f8a0f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startTypewriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a455cc2ac7c3f27ea0348c24c2f8a0f62">164</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a455cc2ac7c3f27ea0348c24c2f8a0f62">startTypewriter</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;code&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### type() {#a8164db5b0eaa9499cf02083114cff358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType HtmlGenerator::type ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8164db5b0eaa9499cf02083114cff358">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#a8164db5b0eaa9499cf02083114cff358">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">Html</a>.

Referenced by <a href="#ae6ff44b008a49f08afd2347655b3831a">endMemberItem</a>, <a href="#aec484816eb09040f49038c4b0a999f23">endSection</a>, <a href="#ae5a12bcaed78c969eac8b73cb19d798f">endTocEntry</a>, <a href="#a2260389b86a386811fc344bb6ec9273d">insertMemberAlignLeft</a>, <a href="#a1ec800447787c1eada0c828c6d3bb374">startMemberItem</a>, <a href="#ae3bbc191d41c6566b7bafe7a063dd1ac">startSection</a> and <a href="#a0c8a6327e1ce58e1d01bc05a1770e94b">startTocEntry</a>.
</div>
</div>

### writeAnchor() {#ac6fc309a5382d6beb8f919fc436709e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6fc309a5382d6beb8f919fc436709e2">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6fc309a5382d6beb8f919fc436709e2">writeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">                        override  </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a name=\""</span><span class="doxyHighlight"> &lt;&lt; name &lt;&lt;</span><span class="doxyHighlightStringLiteral">"\" id=\""</span><span class="doxyHighlight"> &lt;&lt; name &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;/a&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeChar() {#a4a70bf7faba5c41a9fe61307f15ce0d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeChar (char c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 221 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1892 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a70bf7faba5c41a9fe61307f15ce0d3">1892</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a70bf7faba5c41a9fe61307f15ce0d3">HtmlGenerator::writeChar</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">  cs[0]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">  cs[1]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>.
</div>
</div>

### writeDoc() {#a4baf32d6d76de7c48ea865fe47496612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeDoc (const <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> * node, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *, int id)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2622 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4baf32d6d76de7c48ea865fe47496612">2622</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4baf32d6d76de7c48ea865fe47496612">HtmlGenerator::writeDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> *ast,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a> *astImpl = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(ast);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (astImpl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>-&gt;setId(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/htmldocvisitor">HtmlDocVisitor</a> visitor(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,*<a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>,ctx,<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(visitor,astImpl-&gt;<a href="/web-doxygen/docs/api/classes/docnodeast/#a77e351cc54c344eac97ef21709f44305">root</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m&#95;codeList</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/docnodeast/#a77e351cc54c344eac97ef21709f44305">DocNodeAST::root</a>.
</div>
</div>

### writeFooter() {#a2c585c2b2bb740380ac384da86ae8477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeFooter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; navPath)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1556 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c585c2b2bb740380ac384da86ae8477">1556</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2c585c2b2bb740380ac384da86ae8477">HtmlGenerator::writeFooter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;navPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,navPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m&#95;lastTitle</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a>.
</div>
</div>

### writeGraphicalHierarchy() {#ad05e0b9d1baf567428af8a4e6b96b0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeGraphicalHierarchy (<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp; g)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 285 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2502 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad05e0b9d1baf567428af8a4e6b96b0ca">2502</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad05e0b9d1baf567428af8a4e6b96b0ca">HtmlGenerator::writeGraphicalHierarchy</a>(<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a47c5aeaf257c00ebecc958a4c78c5de9">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a47c5aeaf257c00ebecc958a4c78c5de9">DotGfxHierarchyTable::writeGraph</a>.
</div>
</div>

### writeInheritedSectionTitle() {#af012e45f04c5da89f11d17770dad1b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeInheritedSectionTitle (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 207 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3471 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af012e45f04c5da89f11d17770dad1b00">3471</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3472</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3473</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3474</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3475</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3476</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- writeInheritedSectionTitle --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3477</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> a = anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.isEmpty()) a.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3479</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> classLink = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;a class=\"el\" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3480</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3481</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3482</span><span class="doxyLineContent"><span class="doxyHighlight">    classLink+= <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3483</span><span class="doxyLineContent"><span class="doxyHighlight">    classLink += </span><span class="doxyHighlightStringLiteral">" href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3484</span><span class="doxyLineContent"><span class="doxyHighlight">    classLink+= <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>(<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,ref,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3485</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3487</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3488</span><span class="doxyLineContent"><span class="doxyHighlight">    classLink += </span><span class="doxyHighlightStringLiteral">"href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3489</span><span class="doxyLineContent"><span class="doxyHighlight">    classLink+=<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3490</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3491</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3492</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3493</span><span class="doxyLineContent"><span class="doxyHighlight">  classLink=classLink+fn+a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3494</span><span class="doxyLineContent"><span class="doxyHighlight">  classLink+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">)+<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(name,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)+</span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3495</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"inherit_header "</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3496</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;td colspan=\"2\" onclick=\"javascript:dynsection.toggleInherit('"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"')\"&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3497</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"dynarrow\"&gt;&lt;span class=\"arrowhead closed\"&gt;&lt;/span&gt;&lt;/span&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3498</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInheritedFrom(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(title,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),classLink)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3499</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3500</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### writeLabel() {#a8ebfa2100dc76714c34b65372f8ce867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, bool isLast)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 326 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3425 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ebfa2100dc76714c34b65372f8ce867">3425</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;label,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*isLast*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3426</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3427</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG_HTML</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- writeLabel("</span><span class="doxyHighlight"> &lt;&lt; label &lt;&lt; </span><span class="doxyHighlightStringLiteral">") --&gt;\n"</span><span class="doxyHighlight">;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3428</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3429</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> convertLabelToClass = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;lab) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3430</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> input = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(lab);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3431</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3432</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=input.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3433</span><span class="doxyLineContent"><span class="doxyHighlight">    result.<a href="/web-doxygen/docs/api/classes/qcstring/#a973167288278eae74d1d1c25313043fe">reserve</a>(l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3434</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Create valid class selector, see 10.2 here https://www.w3.org/TR/selectors-3/#w3cselgrammar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ident     [-]?{nmstart}{nmchar}*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3437</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// nmstart   [_a-z]|{nonascii}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3438</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// nonascii  [^\0-\177]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3439</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// nmchar    [_a-z0-9-]|{nonascii}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3440</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3441</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> nmstart=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0; i&lt;l; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3443</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3444</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = input.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3445</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c&lt;0 || (c&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// nmstart pattern</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3446</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3447</span><span class="doxyLineContent"><span class="doxyHighlight">        nmstart=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3448</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3449</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3450</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nmstart &amp;&amp; (c&lt;0 || (c&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) || (c&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">) || c==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// nmchar pattern</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3451</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3452</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3453</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3454</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nmstart &amp;&amp; (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">)) </span><span class="doxyHighlightComment">// show whitespace as -</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3455</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3456</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3457</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3458</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3459</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3460</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3461</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3462</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"mlabel "</span><span class="doxyHighlight"> &lt;&lt; convertLabelToClass(label.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; label &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3463</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a0f5cdb91a5e817f82987bef2e7f9fc45">DBG&#95;HTML</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a973167288278eae74d1d1c25313043fe">QCString::reserve</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.
</div>
</div>

### writeLatexSpacing() {#a504ef77641d52aea691b99b67a12445f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeLatexSpacing ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a504ef77641d52aea691b99b67a12445f">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a504ef77641d52aea691b99b67a12445f">writeLatexSpacing</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### writeLogo() {#a049734b4a24f5f4c365cc8352a9e9e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeLogo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 254 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1545 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a049734b4a24f5f4c365cc8352a9e9e39">1545</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a049734b4a24f5f4c365cc8352a9e9e39">HtmlGenerator::writeLogo</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">writeLogoAsString</a>(<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">writeLogoAsString</a>.
</div>
</div>

### writeNavigationPath() {#a4546e1dafb6db9b26352c6c0aca8f0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeNavigationPath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 253 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3038 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4546e1dafb6db9b26352c6c0aca8f0dd">3038</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4546e1dafb6db9b26352c6c0aca8f0dd">HtmlGenerator::writeNavigationPath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3039</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(s,</span><span class="doxyHighlightStringLiteral">"$relpath^"</span><span class="doxyHighlight">,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3041</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.
</div>
</div>

### writeNonBreakableSpace() {#a6f723ce20e5ff505a49cac90da7e2d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeNonBreakableSpace (int n)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 262 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2552 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f723ce20e5ff505a49cac90da7e2d3d">2552</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6f723ce20e5ff505a49cac90da7e2d3d">HtmlGenerator::writeNonBreakableSpace</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2553</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;n; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeObjectLink() {#a46e18e094779f6af393deafc4b64d454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeObjectLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 159 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1745 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46e18e094779f6af393deafc4b64d454">1745</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a46e18e094779f6af393deafc4b64d454">HtmlGenerator::writeObjectLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\"elRef\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\"el\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>(<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,ref,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>() == <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+fn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">                       fn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">                       anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>, <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writePageLink() {#aefbbae5ae8945e7c52e4a33daa40e9b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writePageLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefbbae5ae8945e7c52e4a33daa40e9b7">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aefbbae5ae8945e7c52e4a33daa40e9b7">writePageLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### writePageOutline() {#a715a0d36fadb1999b1e2d0162aa03825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writePageOutline ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 257 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3529 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a715a0d36fadb1999b1e2d0162aa03825">3529</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a715a0d36fadb1999b1e2d0162aa03825">HtmlGenerator::writePageOutline</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3530</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3531</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"page-nav\" class=\"page-nav-panel\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3532</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"page-nav-resize-handle\"&gt;&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3533</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"page-nav-tree\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3534</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"page-nav-contents\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3535</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- page-nav-contents --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3536</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- page-nav-tree --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3537</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- page-nav --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3538</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeQuickLinks() {#a23778fa833bc3d55e61c2cb13d39c090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeQuickLinks (<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, bool extraTabs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 255 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3063 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23778fa833bc3d55e61c2cb13d39c090">3063</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a23778fa833bc3d55e61c2cb13d39c090">HtmlGenerator::writeQuickLinks</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> extraTabs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3064</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3065</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,hli,file,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,extraTabs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3066</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>.
</div>
</div>

### writeRuler() {#a4a3ba3fa4795d6f4130c6430252a099e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeRuler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 211 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a3ba3fa4795d6f4130c6430252a099e">211</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a3ba3fa4795d6f4130c6430252a099e">writeRuler</a>()</span><span class="doxyHighlightKeyword"> override    </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;hr/&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeSearchInfo() {#a3b34fac2db4cc617332b082a1a087095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSearchInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1517 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b34fac2db4cc617332b082a1a087095">1517</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3b34fac2db4cc617332b082a1a087095">HtmlGenerator::writeSearchInfo</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aae6341c32bafc4883a531b50502dfcd9">writeSearchInfoStatic</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#aae6341c32bafc4883a531b50502dfcd9">writeSearchInfoStatic</a>.
</div>
</div>

### writeSplitBar() {#add51830ca796373d40b216621b6d4b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSplitBar (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; allMembersFile)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 252 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3033 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add51830ca796373d40b216621b6d4b8e">3033</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#add51830ca796373d40b216621b6d4b8e">HtmlGenerator::writeSplitBar</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;allMembersFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3034</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3035</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a>(name,<a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>,allMembersFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3036</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a> and <a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a>.
</div>
</div>

### writeStartAnnoItem() {#a9af437de0126be35d936123ca8eff51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeStartAnnoItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 232 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1733 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9af437de0126be35d936123ca8eff51a">1733</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9af437de0126be35d936123ca8eff51a">HtmlGenerator::writeStartAnnoItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;li&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!path.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\"el\" href=\""</span><span class="doxyHighlight"> &lt;&lt; fn &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeString() {#a77a2e0e20f56eb2256b9b8741ec8b33f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 144 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1675 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77a2e0e20f56eb2256b9b8741ec8b33f">1675</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a77a2e0e20f56eb2256b9b8741ec8b33f">HtmlGenerator::writeString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeStyleInfo() {#a86eb94b45459e81c896e184152dd7176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeStyleInfo (int part)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 138 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1576 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a86eb94b45459e81c896e184152dd7176">1576</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a86eb94b45459e81c896e184152dd7176">HtmlGenerator::writeStyleInfo</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> part)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("writeStyleInfo(%d)\n",part);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (part==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_STYLESHEET).isEmpty()) </span><span class="doxyHighlightComment">// write default style sheet</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("write doxygen.css\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a>(</span><span class="doxyHighlightStringLiteral">"doxygen.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"doxygen.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// write user defined style sheet</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cssName=<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_STYLESHEET);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cssName.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"http:"</span><span class="doxyHighlight">) &amp;&amp; !cssName.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"https:"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cssfi(cssName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() || !cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>() || !cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">isReadable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"style sheet {} does not exist or is not readable!\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_STYLESHEET));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// convert style sheet to string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileStr = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(cssName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// write the string into the output dir</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a>(cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; fileStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(cssfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;extraCssFiles = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(HTML_EXTRA_STYLESHEET);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> : extraCssFiles)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"jquery.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"navtree.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"dynsections.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"darkmode_toggle.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(INTERACTIVE_SVG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"svg.min.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"menu.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"menudata.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config&#95;getList</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="#abb4a012326a0991e0f7cf339b21eafa5">endPlainFile</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">FileInfo::isFile</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#aa7bd4cf0e93293d4c3bf057b53f02063">FileInfo::isReadable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>, <a href="#afcbb993451628a18541fe8323e2dbf13">startPlainFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>.
</div>
</div>

### writeSummaryLink() {#abf222cd6347aaf899d714dae6ddeb52f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSummaryLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, bool first)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 256 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3502 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf222cd6347aaf899d714dae6ddeb52f">3502</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abf222cd6347aaf899d714dae6ddeb52f">HtmlGenerator::writeSummaryLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3503</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3505</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3506</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;div class=\"summary\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3507</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3509</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3510</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" &amp;#124;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3511</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3512</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3513</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3514</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3515</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3516</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3517</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a> &lt;&lt; fn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3518</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3519</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3520</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3521</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3522</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3523</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3524</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3525</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3526</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3527</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aad7805f9de9a7ccdde7715e25882e281">m&#95;relPath</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.
</div>
</div>

### writeSynopsis() {#a658e00cd4c2a6a97fa1f6746739c3984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSynopsis ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a658e00cd4c2a6a97fa1f6746739c3984">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a658e00cd4c2a6a97fa1f6746739c3984">writeSynopsis</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### docify&#95;() {#a894bfecdbda01b83760c93a6a6947b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::docify_ (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text, bool inHtmlComment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 341 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1859 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a894bfecdbda01b83760c93a6a6947b9d">1859</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a894bfecdbda01b83760c93a6a6947b9d">HtmlGenerator::docify_</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inHtmlComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=*p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;amp;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inHtmlComment) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#45;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">                     { <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">; p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">                     { <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">; p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">                     { <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;zwj;("</span><span class="doxyHighlight">; p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">                     { <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;zwj;)"</span><span class="doxyHighlight">; p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:   <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.

Referenced by <a href="#ad8c12afa5b7d84e2e403af4c3ed30cbb">docify</a>.
</div>
</div>

### endTitle() {#ae1337adbb5ad6cea03fcee0d5a7cdfce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::endTitle ()</td>
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


<p>Definition at line 339 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1337adbb5ad6cea03fcee0d5a7cdfce">339</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae1337adbb5ad6cea03fcee0d5a7cdfce">endTitle</a>() { <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.

Referenced by <a href="#aebe66b78ec5e7be56c1d8e4d5c6f2b2e">endTitleHead</a>.
</div>
</div>

### startTitle() {#a0fd5a2e848ea16b025b1fb07b4b307fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::startTitle ()</td>
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


<p>Definition at line 338 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fd5a2e848ea16b025b1fb07b4b307fc">338</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0fd5a2e848ea16b025b1fb07b4b307fc">startTitle</a>() { <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"title\"&gt;"</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m&#95;t</a>.

Referenced by <a href="#ab529153ad002aa294643ef13adbf351a">startTitleHead</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;codeGen {#aa32061e00ef95a2b936ab97ea46b0cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlCodeGenerator* HtmlGenerator::m_codeGen = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 349 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa32061e00ef95a2b936ab97ea46b0cad">349</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/htmlcodegenerator">HtmlCodeGenerator</a>              *<a href="#aa32061e00ef95a2b936ab97ea46b0cad">m_codeGen</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ab7780b856bce0c4e0ea29e92fec08dce">addCodeGen</a>, <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a>, <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a> and <a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a>.
</div>
</div>

### m&#95;codeList {#aafdacbdd11fedcc8091b0679b8ff436f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;OutputCodeList&gt; HtmlGenerator::m_codeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 348 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aafdacbdd11fedcc8091b0679b8ff436f">348</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeList&gt; <a href="#aafdacbdd11fedcc8091b0679b8ff436f">m_codeList</a>;</span></span></div>

</div>


Referenced by <a href="#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator</a>, <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a> and <a href="#a4baf32d6d76de7c48ea865fe47496612">writeDoc</a>.
</div>
</div>

### m&#95;emptySection {#adb2b5c6cda4bb7881bc0b0f5466c2116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HtmlGenerator::m_emptySection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 347 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">347</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                            <a href="#adb2b5c6cda4bb7881bc0b0f5466c2116">m_emptySection</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a9261c777bbdaa1882cbd9186c6b08fb6">endMemberSections</a>, <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a>, <a href="#aed122d098bf970698797293cabd09b21">startInlineHeader</a>, <a href="#a477b9bf180d9c7a57edcd11c408cdb5b">startMemberDescription</a>, <a href="#aea90b1337254e9c10ceaefcff8b9c825">startMemberHeader</a>, <a href="#a1ec800447787c1eada0c828c6d3bb374">startMemberItem</a>, <a href="#a90e8e67b9d4140660537473a3c98c3d4">startMemberSections</a> and <a href="#a287320869b27536a66d09bd7f545507a">startMemberSubtitle</a>.
</div>
</div>

### m&#95;lastFile {#a453969afc6bce23453c23dbc81bc0996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::m_lastFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 344 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a453969afc6bce23453c23dbc81bc0996">344</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                        <a href="#a453969afc6bce23453c23dbc81bc0996">m_lastFile</a>;</span></span></div>

</div>


Referenced by <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a> and <a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a>.
</div>
</div>

### m&#95;lastTitle {#afbc1dd6ef2f559ec1a02527fc7e6ab65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::m_lastTitle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 343 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">343</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                        <a href="#afbc1dd6ef2f559ec1a02527fc7e6ab65">m_lastTitle</a>;</span></span></div>

</div>


Referenced by <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a>, <a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a> and <a href="#a2c585c2b2bb740380ac384da86ae8477">writeFooter</a>.
</div>
</div>

### m&#95;pageOutlineIndent {#a8830ad77ec53a2c66f11d161cedf292c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HtmlGenerator::m_pageOutlineIndent = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 350 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8830ad77ec53a2c66f11d161cedf292c">350</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                             <a href="#a8830ad77ec53a2c66f11d161cedf292c">m_pageOutlineIndent</a> = 0;</span></span></div>

</div>

</div>
</div>

### m&#95;relPath {#aad7805f9de9a7ccdde7715e25882e281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::m_relPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 345 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad7805f9de9a7ccdde7715e25882e281">345</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                        <a href="#aad7805f9de9a7ccdde7715e25882e281">m_relPath</a>;</span></span></div>

</div>


Referenced by <a href="#add957a1f68cc9b99a4c57caa58b33a9b">endCallGraph</a>, <a href="#a6e132b23d93e17c4e30b815977a5c865">endClassDiagram</a>, <a href="#a603fd2d86e322ea4018747febe523edf">endDirDepGraph</a>, <a href="#a8bf91873a8da583cfbb47b15806c0ae4">endDotGraph</a>, <a href="#aabf59d930dff9f6aa46e3e5674678a35">endGroupCollaboration</a>, <a href="#ac78029628ccb4f7aef7ca0c4cbce0ae3">endInclDepGraph</a>, <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a>, <a href="#a34d21b07f7218dcc1161ed797dc8a74a">startCallGraph</a>, <a href="#a005f1a46f9808e8a719ba756407259ec">startClassDiagram</a>, <a href="#a41dc42e70634afb2a68fd1c45dd16f91">startDirDepGraph</a>, <a href="#a4cacd7e83fff3a670a66073686c882a8">startDotGraph</a>, <a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a>, <a href="#a6d892ee256e9a34db8cf761569bb2c9c">startGroupCollaboration</a>, <a href="#a20449975cf6595d7c2cb353f1c26534f">startInclDepGraph</a>, <a href="#a80da85d198868bc3351b1a6a90f32a75">startIndexItem</a>, <a href="#a1099f1315ce5240b9165563e30471124">startTextLink</a>, <a href="#a2c585c2b2bb740380ac384da86ae8477">writeFooter</a>, <a href="#af012e45f04c5da89f11d17770dad1b00">writeInheritedSectionTitle</a>, <a href="#a049734b4a24f5f4c365cc8352a9e9e39">writeLogo</a>, <a href="#a4546e1dafb6db9b26352c6c0aca8f0dd">writeNavigationPath</a>, <a href="#a46e18e094779f6af393deafc4b64d454">writeObjectLink</a>, <a href="#a23778fa833bc3d55e61c2cb13d39c090">writeQuickLinks</a>, <a href="#a3b34fac2db4cc617332b082a1a087095">writeSearchInfo</a>, <a href="#add51830ca796373d40b216621b6d4b8e">writeSplitBar</a> and <a href="#abf222cd6347aaf899d714dae6ddeb52f">writeSummaryLink</a>.
</div>
</div>

### m&#95;sectionCount {#a306ac96cc0bd258bec437951ca315dcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HtmlGenerator::m_sectionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 346 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a306ac96cc0bd258bec437951ca315dcd">346</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                             <a href="#a306ac96cc0bd258bec437951ca315dcd">m_sectionCount</a> = 0;</span></span></div>

</div>


Referenced by <a href="#add957a1f68cc9b99a4c57caa58b33a9b">endCallGraph</a>, <a href="#a6e132b23d93e17c4e30b815977a5c865">endClassDiagram</a>, <a href="#a603fd2d86e322ea4018747febe523edf">endDirDepGraph</a>, <a href="#a8bf91873a8da583cfbb47b15806c0ae4">endDotGraph</a>, <a href="#aabf59d930dff9f6aa46e3e5674678a35">endGroupCollaboration</a>, <a href="#ac78029628ccb4f7aef7ca0c4cbce0ae3">endInclDepGraph</a>, <a href="#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator</a>, <a href="#a2a179f3313aad4e67a77b536a25a101b">operator=</a>, <a href="#a34d21b07f7218dcc1161ed797dc8a74a">startCallGraph</a>, <a href="#a005f1a46f9808e8a719ba756407259ec">startClassDiagram</a>, <a href="#a41dc42e70634afb2a68fd1c45dd16f91">startDirDepGraph</a>, <a href="#a4cacd7e83fff3a670a66073686c882a8">startDotGraph</a>, <a href="#ab59c183ba1429ec58b88fd83ea686d6c">startFile</a>, <a href="#a6d892ee256e9a34db8cf761569bb2c9c">startGroupCollaboration</a> and <a href="#a20449975cf6595d7c2cb353f1c26534f">startInclDepGraph</a>.
</div>
</div>

### m&#95;tocState {#a3742f232f4e229f51178530f132dfc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TocState HtmlGenerator::m_tocState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 362 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3742f232f4e229f51178530f132dfc3a">362</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/htmlgenerator/tocstate">TocState</a> <a href="#a3742f232f4e229f51178530f132dfc3a">m_tocState</a>;</span></span></div>

</div>


Referenced by <a href="#aafb64fea3c5e96e1c48b5caba59681fb">endLocalToc</a>, <a href="#ae5a12bcaed78c969eac8b73cb19d798f">endTocEntry</a>, <a href="#a5af845a03a3c0c16a3855d88034dfa70">startLocalToc</a> and <a href="#a0c8a6327e1ce58e1d01bc05a1770e94b">startTocEntry</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getMathJaxMacros() {#af3ae2deb6a25b4b0307edd25ad66896f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::getMathJaxMacros ()</td>
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


<p>Declaration at line 116 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3544 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3ae2deb6a25b4b0307edd25ad66896f">3544</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af3ae2deb6a25b4b0307edd25ad66896f">HtmlGenerator::getMathJaxMacros</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3545</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3546</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3547</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>.
</div>
</div>

### getNavTreeCss() {#a3874b75d86f996ce7d7ca32bea785c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::getNavTreeCss ()</td>
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


<p>Declaration at line 117 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3549 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3874b75d86f996ce7d7ca32bea785c56">3549</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3874b75d86f996ce7d7ca32bea785c56">HtmlGenerator::getNavTreeCss</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3550</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3551</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr">ResourceMgr</a> &amp;mgr = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3552</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"navtree.css"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3553</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.

Referenced by <a href="#a0c4c6cd48e43f74bf258851f8b109faf">init</a>.
</div>
</div>

### init() {#a0c4c6cd48e43f74bf258851f8b109faf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::init ()</td>
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


<p>Declaration at line 105 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1136 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c4c6cd48e43f74bf258851f8b109faf">1136</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dname = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(dname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>() &amp;&amp; !d.<a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">mkdir</a>(dname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not create output directory {}\n"</span><span class="doxyHighlight">,dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//writeLogo(dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_HEADER).isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>=<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_HEADER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a>=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("g_header='%s'\n",qPrint(g_header));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>(result,<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_HEADER),<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>=</span><span class="doxyHighlightStringLiteral">"header.html"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a> = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>(result,</span><span class="doxyHighlightStringLiteral">"&lt;default header.html&gt;"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_FOOTER).isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>=<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_FOOTER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a>=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("g_footer='%s'\n",qPrint(g_footer));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>(result,<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_FOOTER),<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a> = </span><span class="doxyHighlightStringLiteral">"footer.html"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a> = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>(result,</span><span class="doxyHighlightStringLiteral">"&lt;default footer.html&gt;"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_MATHJAX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(MATHJAX_CODEFILE).isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a4e0395c7f64c90455b817813fdaf3952">g_mathjax_code</a>=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(MATHJAX_CODEFILE));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("g_mathjax_code='%s'\n",qPrint(g_mathjax_code));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#abe3baaa3e5fc0455cd443d1722191cf5">g_latex_macro</a>=<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("converted g_latex_macro='%s'\n",qPrint(g_latex_macro));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr">ResourceMgr</a> &amp;mgr = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tabsCss;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">      tabsCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"tabs.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// stylesheet for the 'old' static tabs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">      tabsCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"fixed_tabs.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(dname+</span><span class="doxyHighlightStringLiteral">"/tabs.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(tabsCss);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">  mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"jquery.js"</span><span class="doxyHighlight">,dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(INTERACTIVE_SVG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">    mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"svg.min.js"</span><span class="doxyHighlight">,dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">    mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"menu.js"</span><span class="doxyHighlight">,dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// copy navtree.css</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(dname+</span><span class="doxyHighlightStringLiteral">"/navtree.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="#a3874b75d86f996ce7d7ca32bea785c56">getNavTreeCss</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_COPY_CLIPBOARD))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(dname+</span><span class="doxyHighlightStringLiteral">"/clipboard.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"clipboard.js"</span><span class="doxyHighlight">),</span><span class="doxyHighlightStringLiteral">"$copy_to_clipboard_text"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCopyToClipboard());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasCookie = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW) || <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE) || <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasCookie)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">    mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"cookie.js"</span><span class="doxyHighlight">,dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(dname+</span><span class="doxyHighlightStringLiteral">"/darkmode_toggle.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"darkmode_toggle.js"</span><span class="doxyHighlight">)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"$PROJECTID"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/util-cpp/#aba6653be2d238e1fc793706547950107">getProjectId</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(dname+</span><span class="doxyHighlightStringLiteral">"/dynsections.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"dynsections.js"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SOURCE_BROWSER) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SOURCE_TOOLTIPS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"dynsections_tooltips.js"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">ResourceMgr::copyResource</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g&#95;footer</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g&#95;footer&#95;file</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g&#95;header</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g&#95;header&#95;file</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#abe3baaa3e5fc0455cd443d1722191cf5">g&#95;latex&#95;macro</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a4e0395c7f64c90455b817813fdaf3952">g&#95;mathjax&#95;code</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="#a3874b75d86f996ce7d7ca32bea785c56">getNavTreeCss</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aba6653be2d238e1fc793706547950107">getProjectId</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a789823b9d7598023371f64ac0da067da">htmlMarkerInfo</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">Dir::mkdir</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### writeExternalSearchPage() {#a9588784ebebaad9cb24e153c07aeb662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeExternalSearchPage ()</td>
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


<p>Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3168 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9588784ebebaad9cb24e153c07aeb662">3168</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3169</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3170</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> disableIndex            = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3171</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView        = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fullSidebar             = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> quickLinksAfterSplitbar = !disableIndex &amp;&amp; generateTreeView &amp;&amp; fullSidebar;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3174</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dname               = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3175</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>            = dname+</span><span class="doxyHighlightStringLiteral">"/search"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3176</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3178</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3179</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3180</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a>,</span><span class="doxyHighlightStringLiteral">"Search"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3181</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3182</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedBy() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" Doxygen "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3183</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3184</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3185</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var searchBox = new SearchBox(\"searchBox\", \""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3186</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"search/\",'"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"');\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3187</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3188</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3189</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!disableIndex &amp;&amp; !quickLinksAfterSplitbar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3190</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3191</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>(t,<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">HighlightedItem::Search</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3192</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3193</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3194</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3195</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- top --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3196</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3197</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a>(</span><span class="doxyHighlightStringLiteral">"search.php"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3198</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (quickLinksAfterSplitbar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3199</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3200</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>(t,<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">HighlightedItem::Search</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3201</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3202</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3203</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"header\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3204</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;div class=\"headertitle\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3205</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;div class=\"title\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResultsTitle() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3206</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3207</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3208</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"contents\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3209</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3210</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"searchresults\"&gt;&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3211</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3212</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3213</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3214</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3215</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- doc-content --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3216</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- container --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3217</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3219</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a>(t,</span><span class="doxyHighlightStringLiteral">"Search"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3220</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3221</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3222</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3223</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3224</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scriptName = dname+</span><span class="doxyHighlightStringLiteral">"/search/search.js"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3225</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(scriptName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3227</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3228</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3229</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var searchResultsText=["</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3230</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(0) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\","</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3231</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(1) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\","</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3232</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(2) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3233</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var serverUrl=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(SEARCHENGINE_URL) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3234</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var tagMap = {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3235</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3236</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// add search mappings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3237</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;extraSearchMappings = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(EXTRA_SEARCH_MAPPINGS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ml : extraSearchMappings)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3239</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3240</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mapLine = ml.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3241</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> eqPos = mapLine.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3242</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (eqPos!=-1) </span><span class="doxyHighlightComment">// tag command contains a destination</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3243</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3244</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagName = mapLine.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(eqPos).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3245</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> destName = mapLine.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(mapLine.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-eqPos-1).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3246</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tagName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3247</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3248</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3249</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  \""</span><span class="doxyHighlight"> &lt;&lt; tagName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\": \""</span><span class="doxyHighlight"> &lt;&lt; destName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3250</span><span class="doxyLineContent"><span class="doxyHighlight">          first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3251</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3252</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3253</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3255</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"};\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3256</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"extsearch.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3257</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3258</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$(function() {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3259</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  var query = trim(getURLParameter('query'));\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3260</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  if (query) {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3261</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    searchFor(query,0,20);\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3262</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  } else {\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3263</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    var results = $('#results');\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3264</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    results.html('&lt;p&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(0) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/p&gt;');\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3265</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3266</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"});\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3267</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3269</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3270</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Failed to open file '{}' for writing...\n"</span><span class="doxyHighlight">,scriptName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3271</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3272</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config&#95;getList</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g&#95;header</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g&#95;header&#95;file</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a> and <a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### writeFooterFile() {#a6c1132096e93e030970694a61ea6c65f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeFooterFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Declaration at line 108 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1440 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c1132096e93e030970694a61ea6c65f">1440</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6c1132096e93e030970694a61ea6c65f">HtmlGenerator::writeFooterFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- HTML footer for doxygen "</span><span class="doxyHighlight"> &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"--&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"footer.html"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a> and <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### writeHeaderFile() {#ab00e0c98e1c833ae27198d1e10c9c22e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeHeaderFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cssname)</td>
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


<p>Declaration at line 107 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1434 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab00e0c98e1c833ae27198d1e10c9c22e">1434</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab00e0c98e1c833ae27198d1e10c9c22e">HtmlGenerator::writeHeaderFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/*cssname*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- HTML header for doxygen "</span><span class="doxyHighlight"> &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"--&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"header.html"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a> and <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### writeLogoAsString() {#a540a1a09ba6e1bcaf7e0704cc05e3880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::writeLogoAsString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
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


<p>Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1523 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">1523</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">HtmlGenerator::writeLogoAsString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(TIMESTAMP))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> TIMESTAMP_t::NO:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedBy();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedAt(</span><span class="doxyHighlightStringLiteral">"&lt;span class=\"timestamp\"&gt;&lt;/span&gt;"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  result += </span><span class="doxyHighlightStringLiteral">"&amp;#160;\n&lt;a href=\"https://www.doxygen.org/index.html\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"&lt;img class=\"footer\" src=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">  result += path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">  result += </span><span class="doxyHighlightStringLiteral">"doxygen.svg\" width=\"104\" height=\"31\" alt=\"doxygen\"/&gt;&lt;/a&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">  result += getDoxygenVersion();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">  result += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="#a049734b4a24f5f4c365cc8352a9e9e39">writeLogo</a> and <a href="#a1fd6971ba73b744d9ceb90478194d61d">writeSearchPage</a>.
</div>
</div>

### writeSearchData() {#a9114c68d96141e80c08efdd497fc010e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSearchData (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; dir)</td>
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


<p>Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1292 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9114c68d96141e80c08efdd497fc010e">1292</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9114c68d96141e80c08efdd497fc010e">HtmlGenerator::writeSearchData</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;dname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//bool serverBasedSearch = Config_getBool(SERVER_BASED_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//writeImgData(dname,serverBasedSearch ? search_server_data : search_client_data);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr">ResourceMgr</a> &amp;mgr = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> searchDirName = dname;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(searchDirName+</span><span class="doxyHighlightStringLiteral">"/search.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> searchCss;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// the position of the search box depends on a number of settings.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Insert the right piece of CSS code depending on which options are selected</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">      searchCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"search_sidebar.css"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// we have a full height side bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_COLORSTYLE)==HTML_COLORSTYLE_t::TOGGLE)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">        searchCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"search_nomenu_toggle.css"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// we have no tabs but do have a darkmode button</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">        searchCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"search_nomenu.css"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// we have no tabs and no darkmode button</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_DYNAMIC_MENUS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">      searchCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"search_fixedtabs.css"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// we have tabs, but they are static</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">      searchCss = mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"search.css"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// default case with a dynamic menu bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// and then add the option independent part of the styling</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">    searchCss += mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"search_common.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">    searchCss = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(searchCss,</span><span class="doxyHighlightStringLiteral">"$doxygenversion"</span><span class="doxyHighlight">,getDoxygenVersion());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>(searchCss);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"search/search.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### writeSearchInfoStatic() {#aae6341c32bafc4883a531b50502dfcd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSearchInfoStatic (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath)</td>
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


<p>Declaration at line 110 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1487 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aae6341c32bafc4883a531b50502dfcd9">1487</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aae6341c32bafc4883a531b50502dfcd9">HtmlGenerator::writeSearchInfoStatic</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> searchEngine      = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> serverBasedSearch = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SERVER_BASED_SEARCH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (searchEngine &amp;&amp; !serverBasedSearch)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- window showing the filter options --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"MSearchSelectWindow\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"     onmouseover=\"return searchBox.OnSearchSelectShow()\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"     onmouseout=\"return searchBox.OnSearchSelectHide()\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"     onkeydown=\"return searchBox.OnSearchSelectKey(event)\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- iframe showing the search results (closed by default) --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"MSearchResultsWindow\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"MSearchResults\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"SRPage\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"SRIndex\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"SRResults\"&gt;&lt;/div&gt;\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// here the results will be inserted</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"SRStatus\" id=\"Loading\"&gt;"</span><span class="doxyHighlight">   &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trLoading()   &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"SRStatus\" id=\"Searching\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearching() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"SRStatus\" id=\"NoMatches\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNoMatches() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// SRIndex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// SRPage</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// MSearchResults</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// MSearchResultsWindow</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.

Referenced by <a href="#a3b34fac2db4cc617332b082a1a087095">writeSearchInfo</a>.
</div>
</div>

### writeSearchPage() {#a1fd6971ba73b744d9ceb90478194d61d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeSearchPage ()</td>
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


<p>Declaration at line 112 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 3069 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fd6971ba73b744d9ceb90478194d61d">3069</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3070</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3071</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> disableIndex            = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3072</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView        = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3073</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fullSidebar             = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3074</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> quickLinksAfterSplitbar = !disableIndex &amp;&amp; generateTreeView &amp;&amp; fullSidebar;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3075</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> projectName         = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3076</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> htmlOutput          = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3077</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3078</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// OPENSEARCH_PROVIDER {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3079</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> configFileName = htmlOutput+</span><span class="doxyHighlightStringLiteral">"/search_config.php"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3080</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(configFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3081</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3082</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3083</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3084</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?php\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3085</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$config = array(\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3086</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'PROJECT_NAME' =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(projectName) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3087</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'GENERATE_TREEVIEW' =&gt; "</span><span class="doxyHighlight"> &lt;&lt; (generateTreeView?</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3088</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'DISABLE_INDEX' =&gt; "</span><span class="doxyHighlight"> &lt;&lt; (disableIndex?</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3089</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'FULL_SIDEBAR' =&gt; "</span><span class="doxyHighlight"> &lt;&lt; (fullSidebar?</span><span class="doxyHighlightStringLiteral">"true"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"false"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3090</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">");\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3091</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$translator = array(\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3092</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'search_results_title' =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResultsTitle() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3093</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'search_results' =&gt; array(\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3094</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    0 =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(0) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3095</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    1 =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(1) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3096</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    2 =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchResults(2), </span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"\\$"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3097</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  ),\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3098</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'search_matches' =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearchMatches() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3099</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'search' =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSearch() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3100</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  'logo' =&gt; \""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">writeLogoAsString</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">), </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\\\""</span><span class="doxyHighlight">), </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\\n"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\",\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3101</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">");\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3102</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3103</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3104</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3105</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"search_functions.php"</span><span class="doxyHighlight">,htmlOutput);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"search_opensearch.php"</span><span class="doxyHighlight">,htmlOutput);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// OPENSEARCH_PROVIDER }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3109</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> = htmlOutput+</span><span class="doxyHighlightStringLiteral">"/search.php"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3111</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3113</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3114</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3115</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g_header_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g_header</a>,</span><span class="doxyHighlightStringLiteral">"Search"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3116</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3117</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGeneratedBy() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" Doxygen "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3118</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3119</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3120</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var searchBox = new SearchBox(\"searchBox\", \""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3121</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"search/\",'"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"');\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3122</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3123</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3124</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!disableIndex &amp;&amp; !quickLinksAfterSplitbar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3125</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3126</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>(t,<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">HighlightedItem::Search</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3127</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3128</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3129</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3130</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- top --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3131</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3132</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a>(</span><span class="doxyHighlightStringLiteral">"search.php"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (quickLinksAfterSplitbar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3134</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3135</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>(t,<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">HighlightedItem::Search</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3136</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3137</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!-- generated --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3138</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3139</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?php\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3140</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"require_once \"search_functions.php\";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3141</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"main();\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3142</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3143</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Write empty navigation path, to make footer connect properly</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3146</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3147</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- doc-content --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3148</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- container --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3149</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3150</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3151</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a>(t,</span><span class="doxyHighlightStringLiteral">"Search"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3152</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3153</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3154</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3155</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scriptName = htmlOutput+</span><span class="doxyHighlightStringLiteral">"/search/search.js"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3156</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(scriptName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3160</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"extsearch.js"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3161</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3164</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Failed to open file '{}' for writing...\n"</span><span class="doxyHighlight">,scriptName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3165</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3166</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">ResourceMgr::copyResource</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a3498eed8e2e90303039a4e2245c319d3">g&#95;header</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a357af50f3d94adbe34df93d23e5bdd44">g&#95;header&#95;file</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a13348442cc6a27032d2b4aa28b75a5d3">Search</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="#a540a1a09ba6e1bcaf7e0704cc05e3880">writeLogoAsString</a>, <a href="#a9b5d4e446eeaff119ace5a9e0407e984">writePageFooter</a> and <a href="#ab34d97b712a57f3428678326f92651d4">writeSplitBarAsString</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### writeSplitBarAsString() {#ab34d97b712a57f3428678326f92651d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlGenerator::writeSplitBarAsString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relpath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; allMembersFile)</td>
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


<p>Declaration at line 115 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 2998 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab34d97b712a57f3428678326f92651d4">2998</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab34d97b712a57f3428678326f92651d4">HtmlGenerator::writeSplitBarAsString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relpath,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;allMembersFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2999</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3000</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3001</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3002</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write split bar</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3003</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3004</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3005</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3006</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3007</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3008</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3009</span><span class="doxyLineContent"><span class="doxyHighlight">      result += <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3010</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"&lt;div id=\"side-nav\" class=\"ui-resizable side-nav-resizable\"&gt;\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3011</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3012</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3013</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"  &lt;div id=\"nav-tree\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3014</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"    &lt;div id=\"nav-tree-contents\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3015</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"      &lt;div id=\"nav-sync\" class=\"sync\"&gt;&lt;/div&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3016</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"    &lt;/div&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3017</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"  &lt;/div&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3018</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"  &lt;div id=\"splitbar\" style=\"-moz-user-select:none;\" \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3019</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"       class=\"ui-resizable-handle\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3020</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"  &lt;/div&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3021</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3022</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"text/javascript\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3023</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"$(function(){initNavTree('"</span><span class="doxyHighlight"> + fn + </span><span class="doxyHighlightStringLiteral">"','"</span><span class="doxyHighlight"> + relpath + </span><span class="doxyHighlightStringLiteral">"','"</span><span class="doxyHighlight"> + allMembersFile + </span><span class="doxyHighlightStringLiteral">"'); });\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3024</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3025</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(DISABLE_INDEX) || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FULL_SIDEBAR))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3026</span><span class="doxyLineContent"><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3027</span><span class="doxyLineContent"><span class="doxyHighlight">       result+=</span><span class="doxyHighlightStringLiteral">"&lt;div id=\"container\"&gt;\n&lt;div id=\"doc-content\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3028</span><span class="doxyLineContent"><span class="doxyHighlight">     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3029</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3030</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3031</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a> and <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>.

Referenced by <a href="#a9588784ebebaad9cb24e153c07aeb662">writeExternalSearchPage</a>, <a href="#a1fd6971ba73b744d9ceb90478194d61d">writeSearchPage</a> and <a href="#add51830ca796373d40b216621b6d4b8e">writeSplitBar</a>.
</div>
</div>

### writeStyleSheetFile() {#a9e0dc4a7197da8f8aa16b96d1c958ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeStyleSheetFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1428 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e0dc4a7197da8f8aa16b96d1c958ab2">1428</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e0dc4a7197da8f8aa16b96d1c958ab2">HtmlGenerator::writeStyleSheetFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac082e13d5df852dc8a34fd6e84668dff">fillColorStyleMaps</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac7339dc7ff25bcb7a9fbea1d671a16da">writeDefaultStyleSheet</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### writeTabData() {#a7306ef9abbceafd6074b4d883a59f033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writeTabData ()</td>
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
<p>Additional initialization after indices have been created.</p>

<p>Declaration at line 109 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1283 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7306ef9abbceafd6074b4d883a59f033">1283</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7306ef9abbceafd6074b4d883a59f033">HtmlGenerator::writeTabData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addStyleSheetFile(</span><span class="doxyHighlightStringLiteral">"tabs.css"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dname=<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr">ResourceMgr</a> &amp;mgr = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">  mgr.<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"doxygen.svg"</span><span class="doxyHighlight">,dname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addImageFile(</span><span class="doxyHighlightStringLiteral">"doxygen.svg"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">ResourceMgr::copyResource</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a> and <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### writePageFooter() {#a9b5d4e446eeaff119ace5a9e0407e984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::writePageFooter (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lastTitle, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; navPath)</td>
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


<p>Declaration at line 340 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1550 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b5d4e446eeaff119ace5a9e0407e984">1550</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9b5d4e446eeaff119ace5a9e0407e984">HtmlGenerator::writePageFooter</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lastTitle,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;navPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>(<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g_footer_file</a>,<a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g_footer</a>,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(lastTitle),relPath,navPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6ef18a9e8d540c96bde81562abb60e42">g&#95;footer</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a932663422cdebc372564c94056bf0a7e">g&#95;footer&#95;file</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>.

Referenced by <a href="#a9588784ebebaad9cb24e153c07aeb662">writeExternalSearchPage</a>, <a href="#a2c585c2b2bb740380ac384da86ae8477">writeFooter</a> and <a href="#a1fd6971ba73b744d9ceb90478194d61d">writeSearchPage</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
