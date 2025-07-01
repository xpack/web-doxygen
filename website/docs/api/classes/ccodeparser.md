---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/ccodeparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CCodeParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class CCodeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/code-h">src/code.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/codeparserinterface">CodeParserInterface</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Abstract interface for code parsers. <a href="/web-doxygen/docs/api/classes/codeparserinterface/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997869f7ed19a9e8871fcaea7518adc9">~CCodeParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a106ea78aa6382f5b06dbd2563d5b99e4">parseCode</a> (OutputCodeList &amp;codeOutIntf, const QCString &amp;scopeName, const QCString &amp;input, SrcLangExt lang, bool stripCodeComments, bool isExampleBlock, const QCString &amp;exampleName=QCString(), const FileDef *fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=FALSE, const MemberDef *memberDef=nullptr, bool showLineNumbers=TRUE, const Definition *searchCtx=nullptr, bool collectXRefs=TRUE) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parses a source file or fragment with the goal to produce highlighted and cross-referenced output. <a href="#a106ea78aa6382f5b06dbd2563d5b99e4">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2518a33cb478dee30fe9eeb62a51f3ae">resetCodeParserState</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Resets the state of the code parser. <a href="#a2518a33cb478dee30fe9eeb62a51f3ae">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93aa7a5adf58ca0282b3d19f4cdb07b4">setInsideCodeLine</a> (bool inp)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a8bc3a1f0f692975cc1fbde99fbbce">insideCodeLine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/ccodeparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a></td>
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


Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>.

<div class="doxySectionDef">

## Public Constructors

### CCodeParser() {#a53fde266eef5df6e4c65286e04fd739c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCodeParser::CCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>, definition at line 4066 of file <a href="/web-doxygen/docs/api/files/src/code-l">code.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53fde266eef5df6e4c65286e04fd739c">4066</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser::CCodeParser</a>() : <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>(std::make_unique&lt;<a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser</a>::<a href="/web-doxygen/docs/api/structs/ccodeparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4067</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4068</span><span class="doxyLineContent"><span class="doxyHighlight">  codeYYlex_init_extra(&amp;<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;state,&amp;<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4069</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4070</span><span class="doxyLineContent"><span class="doxyHighlight">  codeYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">Debug::Lex_code</a>)?1:0,<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4071</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4072</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2518a33cb478dee30fe9eeb62a51f3ae">resetCodeParserState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4073</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">Debug::Lex\_code</a>, <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a> and <a href="#a2518a33cb478dee30fe9eeb62a51f3ae">resetCodeParserState</a>.

Referenced by <a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CCodeParser() {#a997869f7ed19a9e8871fcaea7518adc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CCodeParser::~CCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>, definition at line 4075 of file <a href="/web-doxygen/docs/api/files/src/code-l">code.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a997869f7ed19a9e8871fcaea7518adc9">4075</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a997869f7ed19a9e8871fcaea7518adc9">CCodeParser::~CCodeParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4076</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4077</span><span class="doxyLineContent"><span class="doxyHighlight">  codeYYlex_destroy(<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4078</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### insideCodeLine() {#af6a8bc3a1f0f692975cc1fbde99fbbce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CCodeParser::insideCodeLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>, definition at line 4098 of file <a href="/web-doxygen/docs/api/files/src/code-l">code.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6a8bc3a1f0f692975cc1fbde99fbbce">4098</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af6a8bc3a1f0f692975cc1fbde99fbbce">CCodeParser::insideCodeLine</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4099</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4101</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> yyextra-&gt;insideCodeLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4102</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>.
</div>
</div>

### parseCode() {#a106ea78aa6382f5b06dbd2563d5b99e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CCodeParser::parseCode (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, bool stripCodeComments, bool isExampleBlock, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * memberDef=nullptr, bool showLineNumbers=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * searchCtx=nullptr, bool collectXRefs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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

Parses a source file or fragment with the goal to produce highlighted and cross-referenced output.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] codeOutList</td>
<td class="doxyParamItemDescription">interface for writing the result.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] scopeName</td>
<td class="doxyParamItemDescription">Name of scope to which the code belongs.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] input</td>
<td class="doxyParamItemDescription">Actual code in the form of a string</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] lang</td>
<td class="doxyParamItemDescription">The programming language of the code fragment.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] stripCodeComments</td>
<td class="doxyParamItemDescription">signals whether or not for the code block the doxygen comments should be stripped.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] isExampleBlock</td>
<td class="doxyParamItemDescription">TRUE iff the code is part of an example.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] exampleName</td>
<td class="doxyParamItemDescription">Name of the example.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileDef</td>
<td class="doxyParamItemDescription">File definition to which the code is associated.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] startLine</td>
<td class="doxyParamItemDescription">Starting line in case of a code fragment.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] endLine</td>
<td class="doxyParamItemDescription">Ending line of the code fragment.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] inlineFragment</td>
<td class="doxyParamItemDescription">Code fragment that is to be shown inline as part of the documentation.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] memberDef</td>
<td class="doxyParamItemDescription">Member definition to which the code is associated (non null in case of an inline fragment for a member).</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] showLineNumbers</td>
<td class="doxyParamItemDescription">if set to TRUE and also fileDef is not 0, line numbers will be added to the source fragment</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] searchCtx</td>
<td class="doxyParamItemDescription">context under which search data has to be stored.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] collectXRefs</td>
<td class="doxyParamItemDescription">collect cross-reference relations.</td>
</tr>
</table>
</dd>
</dl>

