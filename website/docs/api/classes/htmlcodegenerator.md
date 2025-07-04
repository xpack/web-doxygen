---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/htmlcodegenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HtmlCodeGenerator` Class Reference

<p>Generator for HTML code fragments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class HtmlCodeGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/htmlgen-h">src/htmlgen.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for code generators. <a href="/web-doxygen/docs/api/classes/outputcodeintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99b4eb5ba4f3d5e4a93b224bb9b178b">HtmlCodeGenerator</a> (TextStream *t, const QCString &amp;relPath)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace5b6a3e0a5a8c7a6ffcf2465302c9f7">HtmlCodeGenerator</a> (TextStream *t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9589e0f726aa6dcd23464bcf609a8fb">setTextStream</a> (TextStream *t)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220de109bb39c3369cad7f04261d30a1">setFileName</a> (const QCString fileName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee68c6253f5c9ed82886d0197d276ef">type</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4fea87990dd2c3eb9fe3ca6bf2c89c9">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9b21b46a1623df6d59c0ccbe0c53c6">stripCodeComments</a> (bool b) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c925b83a96ace6b647f17e8812749ba">startSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9118ec2f1fcd682d16bbfeadd11ed74">endSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7de139146f10ccf63c8527a63eb6783">setStripIndentAmount</a> (size_t amount) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833284e18308ead496c0d94f6b3f1d71">writeCodeLink</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab450dd921a83f6ef2535324349f6f1c1">writeTooltip</a> (const QCString &amp;id, const DocLinkInfo &amp;docInfo, const QCString &amp;decl, const QCString &amp;desc, const SourceLinkInfo &amp;defInfo, const SourceLinkInfo &amp;declInfo) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, int, bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a899976eb9aee4bb9bd881e9b204cc069">startCodeLine</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c946ea34b71976fa126dd6fcb2fb02">startFontClass</a> (const QCString &amp;s) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab62059c61bf5f1b846ffb3fe1c97f736">endFontClass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c6f9dce1570e8f0659c9ea6c6640720">writeCodeAnchor</a> (const QCString &amp;anchor) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8aef00bed9d8deb56b3d9e0c6119663">startCodeFragment</a> (const QCString &amp;style) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe694794f2c376ae77a3f8e34f6ad103">endCodeFragment</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a844e206331cbfc112bffb3470cf77cc7">startFold</a> (int, const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae2acca6bf32650c094eab3b7ac41cd">endFold</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc120e267a5830b05030cf6c74a3d41">setRelativePath</a> (const QCString &amp;path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a> (const QCString &amp;className, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32362ad20dbefb236ea5168dfa7d6a64">m_fileName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3aad60163725943e1aab97162524e3">m_stripCodeComments</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/htmlcodegenerator/lineinfo">LineInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a> = 0</td>
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

<p>Generator for HTML code fragments.</p>

<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HtmlCodeGenerator() {#aa99b4eb5ba4f3d5e4a93b224bb9b178b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlCodeGenerator::HtmlCodeGenerator (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 715 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa99b4eb5ba4f3d5e4a93b224bb9b178b">715</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa99b4eb5ba4f3d5e4a93b224bb9b178b">HtmlCodeGenerator::HtmlCodeGenerator</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>(t), <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>(relPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:HtmlCodeGenerator()\n",(void*)this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### HtmlCodeGenerator() {#ace5b6a3e0a5a8c7a6ffcf2465302c9f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlCodeGenerator::HtmlCodeGenerator (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 710 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace5b6a3e0a5a8c7a6ffcf2465302c9f7">710</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa99b4eb5ba4f3d5e4a93b224bb9b178b">HtmlCodeGenerator::HtmlCodeGenerator</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) : <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>(t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:HtmlCodeGenerator()\n",(void*)this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ac4fea87990dd2c3eb9fe3ca6bf2c89c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputCodeIntf &gt; HtmlCodeGenerator::clone ()</td>
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



<p>Definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4fea87990dd2c3eb9fe3ca6bf2c89c9">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeIntf&gt; <a href="#ac4fea87990dd2c3eb9fe3ca6bf2c89c9">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;HtmlCodeGenerator&gt;(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">); }</span></span></div>

</div>

</div>
</div>

### codify() {#a0941dd0ea229339847ef6604ea6b8003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::codify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0941dd0ea229339847ef6604ea6b8003">726</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0941dd0ea229339847ef6604ea6b8003">HtmlCodeGenerator::codify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightComment">// only update column count</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a>(p,<a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// actually output content and keep track of m_col</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=*p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">: {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> spacesToNextTabStop = tabSize - (<a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (spacesToNextTabStop--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>&gt;=<a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a>) *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>&gt;=<a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a>) *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;amp;"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#39;"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++; </span><span class="doxyHighlightComment">// &amp;apos; is not valid XHTML</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">                     { *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">; p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">                     { *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">; p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">                     { *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;zwj;("</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                     { *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;zwj;)"</span><span class="doxyHighlight">; <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;p++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">                       *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">                       uint8_t uc = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (uc&lt;32)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">                         *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#x24"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[uc&gt;&gt;4] &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[uc&amp;0xF] &lt;&lt; </span><span class="doxyHighlightStringLiteral">";"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (uc&lt;0x80) </span><span class="doxyHighlightComment">// printable ASCII char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">                         *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// multibyte UTF-8 char</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">                         p=<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>(*<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>,p-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a>, <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a> and <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ae9de248ba9e19731fb682352dcbc1b3c">writeUTF8Char</a>.</p>


<p>Referenced by <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a> and <a href="#ab450dd921a83f6ef2535324349f6f1c1">writeTooltip</a>.</p>

</div>
</div>

### endCodeFragment() {#afe694794f2c376ae77a3f8e34f6ad103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::endCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 60 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1033 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe694794f2c376ae77a3f8e34f6ad103">1033</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afe694794f2c376ae77a3f8e34f6ad103">HtmlCodeGenerator::endCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//endCodeLine checks is there is still an open code line, if so closes it.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;&lt;!-- fragment --&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### endCodeLine() {#a2e5d792a6c236db33c8317ace6c4626f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::endCodeLine ()</td>
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



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 995 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e5d792a6c236db33c8317ace6c4626f">995</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2e5d792a6c236db33c8317ace6c4626f">HtmlCodeGenerator::endCodeLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a> == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>


<p>Referenced by <a href="#afe694794f2c376ae77a3f8e34f6ad103">endCodeFragment</a>.</p>

</div>
</div>

### endFold() {#a8ae2acca6bf32650c094eab3b7ac41cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::endFold ()</td>
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



<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1075 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ae2acca6bf32650c094eab3b7ac41cd">1075</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8ae2acca6bf32650c094eab3b7ac41cd">HtmlCodeGenerator::endFold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>) </span><span class="doxyHighlightComment">// if we have a hidden comment in a code fold, we need to end the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a>, <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### endFontClass() {#ab62059c61bf5f1b846ffb3fe1c97f736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::endFontClass ()</td>
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



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1016 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab62059c61bf5f1b846ffb3fe1c97f736">1016</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab62059c61bf5f1b846ffb3fe1c97f736">HtmlCodeGenerator::endFontClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### endSpecialComment() {#aa9118ec2f1fcd682d16bbfeadd11ed74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::endSpecialComment ()</td>
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



<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 818 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9118ec2f1fcd682d16bbfeadd11ed74">818</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa9118ec2f1fcd682d16bbfeadd11ed74">HtmlCodeGenerator::endSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//*m_t &lt;&lt; "[END]";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>.</p>

</div>
</div>

### fileName() {#a44b4f06b94e8f45f5364a3a234ad92a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlCodeGenerator::fileName ()</td>
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



<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44b4f06b94e8f45f5364a3a234ad92a4">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a32362ad20dbefb236ea5168dfa7d6a64">m_fileName</a>; }</span></span></div>

</div>


<p>Reference <a href="#a32362ad20dbefb236ea5168dfa7d6a64">m_fileName</a>.</p>


<p>Referenced by <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#a220de109bb39c3369cad7f04261d30a1">setFileName</a> and <a href="#ab450dd921a83f6ef2535324349f6f1c1">writeTooltip</a>.</p>

</div>
</div>

### setFileName() {#a220de109bb39c3369cad7f04261d30a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::setFileName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName)</td>
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



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a220de109bb39c3369cad7f04261d30a1">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a220de109bb39c3369cad7f04261d30a1">setFileName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>) { <a href="#a32362ad20dbefb236ea5168dfa7d6a64">m_fileName</a> = <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>; }</span></span></div>

</div>


<p>References <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a> and <a href="#a32362ad20dbefb236ea5168dfa7d6a64">m_fileName</a>.</p>

</div>
</div>

### setRelativePath() {#a9bc120e267a5830b05030cf6c74a3d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::setRelativePath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 721 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9bc120e267a5830b05030cf6c74a3d41">721</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9bc120e267a5830b05030cf6c74a3d41">HtmlCodeGenerator::setRelativePath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a> = path;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>.</p>

</div>
</div>

### setStripIndentAmount() {#aa7de139146f10ccf63c8527a63eb6783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::setStripIndentAmount (size_t amount)</td>
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



<p>Declaration at line 41 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 824 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7de139146f10ccf63c8527a63eb6783">824</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa7de139146f10ccf63c8527a63eb6783">HtmlCodeGenerator::setStripIndentAmount</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> amount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a> = amount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a>.</p>

</div>
</div>

### setTextStream() {#ad9589e0f726aa6dcd23464bcf609a8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::setTextStream (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
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



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9589e0f726aa6dcd23464bcf609a8fb">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad9589e0f726aa6dcd23464bcf609a8fb">setTextStream</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) { <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> = t; }</span></span></div>

</div>


<p>Reference <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### startCodeFragment() {#ab8aef00bed9d8deb56b3d9e0c6119663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::startCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1028 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8aef00bed9d8deb56b3d9e0c6119663">1028</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8aef00bed9d8deb56b3d9e0c6119663">HtmlCodeGenerator::startCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"fragment\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### startCodeLine() {#a899976eb9aee4bb9bd881e9b204cc069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::startCodeLine (int)</td>
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



<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 984 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a899976eb9aee4bb9bd881e9b204cc069">984</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a899976eb9aee4bb9bd881e9b204cc069">HtmlCodeGenerator::startCodeLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"line\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>, <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startFold() {#a844e206331cbfc112bffb3470cf77cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::startFold (int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; startMarker, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; endMarker)</td>
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



<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1041 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a844e206331cbfc112bffb3470cf77cc7">1041</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a844e206331cbfc112bffb3470cf77cc7">HtmlCodeGenerator::startFold</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;startMarker,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;endMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>) </span><span class="doxyHighlightComment">// if we have a hidden comment in a code fold, we need to end the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxLineNrStr = 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lineNumber[maxLineNrStr];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(lineNumber,maxLineNrStr,</span><span class="doxyHighlightStringLiteral">"%05d"</span><span class="doxyHighlight">,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"foldopen\" id=\"foldopen"</span><span class="doxyHighlight"> &lt;&lt; lineNumber &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\" data-start=\""</span><span class="doxyHighlight"> &lt;&lt; startMarker &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\" data-end=\""</span><span class="doxyHighlight"> &lt;&lt; endMarker &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>) </span><span class="doxyHighlightComment">// if we have a hidden comment in a code fold, we need to restart the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"line\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>, <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>.</p>

</div>
</div>

### startFontClass() {#a36c946ea34b71976fa126dd6fcb2fb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::startFontClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1010 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36c946ea34b71976fa126dd6fcb2fb02">1010</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a36c946ea34b71976fa126dd6fcb2fb02">HtmlCodeGenerator::startFontClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\""</span><span class="doxyHighlight"> &lt;&lt; s &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### startSpecialComment() {#a1c925b83a96ace6b647f17e8812749ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::startSpecialComment ()</td>
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



<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 812 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c925b83a96ace6b647f17e8812749ba">812</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c925b83a96ace6b647f17e8812749ba">HtmlCodeGenerator::startSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> = <a href="#a0d3aad60163725943e1aab97162524e3">m_stripCodeComments</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//*m_t &lt;&lt; "[START]";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> and <a href="#a0d3aad60163725943e1aab97162524e3">m_stripCodeComments</a>.</p>

</div>
</div>

### stripCodeComments() {#afe9b21b46a1623df6d59c0ccbe0c53c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::stripCodeComments (bool b)</td>
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



<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 807 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe9b21b46a1623df6d59c0ccbe0c53c6">807</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afe9b21b46a1623df6d59c0ccbe0c53c6">HtmlCodeGenerator::stripCodeComments</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0d3aad60163725943e1aab97162524e3">m_stripCodeComments</a> = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a0d3aad60163725943e1aab97162524e3">m_stripCodeComments</a>.</p>

</div>
</div>

### type() {#afee68c6253f5c9ed82886d0197d276ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType HtmlCodeGenerator::type ()</td>
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



<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afee68c6253f5c9ed82886d0197d276ef">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#afee68c6253f5c9ed82886d0197d276ef">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>; }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">Html</a>.</p>


<p>Referenced by <a href="#a833284e18308ead496c0d94f6b3f1d71">writeCodeLink</a>.</p>

</div>
</div>

### writeCodeAnchor() {#a3c6f9dce1570e8f0659c9ea6c6640720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::writeCodeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1022 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c6f9dce1570e8f0659c9ea6c6640720">1022</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3c6f9dce1570e8f0659c9ea6c6640720">HtmlCodeGenerator::writeCodeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a id=\""</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" name=\""</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>

</div>
</div>

### writeCodeLink() {#a833284e18308ead496c0d94f6b3f1d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::writeCodeLink (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
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



<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 860 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a833284e18308ead496c0d94f6b3f1d71">860</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a833284e18308ead496c0d94f6b3f1d71">HtmlCodeGenerator::writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> <a href="#afee68c6253f5c9ed82886d0197d276ef">type</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tooltip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *hl = <a href="/web-doxygen/docs/api/files/src/types-h/#a389e5ceddb8aa06e92dbb3f0de27601e">codeSymbolType2Str</a>(<a href="#afee68c6253f5c9ed82886d0197d276ef">type</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> hlClass = </span><span class="doxyHighlightStringLiteral">"code"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">    hlClass+=</span><span class="doxyHighlightStringLiteral">" hl_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">    hlClass+=hl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>(hlClass,ref,f,anchor,name,tooltip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a389e5ceddb8aa06e92dbb3f0de27601e">codeSymbolType2Str</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> and <a href="#afee68c6253f5c9ed82886d0197d276ef">type</a>.</p>

</div>
</div>

### writeLineNumber() {#a87bd505cf0e4598b8e8ae320087166f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::writeLineNumber (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; filename, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int l, bool writeLineAnchor)</td>
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



<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 829 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87bd505cf0e4598b8e8ae320087166f3">829</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a87bd505cf0e4598b8e8ae320087166f3">HtmlCodeGenerator::writeLineNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;filename,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> writeLineAnchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a> = <a href="/web-doxygen/docs/api/structs/htmlcodegenerator/lineinfo">LineInfo</a>(ref,filename,anchor,l,writeLineAnchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxLineNrStr = 10;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lineNumber[maxLineNrStr];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lineAnchor[maxLineNrStr];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(lineNumber,maxLineNrStr,</span><span class="doxyHighlightStringLiteral">"%5d"</span><span class="doxyHighlight">,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(lineAnchor,maxLineNrStr,</span><span class="doxyHighlightStringLiteral">"l%05d"</span><span class="doxyHighlight">,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"line\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (writeLineAnchor) *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a id=\""</span><span class="doxyHighlight"> &lt;&lt; lineAnchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" name=\""</span><span class="doxyHighlight"> &lt;&lt; lineAnchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;span class=\"lineno\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!filename.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>(</span><span class="doxyHighlightStringLiteral">"line"</span><span class="doxyHighlight">,ref,filename,anchor,lineNumber,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>(lineNumber);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/span&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>, <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>, <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a>.</p>

</div>
</div>

### writeTooltip() {#ab450dd921a83f6ef2535324349f6f1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::writeTooltip (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, const <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp; docInfo, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; decl, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; desc, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp; defInfo, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp; declInfo)</td>
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



<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 904 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab450dd921a83f6ef2535324349f6f1c1">904</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab450dd921a83f6ef2535324349f6f1c1">HtmlCodeGenerator::writeTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;docInfo,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;decl, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;desc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;defInfo,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;declInfo)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"ttc\" id=\""</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"ttname\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a7607f6298e3e16dd3ef26d2f823bbb9c">url</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a7607f6298e3e16dd3ef26d2f823bbb9c">url</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>(<a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>,docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#abe4bbcd9b1709f58b0b29a9020c42e42">ref</a>,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>()==fn,fn,docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a2827af934ddee422d0f8711c9889f5e8">anchor</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>(docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a92c73ddcfa2201e6b0029f4b4e64458b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a7607f6298e3e16dd3ef26d2f823bbb9c">url</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!decl.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"ttdeci\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>(decl);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!desc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"ttdoc\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>(desc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">file</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"ttdef\"&gt;&lt;b&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDefinition() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>(<a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>,defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a53631fa171fa05192c059087d66278c0">ref</a>,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>()==fn,fn,defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a3a271e40098bce60ea2d71f452be7fa6">anchor</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">file</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight"> &lt;&lt; defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#abff71a239d4a657ea1543c0426b5726c">line</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">file</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"ttdecl\"&gt;&lt;b&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDeclaration() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/b&gt; "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>(<a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>,declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a53631fa171fa05192c059087d66278c0">ref</a>,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>()==fn,fn,declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a3a271e40098bce60ea2d71f452be7fa6">anchor</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">file</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight"> &lt;&lt; declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#abff71a239d4a657ea1543c0426b5726c">line</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!declInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#a2827af934ddee422d0f8711c9889f5e8">DocLinkInfo::anchor</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a3a271e40098bce60ea2d71f452be7fa6">SourceLinkInfo::anchor</a>, <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">SourceLinkInfo::file</a>, <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#abff71a239d4a657ea1543c0426b5726c">SourceLinkInfo::line</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>, <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#a92c73ddcfa2201e6b0029f4b4e64458b">DocLinkInfo::name</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#abe4bbcd9b1709f58b0b29a9020c42e42">DocLinkInfo::ref</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a53631fa171fa05192c059087d66278c0">SourceLinkInfo::ref</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#a7607f6298e3e16dd3ef26d2f823bbb9c">DocLinkInfo::url</a> and <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">SourceLinkInfo::url</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### \_startOpenLine() {#ae3ec37310a697018215b582fe59c7e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::_startOpenLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 1061 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3ec37310a697018215b582fe59c7e12">1061</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3ec37310a697018215b582fe59c7e12">HtmlCodeGenerator::_startOpenLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"line\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> wasHidden=<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a>(<a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>.ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>.fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>.anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>.line+1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>.writeAnchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> = wasHidden;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>, <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a>, <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> and <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a>.</p>


<p>Referenced by <a href="#a8ae2acca6bf32650c094eab3b7ac41cd">endFold</a>.</p>

</div>
</div>

### \_writeCodeLink() {#a93bbb9cd89a6d58d81a9796597e79fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlCodeGenerator::_writeCodeLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; className, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>, definition at line 876 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93bbb9cd89a6d58d81a9796597e79fb9">876</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">HtmlCodeGenerator::_writeCodeLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;className,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tooltip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>+=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\""</span><span class="doxyHighlight"> &lt;&lt; className &lt;&lt; </span><span class="doxyHighlightStringLiteral">"Ref\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;a class=\""</span><span class="doxyHighlight"> &lt;&lt; className &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>(<a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>,ref,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>()==fn,fn,anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tooltip.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" title=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(tooltip) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/a&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#affffe2fa50a969f0c573d8a467deb31b">createHtmlUrl</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a>, <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a>, <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a> and <a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>.</p>


<p>Referenced by <a href="#a833284e18308ead496c0d94f6b3f1d71">writeCodeLink</a> and <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_col {#af93c801b64ebb983dd0a52eb623dce64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t HtmlCodeGenerator::m_col = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af93c801b64ebb983dd0a52eb623dce64">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#af93c801b64ebb983dd0a52eb623dce64">m_col</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>, <a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a>, <a href="#a899976eb9aee4bb9bd881e9b204cc069">startCodeLine</a> and <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a>.</p>

</div>
</div>

### m\_fileName {#a32362ad20dbefb236ea5168dfa7d6a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlCodeGenerator::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32362ad20dbefb236ea5168dfa7d6a64">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a32362ad20dbefb236ea5168dfa7d6a64">m_fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a44b4f06b94e8f45f5364a3a234ad92a4">fileName</a> and <a href="#a220de109bb39c3369cad7f04261d30a1">setFileName</a>.</p>

</div>
</div>

### m\_hide {#a96f238a9c348cd9c92a11f447b1999ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HtmlCodeGenerator::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96f238a9c348cd9c92a11f447b1999ae">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a96f238a9c348cd9c92a11f447b1999ae">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a>, <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>, <a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a>, <a href="#ab62059c61bf5f1b846ffb3fe1c97f736">endFontClass</a>, <a href="#aa9118ec2f1fcd682d16bbfeadd11ed74">endSpecialComment</a>, <a href="#a899976eb9aee4bb9bd881e9b204cc069">startCodeLine</a>, <a href="#a844e206331cbfc112bffb3470cf77cc7">startFold</a>, <a href="#a36c946ea34b71976fa126dd6fcb2fb02">startFontClass</a>, <a href="#a1c925b83a96ace6b647f17e8812749ba">startSpecialComment</a>, <a href="#a3c6f9dce1570e8f0659c9ea6c6640720">writeCodeAnchor</a>, <a href="#a833284e18308ead496c0d94f6b3f1d71">writeCodeLink</a>, <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a> and <a href="#ab450dd921a83f6ef2535324349f6f1c1">writeTooltip</a>.</p>

</div>
</div>

### m\_lastLineInfo {#afe5815ad622f13173eac838e1b85f73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LineInfo HtmlCodeGenerator::m_lastLineInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe5815ad622f13173eac838e1b85f73c">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/htmlcodegenerator/lineinfo">LineInfo</a> <a href="#afe5815ad622f13173eac838e1b85f73c">m_lastLineInfo</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a> and <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a>.</p>

</div>
</div>

### m\_lineOpen {#a70013bc13c93e0eacaaed91618a24501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HtmlCodeGenerator::m_lineOpen = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70013bc13c93e0eacaaed91618a24501">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a70013bc13c93e0eacaaed91618a24501">m_lineOpen</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a>, <a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a>, <a href="#a8ae2acca6bf32650c094eab3b7ac41cd">endFold</a>, <a href="#a899976eb9aee4bb9bd881e9b204cc069">startCodeLine</a>, <a href="#a844e206331cbfc112bffb3470cf77cc7">startFold</a> and <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a>.</p>

</div>
</div>

### m\_relPath {#a80720eb841d423de493dda614c8fed50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlCodeGenerator::m_relPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80720eb841d423de493dda614c8fed50">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a80720eb841d423de493dda614c8fed50">m_relPath</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#aa99b4eb5ba4f3d5e4a93b224bb9b178b">HtmlCodeGenerator</a>, <a href="#a9bc120e267a5830b05030cf6c74a3d41">setRelativePath</a> and <a href="#ab450dd921a83f6ef2535324349f6f1c1">writeTooltip</a>.</p>

</div>
</div>

### m\_stripCodeComments {#a0d3aad60163725943e1aab97162524e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HtmlCodeGenerator::m_stripCodeComments = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d3aad60163725943e1aab97162524e3">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0d3aad60163725943e1aab97162524e3">m_stripCodeComments</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a1c925b83a96ace6b647f17e8812749ba">startSpecialComment</a> and <a href="#afe9b21b46a1623df6d59c0ccbe0c53c6">stripCodeComments</a>.</p>

</div>
</div>

### m\_stripIndentAmount {#a52afd41d498a9cfaa87b4d834058ff48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t HtmlCodeGenerator::m_stripIndentAmount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52afd41d498a9cfaa87b4d834058ff48">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a52afd41d498a9cfaa87b4d834058ff48">m_stripIndentAmount</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a> and <a href="#aa7de139146f10ccf63c8527a63eb6783">setStripIndentAmount</a>.</p>

</div>
</div>

### m\_t {#ad79a609c97a096252ad170efaa5f5e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream* HtmlCodeGenerator::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad79a609c97a096252ad170efaa5f5e9c">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *<a href="#ad79a609c97a096252ad170efaa5f5e9c">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae3ec37310a697018215b582fe59c7e12">_startOpenLine</a>, <a href="#a93bbb9cd89a6d58d81a9796597e79fb9">_writeCodeLink</a>, <a href="#a0941dd0ea229339847ef6604ea6b8003">codify</a>, <a href="#afe694794f2c376ae77a3f8e34f6ad103">endCodeFragment</a>, <a href="#a2e5d792a6c236db33c8317ace6c4626f">endCodeLine</a>, <a href="#a8ae2acca6bf32650c094eab3b7ac41cd">endFold</a>, <a href="#ab62059c61bf5f1b846ffb3fe1c97f736">endFontClass</a>, <a href="#ace5b6a3e0a5a8c7a6ffcf2465302c9f7">HtmlCodeGenerator</a>, <a href="#aa99b4eb5ba4f3d5e4a93b224bb9b178b">HtmlCodeGenerator</a>, <a href="#ad9589e0f726aa6dcd23464bcf609a8fb">setTextStream</a>, <a href="#ab8aef00bed9d8deb56b3d9e0c6119663">startCodeFragment</a>, <a href="#a899976eb9aee4bb9bd881e9b204cc069">startCodeLine</a>, <a href="#a844e206331cbfc112bffb3470cf77cc7">startFold</a>, <a href="#a36c946ea34b71976fa126dd6fcb2fb02">startFontClass</a>, <a href="#a3c6f9dce1570e8f0659c9ea6c6640720">writeCodeAnchor</a>, <a href="#a87bd505cf0e4598b8e8ae320087166f3">writeLineNumber</a> and <a href="#ab450dd921a83f6ef2535324349f6f1c1">writeTooltip</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlgen-cpp">htmlgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
