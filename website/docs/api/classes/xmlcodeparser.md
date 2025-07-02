---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/xmlcodeparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `XMLCodeParser` Class Reference

XML scanner. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class XMLCodeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/xmlcode-h">src/xmlcode.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b752edfd8cc2c382a7a0289b315f890">XMLCodeParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263794216c9fc12d04d5bcdd12b9cadd">~XMLCodeParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e7283cd50a9220c8381cbdf953702ca">parseCode</a> (OutputCodeList &amp;codeOutIntf, const QCString &amp;scopeName, const QCString &amp;input, SrcLangExt, bool stripCodeComments, bool isExampleBlock, const QCString &amp;exampleName=QCString(), const FileDef *fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=FALSE, const MemberDef *memberDef=nullptr, bool showLineNumbers=TRUE, const Definition *searchCtx=nullptr, bool collectXRefs=TRUE) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parses a source file or fragment with the goal to produce highlighted and cross-referenced output. <a href="#a1e7283cd50a9220c8381cbdf953702ca">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">resetCodeParserState</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Resets the state of the code parser. <a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/xmlcodeparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a></td>
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

XML scanner.


Only support syntax highlighting of code at the moment.

Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a>.

<div class="doxySectionDef">

## Public Constructors

### XMLCodeParser() {#a7b752edfd8cc2c382a7a0289b315f890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLCodeParser::XMLCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a>, definition at line 395 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-l">xmlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b752edfd8cc2c382a7a0289b315f890">395</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a7b752edfd8cc2c382a7a0289b315f890">XMLCodeParser::XMLCodeParser</a>() : <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/xmlcodeparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlcodeYYlex_init_extra(&amp;<a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>-&gt;state,&amp;<a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlcodeYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">Debug::Lex_xmlcode</a>)?1:0,<a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">resetCodeParserState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">Debug::Lex\_xmlcode</a>, <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a> and <a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">resetCodeParserState</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~XMLCodeParser() {#a263794216c9fc12d04d5bcdd12b9cadd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLCodeParser::~XMLCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a>, definition at line 404 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-l">xmlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a263794216c9fc12d04d5bcdd12b9cadd">404</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a263794216c9fc12d04d5bcdd12b9cadd">XMLCodeParser::~XMLCodeParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlcodeYYlex_destroy(<a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseCode() {#a1e7283cd50a9220c8381cbdf953702ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeParser::parseCode (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, bool stripCodeComments, bool isExampleBlock, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * memberDef=nullptr, bool showLineNumbers=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * searchCtx=nullptr, bool collectXRefs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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

Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a>, definition at line 416 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-l">xmlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e7283cd50a9220c8381cbdf953702ca">416</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1e7283cd50a9220c8381cbdf953702ca">XMLCodeParser::parseCode</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;codeOutIntf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* scopeName */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> stripCodeComments,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isExampleBlock,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;exampleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineFragment,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * </span><span class="doxyHighlightComment">/* memberDef */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* showLineNumbers */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *searchCtx,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlightComment">/* collectXRefs */</span><span class="doxyHighlight"> </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">Debug::Lex_xmlcode</a>, __FILE__, fileDef ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileDef-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>()): </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = fileDef ? fileDef-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;code = &amp;codeOutIntf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString   = input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentFontClass = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;searchCtx = searchCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = endLine+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = yyextra-&gt;yyLineNr + <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>(yyscanner) - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;stripCodeComments = stripCodeComments;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleBlock  = isExampleBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleName   = exampleName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;sourceFileDef = fileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isExampleBlock &amp;&amp; fileDef==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// create a dummy filedef for the example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,(!exampleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()?exampleName:<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"generated"</span><span class="doxyHighlight">)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef = yyextra-&gt;exampleFileDef.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;sourceFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"l00001"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;includeCodeFragment = inlineFragment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Starts line 1 on the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlcodeYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlcodeYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideCodeLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;exampleFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// delete the temporary file definition used for this example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">FileDef::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">Debug::Lex\_xmlcode</a>, <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>.
</div>
</div>

### resetCodeParserState() {#a65af5d8f7fc3c7f6770ad1caddeeb015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLCodeParser::resetCodeParserState ()</td>
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
<dd><a href="#a1e7283cd50a9220c8381cbdf953702ca">parseCode()</a></dd>
</dl>


Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a>, definition at line 409 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-l">xmlcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">409</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">XMLCodeParser::resetCodeParserState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentDefinition = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentMemberDef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>.

Referenced by <a href="#a7b752edfd8cc2c382a7a0289b315f890">XMLCodeParser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a10f5a26fdd5455f9e6260ab179b70904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; XMLCodeParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10f5a26fdd5455f9e6260ab179b70904">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a10f5a26fdd5455f9e6260ab179b70904">p</a>;</span></span></div>

</div>


Referenced by <a href="#a1e7283cd50a9220c8381cbdf953702ca">parseCode</a>, <a href="#a65af5d8f7fc3c7f6770ad1caddeeb015">resetCodeParserState</a>, <a href="#a7b752edfd8cc2c382a7a0289b315f890">XMLCodeParser</a> and <a href="#a263794216c9fc12d04d5bcdd12b9cadd">\~XMLCodeParser</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/xmlcode-h">xmlcode.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/xmlcode-l">xmlcode.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