Declaration at line 35 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>, definition at line 4104 of file <a href="/web-doxygen/docs/api/files/src/code-l">code.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a106ea78aa6382f5b06dbd2563d5b99e4">4104</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;od,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4105</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> stripCodeComments,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> exBlock,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;exName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4106</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineFragment,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4107</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *memberDef,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showLineNumbers,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *searchCtx,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4108</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> collectXRefs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4109</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4112</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"***parseCode() exBlock=%d exName=%s fd=%p scopeName=%s searchCtx=%s\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4113</span><span class="doxyLineContent"><span class="doxyHighlight">           exBlock,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(exName),(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">*)fd,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(scopeName),searchCtx?<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(searchCtx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()):</span><span class="doxyHighlightStringLiteral">"&lt;none&gt;"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4114</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4116</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4117</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">Debug::Lex_code</a>, __FILE__, fd ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>()): !exName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(exName) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4118</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4119</span><span class="doxyLineContent"><span class="doxyHighlight">  od.<a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">stripCodeComments</a>(stripCodeComments);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4120</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;code = &amp;od;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4121</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString   = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4122</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = fd ? fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4123</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;absFileName   = fd ? fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4124</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4125</span><span class="doxyLineContent"><span class="doxyHighlight">  codeYYrestart(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4126</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentFontClass = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4127</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;searchCtx = searchCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4128</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;collectXRefs = collectXRefs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4129</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inFunctionTryBlock = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4130</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;symbolResolver.setFileScope(fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4131</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;foldStack.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4132</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideSpecialComment = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4133</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4135</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4137</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4138</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4140</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = endLine+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4142</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = yyextra-&gt;yyLineNr + <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>(yyscanner) - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4143</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4144</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;curlyCount    = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4145</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;bodyCurlyCount    = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4146</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;bracketCount  = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4147</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;sharpCount    = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4148</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideTemplate = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4149</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;theCallContext.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4150</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;scopeStack.empty()) yyextra-&gt;scopeStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4151</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;scopeName     = scopeName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4152</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"parseCCode %s\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(scopeName)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4153</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleBlock  = exBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4154</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleName   = exName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4155</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;sourceFileDef = fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4156</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNumbers   = fd &amp;&amp; showLineNumbers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4159</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// create a dummy filedef for the example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4160</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),(!exName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()?exName:</span><span class="doxyHighlightStringLiteral">"generated"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4161</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef  = yyextra-&gt;exampleFileDef.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4162</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4163</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lang        = lang;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4164</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideObjC  = lang==SrcLangExt::ObjC;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;sourceFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4166</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4167</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"l00001"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4168</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4169</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentDefinition = searchCtx ? searchCtx : <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac29daa4ae4a11022a30d2deb6934624c">getResolvedNamespace</a>(scopeName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4170</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentMemberDef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4171</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;searchingForBody = exBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4172</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideBody = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4173</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;bracketCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;exampleName.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4175</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4176</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFile = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>(yyextra-&gt;exampleName+</span><span class="doxyHighlightStringLiteral">"-example"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4177</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"yyextra-&gt;exampleFile=%s\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(yyextra-&gt;exampleFile)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4178</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4179</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;includeCodeFragment = inlineFragment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"** exBlock=%d exName=%s include=%d\n"</span><span class="doxyHighlight">,exBlock,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(exName),inlineFragment));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;insideCodeLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4182</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4183</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4184</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4185</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;type.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4186</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;name.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4187</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;args.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4188</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;parmName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4189</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;parmType.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memberDef) <a href="/web-doxygen/docs/api/files/src/code-l/#add91dbbc9b0c632da7f20c52ca03e6c8">setParameterList</a>(yyscanner,memberDef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4191</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( Body );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4192</span><span class="doxyLineContent"><span class="doxyHighlight">  codeYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4193</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lexInit=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideCodeLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4195</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4196</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4197</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_CODE_FOLDING))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4199</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;foldStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4201</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4202</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;code-&gt;endFold();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4203</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;foldStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4204</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4205</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;exampleFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4207</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4208</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// delete the temporary file definition used for this example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4209</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4210</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4211</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write the tooltips</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4213</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;tooltipManager.writeTooltips(od);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4214</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG\_CTX</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">FileDef::fileName</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac29daa4ae4a11022a30d2deb6934624c">getResolvedNamespace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">Debug::Lex\_code</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#add91dbbc9b0c632da7f20c52ca03e6c8">setParameterList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">OutputCodeList::stripCodeComments</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### resetCodeParserState() {#a2518a33cb478dee30fe9eeb62a51f3ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CCodeParser::resetCodeParserState ()</td>
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

