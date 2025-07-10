---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/vhdlcodeparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VHDLCodeParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class VHDLCodeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/vhdlcode-h">src/vhdlcode.h</a>&gt;
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
<p>Abstract interface for code parsers. <a href="/web-doxygen/docs/api/classes/codeparserinterface/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c48ab414d705c2bc9c6c7c48cf04b90">VHDLCodeParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae268bd1553979a83b62aad2ef43ad6b8">~VHDLCodeParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ff704e68bb7562a054bd1c7f8bba09">parseCode</a> (OutputCodeList &amp;codeOutIntf, const QCString &amp;scopeName, const QCString &amp;input, SrcLangExt lang, bool stripCodeComments, bool isExampleBlock, const QCString &amp;exampleName=QCString(), const FileDef *fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=FALSE, const MemberDef *memberDef=nullptr, bool showLineNumbers=TRUE, const Definition *searchCtx=nullptr, bool collectXRefs=TRUE) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a source file or fragment with the goal to produce highlighted and cross-referenced output. <a href="#a49ff704e68bb7562a054bd1c7f8bba09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbae7f971cc80bd619ce238e4a54415">resetCodeParserState</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the state of the code parser. <a href="#a4dbae7f971cc80bd619ce238e4a54415">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/vhdlcodeparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee0b22f354554d52e83f05579caca3f1">p</a></td>
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


