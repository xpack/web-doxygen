---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docbookcodegenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocbookCodeGenerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class DocbookCodeGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docbookgen-h">src/docbookgen.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4431643d4f46ebaeac457c97972501d6">DocbookCodeGenerator</a> (TextStream *t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf393050531556f10b6f1f56bc418555">setTextStream</a> (TextStream *t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac743a3012223769c891bf492df78ff94">type</a> () const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac502da99b2bbd97edc273ecf3965ad37">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ccf1a3b7b5c57e2321301a36250d918">stripCodeComments</a> (bool b) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8605e43fe00b5cf05de1e5fc83b1fb">startSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace343b1b542c4e21b4a94eafca30fa3a">endSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb40fdc605009b4c5d9c65471c76ca75">setStripIndentAmount</a> (size_t amount) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d4a8f26f5daff4ffb1702f24b35697">writeCodeLink</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbcce024dec33fe27f6d4eaa4c1e3c1">writeTooltip</a> (const QCString &amp;, const DocLinkInfo &amp;, const QCString &amp;, const QCString &amp;, const SourceLinkInfo &amp;, const SourceLinkInfo &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaaaa54a0aec67674d41d61bef0f2a2b">startCodeLine</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd8cfddee95768c329a3c284c4ede9f">startFontClass</a> (const QCString &amp;colorClass) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d035c6d2cb17becc47cf8a25764e1a8">endFontClass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889f1558d0b0638e9fc8d1bf051ec1d0">writeCodeAnchor</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a> (const QCString &amp;extRef, const QCString &amp;compId, const QCString &amp;anchorId, int l, bool writeLineAnchor) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac180046d6b800198aa9b41e964e78d">startCodeFragment</a> (const QCString &amp;style) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfd30b3411a87069f1f0e8e8cb31708">endCodeFragment</a> (const QCString &amp;style) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b1e35ba9bd4535403cb63aefa41ab5">startFold</a> (int, const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2b1b6fa4bd9afee3ddcf679affd624">endFold</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831a2985374b5c317e9778c12f4fc7b4">setRelativePath</a> (const QCString &amp;path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6e2bf360ffa9f8f14c457405273d4c0">setSourceFileName</a> (const QCString &amp;sourceFileName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab495ebcb45b5e583da811c8d7d02599a">sourceFileName</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab587badbb22f04c80d79fd6bf0b69b9a">finish</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada73fe6def10a3e449256fc96929e8b2">writeCodeLinkLine</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip, bool)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46241908135ae139616266510f569d75">m_refId</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac00ed89685c510a7a0c97366ba1c40">m_external</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370944cca11dccabf9887d3bd6c00a9b">m_lineNumber</a> = -1</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af499b4de75488065fce50243bc944fd2">m_insideSpecialHL</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0a45a3c1f211abf95b25311db49b84">m_relPath</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf4ba4b85110ada9f9ca1148b918db9e">m_stripCodeComments</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49e81624375512b4bde1d521968c2167">m_stripIndentAmount</a> = 0</td>
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


<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocbookCodeGenerator() {#a4431643d4f46ebaeac457c97972501d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookCodeGenerator::DocbookCodeGenerator (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4431643d4f46ebaeac457c97972501d6">162</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a4431643d4f46ebaeac457c97972501d6">DocbookCodeGenerator::DocbookCodeGenerator</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) : <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>(t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ac502da99b2bbd97edc273ecf3965ad37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputCodeIntf &gt; DocbookCodeGenerator::clone ()</td>
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



<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac502da99b2bbd97edc273ecf3965ad37">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeIntf&gt; <a href="#ac502da99b2bbd97edc273ecf3965ad37">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;DocbookCodeGenerator&gt;(<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>); }</span></span></div>

</div>


<p>Reference <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>

</div>
</div>

### codify() {#ada15c258bd04d178eb923ca8de03ad5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::codify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada15c258bd04d178eb923ca8de03ad5f">166</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ada15c258bd04d178eb923ca8de03ad5f">DocbookCodeGenerator::codify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(codify \"%s\")\n"</span><span class="doxyHighlight">,text));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a>(<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>,*<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>,text,<a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a49e81624375512b4bde1d521968c2167">m_stripIndentAmount</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#a49e81624375512b4bde1d521968c2167">m_stripIndentAmount</a>, <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> and <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a>.</p>


<p>Referenced by <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

### endCodeFragment() {#a1dfd30b3411a87069f1f0e8e8cb31708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::endCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Declaration at line 75 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 308 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1dfd30b3411a87069f1f0e8e8cb31708">308</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1dfd30b3411a87069f1f0e8e8cb31708">DocbookCodeGenerator::endCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aad86f7a60609e9852bce76f5a1626d5a">DB_GEN_C1</a>(*<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//endCodeLine checks is there is still an open code line, if so closes it.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aad86f7a60609e9852bce76f5a1626d5a">DB_GEN_C1</a>, <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a> and <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>

</div>
</div>

### endCodeLine() {#acca93adef4af10baa753afe68846138a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::endCodeLine ()</td>
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



<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acca93adef4af10baa753afe68846138a">233</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acca93adef4af10baa753afe68846138a">DocbookCodeGenerator::endCodeLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a>) *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(endCodeLine)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a370944cca11dccabf9887d3bd6c00a9b">m_lineNumber</a> = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a46241908135ae139616266510f569d75">m_refId</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0ac00ed89685c510a7a0c97366ba1c40">m_external</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a0ac00ed89685c510a7a0c97366ba1c40">m_external</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a>, <a href="#a370944cca11dccabf9887d3bd6c00a9b">m_lineNumber</a>, <a href="#a46241908135ae139616266510f569d75">m_refId</a> and <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>


<p>Referenced by <a href="#a1dfd30b3411a87069f1f0e8e8cb31708">endCodeFragment</a> and <a href="#ab587badbb22f04c80d79fd6bf0b69b9a">finish</a>.</p>

</div>
</div>

### endFold() {#a4f2b1b6fa4bd9afee3ddcf679affd624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::endFold ()</td>
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



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f2b1b6fa4bd9afee3ddcf679affd624">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4f2b1b6fa4bd9afee3ddcf679affd624">endFold</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### endFontClass() {#a1d035c6d2cb17becc47cf8a25764e1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::endFontClass ()</td>
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



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d035c6d2cb17becc47cf8a25764e1a8">252</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d035c6d2cb17becc47cf8a25764e1a8">DocbookCodeGenerator::endFontClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(endFontClass)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// non DocBook</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af499b4de75488065fce50243bc944fd2">m_insideSpecialHL</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#af499b4de75488065fce50243bc944fd2">m_insideSpecialHL</a> and <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>

</div>
</div>

### endSpecialComment() {#ace343b1b542c4e21b4a94eafca30fa3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::endSpecialComment ()</td>
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



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace343b1b542c4e21b4a94eafca30fa3a">182</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ace343b1b542c4e21b4a94eafca30fa3a">DocbookCodeGenerator::endSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>.</p>

</div>
</div>

### finish() {#ab587badbb22f04c80d79fd6bf0b69b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::finish ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab587badbb22f04c80d79fd6bf0b69b9a">297</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab587badbb22f04c80d79fd6bf0b69b9a">DocbookCodeGenerator::finish</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>.</p>

</div>
</div>

### setRelativePath() {#a831a2985374b5c317e9778c12f4fc7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::setRelativePath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
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



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a831a2985374b5c317e9778c12f4fc7b4">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a831a2985374b5c317e9778c12f4fc7b4">setRelativePath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path) { <a href="#a4a0a45a3c1f211abf95b25311db49b84">m_relPath</a> = path; }</span></span></div>

</div>


<p>Reference <a href="#a4a0a45a3c1f211abf95b25311db49b84">m_relPath</a>.</p>

</div>
</div>

### setSourceFileName() {#ab6e2bf360ffa9f8f14c457405273d4c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::setSourceFileName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sourceFileName)</td>
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



<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6e2bf360ffa9f8f14c457405273d4c0">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab6e2bf360ffa9f8f14c457405273d4c0">setSourceFileName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#ab495ebcb45b5e583da811c8d7d02599a">sourceFileName</a>) { <a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a> = <a href="#ab495ebcb45b5e583da811c8d7d02599a">sourceFileName</a>; }</span></span></div>

</div>


<p>References <a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a> and <a href="#ab495ebcb45b5e583da811c8d7d02599a">sourceFileName</a>.</p>

</div>
</div>

### setStripIndentAmount() {#adb40fdc605009b4c5d9c65471c76ca75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::setStripIndentAmount (size_t amount)</td>
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



<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb40fdc605009b4c5d9c65471c76ca75">187</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adb40fdc605009b4c5d9c65471c76ca75">DocbookCodeGenerator::setStripIndentAmount</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> amount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a49e81624375512b4bde1d521968c2167">m_stripIndentAmount</a> = amount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a49e81624375512b4bde1d521968c2167">m_stripIndentAmount</a>.</p>

</div>
</div>

### setTextStream() {#adf393050531556f10b6f1f56bc418555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::setTextStream (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
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



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf393050531556f10b6f1f56bc418555">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adf393050531556f10b6f1f56bc418555">setTextStream</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) { <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> = t; }</span></span></div>

