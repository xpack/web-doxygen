---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/styledata
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `StyleData` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct StyleData { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/rtfstyle-h">src/rtfstyle.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b065b8e48e6258fdc607f8b362ded48">StyleData</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4e839cadb0aa89001d0a3b45845ce9">StyleData</a> (const std::string &amp;reference, const std::string &amp;definition)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9ef51c3d04534f0d123bc771ab3367">setStyle</a> (const std::string &amp;command, const std::string &amp;styleName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a443c5942e29a67d8410ed800671c3d0b">m_index</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b4270cec917791d56b70ff1c5606e3">m_reference</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8d293d6b6162f687f6d753e9221729">m_definition</a></td>
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


Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxySectionDef">

## Public Constructors

### StyleData() {#a0b065b8e48e6258fdc607f8b362ded48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StyleData::StyleData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

References <a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a> and <a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>.
</div>
</div>

### StyleData() {#afa4e839cadb0aa89001d0a3b45845ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StyleData::StyleData (const std::string &amp; reference, const std::string &amp; definition)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>, definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa4e839cadb0aa89001d0a3b45845ce9">286</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0b065b8e48e6258fdc607f8b362ded48">StyleData::StyleData</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(<a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>,match,<a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a7ce4348d587548a514b1e698abed1a54">s_clause</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a443c5942e29a67d8410ed800671c3d0b">m_index</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::stoul(match[1].str()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a443c5942e29a67d8410ed800671c3d0b">m_index</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af7b4270cec917791d56b70ff1c5606e3">m_reference</a> = <a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afb8d293d6b6162f687f6d753e9221729">m_definition</a> = <a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a>, <a href="#afb8d293d6b6162f687f6d753e9221729">m\_definition</a>, <a href="#a443c5942e29a67d8410ed800671c3d0b">m\_index</a>, <a href="#af7b4270cec917791d56b70ff1c5606e3">m\_reference</a>, <a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a7ce4348d587548a514b1e698abed1a54">s\_clause</a> and <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### definition() {#acae6677bf1fd21e0b3b0607243d3f01a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * StyleData::definition ()</td>
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



Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acae6677bf1fd21e0b3b0607243d3f01a">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afb8d293d6b6162f687f6d753e9221729">m_definition</a>.c_str(); }</span></span></div>

</div>


Reference <a href="#afb8d293d6b6162f687f6d753e9221729">m\_definition</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a>, <a href="#a0b065b8e48e6258fdc607f8b362ded48">StyleData</a> and <a href="#afa4e839cadb0aa89001d0a3b45845ce9">StyleData</a>.
</div>
</div>

### index() {#a778df6e3e0962fc37bdbbb8cf4dced15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t StyleData::index ()</td>
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



Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a778df6e3e0962fc37bdbbb8cf4dced15">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a443c5942e29a67d8410ed800671c3d0b">m_index</a>; }</span></span></div>

</div>


Reference <a href="#a443c5942e29a67d8410ed800671c3d0b">m\_index</a>.

Referenced by <a href="#a7a9ef51c3d04534f0d123bc771ab3367">setStyle</a>.
</div>
</div>

### reference() {#af5bfe4b887b11e7daba3c3648697e031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * StyleData::reference ()</td>
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



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5bfe4b887b11e7daba3c3648697e031">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af7b4270cec917791d56b70ff1c5606e3">m_reference</a>.c_str(); }</span></span></div>

</div>


Reference <a href="#af7b4270cec917791d56b70ff1c5606e3">m\_reference</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7467e3f0f800ca5303ce1e6e473cdcfe">RTFDocVisitor::getStyle</a>, <a href="#a0b065b8e48e6258fdc607f8b362ded48">StyleData</a> and <a href="#afa4e839cadb0aa89001d0a3b45845ce9">StyleData</a>.
</div>
</div>

### setStyle() {#a7a9ef51c3d04534f0d123bc771ab3367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StyleData::setStyle (const std::string &amp; command, const std::string &amp; styleName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>, definition at line 301 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a9ef51c3d04534f0d123bc771ab3367">301</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7a9ef51c3d04534f0d123bc771ab3367">StyleData::setStyle</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;command, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;styleName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(command,match,<a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a7ce4348d587548a514b1e698abed1a54">s_clause</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Style sheet '{}' contains no '\\s' clause.\n{{{}}}\n"</span><span class="doxyHighlight">, styleName, command);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a443c5942e29a67d8410ed800671c3d0b">m_index</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::stoul(match[1].str()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a> = command.find(</span><span class="doxyHighlightStringLiteral">"\\sbasedon"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a>!=std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af7b4270cec917791d56b70ff1c5606e3">m_reference</a>  = command.substr(0,<a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afb8d293d6b6162f687f6d753e9221729">m_definition</a> = command.substr(<a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a>, <a href="#afb8d293d6b6162f687f6d753e9221729">m\_definition</a>, <a href="#a443c5942e29a67d8410ed800671c3d0b">m\_index</a>, <a href="#af7b4270cec917791d56b70ff1c5606e3">m\_reference</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a7ce4348d587548a514b1e698abed1a54">s\_clause</a> and <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a1a60858edb01bcbd780025cecdf65c8f">loadStylesheet</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_definition {#afb8d293d6b6162f687f6d753e9221729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string StyleData::m_definition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb8d293d6b6162f687f6d753e9221729">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#afb8d293d6b6162f687f6d753e9221729">m_definition</a>;   </span><span class="doxyHighlightComment">// additional tags like \snext and style name</span></span></div>

</div>


Referenced by <a href="#acae6677bf1fd21e0b3b0607243d3f01a">definition</a>, <a href="#a7a9ef51c3d04534f0d123bc771ab3367">setStyle</a> and <a href="#afa4e839cadb0aa89001d0a3b45845ce9">StyleData</a>.
</div>
</div>

### m\_index {#a443c5942e29a67d8410ed800671c3d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t StyleData::m_index = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a443c5942e29a67d8410ed800671c3d0b">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#a443c5942e29a67d8410ed800671c3d0b">m_index</a> = 0; </span><span class="doxyHighlightComment">// index in style-sheet, i.e. number in s-clause</span></span></div>

</div>


Referenced by <a href="#a778df6e3e0962fc37bdbbb8cf4dced15">index</a>, <a href="#a7a9ef51c3d04534f0d123bc771ab3367">setStyle</a> and <a href="#afa4e839cadb0aa89001d0a3b45845ce9">StyleData</a>.
</div>
</div>

### m\_reference {#af7b4270cec917791d56b70ff1c5606e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string StyleData::m_reference</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7b4270cec917791d56b70ff1c5606e3">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#af7b4270cec917791d56b70ff1c5606e3">m_reference</a>;    </span><span class="doxyHighlightComment">// everything required to apply the style</span></span></div>

</div>


Referenced by <a href="#af5bfe4b887b11e7daba3c3648697e031">reference</a>, <a href="#a7a9ef51c3d04534f0d123bc771ab3367">setStyle</a> and <a href="#afa4e839cadb0aa89001d0a3b45845ce9">StyleData</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