<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VHDLCodeParser() {#a6c48ab414d705c2bc9c6c7c48cf04b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VHDLCodeParser::VHDLCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a>, definition at line 1632 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-l">vhdlcode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c48ab414d705c2bc9c6c7c48cf04b90">1632</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a6c48ab414d705c2bc9c6c7c48cf04b90">VHDLCodeParser::VHDLCodeParser</a>() : <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/vhdlcodeparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  vhdlcodeYYlex_init_extra(&amp;<a href="#aee0b22f354554d52e83f05579caca3f1">p</a>-&gt;state,&amp;<a href="#aee0b22f354554d52e83f05579caca3f1">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  vhdlcodeYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">Debug::Lex_vhdlcode</a>)?1:0,<a href="#aee0b22f354554d52e83f05579caca3f1">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4dbae7f971cc80bd619ce238e4a54415">resetCodeParserState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">Debug::Lex_vhdlcode</a>, <a href="#aee0b22f354554d52e83f05579caca3f1">p</a> and <a href="#a4dbae7f971cc80bd619ce238e4a54415">resetCodeParserState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VHDLCodeParser() {#ae268bd1553979a83b62aad2ef43ad6b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VHDLCodeParser::~VHDLCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a>, definition at line 1641 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-l">vhdlcode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae268bd1553979a83b62aad2ef43ad6b8">1641</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ae268bd1553979a83b62aad2ef43ad6b8">VHDLCodeParser::~VHDLCodeParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">  vhdlcodeYYlex_destroy(<a href="#aee0b22f354554d52e83f05579caca3f1">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseCode() {#a49ff704e68bb7562a054bd1c7f8bba09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLCodeParser::parseCode (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, bool stripCodeComments, bool isExampleBlock, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * memberDef=nullptr, bool showLineNumbers=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * searchCtx=nullptr, bool collectXRefs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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

<p>Parses a source file or fragment with the goal to produce highlighted and cross-referenced output.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] codeOutList</td>
<td class="doxyParamItemDescription"><p>interface for writing the result.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] scopeName</td>
<td class="doxyParamItemDescription"><p>Name of scope to which the code belongs.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] input</td>
<td class="doxyParamItemDescription"><p>Actual code in the form of a string</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] lang</td>
<td class="doxyParamItemDescription"><p>The programming language of the code fragment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] stripCodeComments</td>
<td class="doxyParamItemDescription"><p>signals whether or not for the code block the doxygen comments should be stripped.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] isExampleBlock</td>
<td class="doxyParamItemDescription"><p>TRUE iff the code is part of an example.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] exampleName</td>
<td class="doxyParamItemDescription"><p>Name of the example.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileDef</td>
<td class="doxyParamItemDescription"><p>File definition to which the code is associated.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] startLine</td>
<td class="doxyParamItemDescription"><p>Starting line in case of a code fragment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] endLine</td>
<td class="doxyParamItemDescription"><p>Ending line of the code fragment.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] inlineFragment</td>
<td class="doxyParamItemDescription"><p>Code fragment that is to be shown inline as part of the documentation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] memberDef</td>
<td class="doxyParamItemDescription"><p>Member definition to which the code is associated (non null in case of an inline fragment for a member).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] showLineNumbers</td>
<td class="doxyParamItemDescription"><p>if set to TRUE and also fileDef is not 0, line numbers will be added to the source fragment</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] searchCtx</td>
<td class="doxyParamItemDescription"><p>context under which search data has to be stored.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] collectXRefs</td>
<td class="doxyParamItemDescription"><p>collect cross-reference relations.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a>, definition at line 1651 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-l">vhdlcode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49ff704e68bb7562a054bd1c7f8bba09">1651</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;od,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* className */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span><span class="doxyLineContent"><span class="doxyHighlight">                               <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> stripCodeComments,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> exBlock,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;exName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineFragment,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *memberDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *searchCtx,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* collectXRefs */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("***parseCode() exBlock=%d exName=%s fd=%p\n",exBlock,exName,fd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">Debug::Lex_vhdlcode</a>, __FILE__, fd ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>()): </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = fd ? fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memberDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *dd=memberDef-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dd) yyextra-&gt;currClass=dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">  od.<a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">stripCodeComments</a>(stripCodeComments);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4dbae7f971cc80bd619ce238e4a54415">resetCodeParserState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;code = &amp;od;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString   = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentFontClass = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;searchCtx = searchCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;foldStack.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideSpecialComment = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = endLine+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = yyextra-&gt;yyLineNr + <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>(yyscanner) - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// yyextra-&gt;theCallContext.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleBlock  = exBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleName   = exName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;sourceFileDef = fd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (exBlock &amp;&amp; fd==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// create a dummy filedef for the example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,exName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef = yyextra-&gt;exampleFileDef.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;sourceFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"l00001"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentDefinition = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentMemberDef  = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;vhdlMember        = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;exampleName.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFile = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>(yyextra-&gt;exampleName+</span><span class="doxyHighlightStringLiteral">"-example"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;includeCodeFragment = inlineFragment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;lexInit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a987fee1e906fac322dda62613525a8f9">VhdlDocGen::init</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;lexInit=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  vhdlcodeYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( Bases );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">  vhdlcodeYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideCodeLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HTML_CODE_FOLDING))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;foldStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;code-&gt;endFold();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;foldStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;exampleFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// delete the temporary file definition used for this example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write the tooltips</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;tooltipManager.writeTooltips(od);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">FileDef::fileName</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a987fee1e906fac322dda62613525a8f9">VhdlDocGen::init</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">Debug::Lex_vhdlcode</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="#a4dbae7f971cc80bd619ce238e4a54415">resetCodeParserState</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a> and <a href="/web-doxygen/docs/api/classes/outputcodelist/#aebb587648d0dbbfec75c7b7ffc6873ba">OutputCodeList::stripCodeComments</a>.</p>

</div>
</div>

### resetCodeParserState() {#a4dbae7f971cc80bd619ce238e4a54415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLCodeParser::resetCodeParserState ()</td>
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

<p>Resets the state of the code parser.</p>


<p>Since multiple code fragments can together form a single example, an explicit function is used to reset the code parser state.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a49ff704e68bb7562a054bd1c7f8bba09">parseCode()</a></p></dd>
</dl>


<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a>, definition at line 1646 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-l">vhdlcode.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4dbae7f971cc80bd619ce238e4a54415">1646</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4dbae7f971cc80bd619ce238e4a54415">VHDLCodeParser::resetCodeParserState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>-&gt;state.vhdlKeyDict.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>.</p>


<p>Referenced by <a href="#a49ff704e68bb7562a054bd1c7f8bba09">parseCode</a> and <a href="#a6c48ab414d705c2bc9c6c7c48cf04b90">VHDLCodeParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aee0b22f354554d52e83f05579caca3f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; VHDLCodeParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee0b22f354554d52e83f05579caca3f1">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aee0b22f354554d52e83f05579caca3f1">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a49ff704e68bb7562a054bd1c7f8bba09">parseCode</a>, <a href="#a4dbae7f971cc80bd619ce238e4a54415">resetCodeParserState</a>, <a href="#a6c48ab414d705c2bc9c6c7c48cf04b90">VHDLCodeParser</a> and <a href="#ae268bd1553979a83b62aad2ef43ad6b8">~VHDLCodeParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/vhdlcode-h">vhdlcode.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/vhdlcode-l">vhdlcode.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