</div>


<p>Reference <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>

</div>
</div>

### sourceFileName() {#ab495ebcb45b5e583da811c8d7d02599a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookCodeGenerator::sourceFileName ()</td>
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



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab495ebcb45b5e583da811c8d7d02599a">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab495ebcb45b5e583da811c8d7d02599a">sourceFileName</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a>; }</span></span></div>

</div>


<p>Reference <a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a>.</p>


<p>Referenced by <a href="#ab6e2bf360ffa9f8f14c457405273d4c0">setSourceFileName</a>.</p>

</div>
</div>

### startCodeFragment() {#afac180046d6b800198aa9b41e964e78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::startCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 302 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afac180046d6b800198aa9b41e964e78d">302</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afac180046d6b800198aa9b41e964e78d">DocbookCodeGenerator::startCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aad86f7a60609e9852bce76f5a1626d5a">DB_GEN_C1</a>(*<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting linenumbering=\"unnumbered\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aad86f7a60609e9852bce76f5a1626d5a">DB_GEN_C1</a> and <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>.</p>

</div>
</div>

### startCodeLine() {#adaaaa54a0aec67674d41d61bef0f2a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::startCodeLine (int)</td>
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



<p>Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adaaaa54a0aec67674d41d61bef0f2a2b">225</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adaaaa54a0aec67674d41d61bef0f2a2b">DocbookCodeGenerator::startCodeLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(startCodeLine)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startFold() {#a26b1e35ba9bd4535403cb63aefa41ab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::startFold (int, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a26b1e35ba9bd4535403cb63aefa41ab5">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a26b1e35ba9bd4535403cb63aefa41ab5">startFold</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startFontClass() {#adcd8cfddee95768c329a3c284c4ede9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::startFontClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; colorClass)</td>
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



<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adcd8cfddee95768c329a3c284c4ede9f">244</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adcd8cfddee95768c329a3c284c4ede9f">DocbookCodeGenerator::startFontClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;colorClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(startFontClass)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;emphasis role=\""</span><span class="doxyHighlight"> &lt;&lt; colorClass &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af499b4de75488065fce50243bc944fd2">m_insideSpecialHL</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#af499b4de75488065fce50243bc944fd2">m_insideSpecialHL</a>, <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startSpecialComment() {#aca8605e43fe00b5cf05de1e5fc83b1fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::startSpecialComment ()</td>
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



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca8605e43fe00b5cf05de1e5fc83b1fb">177</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aca8605e43fe00b5cf05de1e5fc83b1fb">DocbookCodeGenerator::startSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a> = <a href="#acf4ba4b85110ada9f9ca1148b918db9e">m_stripCodeComments</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a> and <a href="#acf4ba4b85110ada9f9ca1148b918db9e">m_stripCodeComments</a>.</p>

</div>
</div>

### stripCodeComments() {#a7ccf1a3b7b5c57e2321301a36250d918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::stripCodeComments (bool b)</td>
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



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ccf1a3b7b5c57e2321301a36250d918">172</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7ccf1a3b7b5c57e2321301a36250d918">DocbookCodeGenerator::stripCodeComments</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf4ba4b85110ada9f9ca1148b918db9e">m_stripCodeComments</a> = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#acf4ba4b85110ada9f9ca1148b918db9e">m_stripCodeComments</a>.</p>

</div>
</div>

### type() {#ac743a3012223769c891bf492df78ff94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType DocbookCodeGenerator::type ()</td>
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



<p>Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac743a3012223769c891bf492df78ff94">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#ac743a3012223769c891bf492df78ff94">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">OutputType::Docbook</a>; }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">Docbook</a>.</p>

</div>
</div>

### writeCodeAnchor() {#a889f1558d0b0638e9fc8d1bf051ec1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::writeCodeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 260 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a889f1558d0b0638e9fc8d1bf051ec1d0">260</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a889f1558d0b0638e9fc8d1bf051ec1d0">DocbookCodeGenerator::writeCodeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeCodeAnchor)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>.</p>

</div>
</div>

### writeCodeLink() {#ac0d4a8f26f5daff4ffb1702f24b35697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::writeCodeLink (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
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



<p>Declaration at line 60 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0d4a8f26f5daff4ffb1702f24b35697">192</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac0d4a8f26f5daff4ffb1702f24b35697">DocbookCodeGenerator::writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tooltip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeCodeLink)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a748b4a218a6a5cd91bd9fdcf939b9c3c">writeDocbookLink</a>(*<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>,ref,file,anchor,name,tooltip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>+=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> and <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a748b4a218a6a5cd91bd9fdcf939b9c3c">writeDocbookLink</a>.</p>


<p>Referenced by <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

### writeLineNumber() {#ae3e188b81cd05fbb4e12621850e7d5e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::writeLineNumber (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extRef, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; compId, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchorId, int l, bool writeLineAnchor)</td>
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



<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3e188b81cd05fbb4e12621850e7d5e4">265</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">DocbookCodeGenerator::writeLineNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> writeLineAnchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeLineNumber)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SOURCE_BROWSER))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineNumber;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNumber.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%05d"</span><span class="doxyHighlight">,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ada73fe6def10a3e449256fc96929e8b2">writeCodeLinkLine</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843ca7a1920d61156abc05a60135aefe8bc67">CodeSymbolType::Default</a>,ref,<a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a>,anchor,lineNumber,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),writeLineAnchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac0d4a8f26f5daff4ffb1702f24b35697">writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843ca7a1920d61156abc05a60135aefe8bc67">CodeSymbolType::Default</a>,ref,fileName,anchor,lineNumber,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a>(lineNumber);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; l &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843ca7a1920d61156abc05a60135aefe8bc67">Default</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a>, <a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a>, <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="#ac0d4a8f26f5daff4ffb1702f24b35697">writeCodeLink</a> and <a href="#ada73fe6def10a3e449256fc96929e8b2">writeCodeLinkLine</a>.</p>

