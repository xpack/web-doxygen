---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docinclude
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocInclude` Class Reference

<p>Node representing an included text block from file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocInclude { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docnode">DocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract node interface with type information. <a href="/web-doxygen/docs/api/classes/docnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#a72aa0fd397546547aadf356348ff3eaf">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a> (DocParser *parser, DocNodeVariant *parent, const QCString &amp;file, const QCString &amp;context, Type t, bool stripCodeComments, bool isExample, const QCString &amp;exampleFile, const QCString &amp;blockId, bool isBlock, bool trimLeft)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2dce3078cd4a33bf3923066b2c79957">file</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1201f943eb5e45821291843810df8a51">extension</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9f5167c504937dedc7ffac6a454514">type</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af001e0f412f5189fc3f7105b402996d6">isExample</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135bf24f61094b5ccd0f11184a689105">isBlock</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">m_context</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m_stripCodeComments</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">m_isExample</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bab573719b226a698c1d11987b08158">m_isBlock</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0daa2932a60fa370ef23cd39395b4302">m_trimLeft</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a70d77ba938d4df78c53b194a05b97">m_exampleFile</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a></td>
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

<p>Node representing an included text block from file.</p>

<p>Definition at line 434 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### Type {#a72aa0fd397546547aadf356348ff3eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DocInclude::Type </td>
</tr>
</table>
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
<td class="doxyEnumItemName">Include<a id="a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DontInclude<a id="a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VerbInclude<a id="a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HtmlInclude<a id="a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LatexInclude<a id="a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncWithLines<a id="a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Snippet<a id="a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SnippetWithLines<a id="a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DontIncWithLines<a id="a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RtfInclude<a id="a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ManInclude<a id="a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DocbookInclude<a id="a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XmlInclude<a id="a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00437">437</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">437</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a> { <a href="#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">Include</a>, <a href="#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DontInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">VerbInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">HtmlInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">LatexInclude</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">438</a></span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">IncWithLines</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">Snippet</a> , <a href="#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">SnippetWithLines</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">439</a></span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DontIncWithLines</a>, <a href="#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">RtfInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">ManInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocbookInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">XmlInclude</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">            };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DocInclude() {#a67ca9fd53907aae6f643965e4a8edab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocInclude::DocInclude (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, <a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a> t, bool stripCodeComments, bool isExample, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; blockId, bool isBlock, bool trimLeft)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00441">441</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67ca9fd53907aae6f643965e4a8edab0">441</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#ad2dce3078cd4a33bf3923066b2c79957">file</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>, <a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a> t, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af001e0f412f5189fc3f7105b402996d6">isExample</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a135bf24f61094b5ccd0f11184a689105">isBlock</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    : <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>(<a href="#ad2dce3078cd4a33bf3923066b2c79957">file</a>), <a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">m_context</a>(<a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>), <a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a>(t),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m_stripCodeComments</a>(<a href="#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">m_isExample</a>(<a href="#af001e0f412f5189fc3f7105b402996d6">isExample</a>), <a href="#a4bab573719b226a698c1d11987b08158">m_isBlock</a>(<a href="#a135bf24f61094b5ccd0f11184a689105">isBlock</a>), <a href="#a0daa2932a60fa370ef23cd39395b4302">m_trimLeft</a>(<a href="#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae1a70d77ba938d4df78c53b194a05b97">m_exampleFile</a>(<a href="#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>), <a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a>(<a href="#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>) {}</span></span></div>

</div>


References <a href="#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>, <a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>, <a href="#ad2dce3078cd4a33bf3923066b2c79957">file</a>, <a href="#a135bf24f61094b5ccd0f11184a689105">isBlock</a>, <a href="#af001e0f412f5189fc3f7105b402996d6">isExample</a>, <a href="#a73c26f729f290f5b655be52da766d675">m&#95;blockId</a>, <a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">m&#95;context</a>, <a href="#ae1a70d77ba938d4df78c53b194a05b97">m&#95;exampleFile</a>, <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m&#95;file</a>, <a href="#a4bab573719b226a698c1d11987b08158">m&#95;isBlock</a>, <a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">m&#95;isExample</a>, <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m&#95;stripCodeComments</a>, <a href="#a0daa2932a60fa370ef23cd39395b4302">m&#95;trimLeft</a>, <a href="#a35edc5abc111fdc2728c2db428903acb">m&#95;type</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a> and <a href="#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### blockId() {#a0a32ad9c12a12a6664dd90ba2c141c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::blockId ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00454">454</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a32ad9c12a12a6664dd90ba2c141c26">454</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a>; }</span></span></div>

</div>


Reference <a href="#a73c26f729f290f5b655be52da766d675">m&#95;blockId</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### context() {#afe43ae68ec1e5cb184ab7a3e63b40556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::context ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00453">453</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe43ae68ec1e5cb184ab7a3e63b40556">453</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">m_context</a>; }</span></span></div>

</div>


Reference <a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">m&#95;context</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a> and <a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a>.
</div>
</div>

### exampleFile() {#a9541ad25c955f690e228a07e6d1c0093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::exampleFile ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00457">457</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9541ad25c955f690e228a07e6d1c0093">457</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae1a70d77ba938d4df78c53b194a05b97">m_exampleFile</a>; }</span></span></div>

</div>


Reference <a href="#ae1a70d77ba938d4df78c53b194a05b97">m&#95;exampleFile</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### extension() {#a1201f943eb5e45821291843810df8a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::extension ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00450">450</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1201f943eb5e45821291843810df8a51">450</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1201f943eb5e45821291843810df8a51">extension</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=<a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>.findRev(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> i!=-1 ? <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>.mid(i) : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(); }</span></span></div>

</div>


Reference <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m&#95;file</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### file() {#ad2dce3078cd4a33bf3923066b2c79957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::file ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00449">449</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2dce3078cd4a33bf3923066b2c79957">449</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad2dce3078cd4a33bf3923066b2c79957">file</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>; }</span></span></div>

</div>


Reference <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m&#95;file</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a193a00ab964a64974f8207a0da1f51d3">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### isBlock() {#a135bf24f61094b5ccd0f11184a689105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::isBlock ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00458">458</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a135bf24f61094b5ccd0f11184a689105">458</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a135bf24f61094b5ccd0f11184a689105">isBlock</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4bab573719b226a698c1d11987b08158">m_isBlock</a>; }</span></span></div>

</div>


Reference <a href="#a4bab573719b226a698c1d11987b08158">m&#95;isBlock</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a193a00ab964a64974f8207a0da1f51d3">PrintDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### isExample() {#af001e0f412f5189fc3f7105b402996d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::isExample ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00456">456</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af001e0f412f5189fc3f7105b402996d6">456</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af001e0f412f5189fc3f7105b402996d6">isExample</a>()</span><span class="doxyHighlightKeyword"> const       </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">m_isExample</a>; }</span></span></div>

</div>


Reference <a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">m&#95;isExample</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### parse() {#a191446e0b57311d58cf1ef51a91417ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocInclude::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00460">460</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l00268">268</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a191446e0b57311d58cf1ef51a91417ee">268</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"file={} text={}"</span><span class="doxyHighlight">,<a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(<a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(<a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DontIncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">IncWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">Include</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DontInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a5340de5ad1c86c5c2d03b02e721b51e0">readTextFileByName</a>(<a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>,<a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ac7c9c34f67532338c9595cc7eac91bb6">includeFileName</a>   = <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">includeFileText</a>   = <a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">includeFileOffset</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">includeFileLength</a> = <a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a04744ff470f7989ae2cb1b3d49eb6450">includeFileLine</a>   = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00595ca383d8adbe528f151fd41f437a">includeFileShowLineNo</a> = (<a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a> == <a href="#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DontIncWithLines</a> || <a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a> == <a href="#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">IncWithLines</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ab00c3265540f931c1b03bd3752f70d6a">stripCodeComments</a> = <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m_stripCodeComments</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("parser-&gt;context.includeFile=&lt;&lt;%s&gt;&gt;\n",qPrint(parser-&gt;context.includeFileText));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">VerbInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">HtmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">LatexInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">DocInclude::RtfInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">DocInclude::ManInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">DocInclude::XmlInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocInclude::DocbookInclude</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a5340de5ad1c86c5c2d03b02e721b51e0">readTextFileByName</a>(<a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>,<a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">Snippet</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">SnippetWithLines</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a5340de5ad1c86c5c2d03b02e721b51e0">readTextFileByName</a>(<a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>,<a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// check here for the existence of the blockId inside the file, so we</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// only generate the warning once.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a>.isEmpty() &amp;&amp; (count=<a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>.contains(<a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a>.data()))!=2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>.fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightStringLiteral">"block marked with {} for \\snippet should appear twice in file {}, found it {:d} times"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a>,<a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>,count);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="#a72aa0fd397546547aadf356348ff3eafaef9a97c613611ae895729e6f78c1fc83">DocbookInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafae754cf246a0a671e43c28d1b36c87d9b">DontInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa784c71fd6745f7f5a294b7855d8fea0a">DontIncWithLines</a>, <a href="#a72aa0fd397546547aadf356348ff3eafaa5ea0461256f384958038fb6f8df3859">HtmlInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa2cc6c9824f61c186c983be390d3506a3">Include</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">DocParserContext::includeFileLength</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a04744ff470f7989ae2cb1b3d49eb6450">DocParserContext::includeFileLine</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ac7c9c34f67532338c9595cc7eac91bb6">DocParserContext::includeFileName</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">DocParserContext::includeFileOffset</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a00595ca383d8adbe528f151fd41f437a">DocParserContext::includeFileShowLineNo</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">DocParserContext::includeFileText</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa952cf9f1f8a7019693e43d6dd9230073">IncWithLines</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa46758ee2c283cdfe24b17c2d2f11e8ee">LatexInclude</a>, <a href="#a73c26f729f290f5b655be52da766d675">m&#95;blockId</a>, <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m&#95;file</a>, <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m&#95;stripCodeComments</a>, <a href="#a2178df88e575c03f480a9f8d99e864c8">m&#95;text</a>, <a href="#a35edc5abc111fdc2728c2db428903acb">m&#95;type</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa135c7c87665378652c597d57710d60a1">ManInclude</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a5340de5ad1c86c5c2d03b02e721b51e0">DocParser::readTextFileByName</a>, <a href="#a72aa0fd397546547aadf356348ff3eafafca5fb43380888ff488a49bfc4f32cfd">RtfInclude</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa00513d2ab0b78aa7aed51fb4ad1e3439">Snippet</a>, <a href="#a72aa0fd397546547aadf356348ff3eafa727f8845240d3fbdb08261d2ee34eabe">SnippetWithLines</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ab00c3265540f931c1b03bd3752f70d6a">DocParserContext::stripCodeComments</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="#a72aa0fd397546547aadf356348ff3eafaaad4241a3cd52aa23aebf58063e2f610">VerbInclude</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn&#95;doc&#95;error</a> and <a href="#a72aa0fd397546547aadf356348ff3eafadb264a40d447ec379aa1e80af933cf68">XmlInclude</a>.
</div>
</div>

### stripCodeComments() {#a6d2679020b534464d254f0dea85cded1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::stripCodeComments ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00455">455</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d2679020b534464d254f0dea85cded1">455</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m_stripCodeComments</a>; }</span></span></div>

</div>


Reference <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m&#95;stripCodeComments</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### text() {#ab2a402fcaf6d3c4ecce0cd7647c0e339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::text ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00452">452</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2a402fcaf6d3c4ecce0cd7647c0e339">452</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>; }</span></span></div>

</div>


Reference <a href="#a2178df88e575c03f480a9f8d99e864c8">m&#95;text</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a739b167e0a41f08eff74e1bfdecce329">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### trimLeft() {#ae9583c0c22fe5031fc50b95cbabef0c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::trimLeft ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00459">459</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9583c0c22fe5031fc50b95cbabef0c0">459</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0daa2932a60fa370ef23cd39395b4302">m_trimLeft</a>; }</span></span></div>

</div>


Reference <a href="#a0daa2932a60fa370ef23cd39395b4302">m&#95;trimLeft</a>.

Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

### type() {#a8e9f5167c504937dedc7ffac6a454514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocInclude::type ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00451">451</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e9f5167c504937dedc7ffac6a454514">451</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a> <a href="#a8e9f5167c504937dedc7ffac6a454514">type</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a>; }</span></span></div>

</div>


Reference <a href="#a35edc5abc111fdc2728c2db428903acb">m&#95;type</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#aef2b269b13f233bd8773f2b7b8365443">isDocIncludeVisible</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a739b167e0a41f08eff74e1bfdecce329">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a193a00ab964a64974f8207a0da1f51d3">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;blockId {#a73c26f729f290f5b655be52da766d675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::m_blockId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00472">472</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73c26f729f290f5b655be52da766d675">472</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#a73c26f729f290f5b655be52da766d675">m_blockId</a>;</span></span></div>

</div>


Referenced by <a href="#a0a32ad9c12a12a6664dd90ba2c141c26">blockId</a>, <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a> and <a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a>.
</div>
</div>

### m&#95;context {#a0eadb1403a2d5c6f13c7015d766fd6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::m_context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00464">464</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">464</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#a0eadb1403a2d5c6f13c7015d766fd6ff">m_context</a>;</span></span></div>

</div>


Referenced by <a href="#afe43ae68ec1e5cb184ab7a3e63b40556">context</a> and <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>.
</div>
</div>

### m&#95;exampleFile {#ae1a70d77ba938d4df78c53b194a05b97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::m_exampleFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00471">471</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1a70d77ba938d4df78c53b194a05b97">471</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#ae1a70d77ba938d4df78c53b194a05b97">m_exampleFile</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a> and <a href="#a9541ad25c955f690e228a07e6d1c0093">exampleFile</a>.
</div>
</div>

### m&#95;file {#aff31b9b962ada7c6f4751629cc5e1ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::m_file</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00463">463</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff31b9b962ada7c6f4751629cc5e1ddb">463</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#aff31b9b962ada7c6f4751629cc5e1ddb">m_file</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="#a1201f943eb5e45821291843810df8a51">extension</a>, <a href="#ad2dce3078cd4a33bf3923066b2c79957">file</a> and <a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a>.
</div>
</div>

### m&#95;isBlock {#a4bab573719b226a698c1d11987b08158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::m_isBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00469">469</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bab573719b226a698c1d11987b08158">469</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">      <a href="#a4bab573719b226a698c1d11987b08158">m_isBlock</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a> and <a href="#a135bf24f61094b5ccd0f11184a689105">isBlock</a>.
</div>
</div>

### m&#95;isExample {#a3f3eb2ecb96b0ae84f8adcfe5557ad6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::m_isExample</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00468">468</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">468</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">      <a href="#a3f3eb2ecb96b0ae84f8adcfe5557ad6d">m_isExample</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a> and <a href="#af001e0f412f5189fc3f7105b402996d6">isExample</a>.
</div>
</div>

### m&#95;stripCodeComments {#abc4b9967dd22e6ab83eba8d00e9d012e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::m_stripCodeComments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00467">467</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc4b9967dd22e6ab83eba8d00e9d012e">467</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">      <a href="#abc4b9967dd22e6ab83eba8d00e9d012e">m_stripCodeComments</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a> and <a href="#a6d2679020b534464d254f0dea85cded1">stripCodeComments</a>.
</div>
</div>

### m&#95;text {#a2178df88e575c03f480a9f8d99e864c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocInclude::m_text</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00465">465</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2178df88e575c03f480a9f8d99e864c8">465</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  <a href="#a2178df88e575c03f480a9f8d99e864c8">m_text</a>;</span></span></div>

</div>


Referenced by <a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a> and <a href="#ab2a402fcaf6d3c4ecce0cd7647c0e339">text</a>.
</div>
</div>

### m&#95;trimLeft {#a0daa2932a60fa370ef23cd39395b4302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocInclude::m_trimLeft</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00470">470</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0daa2932a60fa370ef23cd39395b4302">470</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">      <a href="#a0daa2932a60fa370ef23cd39395b4302">m_trimLeft</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a> and <a href="#ae9583c0c22fe5031fc50b95cbabef0c0">trimLeft</a>.
</div>
</div>

### m&#95;type {#a35edc5abc111fdc2728c2db428903acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocInclude::m_type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00466">466</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35edc5abc111fdc2728c2db428903acb">466</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a72aa0fd397546547aadf356348ff3eaf">Type</a>      <a href="#a35edc5abc111fdc2728c2db428903acb">m_type</a>;</span></span></div>

</div>


Referenced by <a href="#a67ca9fd53907aae6f643965e4a8edab0">DocInclude</a>, <a href="#a191446e0b57311d58cf1ef51a91417ee">parse</a> and <a href="#a8e9f5167c504937dedc7ffac6a454514">type</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
