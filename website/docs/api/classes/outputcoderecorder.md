---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/outputcoderecorder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OutputCodeRecorder` Class Reference

<p>Implementation that allows capturing calls made to the code interface to later invoke them on a <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> via <a href="#a89166fa9eb6c282a2351da070e85fe63">replay()</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class OutputCodeRecorder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/outputlist-h">src/outputlist.h</a>&gt;
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f6db688347f0f86e249f07fd3fcb54">type</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6118d7cd0eba1c97ab6554a3a46892">codify</a> (const QCString &amp;s) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc1eca43ed199d785176629763cc987">stripCodeComments</a> (bool) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2a82810d36f25582875e13a4119515">startSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8bbc4e108a1d1457d36092917774306">endSpecialComment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad90779dff0fa670913d994cf163f6c59">setStripIndentAmount</a> (size_t) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0246f7d42a8b0c1f65fcd390e9aa69f7">clone</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557dedc60b16f36981eca737426abbdc">writeCodeLink</a> (CodeSymbolType type, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;tooltip) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade04152adf728b4cc3b1d8e817e975fb">writeLineNumber</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, int lineNumber, bool writeLineAnchor) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12583bf8d4a5c155340ff2d67c178e1d">writeTooltip</a> (const QCString &amp;id, const DocLinkInfo &amp;docInfo, const QCString &amp;decl, const QCString &amp;desc, const SourceLinkInfo &amp;defInfo, const SourceLinkInfo &amp;declInfo) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28951f1bda0edc6710b339c65ddb3432">startCodeLine</a> (int) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6417c62959e9bb11f20a2fd411e4d1f">endCodeLine</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e349809c4aee2ca60c5b85f6e81662">startFontClass</a> (const QCString &amp;c) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fe0d484693f3cd655554a573aeead79">endFontClass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac83ec08ed81d1c5e7159be741ea0f159">writeCodeAnchor</a> (const QCString &amp;name) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f5cf6e8484cf049d20baefc65ff122">startCodeFragment</a> (const QCString &amp;style) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd7aabfd92306068406c28a288f3020c">endCodeFragment</a> (const QCString &amp;style) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08439e8491d0e15d3b6e4ad05e6b8ef2">startFold</a> (int lineNr, const QCString &amp;startMarker, const QCString &amp;endMarker) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a86021e04386f2bb67211be6aa22878">endFold</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89166fa9eb6c282a2351da070e85fe63">replay</a> (OutputCodeList &amp;ol, int startLine, int endLine, bool showLineNumbers, bool stripComment, size_t stripIndentAmount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a> (int lineNr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/outputcoderecorder/callinfo">CallInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25df42a13c59b08f7824e80042a253ef">m_showLineNumbers</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a> = false</td>
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

<p>Implementation that allows capturing calls made to the code interface to later invoke them on a <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> via <a href="#a89166fa9eb6c282a2351da070e85fe63">replay()</a>.</p>

<p>Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### clone() {#a0246f7d42a8b0c1f65fcd390e9aa69f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputCodeIntf &gt; OutputCodeRecorder::clone ()</td>
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



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0246f7d42a8b0c1f65fcd390e9aa69f7">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeIntf&gt; <a href="#a0246f7d42a8b0c1f65fcd390e9aa69f7">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;OutputCodeRecorder&gt;(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">); }</span></span></div>

</div>

</div>
</div>

### codify() {#a5d6118d7cd0eba1c97ab6554a3a46892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::codify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Declaration at line 115 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d6118d7cd0eba1c97ab6554a3a46892">231</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5d6118d7cd0eba1c97ab6554a3a46892">OutputCodeRecorder::codify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;codify(s); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### endCodeFragment() {#acd7aabfd92306068406c28a288f3020c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::endCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Declaration at line 135 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 332 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd7aabfd92306068406c28a288f3020c">332</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acd7aabfd92306068406c28a288f3020c">OutputCodeRecorder::endCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### endCodeLine() {#ad6417c62959e9bb11f20a2fd411e4d1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::endCodeLine ()</td>
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



<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 296 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6417c62959e9bb11f20a2fd411e4d1f">296</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6417c62959e9bb11f20a2fd411e4d1f">OutputCodeRecorder::endCodeLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([](){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;endCodeLine(); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### endFold() {#a1a86021e04386f2bb67211be6aa22878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::endFold ()</td>
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



<p>Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 344 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a86021e04386f2bb67211be6aa22878">344</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1a86021e04386f2bb67211be6aa22878">OutputCodeRecorder::endFold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;endFold(); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### endFontClass() {#a3fe0d484693f3cd655554a573aeead79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::endFontClass ()</td>
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



<p>Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 312 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3fe0d484693f3cd655554a573aeead79">312</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3fe0d484693f3cd655554a573aeead79">OutputCodeRecorder::endFontClass</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol){ ol-&gt;endFontClass(); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### endSpecialComment() {#ac8bbc4e108a1d1457d36092917774306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::endSpecialComment ()</td>
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



<p>Declaration at line 118 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8bbc4e108a1d1457d36092917774306">248</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac8bbc4e108a1d1457d36092917774306">OutputCodeRecorder::endSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;endSpecialComment(); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">                       true</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### replay() {#a89166fa9eb6c282a2351da070e85fe63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::replay (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, int startLine, int endLine, bool showLineNumbers, bool stripComment, size_t stripIndentAmount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 352 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89166fa9eb6c282a2351da070e85fe63">352</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ol,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showLineNumbers,</span><span class="doxyHighlightKeywordType">bool</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2fc1eca43ed199d785176629763cc987">stripCodeComments</a>,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> stripIndentAmount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> startIndex = startLine&gt;0 &amp;&amp; startLine&lt;=(int)<a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>.size() ? <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>[startLine-1] : 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> endIndex   = endLine&gt;0   &amp;&amp; endLine  &lt;=(int)<a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>.size() ? <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>[  endLine-1] : <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("startIndex=%zu endIndex=%zu\n",startIndex,endIndex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// configure run time properties of the rendering</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">stripCodeComments</a>(<a href="#a2fc1eca43ed199d785176629763cc987">stripCodeComments</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a7bc8bc3fc3e31c071445debd32a564ed">setStripIndentAmount</a>(stripIndentAmount);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a25df42a13c59b08f7824e80042a253ef">m_showLineNumbers</a> = showLineNumbers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideSpecialComment = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// in case the start of the special comment marker is outside of the fragment, start it here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startIndex&lt;endIndex &amp;&amp; <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>[startIndex].insideSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a639977987188046433fd28e1bc9a766c">startSpecialComment</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    insideSpecialComment = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// render the requested fragment of the pre-recorded output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=startIndex; i&lt;endIndex; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>[i].condition())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      insideSpecialComment = <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>[i].insideSpecialComment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>[i].function(&amp;ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if we end the fragment inside a special comment, make sure we end it,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// and also the code line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a4b1670c0ebaeda05f89224f58230f497">endSpecialComment</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a27b77a46a240ee024adafb99578ed91b">endCodeLine</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">stripCodeComments</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a7bc8bc3fc3e31c071445debd32a564ed">setStripIndentAmount</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputcodelist/#a27b77a46a240ee024adafb99578ed91b">OutputCodeList::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#a4b1670c0ebaeda05f89224f58230f497">OutputCodeList::endSpecialComment</a>, <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>, <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>, <a href="#a25df42a13c59b08f7824e80042a253ef">m_showLineNumbers</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#a7bc8bc3fc3e31c071445debd32a564ed">OutputCodeList::setStripIndentAmount</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#a639977987188046433fd28e1bc9a766c">OutputCodeList::startSpecialComment</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">OutputCodeList::stripCodeComments</a> and <a href="#a2fc1eca43ed199d785176629763cc987">stripCodeComments</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>.</p>

</div>
</div>

### setStripIndentAmount() {#ad90779dff0fa670913d994cf163f6c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::setStripIndentAmount (size_t)</td>
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



<p>Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad90779dff0fa670913d994cf163f6c59">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad90779dff0fa670913d994cf163f6c59">setStripIndentAmount</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### startCodeFragment() {#a22f5cf6e8484cf049d20baefc65ff122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::startCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style)</td>
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



<p>Declaration at line 134 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 328 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22f5cf6e8484cf049d20baefc65ff122">328</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22f5cf6e8484cf049d20baefc65ff122">OutputCodeRecorder::startCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### startCodeLine() {#a28951f1bda0edc6710b339c65ddb3432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::startCodeLine (int lineNr)</td>
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



<p>Declaration at line 129 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28951f1bda0edc6710b339c65ddb3432">287</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a28951f1bda0edc6710b339c65ddb3432">OutputCodeRecorder::startCodeLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a>(lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([](){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;startCodeLine(lineNr); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>, <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a> and <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a>.</p>

</div>
</div>

### startFold() {#a08439e8491d0e15d3b6e4ad05e6b8ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::startFold (int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; startMarker, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; endMarker)</td>
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



<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 336 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a08439e8491d0e15d3b6e4ad05e6b8ef2">336</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a08439e8491d0e15d3b6e4ad05e6b8ef2">OutputCodeRecorder::startFold</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;startMarker,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;endMarker)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;startFold(lineNr,startMarker,endMarker); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### startFontClass() {#a02e349809c4aee2ca60c5b85f6e81662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::startFontClass (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; c)</td>
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



<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 304 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02e349809c4aee2ca60c5b85f6e81662">304</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a02e349809c4aee2ca60c5b85f6e81662">OutputCodeRecorder::startFontClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;startFontClass(c); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### startSpecialComment() {#aac2a82810d36f25582875e13a4119515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::startSpecialComment ()</td>
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



<p>Declaration at line 117 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac2a82810d36f25582875e13a4119515">239</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac2a82810d36f25582875e13a4119515">OutputCodeRecorder::startSpecialComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;startSpecialComment(); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">                       true</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### stripCodeComments() {#a2fc1eca43ed199d785176629763cc987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::stripCodeComments (bool)</td>
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



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2fc1eca43ed199d785176629763cc987">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2fc1eca43ed199d785176629763cc987">stripCodeComments</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>


<p>Referenced by <a href="#a89166fa9eb6c282a2351da070e85fe63">replay</a>.</p>

</div>
</div>

### type() {#ac5f6db688347f0f86e249f07fd3fcb54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType OutputCodeRecorder::type ()</td>
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



<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5f6db688347f0f86e249f07fd3fcb54">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#ac5f6db688347f0f86e249f07fd3fcb54">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a1aff765143dc4bf8ef68f698234e10f6">OutputType::Recorder</a>; }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a1aff765143dc4bf8ef68f698234e10f6">Recorder</a>.</p>


<p>Referenced by <a href="#a557dedc60b16f36981eca737426abbdc">writeCodeLink</a>.</p>

</div>
</div>

### writeCodeAnchor() {#ac83ec08ed81d1c5e7159be741ea0f159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::writeCodeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Declaration at line 133 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 320 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac83ec08ed81d1c5e7159be741ea0f159">320</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac83ec08ed81d1c5e7159be741ea0f159">OutputCodeRecorder::writeCodeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol){ ol-&gt;writeCodeAnchor(name); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

### writeCodeLink() {#a557dedc60b16f36981eca737426abbdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::writeCodeLink (<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tooltip)</td>
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



<p>Declaration at line 121 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 257 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a557dedc60b16f36981eca737426abbdc">257</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a557dedc60b16f36981eca737426abbdc">OutputCodeRecorder::writeCodeLink</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a55cbcb91fc25e3a2e785b8a30309843c">CodeSymbolType</a> <a href="#ac5f6db688347f0f86e249f07fd3fcb54">type</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tooltip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([](){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;writeCodeLink(<a href="#ac5f6db688347f0f86e249f07fd3fcb54">type</a>,ref,file,anchor,name,tooltip); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>, <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a> and <a href="#ac5f6db688347f0f86e249f07fd3fcb54">type</a>.</p>

</div>
</div>

### writeLineNumber() {#ade04152adf728b4cc3b1d8e817e975fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::writeLineNumber (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int lineNumber, bool writeLineAnchor)</td>
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



<p>Declaration at line 125 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 268 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade04152adf728b4cc3b1d8e817e975fb">268</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ade04152adf728b4cc3b1d8e817e975fb">OutputCodeRecorder::writeLineNumber</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNumber, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> writeLineAnchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a>(lineNumber);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([&amp;]() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a25df42a13c59b08f7824e80042a253ef">m_showLineNumbers</a>; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;writeLineNumber(ref,file,anchor,lineNumber,writeLineAnchor); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>, <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>, <a href="#a25df42a13c59b08f7824e80042a253ef">m_showLineNumbers</a> and <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a>.</p>

</div>
</div>

### writeTooltip() {#a12583bf8d4a5c155340ff2d67c178e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::writeTooltip (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, const <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp; docInfo, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; decl, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; desc, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp; defInfo, const <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp; declInfo)</td>
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



<p>Declaration at line 127 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 278 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12583bf8d4a5c155340ff2d67c178e1d">278</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a12583bf8d4a5c155340ff2d67c178e1d">OutputCodeRecorder::writeTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> &amp;docInfo, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;decl,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;desc, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;defInfo, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> &amp;declInfo)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.emplace_back([](){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">                       [=](<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *ol) { ol-&gt;writeTooltip(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,docInfo,decl,desc,defInfo,declInfo); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### startNewLine() {#a40bdc4d6d3202fa6d7ab544d2f981201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputCodeRecorder::startNewLine (int lineNr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 217 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40bdc4d6d3202fa6d7ab544d2f981201">217</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">OutputCodeRecorder::startNewLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> orgSize = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (orgSize&lt;lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>.resize(lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=orgSize;i&lt;lineNr;i++) </span><span class="doxyHighlightComment">// output lines can be skipped due to hidden comments so fill in the gap</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("%p: startCodeLine(%d) offset=%zu\n",(void*)this,i,m_calls.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>[i]=<a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a> and <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>.</p>


<p>Referenced by <a href="#a28951f1bda0edc6710b339c65ddb3432">startCodeLine</a> and <a href="#ade04152adf728b4cc3b1d8e817e975fb">writeLineNumber</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_calls {#a84ec2538d25d4f3b2f9b942cf818ef11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CallInfo&gt; OutputCodeRecorder::m_calls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84ec2538d25d4f3b2f9b942cf818ef11">152</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;CallInfo&gt; <a href="#a84ec2538d25d4f3b2f9b942cf818ef11">m_calls</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5d6118d7cd0eba1c97ab6554a3a46892">codify</a>, <a href="#ad6417c62959e9bb11f20a2fd411e4d1f">endCodeLine</a>, <a href="#a1a86021e04386f2bb67211be6aa22878">endFold</a>, <a href="#a3fe0d484693f3cd655554a573aeead79">endFontClass</a>, <a href="#ac8bbc4e108a1d1457d36092917774306">endSpecialComment</a>, <a href="#a89166fa9eb6c282a2351da070e85fe63">replay</a>, <a href="#a28951f1bda0edc6710b339c65ddb3432">startCodeLine</a>, <a href="#a08439e8491d0e15d3b6e4ad05e6b8ef2">startFold</a>, <a href="#a02e349809c4aee2ca60c5b85f6e81662">startFontClass</a>, <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a>, <a href="#aac2a82810d36f25582875e13a4119515">startSpecialComment</a>, <a href="#ac83ec08ed81d1c5e7159be741ea0f159">writeCodeAnchor</a>, <a href="#a557dedc60b16f36981eca737426abbdc">writeCodeLink</a>, <a href="#ade04152adf728b4cc3b1d8e817e975fb">writeLineNumber</a> and <a href="#a12583bf8d4a5c155340ff2d67c178e1d">writeTooltip</a>.</p>

</div>
</div>

### m\_insideSpecialComment {#a42b3feb910f8edf3917369e53068a4c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OutputCodeRecorder::m_insideSpecialComment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42b3feb910f8edf3917369e53068a4c0">155</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a42b3feb910f8edf3917369e53068a4c0">m_insideSpecialComment</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a5d6118d7cd0eba1c97ab6554a3a46892">codify</a>, <a href="#ad6417c62959e9bb11f20a2fd411e4d1f">endCodeLine</a>, <a href="#a1a86021e04386f2bb67211be6aa22878">endFold</a>, <a href="#a3fe0d484693f3cd655554a573aeead79">endFontClass</a>, <a href="#ac8bbc4e108a1d1457d36092917774306">endSpecialComment</a>, <a href="#a28951f1bda0edc6710b339c65ddb3432">startCodeLine</a>, <a href="#a08439e8491d0e15d3b6e4ad05e6b8ef2">startFold</a>, <a href="#a02e349809c4aee2ca60c5b85f6e81662">startFontClass</a>, <a href="#aac2a82810d36f25582875e13a4119515">startSpecialComment</a>, <a href="#ac83ec08ed81d1c5e7159be741ea0f159">writeCodeAnchor</a>, <a href="#a557dedc60b16f36981eca737426abbdc">writeCodeLink</a>, <a href="#ade04152adf728b4cc3b1d8e817e975fb">writeLineNumber</a> and <a href="#a12583bf8d4a5c155340ff2d67c178e1d">writeTooltip</a>.</p>

</div>
</div>

### m\_lineOffset {#a661cae19a00beb784468c6decd2abab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;size_t&gt; OutputCodeRecorder::m_lineOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a661cae19a00beb784468c6decd2abab1">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;size_t&gt;   <a href="#a661cae19a00beb784468c6decd2abab1">m_lineOffset</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a89166fa9eb6c282a2351da070e85fe63">replay</a> and <a href="#a40bdc4d6d3202fa6d7ab544d2f981201">startNewLine</a>.</p>

</div>
</div>

### m\_showLineNumbers {#a25df42a13c59b08f7824e80042a253ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OutputCodeRecorder::m_showLineNumbers = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25df42a13c59b08f7824e80042a253ef">154</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a25df42a13c59b08f7824e80042a253ef">m_showLineNumbers</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a89166fa9eb6c282a2351da070e85fe63">replay</a> and <a href="#ade04152adf728b4cc3b1d8e817e975fb">writeLineNumber</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