</div>
</div>

### writeTooltip() {#adfbcce024dec33fe27f6d4eaa4c1e3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::writeTooltip (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;)</td>
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



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfbcce024dec33fe27f6d4eaa4c1e3c1">218</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adfbcce024dec33fe27f6d4eaa4c1e3c1">DocbookCodeGenerator::writeTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">                 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeToolTip)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### writeCodeLinkLine() {#ada73fe6def10a3e449256fc96929e8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookCodeGenerator::writeCodeLinkLine (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip, bool writeLineAnchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 203 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada73fe6def10a3e449256fc96929e8b2">203</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ada73fe6def10a3e449256fc96929e8b2">DocbookCodeGenerator::writeCodeLinkLine</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> writeLineAnchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeCodeLinkLine)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!writeLineAnchor) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;anchor xml:id=\"_"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(file),</span><span class="doxyHighlightStringLiteral">".xml"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1l"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a>(*<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>+=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a>, <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a>, <a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a>.</p>


<p>Referenced by <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_col {#abe315b85fba0294c287bcbbfaa437e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocbookCodeGenerator::m_col = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe315b85fba0294c287bcbbfaa437e71">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">      <a href="#abe315b85fba0294c287bcbbfaa437e71">m_col</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a>, <a href="#adaaaa54a0aec67674d41d61bef0f2a2b">startCodeLine</a>, <a href="#ac0d4a8f26f5daff4ffb1702f24b35697">writeCodeLink</a>, <a href="#ada73fe6def10a3e449256fc96929e8b2">writeCodeLinkLine</a> and <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

### m\_external {#a0ac00ed89685c510a7a0c97366ba1c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookCodeGenerator::m_external</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ac00ed89685c510a7a0c97366ba1c40">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>    <a href="#a0ac00ed89685c510a7a0c97366ba1c40">m_external</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>.</p>

</div>
</div>

### m\_hide {#acc4efc64f554a704a808c88ea0a958fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookCodeGenerator::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc4efc64f554a704a808c88ea0a958fa">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">        <a href="#acc4efc64f554a704a808c88ea0a958fa">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a>, <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>, <a href="#a1d035c6d2cb17becc47cf8a25764e1a8">endFontClass</a>, <a href="#ace343b1b542c4e21b4a94eafca30fa3a">endSpecialComment</a>, <a href="#adaaaa54a0aec67674d41d61bef0f2a2b">startCodeLine</a>, <a href="#adcd8cfddee95768c329a3c284c4ede9f">startFontClass</a>, <a href="#aca8605e43fe00b5cf05de1e5fc83b1fb">startSpecialComment</a>, <a href="#ac0d4a8f26f5daff4ffb1702f24b35697">writeCodeLink</a>, <a href="#ada73fe6def10a3e449256fc96929e8b2">writeCodeLinkLine</a> and <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

### m\_insideCodeLine {#ac67a3dfb9373872b5ae97f7a9ae6873f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookCodeGenerator::m_insideCodeLine = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">        <a href="#ac67a3dfb9373872b5ae97f7a9ae6873f">m_insideCodeLine</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>, <a href="#adaaaa54a0aec67674d41d61bef0f2a2b">startCodeLine</a> and <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

### m\_insideSpecialHL {#af499b4de75488065fce50243bc944fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookCodeGenerator::m_insideSpecialHL = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af499b4de75488065fce50243bc944fd2">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">        <a href="#af499b4de75488065fce50243bc944fd2">m_insideSpecialHL</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a1d035c6d2cb17becc47cf8a25764e1a8">endFontClass</a> and <a href="#adcd8cfddee95768c329a3c284c4ede9f">startFontClass</a>.</p>

</div>
</div>

### m\_lineNumber {#a370944cca11dccabf9887d3bd6c00a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocbookCodeGenerator::m_lineNumber = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a370944cca11dccabf9887d3bd6c00a9b">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">         <a href="#a370944cca11dccabf9887d3bd6c00a9b">m_lineNumber</a> = -1;</span></span></div>

</div>


<p>Referenced by <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>.</p>

</div>
</div>

### m\_refId {#a46241908135ae139616266510f569d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookCodeGenerator::m_refId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46241908135ae139616266510f569d75">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>    <a href="#a46241908135ae139616266510f569d75">m_refId</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>.</p>

</div>
</div>

### m\_relPath {#a4a0a45a3c1f211abf95b25311db49b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookCodeGenerator::m_relPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a0a45a3c1f211abf95b25311db49b84">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>    <a href="#a4a0a45a3c1f211abf95b25311db49b84">m_relPath</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a831a2985374b5c317e9778c12f4fc7b4">setRelativePath</a>.</p>

</div>
</div>

### m\_sourceFileName {#af923797762d09a952aee6ee016867ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookCodeGenerator::m_sourceFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af923797762d09a952aee6ee016867ead">97</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>    <a href="#af923797762d09a952aee6ee016867ead">m_sourceFileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab6e2bf360ffa9f8f14c457405273d4c0">setSourceFileName</a>, <a href="#ab495ebcb45b5e583da811c8d7d02599a">sourceFileName</a> and <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

### m\_stripCodeComments {#acf4ba4b85110ada9f9ca1148b918db9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookCodeGenerator::m_stripCodeComments = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf4ba4b85110ada9f9ca1148b918db9e">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">        <a href="#acf4ba4b85110ada9f9ca1148b918db9e">m_stripCodeComments</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#aca8605e43fe00b5cf05de1e5fc83b1fb">startSpecialComment</a> and <a href="#a7ccf1a3b7b5c57e2321301a36250d918">stripCodeComments</a>.</p>

</div>
</div>

### m\_stripIndentAmount {#a49e81624375512b4bde1d521968c2167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocbookCodeGenerator::m_stripIndentAmount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49e81624375512b4bde1d521968c2167">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">      <a href="#a49e81624375512b4bde1d521968c2167">m_stripIndentAmount</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a> and <a href="#adb40fdc605009b4c5d9c65471c76ca75">setStripIndentAmount</a>.</p>

</div>
</div>

### m\_t {#a6e99049cce2532fbf0c2779e599d744c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream* DocbookCodeGenerator::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e99049cce2532fbf0c2779e599d744c">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *<a href="#a6e99049cce2532fbf0c2779e599d744c">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac502da99b2bbd97edc273ecf3965ad37">clone</a>, <a href="#ada15c258bd04d178eb923ca8de03ad5f">codify</a>, <a href="#a4431643d4f46ebaeac457c97972501d6">DocbookCodeGenerator</a>, <a href="#a1dfd30b3411a87069f1f0e8e8cb31708">endCodeFragment</a>, <a href="#acca93adef4af10baa753afe68846138a">endCodeLine</a>, <a href="#a1d035c6d2cb17becc47cf8a25764e1a8">endFontClass</a>, <a href="#adf393050531556f10b6f1f56bc418555">setTextStream</a>, <a href="#afac180046d6b800198aa9b41e964e78d">startCodeFragment</a>, <a href="#adcd8cfddee95768c329a3c284c4ede9f">startFontClass</a>, <a href="#ac0d4a8f26f5daff4ffb1702f24b35697">writeCodeLink</a>, <a href="#ada73fe6def10a3e449256fc96929e8b2">writeCodeLinkLine</a> and <a href="#ae3e188b81cd05fbb4e12621850e7d5e4">writeLineNumber</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