Resets the state of the code parser.


Since multiple code fragments can together form a single example, an explicit function is used to reset the code parser state.

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<a href="#a106ea78aa6382f5b06dbd2563d5b99e4">parseCode()</a>
</dd>
</dl>


Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>, definition at line 4080 of file <a href="/web-doxygen/docs/api/files/src/code-l">code.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2518a33cb478dee30fe9eeb62a51f3ae">4080</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2518a33cb478dee30fe9eeb62a51f3ae">CCodeParser::resetCodeParserState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4081</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4082</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4083</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG_CTX</a>((stderr,</span><span class="doxyHighlightStringLiteral">"***CodeParser::reset()\n"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4084</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;theVarContext.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4085</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;scopeNameLengthStack.empty()) yyextra-&gt;scopeNameLengthStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4086</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;codeClassMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4087</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;curClassBases.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4088</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;anchorCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4089</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4090</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/code-l/#a234e2efe67eececd88b140b46ea37463">DBG\_CTX</a> and <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>.

Referenced by <a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser</a>.
</div>
</div>

### setInsideCodeLine() {#a93aa7a5adf58ca0282b3d19f4cdb07b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CCodeParser::setInsideCodeLine (bool inp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>, definition at line 4092 of file <a href="/web-doxygen/docs/api/files/src/code-l">code.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93aa7a5adf58ca0282b3d19f4cdb07b4">4092</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a93aa7a5adf58ca0282b3d19f4cdb07b4">CCodeParser::setInsideCodeLine</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4093</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4094</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4095</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine = inp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4096</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aa55de188022eb9630b9b3f5a54bb3628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; CCodeParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa55de188022eb9630b9b3f5a54bb3628">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aa55de188022eb9630b9b3f5a54bb3628">p</a>;</span></span></div>

</div>


Referenced by <a href="#a53fde266eef5df6e4c65286e04fd739c">CCodeParser</a>, <a href="#af6a8bc3a1f0f692975cc1fbde99fbbce">insideCodeLine</a>, <a href="#a106ea78aa6382f5b06dbd2563d5b99e4">parseCode</a>, <a href="#a2518a33cb478dee30fe9eeb62a51f3ae">resetCodeParserState</a>, <a href="#a93aa7a5adf58ca0282b3d19f4cdb07b4">setInsideCodeLine</a> and <a href="#a997869f7ed19a9e8871fcaea7518adc9">\~CCodeParser</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/code-h">code.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/code-l">code.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
