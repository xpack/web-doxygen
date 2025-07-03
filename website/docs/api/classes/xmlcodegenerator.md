---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/xmlcodegenerator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `XMLCodeGenerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class XMLCodeGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/xmlgen-h">src/xmlgen.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae566a902bea279e24182706618efa6a1">XMLCodeGenerator</a> (TextStream *t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1161113df26f973d35819d346c52830f">type</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for producing XML formatted source code. <a href="#a17dd450e496129d67a0208dc421cfd1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3880c26431032448d23e87fd9a9249">stripCodeComments</a> (bool b) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4a64e216077efd517bd7104d59f406">startSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce729ca852a0d77ec9fb6d3aecc554f">endSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135b16eab3b231e381293243dff571a0">setStripIndentAmount</a> (size_t amount) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81ef99c08abac9fb0b86d12f1513550">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0892bdfdb6f093026e4b3437d98c76a5">writeTooltip</a> (const QCString &amp;, const DocLinkInfo &amp;, const QCString &amp;, const QCString &amp;, const SourceLinkInfo &amp;, const SourceLinkInfo &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">startFontClass</a> (const QCString &amp;colorClass) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73db4a6021fb7e1a49ffed5931bead5">endFontClass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3abeec4466c2fd8b4abd70e6465c4ec">writeCodeAnchor</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac332610fed5a983f3b5e012c1fcddef">writeLineNumber</a> (const QCString &amp;extRef, const QCString &amp;compId, const QCString &amp;anchorId, int l, bool writeLineAnchor) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd0e0660e9f1ba00aa9202d90b632a9">startCodeFragment</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8336886fd5704ed637f7e789dda4a2b">endCodeFragment</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047269c60059b0993a62559b002b746d">startFold</a> (int, const QCString &amp;, const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8364c335f851dd813eab9343e20605">endFold</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28def93f4623a2788f74a072a6a72a7d">finish</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a> = -1</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">m_isMemberRef</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a> = true</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0beff851b3e2185134d8f7e490ca957">m_stripCodeComments</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bea8dabe5f8613353769398c42a21c6">m_stripIndentAmount</a> = 0</td>
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


<p>Definition at line 20 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### XMLCodeGenerator() {#ae566a902bea279e24182706618efa6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLCodeGenerator::XMLCodeGenerator (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> * t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae566a902bea279e24182706618efa6a1">201</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ae566a902bea279e24182706618efa6a1">XMLCodeGenerator::XMLCodeGenerator</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *t) : <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>(t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#af81ef99c08abac9fb0b86d12f1513550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputCodeIntf &gt; XMLCodeGenerator::clone ()</td>
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



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af81ef99c08abac9fb0b86d12f1513550">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeIntf&gt; <a href="#af81ef99c08abac9fb0b86d12f1513550">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;XMLCodeGenerator&gt;(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">); }</span></span></div>

</div>

</div>
</div>

### codify() {#a17dd450e496129d67a0208dc421cfd1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::codify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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

<p>Generator for producing XML formatted source code.</p>

<p>Declaration at line 27 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 206 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17dd450e496129d67a0208dc421cfd1c">206</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a17dd450e496129d67a0208dc421cfd1c">XMLCodeGenerator::codify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(codify \"%s\")\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(text)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> &amp;&amp; <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a> &amp;&amp; !<a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a> &amp;&amp; <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;highlight class=\"normal\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ada36c272aa3f598b74e0acb33b19b860">writeXMLCodeString</a>(<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>,*<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>,text,<a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>,<a href="#a1bea8dabe5f8613353769398c42a21c6">m_stripIndentAmount</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>, <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>, <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>, <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>, <a href="#a1bea8dabe5f8613353769398c42a21c6">m_stripIndentAmount</a>, <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ada36c272aa3f598b74e0acb33b19b860">writeXMLCodeString</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### endCodeFragment() {#ad8336886fd5704ed637f7e789dda4a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::endCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 367 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8336886fd5704ed637f7e789dda4a2b">367</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad8336886fd5704ed637f7e789dda4a2b">XMLCodeGenerator::endCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(endCodeFragment)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/programlisting&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### endCodeLine() {#a1ae221fa179fd6cb57ffc68bbefaee49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::endCodeLine ()</td>
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



<p>Declaration at line 41 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 292 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ae221fa179fd6cb57ffc68bbefaee49">292</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">XMLCodeGenerator::endCodeLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(endCodeLine)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a> &amp;&amp; !<a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/highlight&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/codeline&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a> = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>, <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>, <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>, <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a>, <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>, <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>, <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>


<p>Referenced by <a href="#a28def93f4623a2788f74a072a6a72a7d">finish</a>.</p>

</div>
</div>

### endFold() {#a6d8364c335f851dd813eab9343e20605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::endFold ()</td>
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



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d8364c335f851dd813eab9343e20605">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d8364c335f851dd813eab9343e20605">endFold</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### endFontClass() {#ae73db4a6021fb7e1a49ffed5931bead5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::endFontClass ()</td>
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



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 324 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae73db4a6021fb7e1a49ffed5931bead5">324</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae73db4a6021fb7e1a49ffed5931bead5">XMLCodeGenerator::endFontClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(endFontClass)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/highlight&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// non DocBook</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>, <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### endSpecialComment() {#a6ce729ca852a0d77ec9fb6d3aecc554f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::endSpecialComment ()</td>
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



<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 222 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ce729ca852a0d77ec9fb6d3aecc554f">222</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6ce729ca852a0d77ec9fb6d3aecc554f">XMLCodeGenerator::endSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>.</p>

</div>
</div>

### finish() {#a28def93f4623a2788f74a072a6a72a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::finish ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 355 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28def93f4623a2788f74a072a6a72a7d">355</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a28def93f4623a2788f74a072a6a72a7d">XMLCodeGenerator::finish</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(finish insideCodeLine=%d)\n"</span><span class="doxyHighlight">,<a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>) <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### setStripIndentAmount() {#a135b16eab3b231e381293243dff571a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::setStripIndentAmount (size_t amount)</td>
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



<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a135b16eab3b231e381293243dff571a0">232</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a135b16eab3b231e381293243dff571a0">XMLCodeGenerator::setStripIndentAmount</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> amount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1bea8dabe5f8613353769398c42a21c6">m_stripIndentAmount</a> = amount;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a1bea8dabe5f8613353769398c42a21c6">m_stripIndentAmount</a>.</p>

</div>
</div>

### startCodeFragment() {#affd0e0660e9f1ba00aa9202d90b632a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::startCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 361 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#affd0e0660e9f1ba00aa9202d90b632a9">361</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#affd0e0660e9f1ba00aa9202d90b632a9">XMLCodeGenerator::startCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(startCodeFragment)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;programlisting&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### startCodeLine() {#a2e1224334cbe5cfe794c31eeaf4bbc57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::startCodeLine (int)</td>
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



<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">261</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">XMLCodeGenerator::startCodeLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(startCodeLine)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;codeline"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a>!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" lineno=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" refid=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">m_isMemberRef</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">        *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" refkind=\"member\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">        *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" refkind=\"compound\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" external=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>, <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>, <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>, <a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">m_isMemberRef</a>, <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a>, <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>, <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### startFold() {#a047269c60059b0993a62559b002b746d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::startFold (int, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a047269c60059b0993a62559b002b746d">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a047269c60059b0993a62559b002b746d">startFold</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startFontClass() {#aa0280b79aa3d02cc6958d6a30ea31fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::startFontClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; colorClass)</td>
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



<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 311 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">311</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">XMLCodeGenerator::startFontClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;colorClass)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(startFontClass)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a> &amp;&amp; !<a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a> &amp;&amp; !<a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/highlight&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;highlight class=\""</span><span class="doxyHighlight"> &lt;&lt; colorClass &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// non DocBook</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>, <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>, <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>, <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### startSpecialComment() {#a3d4a64e216077efd517bd7104d59f406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::startSpecialComment ()</td>
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



<p>Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d4a64e216077efd517bd7104d59f406">227</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3d4a64e216077efd517bd7104d59f406">XMLCodeGenerator::startSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> = <a href="#aa0beff851b3e2185134d8f7e490ca957">m_stripCodeComments</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> and <a href="#aa0beff851b3e2185134d8f7e490ca957">m_stripCodeComments</a>.</p>

</div>
</div>

### stripCodeComments() {#a9e3880c26431032448d23e87fd9a9249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::stripCodeComments (bool b)</td>
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



<p>Declaration at line 28 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e3880c26431032448d23e87fd9a9249">217</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e3880c26431032448d23e87fd9a9249">XMLCodeGenerator::stripCodeComments</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa0beff851b3e2185134d8f7e490ca957">m_stripCodeComments</a> = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa0beff851b3e2185134d8f7e490ca957">m_stripCodeComments</a>.</p>

</div>
</div>

### type() {#a1161113df26f973d35819d346c52830f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType XMLCodeGenerator::type ()</td>
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



<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1161113df26f973d35819d346c52830f">25</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#a1161113df26f973d35819d346c52830f">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3501bb093d363810b671059b9cfed3f8">OutputType::XML</a>; }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3501bb093d363810b671059b9cfed3f8">XML</a>.</p>

</div>
</div>

### writeCodeAnchor() {#af3abeec4466c2fd8b4abd70e6465c4ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::writeCodeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 332 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3abeec4466c2fd8b4abd70e6465c4ec">332</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af3abeec4466c2fd8b4abd70e6465c4ec">XMLCodeGenerator::writeCodeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeCodeAnchor)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### writeCodeLink() {#a22f6ad09446c1965714f48e8cbf8459a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::writeCodeLink (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
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



<p>Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22f6ad09446c1965714f48e8cbf8459a">237</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22f6ad09446c1965714f48e8cbf8459a">XMLCodeGenerator::writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tooltip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeCodeLink)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a> &amp;&amp; !<a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a> &amp;&amp; <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;highlight class=\"normal\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#addab75b1cb249ffe90ab4624fe4aa530">writeXMLLink</a>(*<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>,ref,file,anchor,name,tooltip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>+=name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a>, <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a>, <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a>, <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a>, <a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#addab75b1cb249ffe90ab4624fe4aa530">writeXMLLink</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### writeLineNumber() {#aac332610fed5a983f3b5e012c1fcddef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::writeLineNumber (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extRef, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; compId, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchorId, int l, bool writeLineAnchor)</td>
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



<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 338 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac332610fed5a983f3b5e012c1fcddef">338</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac332610fed5a983f3b5e012c1fcddef">XMLCodeGenerator::writeLineNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extRef,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;compId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchorId,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeLineNumber)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// we remember the information provided here to use it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// at the &lt;codeline&gt; start tag.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a> = l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!compId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>=compId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchorId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">)+anchorId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">m_isMemberRef</a> = anchorId!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!extRef.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>=extRef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>, <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>, <a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">m_isMemberRef</a>, <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a>, <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

### writeTooltip() {#a0892bdfdb6f093026e4b3437d98c76a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeGenerator::writeTooltip (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;)</td>
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



<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0892bdfdb6f093026e4b3437d98c76a5">253</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0892bdfdb6f093026e4b3437d98c76a5">XMLCodeGenerator::writeTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">                 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a>) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>((</span><span class="doxyHighlightStringLiteral">"(writeToolTip)\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a46e27d9a509ad7bba1d4fabbe1a71b7e">XML_DB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_col {#aacbff059bb56ccc09783ad007c3b280f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XMLCodeGenerator::m_col = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacbff059bb56ccc09783ad007c3b280f">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#aacbff059bb56ccc09783ad007c3b280f">m_col</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a> and <a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a>.</p>

</div>
</div>

### m\_external {#abdb404fb86f03d744dbd295d47e4ae36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString XMLCodeGenerator::m_external</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abdb404fb86f03d744dbd295d47e4ae36">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#abdb404fb86f03d744dbd295d47e4ae36">m_external</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a> and <a href="#aac332610fed5a983f3b5e012c1fcddef">writeLineNumber</a>.</p>

</div>
</div>

### m\_hide {#ad507ebe841d2f8aa80ed6ef350816990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XMLCodeGenerator::m_hide = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad507ebe841d2f8aa80ed6ef350816990">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad507ebe841d2f8aa80ed6ef350816990">m_hide</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a>, <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#ae73db4a6021fb7e1a49ffed5931bead5">endFontClass</a>, <a href="#a6ce729ca852a0d77ec9fb6d3aecc554f">endSpecialComment</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a>, <a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">startFontClass</a>, <a href="#a3d4a64e216077efd517bd7104d59f406">startSpecialComment</a>, <a href="#af3abeec4466c2fd8b4abd70e6465c4ec">writeCodeAnchor</a>, <a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a>, <a href="#aac332610fed5a983f3b5e012c1fcddef">writeLineNumber</a> and <a href="#a0892bdfdb6f093026e4b3437d98c76a5">writeTooltip</a>.</p>

</div>
</div>

### m\_insideCodeLine {#a91f4f54448a0801dd6b300205a5bd033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XMLCodeGenerator::m_insideCodeLine = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91f4f54448a0801dd6b300205a5bd033">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a91f4f54448a0801dd6b300205a5bd033">m_insideCodeLine</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a>, <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#a28def93f4623a2788f74a072a6a72a7d">finish</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a>, <a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">startFontClass</a> and <a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a>.</p>

</div>
</div>

### m\_insideSpecialHL {#a0e4c40bf672d84b66baf63299846b69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XMLCodeGenerator::m_insideSpecialHL = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e4c40bf672d84b66baf63299846b69b">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0e4c40bf672d84b66baf63299846b69b">m_insideSpecialHL</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a>, <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#ae73db4a6021fb7e1a49ffed5931bead5">endFontClass</a>, <a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">startFontClass</a> and <a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a>.</p>

</div>
</div>

### m\_isMemberRef {#afa1a2871d0b2973b2ebac3d87f6ab1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XMLCodeGenerator::m_isMemberRef = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#afa1a2871d0b2973b2ebac3d87f6ab1eb">m_isMemberRef</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a> and <a href="#aac332610fed5a983f3b5e012c1fcddef">writeLineNumber</a>.</p>

</div>
</div>

### m\_lineNumber {#a70bd87abe416e5572fc1847432c9ac3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int XMLCodeGenerator::m_lineNumber = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70bd87abe416e5572fc1847432c9ac3e">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a70bd87abe416e5572fc1847432c9ac3e">m_lineNumber</a> = -1;</span></span></div>

</div>


<p>Referenced by <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a> and <a href="#aac332610fed5a983f3b5e012c1fcddef">writeLineNumber</a>.</p>

</div>
</div>

### m\_normalHLNeedStartTag {#a54b560e7b1518573507fc1e289d704ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XMLCodeGenerator::m_normalHLNeedStartTag = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54b560e7b1518573507fc1e289d704ab">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a54b560e7b1518573507fc1e289d704ab">m_normalHLNeedStartTag</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a>, <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">startFontClass</a> and <a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a>.</p>

</div>
</div>

### m\_refId {#aa8d05dcbd2db6a318e74367b05bb243f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString XMLCodeGenerator::m_refId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa8d05dcbd2db6a318e74367b05bb243f">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa8d05dcbd2db6a318e74367b05bb243f">m_refId</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a> and <a href="#aac332610fed5a983f3b5e012c1fcddef">writeLineNumber</a>.</p>

</div>
</div>

### m\_stripCodeComments {#aa0beff851b3e2185134d8f7e490ca957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool XMLCodeGenerator::m_stripCodeComments = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0beff851b3e2185134d8f7e490ca957">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa0beff851b3e2185134d8f7e490ca957">m_stripCodeComments</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a3d4a64e216077efd517bd7104d59f406">startSpecialComment</a> and <a href="#a9e3880c26431032448d23e87fd9a9249">stripCodeComments</a>.</p>

</div>
</div>

### m\_stripIndentAmount {#a1bea8dabe5f8613353769398c42a21c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XMLCodeGenerator::m_stripIndentAmount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1bea8dabe5f8613353769398c42a21c6">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">  <a href="#a1bea8dabe5f8613353769398c42a21c6">m_stripIndentAmount</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a> and <a href="#a135b16eab3b231e381293243dff571a0">setStripIndentAmount</a>.</p>

</div>
</div>

### m\_t {#ac6417d9f611bebf4366e67e7235aaeef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream* XMLCodeGenerator::m_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6417d9f611bebf4366e67e7235aaeef">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> *<a href="#ac6417d9f611bebf4366e67e7235aaeef">m_t</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a17dd450e496129d67a0208dc421cfd1c">codify</a>, <a href="#ad8336886fd5704ed637f7e789dda4a2b">endCodeFragment</a>, <a href="#a1ae221fa179fd6cb57ffc68bbefaee49">endCodeLine</a>, <a href="#ae73db4a6021fb7e1a49ffed5931bead5">endFontClass</a>, <a href="#affd0e0660e9f1ba00aa9202d90b632a9">startCodeFragment</a>, <a href="#a2e1224334cbe5cfe794c31eeaf4bbc57">startCodeLine</a>, <a href="#aa0280b79aa3d02cc6958d6a30ea31fc3">startFontClass</a>, <a href="#a22f6ad09446c1965714f48e8cbf8459a">writeCodeLink</a> and <a href="#ae566a902bea279e24182706618efa6a1">XMLCodeGenerator</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
