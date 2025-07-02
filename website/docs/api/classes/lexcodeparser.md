---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/lexcodeparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `LexCodeParser` Class Reference

LEX code scanner. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class LexCodeParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/lexcode-h">src/lexcode.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab888b9484e3ea4ac127f6a4e08a66415">LexCodeParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea06a30d26e093ef35584e22381543c0">~LexCodeParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a907e618c99ef07aa00fc0604062e3929">parseCode</a> (OutputCodeList &amp;codeOutIntf, const QCString &amp;scopeName, const QCString &amp;input, SrcLangExt, bool stripCodeComments, bool isExampleBlock, const QCString &amp;exampleName=QCString(), const FileDef *fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=FALSE, const MemberDef *memberDef=nullptr, bool showLineNumbers=TRUE, const Definition *searchCtx=nullptr, bool collectXRefs=TRUE) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parses a source file or fragment with the goal to produce highlighted and cross-referenced output. <a href="#a907e618c99ef07aa00fc0604062e3929">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42c158786f3c520dcfd7d7e8d077dd9">resetCodeParserState</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Resets the state of the code parser. <a href="#ab42c158786f3c520dcfd7d7e8d077dd9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/lexcodeparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a></td>
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

LEX code scanner.

Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a>.

<div class="doxySectionDef">

## Public Constructors

### LexCodeParser() {#ab888b9484e3ea4ac127f6a4e08a66415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexCodeParser::LexCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a>, definition at line 1176 of file <a href="/web-doxygen/docs/api/files/src/lexcode-l">lexcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab888b9484e3ea4ac127f6a4e08a66415">1176</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ab888b9484e3ea4ac127f6a4e08a66415">LexCodeParser::LexCodeParser</a>() : <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/lexcodeparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">  lexcodeYYlex_init_extra(&amp;<a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>-&gt;state, &amp;<a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">  lexcodeYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">Debug::Lex_lexcode</a>)?1:0,<a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab42c158786f3c520dcfd7d7e8d077dd9">resetCodeParserState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">Debug::Lex\_lexcode</a>, <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a> and <a href="#ab42c158786f3c520dcfd7d7e8d077dd9">resetCodeParserState</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LexCodeParser() {#aea06a30d26e093ef35584e22381543c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexCodeParser::~LexCodeParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a>, definition at line 1185 of file <a href="/web-doxygen/docs/api/files/src/lexcode-l">lexcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea06a30d26e093ef35584e22381543c0">1185</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aea06a30d26e093ef35584e22381543c0">LexCodeParser::~LexCodeParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">  lexcodeYYlex_destroy(<a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseCode() {#a907e618c99ef07aa00fc0604062e3929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexCodeParser::parseCode (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, bool stripCodeComments, bool isExampleBlock, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fileDef=nullptr, int startLine=-1, int endLine=-1, bool inlineFragment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * memberDef=nullptr, bool showLineNumbers=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * searchCtx=nullptr, bool collectXRefs=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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

Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a>, definition at line 1197 of file <a href="/web-doxygen/docs/api/files/src/lexcode-l">lexcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a907e618c99ef07aa00fc0604062e3929">1197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a907e618c99ef07aa00fc0604062e3929">LexCodeParser::parseCode</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;codeOutIntf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scopeName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> stripCodeComments,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isExampleBlock,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;exampleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fileDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineFragment,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *memberDef,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showLineNumbers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *searchCtx,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> collectXRefs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">              )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">Debug::Lex_lexcode</a>, __FILE__, fileDef ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileDef-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>()) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;code = &amp;codeOutIntf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString   = input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = fileDef ? fileDef-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">fileName</a>():</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentFontClass = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideCodeLine = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;classScope=scopeName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentMemberDef=memberDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;searchCtx=searchCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;collectXRefs=collectXRefs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;yyLineNr    = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endLine!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = endLine+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputLines  = yyextra-&gt;yyLineNr + <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>(yyscanner) - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;startCCodeLine = yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;stripCodeComments = stripCodeComments;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleBlock  = isExampleBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;exampleName   = exampleName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;sourceFileDef = fileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNumbers   = fileDef!=0 &amp;&amp; showLineNumbers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isExampleBlock &amp;&amp; fileDef==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// create a dummy filedef for the example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),!exampleName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? exampleName : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"generated"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef = yyextra-&gt;exampleFileDef.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;sourceFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"l00001"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;includeCodeFragment = inlineFragment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Starts line 1 on the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">  lexcodeYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( DefSection );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlight">  lexcodeYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideCodeLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;exampleFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// delete the temporary file definition used for this example</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;exampleFileDef.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;sourceFileDef=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/code-l/#a635b111e9953d65f6353bf0d7eb9fb1f">countLines</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a22b46d1ae6472d2565e3bd435f982d16">endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a93e1226e2ce3405e358aebe045c2d691">FileDef::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">Debug::Lex\_lexcode</a>, <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a> and <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>.
</div>
</div>

### resetCodeParserState() {#ab42c158786f3c520dcfd7d7e8d077dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexCodeParser::resetCodeParserState ()</td>
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
<dd><a href="#a907e618c99ef07aa00fc0604062e3929">parseCode()</a></dd>
</dl>


Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a>, definition at line 1190 of file <a href="/web-doxygen/docs/api/files/src/lexcode-l">lexcode.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab42c158786f3c520dcfd7d7e8d077dd9">1190</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab42c158786f3c520dcfd7d7e8d077dd9">LexCodeParser::resetCodeParserState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentDefinition = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;currentMemberDef = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>.

Referenced by <a href="#ab888b9484e3ea4ac127f6a4e08a66415">LexCodeParser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a5368aa527b20abbfee0d01fc5480fa63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; LexCodeParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5368aa527b20abbfee0d01fc5480fa63">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a5368aa527b20abbfee0d01fc5480fa63">p</a>;</span></span></div>

</div>


Referenced by <a href="#ab888b9484e3ea4ac127f6a4e08a66415">LexCodeParser</a>, <a href="#a907e618c99ef07aa00fc0604062e3929">parseCode</a>, <a href="#ab42c158786f3c520dcfd7d7e8d077dd9">resetCodeParserState</a> and <a href="#aea06a30d26e093ef35584e22381543c0">\~LexCodeParser</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/lexcode-h">lexcode.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/lexcode-l">lexcode.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
