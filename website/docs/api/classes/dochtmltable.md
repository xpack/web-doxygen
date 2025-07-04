---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dochtmltable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocHtmlTable` Class Reference

<p>Node representing a HTML table. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocHtmlTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doccompoundnode">DocCompoundNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for nodes with children. <a href="/web-doxygen/docs/api/classes/doccompoundnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af266849ab196138aa08764525b6e8433">DocHtmlTable</a> (DocParser *parser, DocNodeVariant *parent, const HtmlAttribList &amp;attribs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197727d94413c8a39461bb9008d57390">numRows</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa86fa0065c58175e3199426c4fe4d20b">hasCaption</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa067a7324dc0d06431ead1202b669e18">attribs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4ae9d09701b93305b6e90260bc5662">parse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a913b8204fc7637dea2f3783da7b1a2">parseXml</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc50242564e265147b101926f1efce5e">firstRow</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8252a73bf19e6fcbf924a12c5d132815">computeTableGrid</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>determines the location of all cells in a grid, resolving row and column spans. <a href="#a8252a73bf19e6fcbf924a12c5d132815">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc409e9355509116d40f41b0aadcbdf4">m_attribs</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e47f94176d44bbc6c4466576608a88e">m_numCols</a> = 0</td>
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

<p>Node representing a HTML table.</p>

<p>Definition at line 1268 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocHtmlTable() {#af266849ab196138aa08764525b6e8433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocHtmlTable::DocHtmlTable (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp; attribs)</td>
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



<p>Definition at line 1271 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af266849ab196138aa08764525b6e8433">1271</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af266849ab196138aa08764525b6e8433">DocHtmlTable</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#aa067a7324dc0d06431ead1202b669e18">attribs</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#acc409e9355509116d40f41b0aadcbdf4">m_attribs</a>(<a href="#aa067a7324dc0d06431ead1202b669e18">attribs</a>) {}</span></span></div>

</div>


<p>References <a href="#aa067a7324dc0d06431ead1202b669e18">attribs</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="#acc409e9355509116d40f41b0aadcbdf4">m_attribs</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### attribs() {#aa067a7324dc0d06431ead1202b669e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HtmlAttribList &amp; DocHtmlTable::attribs ()</td>
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



<p>Definition at line 1275 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa067a7324dc0d06431ead1202b669e18">1275</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#aa067a7324dc0d06431ead1202b669e18">attribs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acc409e9355509116d40f41b0aadcbdf4">m_attribs</a>; }</span></span></div>

</div>


<p>Reference <a href="#acc409e9355509116d40f41b0aadcbdf4">m_attribs</a>.</p>


<p>Referenced by <a href="#af266849ab196138aa08764525b6e8433">DocHtmlTable</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ace45195acd5464fbc29281fd8d44c66d">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a0c0655fab12e9ffece836f11b46a8c44">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### caption() {#a93e3d4a5878ef927d4b4a32ffa2ec17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeVariant * DocHtmlTable::caption ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1279 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2115 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93e3d4a5878ef927d4b4a32ffa2ec17d">2115</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#a93e3d4a5878ef927d4b4a32ffa2ec17d">DocHtmlTable::caption</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab9d3c8796370b41a72f6158fa461f5ca">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ace45195acd5464fbc29281fd8d44c66d">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a678591cbca0c1070b7a8803d3c5541c7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a57b7db74e73a0b47dde3a73b1976d846">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a781c65343949306e386679f695721435">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3c72fc623be48174c003bb47c523d6c1">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a0c0655fab12e9ffece836f11b46a8c44">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### firstRow() {#afc50242564e265147b101926f1efce5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeVariant * DocHtmlTable::firstRow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1280 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2120 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc50242564e265147b101926f1efce5e">2120</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#afc50242564e265147b101926f1efce5e">DocHtmlTable::firstRow</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().empty() &amp;&amp; std::holds_alternative&lt;DocHtmlRow&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().front()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#ad097d3d024ed9fa293f9099352309a25">front</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a> and <a href="/web-doxygen/docs/api/classes/growvector/#ad097d3d024ed9fa293f9099352309a25">GrowVector&lt; T &gt;::front</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a678591cbca0c1070b7a8803d3c5541c7">LatexDocVisitor::operator()</a>.</p>

</div>
</div>

### hasCaption() {#aa86fa0065c58175e3199426c4fe4d20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocHtmlTable::hasCaption ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1274 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2110 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa86fa0065c58175e3199426c4fe4d20b">2110</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa86fa0065c58175e3199426c4fe4d20b">DocHtmlTable::hasCaption</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>.</p>

</div>
</div>

### numColumns() {#a8885013add9c26d1ddf36d1412bbd6f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocHtmlTable::numColumns ()</td>
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



<p>Definition at line 1278 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8885013add9c26d1ddf36d1412bbd6f9">1278</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8e47f94176d44bbc6c4466576608a88e">m_numCols</a>; }</span></span></div>

</div>


<p>Reference <a href="#a8e47f94176d44bbc6c4466576608a88e">m_numCols</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab9d3c8796370b41a72f6158fa461f5ca">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a678591cbca0c1070b7a8803d3c5541c7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a781c65343949306e386679f695721435">PrintDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a0c0655fab12e9ffece836f11b46a8c44">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### numRows() {#a197727d94413c8a39461bb9008d57390}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocHtmlTable::numRows ()</td>
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



<p>Definition at line 1273 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a197727d94413c8a39461bb9008d57390">1273</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a197727d94413c8a39461bb9008d57390">numRows</a>()</span><span class="doxyHighlightKeyword"> const  </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a2579ab76c81ca4fa987a413fb4c057d1">size</a>(); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a2579ab76c81ca4fa987a413fb4c057d1">GrowVector&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a57b7db74e73a0b47dde3a73b1976d846">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a781c65343949306e386679f695721435">PrintDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a0c0655fab12e9ffece836f11b46a8c44">XmlDocVisitor::operator()</a>.</p>

</div>
</div>

### parse() {#a6f4ae9d09701b93305b6e90260bc5662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocHtmlTable::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1276 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2129 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f4ae9d09701b93305b6e90260bc5662">2129</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">getrow:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// get next token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// skip whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WHITESPACE,TokenRetval::TK_NEWPARA)) tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// should find a html tag now</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273">HtmlTagType</a> tagId=<a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273af9e3cb3f2f4243b958e1b98226ec4f30">HtmlTagType::HTML_THEAD</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;thead&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> getrow;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a20c25807fdf7ad539a764cf1d393464a">HtmlTagType::HTML_TBODY</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;tbody&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> getrow;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a14ef64361eae40bbe02179dc7e9bc4b4">HtmlTagType::HTML_TFOOT</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;tfoot&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> getrow;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad7eb396091ab8336abda28f4d30aedaf">HtmlTagType::HTML_TR</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;tr&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// no caption, just rows</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = Token::make_RetVal_TableRow();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a2861ae6e47c6162fcdfbcbc3e8c23f7e">HtmlTagType::HTML_CAPTION</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;caption&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"table already has a caption, found another one"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a> = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode&lt;DocHtmlCaption&gt;</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;attribs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">        retval=std::get&lt;DocHtmlCaption&gt;(*m_caption).parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_OK)) </span><span class="doxyHighlightComment">// caption was parsed ok</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> getrow;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// found wrong token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected &lt;tr&gt; or &lt;caption&gt; tag but "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"found &lt;{}{}&gt; instead!"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag ? </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF)) </span><span class="doxyHighlightComment">// premature end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected end of comment while looking"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">" for a &lt;tr&gt; or &lt;caption&gt; tag"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// token other than html token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected &lt;tr&gt; tag but found {} token instead!"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">        tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// parse one or more rows</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_TableRow))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a811b08400dcdf6aa65b3fd3149b890c9">attribs</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a>&gt;()-&gt;<a href="#a6f4ae9d09701b93305b6e90260bc5662">parse</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("DocHtmlTable::retval=%s\n",retval.to_string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.is(TokenRetval::RetVal_EndTableRow))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// get next token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">      retval=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip whitespace after &lt;/td&gt; or &lt;/th&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval.is_any_of(TokenRetval::TK_WHITESPACE,TokenRetval::TK_NEWPARA)) retval=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("DocHtmlTable::retval= next=%s name=%s endTag=%d\n",retval.to_string(),qPrint(parser()-&gt;context.token-&gt;name),parser()-&gt;context.token-&gt;endTag);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273">HtmlTagType</a> tagId=<a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad7eb396091ab8336abda28f4d30aedaf">HtmlTagType::HTML_TR</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">        retval = Token::make_RetVal_TableRow();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273af86f2e136782e591c3a3ecdd9713c5a8">HtmlTagType::HTML_TABLE</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">        retval = Token::make_RetVal_EndTable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// found some other tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected &lt;tr&gt; or &lt;/table&gt; tag but "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"found token {} instead!"</span><span class="doxyHighlight">,retval.to_string());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">        retval=Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8252a73bf19e6fcbf924a12c5d132815">computeTableGrid</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_EndTable) ? Token::make_RetVal_OK() : retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a811b08400dcdf6aa65b3fd3149b890c9">TokenInfo::attribs</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="#a8252a73bf19e6fcbf924a12c5d132815">computeTableGrid</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a2861ae6e47c6162fcdfbcbc3e8c23f7e">HTML_CAPTION</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273af86f2e136782e591c3a3ecdd9713c5a8">HTML_TABLE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a20c25807fdf7ad539a764cf1d393464a">HTML_TBODY</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a14ef64361eae40bbe02179dc7e9bc4b4">HTML_TFOOT</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273af9e3cb3f2f4243b958e1b98226ec4f30">HTML_THEAD</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273ad7eb396091ab8336abda28f4d30aedaf">HTML_TR</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>, <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>, <a href="#a6f4ae9d09701b93305b6e90260bc5662">parse</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>.</p>


<p>Referenced by <a href="#a6f4ae9d09701b93305b6e90260bc5662">parse</a>.</p>

</div>
</div>

### parseXml() {#a2a913b8204fc7637dea2f3783da7b1a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocHtmlTable::parseXml ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1277 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2232 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a913b8204fc7637dea2f3783da7b1a2">2232</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// get next token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// skip whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_WHITESPACE,TokenRetval::TK_NEWPARA)) tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// should find a html tag now</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273">HtmlTagType</a> tagId=<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a696b031073e74bf2cb98e5ef201d4aa3">HtmlTagType::UNKNOWN</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_HTMLTAG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">    tagId=<a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a198cc56071a53f9ad84bdb88a3e24867">HtmlTagType::XML_ITEM</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;item&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = Token::make_RetVal_TableRow();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a3e97a35f83d8653e00f2ee154d53cadc">HtmlTagType::XML_LISTHEADER</a> &amp;&amp; !<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;endTag) </span><span class="doxyHighlightComment">// found &lt;listheader&gt; tag</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = Token::make_RetVal_TableRow();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">      isHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// parse one or more rows</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_TableRow))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a811b08400dcdf6aa65b3fd3149b890c9">attribs</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> *tr = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">    retval=tr-&gt;parseXml(isHeader);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">    isHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8252a73bf19e6fcbf924a12c5d132815">computeTableGrid</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">  tagId=<a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tagId==<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a40f0bcd06b9f44f4d797d244ea660b8b">HtmlTagType::XML_LIST</a> &amp;&amp; <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a8492fcbbf13ce7dbb7fa8d1eaa9d1e91">endTag</a> ? Token::make_RetVal_OK() : retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a811b08400dcdf6aa65b3fd3149b890c9">TokenInfo::attribs</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="#a8252a73bf19e6fcbf924a12c5d132815">computeTableGrid</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a8492fcbbf13ce7dbb7fa8d1eaa9d1e91">TokenInfo::endTag</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a198cc56071a53f9ad84bdb88a3e24867">XML_ITEM</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a40f0bcd06b9f44f4d797d244ea660b8b">XML_LIST</a> and <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a3e97a35f83d8653e00f2ee154d53cadc">XML_LISTHEADER</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeTableGrid() {#a8252a73bf19e6fcbf924a12c5d132815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocHtmlTable::computeTableGrid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>determines the location of all cells in a grid, resolving row and column spans.</p>


<p>For each the total number of visible cells is computed, and the total number of visible columns over all rows is stored.</p>


<p>Declaration at line 1283 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2289 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8252a73bf19e6fcbf924a12c5d132815">2289</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8252a73bf19e6fcbf924a12c5d132815">DocHtmlTable::computeTableGrid</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("computeTableGrid()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a8ebd411a505f41da49085559bdc9685e">RowSpanList</a> rowSpans;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t maxCols=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t rowIdx=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rowNode : <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t colIdx=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t cells=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dochtmlrow">DocHtmlRow</a> *row = std::get_if&lt;DocHtmlRow&gt;(&amp;rowNode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (row)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cellNode : row-&gt;<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dochtmlcell">DocHtmlCell</a> *cell = std::get_if&lt;DocHtmlCell&gt;(&amp;cellNode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cell)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">          uint32_t rs = cell-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a6c8e5643943bf242271a39a6f679abf6">rowSpan</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">          uint32_t cs = cell-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcell/#af34c0918c8bdce594c6039dd64506e7a">colSpan</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;rowSpans.size();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rowSpans[i].rowsLeft&gt;0 &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">                rowSpans[i].column==colIdx)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">              colIdx=rowSpans[i].column+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">              cells++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rs&gt;0) rowSpans.emplace_back(rs,colIdx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("found cell at (%d,%d)\n",rowIdx,colIdx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">          cell-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a50304ff7552720198294eea2d4a9e82f">setRowIndex</a>(rowIdx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">          cell-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlcell/#a3d29d907f8b4b39fbdac6dd777f51eeb">setColumnIndex</a>(colIdx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">          colIdx+=cs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">          cells++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;rowSpans.size();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rowSpans[i].rowsLeft&gt;0) rowSpans[i].rowsLeft--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">      row-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlrow/#a1ed44cd8dbe113a2a8180613487261f0">setVisibleCells</a>(cells);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">      row-&gt;<a href="/web-doxygen/docs/api/classes/dochtmlrow/#aded7defbf854f8c8f0049d92e96aea13">setRowIndex</a>(rowIdx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">      rowIdx++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (colIdx-1&gt;maxCols) maxCols=colIdx-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8e47f94176d44bbc6c4466576608a88e">m_numCols</a> = maxCols;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af34c0918c8bdce594c6039dd64506e7a">DocHtmlCell::colSpan</a>, <a href="#a8e47f94176d44bbc6c4466576608a88e">m_numCols</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a6c8e5643943bf242271a39a6f679abf6">DocHtmlCell::rowSpan</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a3d29d907f8b4b39fbdac6dd777f51eeb">DocHtmlCell::setColumnIndex</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a50304ff7552720198294eea2d4a9e82f">DocHtmlCell::setRowIndex</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#aded7defbf854f8c8f0049d92e96aea13">DocHtmlRow::setRowIndex</a> and <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a1ed44cd8dbe113a2a8180613487261f0">DocHtmlRow::setVisibleCells</a>.</p>


<p>Referenced by <a href="#a6f4ae9d09701b93305b6e90260bc5662">parse</a> and <a href="#a2a913b8204fc7637dea2f3783da7b1a2">parseXml</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_attribs {#acc409e9355509116d40f41b0aadcbdf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlAttribList DocHtmlTable::m_attribs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1285 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc409e9355509116d40f41b0aadcbdf4">1285</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a>     <a href="#acc409e9355509116d40f41b0aadcbdf4">m_attribs</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa067a7324dc0d06431ead1202b669e18">attribs</a> and <a href="#af266849ab196138aa08764525b6e8433">DocHtmlTable</a>.</p>

</div>
</div>

### m\_caption {#a4e42170e093b12dc01eeacc44aaf2e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DocNodeVariant&gt; DocHtmlTable::m_caption</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1284 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e42170e093b12dc01eeacc44aaf2e23">1284</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;DocNodeVariant&gt; <a href="#a4e42170e093b12dc01eeacc44aaf2e23">m_caption</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a93e3d4a5878ef927d4b4a32ffa2ec17d">caption</a>, <a href="#aa86fa0065c58175e3199426c4fe4d20b">hasCaption</a> and <a href="#a6f4ae9d09701b93305b6e90260bc5662">parse</a>.</p>

</div>
</div>

### m\_numCols {#a8e47f94176d44bbc6c4466576608a88e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t DocHtmlTable::m_numCols = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1286 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e47f94176d44bbc6c4466576608a88e">1286</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a8e47f94176d44bbc6c4466576608a88e">m_numCols</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a8252a73bf19e6fcbf924a12c5d132815">computeTableGrid</a> and <a href="#a8885013add9c26d1ddf36d1412bbd6f9">numColumns</a>.</p>

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
