---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docstylechange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocStyleChange` Class Reference

<p>Node representing a style change. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocStyleChange { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Style { <a href="#a97757d2d85c39228c90693491a56d277">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a> (DocParser *parser, DocNodeVariant *parent, size_t position, Style s, const QCString &amp;tagName, bool enable, const HtmlAttribList *attribs=nullptr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> (DocParser *parser, DocNodeVariant *parent, size_t position, Style s, const QCString &amp;tagName, bool enable, const QCString &amp;fileName, int lineNr, const HtmlAttribList *attribs=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97757d2d85c39228c90693491a56d277">Style</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d079390f264e34af453a015bd2e2c9">style</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21689e3e2c3b35c3d438ebfff8f35da9">styleString</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ab08efe175ca6bca982f860550d814">fileName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41f0c75b1cc53e0e72462271a4d9c2da">lineNr</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a97757d2d85c39228c90693491a56d277">Style</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a> = <a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">Bold</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">m_fileName</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0afa69fd80290807e2fce395240a9234">m_lineNr</a> = -1</td>
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

<p>Node representing a style change.</p>

<p>Definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Style {#a97757d2d85c39228c90693491a56d277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DocStyleChange::Style </td>
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
<td class="doxyEnumItemName">Bold<a id="a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Italic<a id="a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Code<a id="a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Center<a id="a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;3))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Small<a id="a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;4))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Subscript<a id="a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;5))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Superscript<a id="a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;6))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Preformatted<a id="a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;7))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Span<a id="a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;8))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Div<a id="a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;9))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Strike<a id="a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;10))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Underline<a id="a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;11))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Del<a id="a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;12))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ins<a id="a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;13))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">S<a id="a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;14))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cite<a id="a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;15))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Kbd<a id="a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;16))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Typewriter<a id="a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85"></a></td>
<td class="doxyEnumItemDescription"> (= (1&lt;&lt;17))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 270 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">270</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277">Style</a> { <a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">Bold</a>          = (1&lt;&lt;0),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">271</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">Italic</a>        = (1&lt;&lt;1),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">272</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">Code</a>          = (1&lt;&lt;2),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">273</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">Center</a>        = (1&lt;&lt;3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">274</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">Small</a>         = (1&lt;&lt;4),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">275</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">Subscript</a>     = (1&lt;&lt;5),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">276</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">Superscript</a>   = (1&lt;&lt;6),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">277</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">Preformatted</a>  = (1&lt;&lt;7),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">278</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">Span</a>          = (1&lt;&lt;8),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">279</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">Div</a>           = (1&lt;&lt;9),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">280</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">Strike</a>        = (1&lt;&lt;10),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">281</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">Underline</a>     = (1&lt;&lt;11),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">282</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">Del</a>           = (1&lt;&lt;12),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">283</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">Ins</a>           = (1&lt;&lt;13),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">284</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">S</a>             = (1&lt;&lt;14),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">285</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">Cite</a>          = (1&lt;&lt;15),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">286</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">Kbd</a>           = (1&lt;&lt;16),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">287</a></span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">Typewriter</a>    = (1&lt;&lt;17)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">               };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DocStyleChange() {#a02dbcf18e08adc619e3bd5d6c0b049c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocStyleChange::DocStyleChange (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, size_t position, <a href="#a97757d2d85c39228c90693491a56d277">Style</a> s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagName, bool enable, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> * attribs=nullptr)</td>
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



<p>Definition at line 290 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">290</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>,<a href="#a97757d2d85c39228c90693491a56d277">Style</a> s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> *<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a>(<a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>), <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>(s), <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a>(<a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>) <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>=*<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a> = <a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>, <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>, <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a>, <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a>, <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>, <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a> and <a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>.</p>

</div>
</div>

### DocStyleChange() {#a1c093a46ad6968d6b98baabffe755d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocStyleChange::DocStyleChange (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, size_t position, <a href="#a97757d2d85c39228c90693491a56d277">Style</a> s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagName, bool enable, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> * attribs=nullptr)</td>
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



<p>Definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c093a46ad6968d6b98baabffe755d12">297</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>,<a href="#a97757d2d85c39228c90693491a56d277">Style</a> s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a64ab08efe175ca6bca982f860550d814">fileName</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a41f0c75b1cc53e0e72462271a4d9c2da">lineNr</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> *<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a>(<a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>), <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>(s), <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a>(<a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">m_fileName</a>(<a href="#a64ab08efe175ca6bca982f860550d814">fileName</a>), <a href="#a0afa69fd80290807e2fce395240a9234">m_lineNr</a>(<a href="#a41f0c75b1cc53e0e72462271a4d9c2da">lineNr</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>) <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>=*<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a> = <a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>.lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>, <a href="#a64ab08efe175ca6bca982f860550d814">fileName</a>, <a href="#a41f0c75b1cc53e0e72462271a4d9c2da">lineNr</a>, <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>, <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a>, <a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">m_fileName</a>, <a href="#a0afa69fd80290807e2fce395240a9234">m_lineNr</a>, <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a>, <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>, <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a> and <a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### attribs() {#a3c0ac63aee1132f4dbe442366444c99c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HtmlAttribList &amp; DocStyleChange::attribs ()</td>
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



<p>Definition at line 311 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c0ac63aee1132f4dbe442366444c99c">311</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>; }</span></span></div>

</div>


<p>Reference <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>.</p>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a7cbce284509ccf3109aa71472842ce4e">DocParser::handleInitialStyleCommands</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>.</p>

</div>
</div>

### enable() {#ac8a8c808b962cc17665ab52937b8bd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocStyleChange::enable ()</td>
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



<p>Definition at line 309 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8a8c808b962cc17665ab52937b8bd78">309</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>()</span><span class="doxyHighlightKeyword"> const                   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a>; }</span></span></div>

</div>


<p>Reference <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a>.</p>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a9daef16ea8fc3793c36c55f3657c6d29">insideStyleChangeThatIsOutsideParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa5dd013610540bba019aaef10157b416">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41aaa90a6a3c9ec728048cbdb927c7ae">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a3135258f772ad9dcb6c936b55f913543">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a12175400ef7a7ab13c32e503c40f3638">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a3db4919bff573649528a826a8f75f1f1">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af3beab942bf46b1f903ac30ac39a10d2">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#aac3356483b754f0dab670ad4a1407f98">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### fileName() {#a64ab08efe175ca6bca982f860550d814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocStyleChange::fileName ()</td>
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



<p>Definition at line 313 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64ab08efe175ca6bca982f860550d814">313</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a64ab08efe175ca6bca982f860550d814">fileName</a>()</span><span class="doxyHighlightKeyword"> const             </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">m_fileName</a>; }</span></span></div>

</div>


<p>Reference <a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">m_fileName</a>.</p>


<p>Referenced by <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>.</p>

</div>
</div>

### lineNr() {#a41f0c75b1cc53e0e72462271a4d9c2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocStyleChange::lineNr ()</td>
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



<p>Definition at line 314 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41f0c75b1cc53e0e72462271a4d9c2da">314</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a41f0c75b1cc53e0e72462271a4d9c2da">lineNr</a>()</span><span class="doxyHighlightKeyword"> const                    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0afa69fd80290807e2fce395240a9234">m_lineNr</a>; }</span></span></div>

</div>


<p>Reference <a href="#a0afa69fd80290807e2fce395240a9234">m_lineNr</a>.</p>


<p>Referenced by <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>.</p>

</div>
</div>

### position() {#a9cfdbb1f8ace3872966d8e6338cc9720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocStyleChange::position ()</td>
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



<p>Definition at line 310 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cfdbb1f8ace3872966d8e6338cc9720">310</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>()</span><span class="doxyHighlightKeyword"> const               </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a>; }</span></span></div>

</div>


<p>Reference <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a>.</p>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> and <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>.</p>

</div>
</div>

### style() {#a56d079390f264e34af453a015bd2e2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Style DocStyleChange::style ()</td>
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



<p>Definition at line 307 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56d079390f264e34af453a015bd2e2c9">307</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a97757d2d85c39228c90693491a56d277">Style</a> <a href="#a56d079390f264e34af453a015bd2e2c9">style</a>()</span><span class="doxyHighlightKeyword"> const                   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>; }</span></span></div>

</div>


<p>Reference <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docparser/#a7cbce284509ccf3109aa71472842ce4e">DocParser::handleInitialStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a9daef16ea8fc3793c36c55f3657c6d29">insideStyleChangeThatIsOutsideParagraph</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a86acf8b4839daaae86b0a90ca98767b8">mustBeOutsideParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa5dd013610540bba019aaef10157b416">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41aaa90a6a3c9ec728048cbdb927c7ae">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a3135258f772ad9dcb6c936b55f913543">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a12175400ef7a7ab13c32e503c40f3638">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a3db4919bff573649528a826a8f75f1f1">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af3beab942bf46b1f903ac30ac39a10d2">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#aac3356483b754f0dab670ad4a1407f98">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### styleString() {#a21689e3e2c3b35c3d438ebfff8f35da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DocStyleChange::styleString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21689e3e2c3b35c3d438ebfff8f35da9">125</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a21689e3e2c3b35c3d438ebfff8f35da9">DocStyleChange::styleString</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">DocStyleChange::Bold</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"b"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">DocStyleChange::Italic</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"em"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">DocStyleChange::Code</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"code"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">DocStyleChange::Center</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"center"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">DocStyleChange::Small</a>:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"small"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">DocStyleChange::Cite</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"cite"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">DocStyleChange::Subscript</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"subscript"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">DocStyleChange::Superscript</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"superscript"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">DocStyleChange::Preformatted</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"pre"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">DocStyleChange::Div</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"div"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">DocStyleChange::Span</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"span"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">DocStyleChange::Strike</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"strike"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">DocStyleChange::S</a>:            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"s"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">DocStyleChange::Del</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"del"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">DocStyleChange::Underline</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"u"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">DocStyleChange::Ins</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"ins"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">DocStyleChange::Kbd</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"kbd"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">DocStyleChange::Typewriter</a>:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"tt"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"&lt;invalid&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">Bold</a>, <a href="#a97757d2d85c39228c90693491a56d277ae4330ac7dbaf5ee725a5813109f1854a">Center</a>, <a href="#a97757d2d85c39228c90693491a56d277a4fd52aeff707aa62ec5f03f5cca312e6">Cite</a>, <a href="#a97757d2d85c39228c90693491a56d277ad1c85e30cf1da2bdb0de2f1fe2690aa2">Code</a>, <a href="#a97757d2d85c39228c90693491a56d277a0417c5d59bbd1a5c8fb87853ae58dc63">Del</a>, <a href="#a97757d2d85c39228c90693491a56d277afd9182e9d7bff25af5c122b0dbc41fb1">Div</a>, <a href="#a97757d2d85c39228c90693491a56d277ad4de98733a18ab2f074935240873fdae">Ins</a>, <a href="#a97757d2d85c39228c90693491a56d277a8c32aed981a8fef9dab678551395440d">Italic</a>, <a href="#a97757d2d85c39228c90693491a56d277ad048174170b3f3fc9aa377ef27324a97">Kbd</a>, <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a>, <a href="#a97757d2d85c39228c90693491a56d277a170e0ef8c35d36cb6d94c9210373a817">Preformatted</a>, <a href="#a97757d2d85c39228c90693491a56d277a55596f97583b8bab6927a66ea8f869d5">S</a>, <a href="#a97757d2d85c39228c90693491a56d277a78ba2b4ff14390fbf298b4d232a469bc">Small</a>, <a href="#a97757d2d85c39228c90693491a56d277ab8e6f97aabed0d46a7cb62007fbb825f">Span</a>, <a href="#a97757d2d85c39228c90693491a56d277afbc227d38530df65d31a768c8c68a54e">Strike</a>, <a href="#a97757d2d85c39228c90693491a56d277a5b36fd18bd9fcf1410577a6958997438">Subscript</a>, <a href="#a97757d2d85c39228c90693491a56d277a7883a437d4ca4973a9cb59231980004f">Superscript</a>, <a href="#a97757d2d85c39228c90693491a56d277a6779a1e8815fc7b3a0a95e05166b5e85">Typewriter</a> and <a href="#a97757d2d85c39228c90693491a56d277a75800ad1019038b22142b5a760df10a4">Underline</a>.</p>

</div>
</div>

### tagName() {#a44ca0ca006829c1ca5d0fb87cb699a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocStyleChange::tagName ()</td>
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



<p>Definition at line 312 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44ca0ca006829c1ca5d0fb87cb699a84">312</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>()</span><span class="doxyHighlightKeyword"> const              </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a>; }</span></span></div>

</div>


<p>Reference <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a>.</p>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a7cbce284509ccf3109aa71472842ce4e">DocParser::handleInitialStyleCommands</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_attribs {#aa6391e57c9f4874b9d9f14c840920ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlAttribList DocStyleChange::m_attribs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6391e57c9f4874b9d9f14c840920ed1">320</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> <a href="#aa6391e57c9f4874b9d9f14c840920ed1">m_attribs</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a3c0ac63aee1132f4dbe442366444c99c">attribs</a>, <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a> and <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>.</p>

</div>
</div>

### m\_enable {#a41204f9c47d6239e562b61fdf19c1c67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocStyleChange::m_enable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41204f9c47d6239e562b61fdf19c1c67">319</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">     <a href="#a41204f9c47d6239e562b61fdf19c1c67">m_enable</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> and <a href="#ac8a8c808b962cc17665ab52937b8bd78">enable</a>.</p>

</div>
</div>

### m\_fileName {#ac6f2ce68c2bc1839542313a1c5df3b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocStyleChange::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">322</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac6f2ce68c2bc1839542313a1c5df3b6c">m_fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> and <a href="#a64ab08efe175ca6bca982f860550d814">fileName</a>.</p>

</div>
</div>

### m\_lineNr {#a0afa69fd80290807e2fce395240a9234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocStyleChange::m_lineNr = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0afa69fd80290807e2fce395240a9234">323</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">      <a href="#a0afa69fd80290807e2fce395240a9234">m_lineNr</a> = -1;</span></span></div>

</div>


<p>Referenced by <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> and <a href="#a41f0c75b1cc53e0e72462271a4d9c2da">lineNr</a>.</p>

</div>
</div>

### m\_position {#af205ce9ff9457dfe57bb2581b822bf8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocStyleChange::m_position = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af205ce9ff9457dfe57bb2581b822bf8d">317</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">   <a href="#af205ce9ff9457dfe57bb2581b822bf8d">m_position</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> and <a href="#a9cfdbb1f8ace3872966d8e6338cc9720">position</a>.</p>

</div>
</div>

### m\_style {#a6f7681b0473104f3aed63a29b52efcad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Style DocStyleChange::m_style = <a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">Bold</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f7681b0473104f3aed63a29b52efcad">318</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a97757d2d85c39228c90693491a56d277">Style</a>    <a href="#a6f7681b0473104f3aed63a29b52efcad">m_style</a> = <a href="#a97757d2d85c39228c90693491a56d277a807d9b8b8360cb61511e5ea56237c306">Bold</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a>, <a href="#a56d079390f264e34af453a015bd2e2c9">style</a> and <a href="#a21689e3e2c3b35c3d438ebfff8f35da9">styleString</a>.</p>

</div>
</div>

### m\_tagName {#af89107ebbc7bd64e428a2e0e2b4a54e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocStyleChange::m_tagName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">321</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af89107ebbc7bd64e428a2e0e2b4a54e2">m_tagName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a02dbcf18e08adc619e3bd5d6c0b049c8">DocStyleChange</a>, <a href="#a1c093a46ad6968d6b98baabffe755d12">DocStyleChange</a> and <a href="#a44ca0ca006829c1ca5d0fb87cb699a84">tagName</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
