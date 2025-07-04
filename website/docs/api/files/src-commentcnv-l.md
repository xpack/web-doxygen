---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/commentcnv-l
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `commentcnv.l` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdint.h&gt;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;stack&gt;
#include &lt;algorithm&gt;
#include &lt;deque&gt;
#include &lt;string_view&gt;
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/aliases-h">aliases.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/stringutil-h">stringutil.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include &lt;assert.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-lex-h">doxygen_lex.h</a>"
#include "commentcnv.l.h"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx">commentcnvYY_CondCtx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/commentctx">CommentCtx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/commentcnv-filestate">commentcnv_FileState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/commentcnvyy-state">commentcnvYY_state</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">yyguts_t * <a href="#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a> (int state)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78caf41f8a8faa0b9acff1d672b192c0">replaceCommentMarker</a> (yyscan_t yyscanner, std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a> (yyscan_t yyscanner, std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af10d5bb9a436e8d3b74fefb86034ea">copyToOutput</a> (yyscan_t yyscanner, const char *s, int len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a> (yyscan_t yyscanner, const QCString &amp;sectId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34860cedec3675010f3293403abd9bd3">endCondSection</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332228bad6aeea89cff9fe039cf62738">handleCondSectionId</a> (yyscan_t yyscanner, const char *expression)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a> (yyscan_t yyscanner, std::string_view s, bool replaceComment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>copies string <em>s</em> with length <em>len</em> to the output, while replacing any alias commands found in the string. <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a> (yyscan_t yyscanner, char *buf, int max_size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a> (yyscan_t yyscanner, int offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a> (yyscan_t yyscanner, const QCString &amp;inc, const QCString &amp;blockId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45d3a0f94b1a775de47c0502e3308ef">parseIncludeOptions</a> (yyscan_t yyscanner, std::string_view s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">yylex</a> (yyscan_t yyscanner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a> (const QCString &amp;text, const QCString &amp;marker, int &amp;blockPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the section of text, in between a pair of markers. <a href="#a21f1fbe9d036424f63e72aad296ccfdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a> (const std::string &amp;inBuf, std::string &amp;outBuf, const std::string &amp;fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Converts the comments in a file. <a href="#a4706ae57556b5cab395e8d2c8ec666b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>&nbsp;&nbsp;&nbsp;10*1024*1024</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">YY_TYPEDEF_YY_SCANNER_T</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85523a0c7d95c059d251b4e9829947aa">YY_NO_INPUT</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78ac56cd1f29572e967ed7636952d15">YY_NO_UNISTD_H</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacfdca45fa4beb8b06172525a53c424a">YY_INPUT</a>(buf, result, max_size)&nbsp;&nbsp;&nbsp;result=<a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(yyscanner,buf,max_size);</td>
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


<div class="doxySectionDef">

## Typedefs

### yyscan\_t {#a9484188abbc459dafcbd4c96425fa70b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef yyguts_t* yyscan_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9484188abbc459dafcbd4c96425fa70b">31</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> yyguts_t *<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### clearCommentStack() {#ac28578b1034a1f4803dd53216ab2bfda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void clearCommentStack (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1575 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac28578b1034a1f4803dd53216ab2bfda">1575</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;commentStack.empty()) yyextra-&gt;commentStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>.</p>

</div>
</div>

### computeIndent() {#a2b4acd8f05e7bebf0528ec710692f758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int computeIndent (const char * s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1513 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b4acd8f05e7bebf0528ec710692f758">1513</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">) col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) col+=tabSize-(col%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>.</p>


<p>Referenced by <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>.</p>

</div>
</div>

### convertCppComments() {#a4706ae57556b5cab395e8d2c8ec666b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void convertCppComments (const std::string &amp; inBuf, std::string &amp; outBuf, const std::string &amp; fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Converts the comments in a file.</p>


<p>This function does three things:</p>


<ol class="doxyList" type="1">
<li>It converts multi-line C++ style comment blocks (that are aligned) to C style comment blocks (if MULTILINE_CPP_IS_BRIEF is set to NO).</li>
<li>It replaces aliases with their definition (see ALIASES)</li>
<li>It handles conditional sections (cond...endcond blocks)</li>
</ol>

<p>Definition at line 1964 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">1964</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;inBuf,std::string &amp;outBuf,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName { fn };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/commentcnvyy-state">commentcnvYY_state</a> extra(&amp;inBuf,outBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  commentcnvYYlex_init_extra(&amp;extra,&amp;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">  commentcnvYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">Debug::Lex_commentcnv</a>)?1:0,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("convertCppComments(%s)\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inBufPos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;col      = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;mlBrief = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MULTILINE_CPP_IS_BRIEF);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;skip     = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lang = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;pythonDocString = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNr   = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;raiseLevel = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;raiseLabel = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;raiseIncrement = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;raisePrefix = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;expandedAliases.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;condStack.empty()) yyextra-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;vhdl = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">Debug::Lex_commentcnv</a>,__FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;isFixedForm = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#acb642f5212285f22eca041cbf6a927c1">convertFileNameFortranParserCode</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;isFixedForm = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(inBuf),<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Markdown)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;nestingCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">    BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">    BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a9a7bd1b3d14701eb97c03f3ef34deff1">yylex</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;condStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx">commentcnvYY_CondCtx</a> &amp;ctx = yyextra-&gt;condStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sectionInfo(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx.<a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#ae1eed597f41d62965e72a0f1a4961d4d">sectionId</a>!=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">) sectionInfo.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">" with label '%s' "</span><span class="doxyHighlight">,ctx.<a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#ae1eed597f41d62965e72a0f1a4961d4d">sectionId</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,ctx.<a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#a6788d979220d7bcd5ed1eaf232060e29">lineNr</a>,</span><span class="doxyHighlightStringLiteral">"Conditional section{}does not have "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"a corresponding \\endcond command within this file."</span><span class="doxyHighlight">,sectionInfo.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;nestingCount&gt;0 &amp;&amp; yyextra-&gt;lang!=SrcLangExt::Markdown &amp;&amp; yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lines;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!yyextra-&gt;commentStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = yyextra-&gt;commentStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first) lines += </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">      lines += <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">      first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;commentStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Reached end of file while still inside a (nested) comment. "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"Nesting level {} (possible line reference(s): {})"</span><span class="doxyHighlight">,yyextra-&gt;nestingCount,lines);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;nestingCount = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">Debug::CommentCnv</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">Debug::CommentCnv</a>,0,</span><span class="doxyHighlightStringLiteral">"-----------\nCommentCnv: {}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightStringLiteral">"output=[\n{}]\n-----------\n"</span><span class="doxyHighlight">,fileName,yyextra-&gt;outBuf</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">                );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  commentcnvYYlex_destroy(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">Debug::CommentCnv</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acb642f5212285f22eca041cbf6a927c1">convertFileNameFortranParserCode</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">Debug::Lex_commentcnv</a>, <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#a6788d979220d7bcd5ed1eaf232060e29">commentcnvYY_CondCtx::lineNr</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#ae1eed597f41d62965e72a0f1a4961d4d">commentcnvYY_CondCtx::sectionId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a9a7bd1b3d14701eb97c03f3ef34deff1">yylex</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#a248b40256877fc3c467046ebf1835a8f">generateHtmlForComment</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>.</p>

</div>
</div>

### copyToOutput() {#a2314542f53572b0bab685a608ea5b249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void copyToOutput (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, std::string_view s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1528 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2314542f53572b0bab685a608ea5b249">1528</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;skip) </span><span class="doxyHighlightComment">// only add newlines.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;len;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(s[i])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;col+=tabSize-(yyextra-&gt;col%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;outBuf+=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;len;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (s[i])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: yyextra-&gt;col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">//fprintf(stderr,"---&gt; copy %d\n",g_lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">                   yyextra-&gt;lineNr++; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">: yyextra-&gt;col+=tabSize-(yyextra-&gt;col%tabSize); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:   yyextra-&gt;col++; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>.</p>


<p>Referenced by <a href="#a6af10d5bb9a436e8d3b74fefb86034ea">copyToOutput</a>, <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>, <a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>, <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a> and <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>.</p>

</div>
</div>

### copyToOutput() {#a6af10d5bb9a436e8d3b74fefb86034ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void copyToOutput (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * s, int len)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1570 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6af10d5bb9a436e8d3b74fefb86034ea">1570</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,std::string_view{s,(size_t)len});</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>.</p>

</div>
</div>

### endCondSection() {#a34860cedec3675010f3293403abd9bd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void endCondSection (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1594 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34860cedec3675010f3293403abd9bd3">1594</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34860cedec3675010f3293403abd9bd3">endCondSection</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;condStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Found \\endcond command without matching \\cond"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;skip=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx">commentcnvYY_CondCtx</a> &amp;ctx = yyextra-&gt;condStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;<a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#a4a056399be29b38e047fb83f1d0682fa">skip</a>=ctx.<a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#a4a056399be29b38e047fb83f1d0682fa">skip</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("endCondSection: skip=%d stack=%d\n",g_skip,g_condStack.count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#a4a056399be29b38e047fb83f1d0682fa">commentcnvYY_CondCtx::skip</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### extractBlock() {#a21f1fbe9d036424f63e72aad296ccfdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString extractBlock (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; marker, int &amp; blockPos)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the section of text, in between a pair of markers.</p>


<p>Full lines are returned, excluding the lines on which the markers appear.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>routine <a href="/web-doxygen/docs/api/files/src/util-cpp/#a29dc16dcef3e9ca42657dcf3bfd8d53a">lineBlock</a></p></dd>
</dl>


<p>Definition at line 1643 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21f1fbe9d036424f63e72aad296ccfdc">1643</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;marker,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;blockPos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1644</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1645</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> p=0,i=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find the character positions of the markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> m1 = text.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(marker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (m1==-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> m2 = text.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(marker,m1+</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(marker.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (m2==-1) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// find start and end line positions for the markers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l1=-1,l2=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!found &amp;&amp; (i=text.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">    found = (p&lt;=m1 &amp;&amp; m1&lt;i); </span><span class="doxyHighlightComment">// found the line with the start marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">    p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">  l1=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">  blockPos=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lp=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=text.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">,p))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;=m2 &amp;&amp; m2&lt;i) </span><span class="doxyHighlightComment">// found the line with the end marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">        l2=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">      p=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">      lp=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l2==-1) </span><span class="doxyHighlightComment">// marker at last line without newline (see bug706874)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">    l2=lp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> l2&gt;l1 ? text.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(l1,l2-l1) : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>.</p>


<p>Referenced by <a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>.</p>

</div>
</div>

### getLexerFILE() {#acb5f8818546103e3b804ab8606b52c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getLexerFILE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb5f8818546103e3b804ab8606b52c4a">166</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acb5f8818546103e3b804ab8606b52c4a">getLexerFILE</a>() {</span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> __FILE__;}</span></span></div>

</div>

</div>
</div>

### handleCondSectionId() {#a332228bad6aeea89cff9fe039cf62738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleCondSectionId (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const char * expression)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1611 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a332228bad6aeea89cff9fe039cf62738">1611</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a332228bad6aeea89cff9fe039cf62738">handleCondSectionId</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *expression)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> oldSkip=yyextra-&gt;skip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(yyscanner,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(expression));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((yyextra-&gt;condCtx==CComment || yyextra-&gt;readLineCtx==SComment) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">      !oldSkip &amp;&amp; yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;lang!=SrcLangExt::VHDL &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;lang!=SrcLangExt::Markdown &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;col+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;readLineCtx==SComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">    BEGIN(SComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    BEGIN(yyextra-&gt;condCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>.</p>

</div>
</div>

### insertCommentStart() {#a514e0fc34f72927bb6d0ad62e0eca7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertCommentStart (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1685 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">1685</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1688</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startCol=yyextra-&gt;blockHeadCol;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1689</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> contentCol=yyextra-&gt;insertCommentCol;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> markerSpace=contentCol-startCol;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("insertCommentStart startCol=%d contentCol=%d mlBrief=%d insertCppCommentMarker=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    yyextra-&gt;blockHeadCol,yyextra-&gt;insertCommentCol,yyextra-&gt;mlBrief,yyextra-&gt;insertCppCommentMarker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string marker;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Python) </span><span class="doxyHighlightComment">// need to insert # or space</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;pythonDocString) </span><span class="doxyHighlightComment">// """! style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">      marker=</span><span class="doxyHighlightStringLiteral">"    "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">      marker=</span><span class="doxyHighlightStringLiteral">"# "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Fortran) </span><span class="doxyHighlightComment">// need to insert !!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">    marker=</span><span class="doxyHighlightStringLiteral">"!! "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Markdown)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">    marker=</span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insertCppCommentMarker) </span><span class="doxyHighlightComment">// need to insert ///</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">    marker=</span><span class="doxyHighlightStringLiteral">"/// "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1716</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startCol&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// insert `///` instead of '* '</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">      startCol--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">      markerSpace++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// need to insert *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">    marker=</span><span class="doxyHighlightStringLiteral">"* "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;i&lt;startCol;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(marker.length())&lt;=markerSpace &amp;&amp; !yyextra-&gt;firstIncludeLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,marker);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">    i+=marker.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;i&lt;contentCol;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;firstIncludeLine = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>.</p>


<p>Referenced by <a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>.</p>

</div>
</div>

### parseIncludeOptions() {#af45d3a0f94b1a775de47c0502e3308ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseIncludeOptions (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, std::string_view s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1401 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af45d3a0f94b1a775de47c0502e3308ef">1401</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af45d3a0f94b1a775de47c0502e3308ef">parseIncludeOptions</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1405</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("parseIncludeOptions=%s\n",qPrint(QCString(s)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1406</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> optIdxStart = s.find(</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> optIdxEnd   = optIdxStart!=std::string::npos ? s.find(</span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">,optIdxStart+1) : std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string cmdName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> optList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (optIdxStart == std::string::npos) </span><span class="doxyHighlightComment">// no options</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">    cmdName = <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(s.substr(1)); </span><span class="doxyHighlightComment">// to remove {CMD}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1414</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// options present</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">    cmdName = <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(s.substr(1,optIdxStart-1)); </span><span class="doxyHighlightComment">// to remove {CMD}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">    optList = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(std::string{s.substr(optIdxStart+1,optIdxEnd-optIdxStart-1)},</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDoc = cmdName==</span><span class="doxyHighlightStringLiteral">"includedoc"</span><span class="doxyHighlight"> || cmdName==</span><span class="doxyHighlightStringLiteral">"snippetdoc"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : optList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(opt)==std::string_view{</span><span class="doxyHighlightStringLiteral">"doc"</span><span class="doxyHighlight">})</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1423</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1424</span><span class="doxyLineContent"><span class="doxyHighlight">      isDoc=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isDoc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;opt : optList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string_view locOpt = <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(opt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1434</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> posEqual = locOpt.find(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1435</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string_view option = posEqual!=std::string::npos ? <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(locOpt.substr(0,posEqual)) : locOpt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string_view value  = posEqual!=std::string::npos ? <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>(locOpt.substr(posEqual+1)) : std::string_view();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option==std::string_view{</span><span class="doxyHighlightStringLiteral">"doc"</span><span class="doxyHighlight">} &amp;&amp; value.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option==std::string_view{</span><span class="doxyHighlightStringLiteral">"raise"</span><span class="doxyHighlight">} &amp;&amp; !value.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;raiseIncrement = atoi(value.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;raiseLevel+yyextra-&gt;raiseIncrement&gt;=<a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>) </span><span class="doxyHighlightComment">// check range</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Raising section level from {} to {}, exceeds allowed range [0-{}], adjusting"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">              yyextra-&gt;raiseLevel,yyextra-&gt;raiseLevel+yyextra-&gt;raiseIncrement,<a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">          yyextra-&gt;raiseIncrement = std::max(0,<a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>-1-yyextra-&gt;raiseLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option==std::string_view{</span><span class="doxyHighlightStringLiteral">"prefix"</span><span class="doxyHighlight">} &amp;&amp; !value.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;raisePrefix = value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Unsupported option '{}' for {} command"</span><span class="doxyHighlight">,option, cmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> isDoc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/sectiontype/#a2f832ab2bf817c8581feb03e123f09d5">SectionType::MaxLevel</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### readIncludeFile() {#acb71ba8a95e7beb78c1e3a685d8696ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readIncludeFile (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inc, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; blockId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1744 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb71ba8a95e7beb78c1e3a685d8696ed">1744</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inc,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;blockId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("readIncludeFile(inc=%s,blockId=%s)\n",qPrint(inc),qPrint(blockId));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ambig = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absFileName = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a103513ad1b948e1fc70ba3a98c761e31">findFilePath</a>(inc,ambig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(absFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!absFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ambig)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"included file name '{}' is ambiguous"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Possible candidates:\n{}"</span><span class="doxyHighlight">,inc, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#ae1bf779155bea73ec696cba27e640e66">Doxygen::exampleNameLinkedMap</a>,inc));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> alreadyProcessed = std::any_of(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;includeStack.begin(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;includeStack.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">      [&amp;absFileName,&amp;blockId](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;lfs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">        { return lfs-&gt;fileName==absFileName &amp;&amp; lfs-&gt;blockId==blockId; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (alreadyProcessed)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!blockId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"recursive usage of '\\snippet{{doc}}' block with name '{}' and file name '{}', skipping"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">             blockId,absFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"recursive usage of '\\include{{doc}}' with file name '{}', skipping"</span><span class="doxyHighlight">, absFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fs = std::make_unique&lt;commentcnv_FileState&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>(absFileName,fs-&gt;fileBuf,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"\\{}{{doc}} file '{}' could not be read"</span><span class="doxyHighlight">,blockId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()?</span><span class="doxyHighlightStringLiteral">"include"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"snippet"</span><span class="doxyHighlight">,absFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">      fs.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!blockId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> incText { fs-&gt;fileBuf };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count = incText.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(blockId.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count!=2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"block marked with {} for \\snippet{{doc}} should appear twice in file {}, found it {:d} times, skipping"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">            blockId,absFileName,count);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">      lineNr = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a29dc16dcef3e9ca42657dcf3bfd8d53a">lineBlock</a>(incText, blockId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> blockPos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">      incText = <a href="#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>(incText, blockId, blockPos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">      fs-&gt;fileBuf.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!incText.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">        fs-&gt;fileBuf.append(incText.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> oldRaiseLevel = yyextra-&gt;raiseLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> oldRaiseLabel = yyextra-&gt;raiseLabel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;raiseLevel+=yyextra-&gt;raiseIncrement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;raiseLabel+=yyextra-&gt;raisePrefix;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineStr=</span><span class="doxyHighlightStringLiteral">" \\ifile \""</span><span class="doxyHighlight">+absFileName+</span><span class="doxyHighlightStringLiteral">"\" \\iline "</span><span class="doxyHighlight"> + std::to_string(lineNr)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;raiseLevel&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">      lineStr+=</span><span class="doxyHighlightStringLiteral">"\\iraise "</span><span class="doxyHighlight"> + std::to_string(yyextra-&gt;raiseLevel)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;raiseLabel.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">      lineStr+=</span><span class="doxyHighlightStringLiteral">"\\iprefix \""</span><span class="doxyHighlight"> + yyextra-&gt;raiseLabel + </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">    lineStr+=</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,lineStr.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;fileName      = absFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;bufState      = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldLineNr     = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldFileName   = yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldState      = yyextra-&gt;includeCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldFileBuf    = yyextra-&gt;inBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldFileBufPos = yyextra-&gt;inBufPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldIncludeCtx = yyextra-&gt;includeCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldRaiseLvl   = oldRaiseLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;oldRaiseLbl   = oldRaiseLabel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">    fs-&gt;blockId       = blockId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">    yy_switch_to_buffer(yy_create_buffer(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, <a href="#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>, yyscanner),yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;fileName = absFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;lineNr   = lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inBuf    = &amp;fs-&gt;fileBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inBufPos = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;includeStack.push_back(std::move(fs));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("switched to %s\n",qPrint(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"\\{}{{doc}} file '{}' not found"</span><span class="doxyHighlight">,blockId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()?</span><span class="doxyHighlightStringLiteral">"include"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"snippet"</span><span class="doxyHighlight">,inc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ae1bf779155bea73ec696cba27e640e66">Doxygen::exampleNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a103513ad1b948e1fc70ba3a98c761e31">findFilePath</a>, <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">FileInfo::isFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a29dc16dcef3e9ca42657dcf3bfd8d53a">lineBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70d0b468521b0304252fb659f3b15e24">showFileDefMatches</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">QCString::view</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a> and <a href="#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>.</p>

</div>
</div>

### replaceAliases() {#a7d6c5be747e636417e19cc8dbbaa38b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceAliases (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, std::string_view s, bool replaceComment=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>copies string <em>s</em> with length <em>len</em> to the output, while replacing any alias commands found in the string.</p>

<p>Definition at line 1853 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d6c5be747e636417e19cc8dbbaa38b9">1853</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,std::string_view s,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos = s.find(</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string cmd { s.substr(1, pos!=std::string::npos ? pos-1 : s.length()-1) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;expAlias = yyextra-&gt;expandedAliases;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::find(expAlias.begin(),expAlias.end(),cmd)!=std::end(expAlias))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// prevent recursive expansion</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cmd==</span><span class="doxyHighlightStringLiteral">"ialias"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.length()&gt;cmd.length()+3) </span><span class="doxyHighlightComment">// \cmd{value}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string value { s.substr(cmd.length()+2,s.length()-cmd.length()-3) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("removing value '%s'\n",qPrint(value));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">      expAlias.erase(std::remove(expAlias.begin(),expAlias.end(),value),expAlias.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string result = <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a6b8eb655dd98d5b700055fc5ae0440dc">resolveAliasCmd</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inVerbatim) </span><span class="doxyHighlightComment">// inside verbatim blocks (like @code...@endcode) only expand aliases if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightComment">// their expansion contains the matching end block marker.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string blk = yyextra-&gt;blockName.str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">    assert(!blk.empty());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isNamedCommand=<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(blk[0]); </span><span class="doxyHighlightComment">// true for e.g. @endcode, false for e.g. ~~~</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0,p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((i=result.find(blk,p))!=std::string::npos &amp;&amp; !found) </span><span class="doxyHighlightComment">// for each match of blk in result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">      found = !isNamedCommand ||                                                                  </span><span class="doxyHighlightComment">// e.g. '~~~' or '--&gt;'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">              (i&gt;0 &amp;&amp; (result[i-1]==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight"> || result[i-1]==</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">) &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(result[i+blk.length()]));  </span><span class="doxyHighlightComment">// e.g. '@endcode' but not ~endcode or @endcodex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">      p = i+yyextra-&gt;blockName.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("blk=%s result=%s found=%d\n",qPrint(blk),qPrint(result),found);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found) </span><span class="doxyHighlightComment">// treat alias as part of the verbatim block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("replaceAliases(%s)-&gt;'%s' replaceComment=%d\n",qPrint(s),qPrint(result),replaceComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result!=s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>) </span><span class="doxyHighlightComment">// In case we are replacing a multiline /// comment by a C style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// and we have new lines in the alias argument, we need to place back a /// for each new line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// to prevent breaking the multiline comment into multiple C style comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a6bd7b0c2ab29fbcc02a4d17b39fb285b">substituteStringView</a>(result,</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\n///"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">    expAlias.push_back(cmd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// add a ialias command to allow expansion of cmd again</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">    result += </span><span class="doxyHighlightStringLiteral">" \\ilinebr \\ialias{"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">    result += cmd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">    result += </span><span class="doxyHighlightStringLiteral">"}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)result.length()-1; i&gt;=0; i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">      unput(result[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>, <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a6b8eb655dd98d5b700055fc5ae0440dc">resolveAliasCmd</a> and <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a6bd7b0c2ab29fbcc02a4d17b39fb285b">substituteStringView</a>.</p>

</div>
</div>

### replaceComment() {#a43d00492ecd78767dd0bf065cc3b8f9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceComment (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, int offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1933 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a43d00492ecd78767dd0bf065cc3b8f9a">1933</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> offset)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;mlBrief || yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=<a href="#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(&amp;yytext[offset]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("i=%d blockHeadCol=%d\n",i,yyextra-&gt;blockHeadCol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i==yyextra-&gt;blockHeadCol || i+1==yyextra-&gt;blockHeadCol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a78caf41f8a8faa0b9acff1d672b192c0">replaceCommentMarker</a>(yyscanner,std::string_view(yytext,yyleng));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" */"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1;i&gt;=0;i--) unput(yytext[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;inSpecialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">      BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>, <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a78caf41f8a8faa0b9acff1d672b192c0">replaceCommentMarker</a>.</p>


<p>Referenced by <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a> and <a href="#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a>.</p>

</div>
</div>

### replaceCommentMarker() {#a78caf41f8a8faa0b9acff1d672b192c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceCommentMarker (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, std::string_view s)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1466 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78caf41f8a8faa0b9acff1d672b192c0">1466</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a78caf41f8a8faa0b9acff1d672b192c0">replaceCommentMarker</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,std::string_view s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> p   = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// copy leading blanks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;len &amp;&amp; (c=s[p]) &amp;&amp; (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;outBuf+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { yyextra-&gt;lineNr++; yyextra-&gt;col=0; } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> { yyextra-&gt;col++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// replace start of comment marker by blanks and the last character by a *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> blanks=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (p&lt;len &amp;&amp; (c=s[p]) &amp;&amp; (c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">    blanks++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">    p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;len &amp;&amp; s[p]==</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// comment-after-item marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">      blanks++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">      p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// end after first !</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (blanks&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (blanks&gt;2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">      blanks--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (blanks&gt;1) { yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">; yyextra-&gt;col++; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// copy comment line to output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;outBuf+=s.substr(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;col+=s.substr(p).length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>.</p>

</div>
</div>

### startCondSection() {#a0ec58197ab496c7ea5a9be5edb5d6073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startCondSection (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sectId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1581 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ec58197ab496c7ea5a9be5edb5d6073">1581</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sectId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("startCondSection: skip=%d stack=%d\n",g_skip,g_condStack.count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/condparser">CondParser</a> prs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> expResult = prs.<a href="/web-doxygen/docs/api/classes/condparser/#af254c02cc742b034cf62a9846b7b9749">parse</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,sectId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;condStack.emplace(yyextra-&gt;lineNr,sectId,yyextra-&gt;skip);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!expResult) </span><span class="doxyHighlightComment">// not enabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;skip=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/condparser/#af254c02cc742b034cf62a9846b7b9749">CondParser::parse</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a332228bad6aeea89cff9fe039cf62738">handleCondSectionId</a>.</p>

</div>
</div>

### stateToString() {#a6458e40b3ca285dc65cd5df59d63e5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * stateToString (int state)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<p>Reference <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>.</p>

</div>
</div>

### yylex() {#a1d80d8ed8c19744ed31163f6e7525e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yylex (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d80d8ed8c19744ed31163f6e7525e54">252</a></span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{NUMBER}</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">//Note similar code in code.l</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Cpp) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">                                      <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;[^"'!\/\n\\#,\-=; \t@$]*</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">/* eat anything that is not " / , or \n */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;[,= ;\t]</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">/* eat , so we have a nice separator in long initialization lines */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"'''"!</span><span class="doxyHighlight">                        |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"\"\"\""!</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">/* start of python long comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;pythonDocString = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;pythonDocStringChar = yytext[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"'''"</span><span class="doxyHighlight">                        |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"\"\"\""</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">/* start of python long comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PYTHON_DOCSTRING))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">                                     { </span><span class="doxyHighlightComment">/* handle as if """! */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;pythonDocString = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;pythonDocStringChar = yytext[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{B}*![&gt;&lt;!]/.*\n</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount=0; </span><span class="doxyHighlightComment">// Fortran doesn't have an end comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;specialComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=yyextra-&gt;col-2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;[Cc\*][&gt;&lt;!]/.*\n</span><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">/* check for fixed format; we might have some conditional as part of multiline if like C&lt;5 .and. &amp; */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;isFixedForm &amp;&amp; (yyextra-&gt;col == 0))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;nestingCount=0; </span><span class="doxyHighlightComment">// Fortran doesn't have an end comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;specialComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;blockHeadCol=yyextra-&gt;col-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">                                         BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">                                         REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;!.*\n</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;[Cc\*].*\n</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;col == 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">                                         REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;[$]?"@\""</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">/* start of an interpolated verbatim C# string */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::CSharp) REJECT</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;stringContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(SkipVerbString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"\""</span><span class="doxyHighlight">                         { </span><span class="doxyHighlightComment">/* start of a string */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;stringContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(SkipString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;'</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;charContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(SkipChar);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;\n</span><span class="doxyHighlight">                           { </span><span class="doxyHighlightComment">/* new line */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CPPC}[!/]/.*\n[ \t]*{CPPC}[!/][ \t]*{CMD}"}"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// see bug #8731, don't treat multiline C++ comment as detailed description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">                                                      </span><span class="doxyHighlightComment">// if the next line is an end of group marker.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inSpecialComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockHeadCol=yyextra-&gt;col+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CPPC}"!"/.*\n[ \t]*{CPPC}[\/!][^\/]</span><span class="doxyHighlight"> | </span><span class="doxyHighlightComment">/* start C++ style special comment block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;({CPPC}"/"[/]*)/[^/].*\n[ \t]*{CPPC}[\/!][^\/]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* start C++ style special comment block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;mlBrief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT; </span><span class="doxyHighlightComment">// bail out if we do not need to convert</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[2]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng &amp;&amp; yytext[i]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=yyextra-&gt;col+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[2] == </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"/*!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"/**"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;yyleng) <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>(yyscanner,yytext+i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inSpecialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">//BEGIN(SComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;readLineCtx=SComment;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CPPC}"##Documentation"{ANYopt}/\n</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">/* Start of Rational Rose ANSI C++ comment block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;mlBrief) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=17; </span><span class="doxyHighlightComment">//=strlen("//##Documentation");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockHeadCol=yyextra-&gt;col+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"/**"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;yyleng) <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>(yyscanner,yytext+i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inRoseComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(SComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CPPC}[!\/]/.*\n[ \t]*{CPPC}[|\/][ \t]*[@\\]"}"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// next line contains an end marker, see bug 752712</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inSpecialComment=yytext[2]==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> || yytext[2]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inSpecialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=yyextra-&gt;col+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CPPC}[!/]/.*\n</span><span class="doxyHighlight">              { </span><span class="doxyHighlightComment">/* one line special C++ comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inSpecialComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockHeadCol=yyextra-&gt;col+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CPPC}/.*\n</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">/* one line normal C++ comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inSpecialComment=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(CopyLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CCS}{CCE}</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">/* avoid matching next rule for empty C comment, see bug 711723 */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{CCS}[*!]?</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">/* start of a C comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Python)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;specialComment=(int)yyleng==3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;nestingCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;specialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CNComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"#"[^\n]*\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::PHP)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"#"("#")?</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount=0; </span><span class="doxyHighlightComment">// Python doesn't have an end comment for #</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;specialComment=(int)yyleng==2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;specialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;blockHeadCol=yyextra-&gt;col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"--"[^!][^\n]*</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"--!"</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;specialComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=yyextra-&gt;col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;vhdl = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount=0;  </span><span class="doxyHighlightComment">// VHDL doesn't have an end comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;{B}*![&gt;&lt;!]</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount=0;  </span><span class="doxyHighlightComment">// Fortran doesn't have an end comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner); </span><span class="doxyHighlightComment">/*  to be on the save side */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;specialComment=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=yyextra-&gt;col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment,ReadLine,IncludeFile&gt;{MAILADDR}</span><span class="doxyHighlight">       |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment,ReadLine,IncludeFile&gt;"&lt;"{MAILADDR}"&gt;"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// Mail address, to prevent seeing e.g x@code-factory.org as start of a code block</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,IncludeFile&gt;"{"[ \t]*"@code"/[ \t\n]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"@iliteral{code}"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;javaBlock=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">)+&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(VerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,IncludeFile&gt;"{"[ \t]*"@literal"/[ \t\n]</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"@iliteral"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;javaBlock=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">)+&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(VerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;{CMD}"ilinebr"[ \t]+("```"[`]*|"~~~"[~]*)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* start of markdown code block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;javaBlock=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(3); </span><span class="doxyHighlightComment">// take the ``` or ~~~ part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(VerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;^[ \t]*("```"[`]*|"~~~"[~]*)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* start of markdown code block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;javaBlock=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(3); </span><span class="doxyHighlightComment">// take the ``` or ~~~ part</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(VerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]("dot"|"code"|"msc"|"startuml")/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* start of a verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;javaBlock=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(&amp;yytext[1],</span><span class="doxyHighlightStringLiteral">"startuml"</span><span class="doxyHighlight">)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">"enduml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">)+&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(VerbatimCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]("f$"|"f["|"f{"|"f(")</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;blockName.at(1)==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockName.at(1)=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;blockName.at(1)==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockName.at(1)=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;blockName.at(1)==</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockName.at(1)=</span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(Verbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;"&lt;!--!"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* HTML comment doxygen command*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inVerbatim) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">//copyToOutput(yyscanner,"     ",5);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inHtmlDoxygenCommand=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;"--&gt;"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* potential end HTML comment doxygen command*/</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inHtmlDoxygenCommand)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inHtmlDoxygenCommand=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;"&lt;!--"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* HTML comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=</span><span class="doxyHighlightStringLiteral">"--&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(Verbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]("verbatim"|"iliteral"|"latexonly"|"htmlonly"|"xmlonly"|"docbookonly"|"rtfonly"|"manonly")/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* start of a verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockName=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"end"</span><span class="doxyHighlight">)+&amp;yytext[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastCommentContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(Verbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"\\\""</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">/* escaped double quote */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;"\\\\"</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">/* escaped backslash */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Scan&gt;.</span><span class="doxyHighlight">                            { </span><span class="doxyHighlightComment">/* any other character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Verbatim&gt;[\\@]("endverbatim"|"endiliteral"|"endlatexonly"|"endhtmlonly"|"endxmlonly"|"enddocbookonly"|"endrtfonly"|"endmanonly"|"f$"|"f]"|"f}"|"f)")</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* end of verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;yytext[1]==yyextra-&gt;blockName) </span><span class="doxyHighlightComment">// end of command or formula</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;lastCommentContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Verbatim&gt;"--&gt;"</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext==yyextra-&gt;blockName) </span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;lastCommentContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VerbatimCode&gt;"{"</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;javaBlock==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;javaBlock++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VerbatimCode&gt;"}"</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;javaBlock==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;javaBlock--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;javaBlock==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" @endiliteral "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">                                         BEGIN(yyextra-&gt;lastCommentContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VerbatimCode&gt;("```"[`]*|"~~~"[~]*)</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* end of markdown code block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[0]==yyextra-&gt;blockName[0])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;lastCommentContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VerbatimCode&gt;[\\@]("enddot"|"endcode"|"endmsc"|"enduml")/("{")?</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* end of verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;yytext[1]==yyextra-&gt;blockName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;lastCommentContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;VerbatimCode&gt;^[ \t]*{CPPC}[\!\/]?</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">/* skip leading comments */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;inSpecialComment || yyextra-&gt;mlBrief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (yytext[l]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || yytext[l]==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">                                         l++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyleng-l==3) </span><span class="doxyHighlightComment">// ends with //! or ///</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" * "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// ends with //</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"//"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Verbatim,VerbatimCode&gt;[^`~@\/\-\\\n{}]*</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* any character not a backslash or new line or } */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Verbatim,VerbatimCode&gt;\n</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">/* new line in verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lastCommentContext == IncludeFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Verbatim&gt;^[ \t]*{CPPC}[/!]</span><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;blockName==</span><span class="doxyHighlightStringLiteral">"enddot"</span><span class="doxyHighlight"> || yyextra-&gt;blockName==</span><span class="doxyHighlightStringLiteral">"endmsc"</span><span class="doxyHighlight"> || yyextra-&gt;blockName==</span><span class="doxyHighlightStringLiteral">"enduml"</span><span class="doxyHighlight"> || yyextra-&gt;blockName.at(0)==</span><span class="doxyHighlightCharLiteral">'f'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">// see bug 487871, strip /// from dot images and formulas.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (yytext[l]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || yytext[l]==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">                                         l++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"   "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// even slashes are verbatim (e.g. \verbatim, \code)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;Verbatim,VerbatimCode&gt;.</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">/* any other character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;\\.</span><span class="doxyHighlight">                    { </span><span class="doxyHighlightComment">/* escaped character in string */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Fortran || yyextra-&gt;lang==SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">                                       unput(yytext[1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;"\""</span><span class="doxyHighlight">                   { </span><span class="doxyHighlightComment">/* end of string */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;.</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">/* any other string character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipString&gt;\n</span><span class="doxyHighlight">                     { </span><span class="doxyHighlightComment">/* new line inside string (illegal for some compilers) */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbString&gt;[^"\n]+</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbString&gt;\"\"</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">// escaped quote</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbString&gt;"\""</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">/* end of string */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;stringContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbString&gt;.</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipVerbString&gt;\n</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipChar&gt;\\.</span><span class="doxyHighlight">                      { </span><span class="doxyHighlightComment">/* escaped character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Fortran || yyextra-&gt;lang==SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">                                       unput(yytext[1]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipChar&gt;'</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">/* end of character literal */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;charContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipChar&gt;.</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">/* any other string character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipChar&gt;\n</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">/* new line character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;[^ `~&lt;\\!@*\n{\"'\/-]*</span><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">/* anything that is not a '*' or command */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;^{B}*"*"+[^*\/&lt;\\@\n{\"]*</span><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">/* stars without slashes */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Markdown) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;col = <a href="#a2b4acd8f05e7bebf0528ec710692f758">computeIndent</a>(yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;col&gt;yyextra-&gt;blockHeadCol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">//printf("new blockHeadCol=%d\n",yyextra-&gt;blockHeadCol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;blockHeadCol=yyextra-&gt;col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment&gt;"'''"</span><span class="doxyHighlight">                    |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment&gt;"\"\"\""</span><span class="doxyHighlight">                 { </span><span class="doxyHighlightComment">/* end of Python docstring */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;pythonDocStringChar != yytext[0])</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;pythonDocString = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;pythonDocStringChar = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;\n</span><span class="doxyHighlight">             { </span><span class="doxyHighlightComment">/* new line in comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">/* in case of Fortran always end of comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;"/""/"+/"*/"</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">/* we are already in C-comment so not a start of a nested comment but</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                      * just the end of the comment (the end part is handled later). */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;"/"+"*"</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">/* nested C comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Python ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;lang==SrcLangExt::Markdown)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;nestingCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;commentStack.push(yyextra-&gt;lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;^{B}*"*"+"/"</span><span class="doxyHighlight">   |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;"*"+"/"</span><span class="doxyHighlight">                  { </span><span class="doxyHighlightComment">/* end of C comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Python ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;lang==SrcLangExt::Markdown)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;nestingCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;nestingCount&lt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">                                         BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightComment">//yyextra-&gt;nestingCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;commentStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* Python an VHDL share CComment,CNComment, so special attention for ending comments is required */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;"\n"/[ \t]*"#"</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vhdl) </span><span class="doxyHighlightComment">// inside --! comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;vhdl = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">                                         BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// C-type comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">                                         REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;"\n"/[ \t]*"-"</span><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python || yyextra-&gt;pythonDocString)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;"\n"/[ \t]*[^ \t#\-]</span><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::Python)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;pythonDocString)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">                                         REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">                                         BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang==SrcLangExt::VHDL)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;vhdl) </span><span class="doxyHighlightComment">// inside --! comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;vhdl = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">                                         BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// C-type comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">                                         REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightComment">/* removed for bug 674842 (bug was introduced in rev 768)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;CComment,CNComment&gt;"'"                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                     yyextra-&gt;charContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                     copyToOutput(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                     BEGIN(SkipChar);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;CComment,CNComment&gt;"\""                           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                     yyextra-&gt;stringContext = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                     copyToOutput(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                     BEGIN(SkipString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlightComment">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlightComment">   */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;{CMD}"~"[a-z_A-Z-]*</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// language switch command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Markdown) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> langId = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!langId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config_getEnumAsString</a>(OUTPUT_LANGUAGE),langId)!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">                                     { </span><span class="doxyHighlightComment">// enable language specific section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a6f9c44a0d76faf919b0517a9931d6817">Config_isAvailableEnum</a>(OUTPUT_LANGUAGE,langId))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightStringLiteral">"non supported language '{}' specified in '{}'"</span><span class="doxyHighlight">,langId,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(SkipLang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;{CMD}{CMD}</span><span class="doxyHighlight">     |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment&gt;.</span><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLang&gt;{CMD}"~"[a-zA-Z-]*</span><span class="doxyHighlight">       { </span><span class="doxyHighlightComment">/* language switch */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> langId(&amp;yytext[2]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!langId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a6f9c44a0d76faf919b0517a9931d6817">Config_isAvailableEnum</a>(OUTPUT_LANGUAGE,langId))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">                                        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">                                        </span><span class="doxyHighlightStringLiteral">"non supported language '{}' specified in '{}'"</span><span class="doxyHighlight">,langId,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(yytext).<a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (langId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">                                         <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config_getEnumAsString</a>(OUTPUT_LANGUAGE),langId)==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">                                     { </span><span class="doxyHighlightComment">// enable language specific section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(CComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLang&gt;[^*@\\\n]*</span><span class="doxyHighlight">               { </span><span class="doxyHighlightComment">/* any character not a *, @, backslash or new line */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLang&gt;\n</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">/* new line in language block, needed for keeping track of line numbers */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SkipLang&gt;.</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">/* any other character */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;^[ \t]*{CPPC}"/"{SLASHopt}/\n</span><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}"/"{SLASHopt}/\n</span><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;^[ \t]*{CPPC}"/"[^\/\n]/.*\n</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1040</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}[\/!]("&lt;")?[ \t]*[\\@]"}".*\n</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1045</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">/* See Bug 752712: end the multiline comment when finding a @} or \} command */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" */"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inSpecialComment=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inRoseComment=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1050</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}"/"[^\\@\/\n]/.*\n</span><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;^[ \t]*{CPPC}"!"</span><span class="doxyHighlight">             |    </span><span class="doxyHighlightComment">// just //!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1058</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;^[ \t]*{CPPC}"!&lt;"/.*\n</span><span class="doxyHighlight">       |    </span><span class="doxyHighlightComment">// or   //!&lt; something</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;^[ \t]*{CPPC}"!"[^&lt;]/.*\n</span><span class="doxyHighlight">    {    </span><span class="doxyHighlightComment">// or   //!something</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}"!"</span><span class="doxyHighlight">            |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}"!&lt;"/.*\n</span><span class="doxyHighlight">      |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}"!"[^&lt;\n]/.*\n</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;^[ \t]*{CPPC}"##"/.*\n</span><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;inRoseComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1081</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1082</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n[ \t]*{CPPC}"##"/.*\n</span><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;inRoseComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">                                       REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1087</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1088</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>(yyscanner,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;readLineCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1092</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(ReadLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1093</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SComment&gt;\n</span><span class="doxyHighlight">                       { </span><span class="doxyHighlightComment">/* end of special comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" */"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1097</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1098</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inSpecialComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;inRoseComment=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;readLineCtx = Scan; </span><span class="doxyHighlightComment">// reset, otherwise there will be problems with:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">                                                                  </span><span class="doxyHighlightComment">//   static void handleCondSectionId</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(Scan);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine&gt;{CCS}"*"</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1106</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"/&amp;zwj;**"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1107</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1108</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine&gt;{CCE}</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"*&amp;zwj;/"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine,CopyLine&gt;"*"</span><span class="doxyHighlight">             {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1114</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine,CopyLine&gt;{RL}</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1115</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine,CopyLine&gt;{RL}/{B}{CMD}"ilinebr"{B}</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1120</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine,CopyLine&gt;{RLopt}/\n</span><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1121</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;readLineCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1125</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment,ReadLine&gt;"\\&lt;"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* escaped html comment */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1126</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,CNComment,ReadLine&gt;[\\@][\\@][~a-z_A-Z][a-z_A-Z0-9]*[ \t]*</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// escaped command</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1132</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]("include"{OPTS}|"includedoc"{OPTS}*)</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#af45d3a0f94b1a775de47c0502e3308ef">parseIncludeOptions</a>(yyscanner,std::string_view{yytext,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyleng)})) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;includeCtx = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;firstIncludeLine = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCommentCol = yyextra-&gt;col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;insertCppCommentMarker &amp;&amp; (yyextra-&gt;includeCtx==ReadLine || yyextra-&gt;includeCtx==IncludeFile))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1138</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;insertCppCommentMarker = yyextra-&gt;mlBrief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">//printf("blockHeadCol=%d insertCommentCol=%d\n",yyextra-&gt;blockHeadCol, yyextra-&gt;insertCommentCol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(IncludeDoc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1144</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]("snippet"{OPTS}|"snippetdoc"{OPTS}*)</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#af45d3a0f94b1a775de47c0502e3308ef">parseIncludeOptions</a>(yyscanner,std::string_view{yytext,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyleng)})) REJECT;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;includeCtx = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;firstIncludeLine = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCommentCol = yyextra-&gt;col;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1149</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;insertCppCommentMarker &amp;&amp; (yyextra-&gt;includeCtx==ReadLine || yyextra-&gt;includeCtx==IncludeFile))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1150</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;insertCppCommentMarker = yyextra-&gt;mlBrief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">//printf("blockHeadCol=%d insertCommentCol=%d\n",yyextra-&gt;blockHeadCol, yyextra-&gt;insertCommentCol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(SnippetDoc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeDoc,SnippetDoc&gt;{B}*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeDoc&gt;{FILEMASK}|"\""[^\n\"]+"\""</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yytext[0]==</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">                                       fileName=fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1,fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-2); </span><span class="doxyHighlightComment">// strip quotes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(yyscanner,fileName,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(IncludeFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;includeCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SnippetDoc&gt;({FILEMASK}|"\""[^\n\"]+"\""){B}+</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;snippetFileName=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;snippetFileName=yyextra-&gt;snippetFileName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1175</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;snippetFileName == </span><span class="doxyHighlightStringLiteral">"this"</span><span class="doxyHighlight">) yyextra-&gt;snippetFileName=yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1176</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;snippetName = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(SnippetDocTag);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SnippetDocTag&gt;[^\\@\n]+</span><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;snippetName += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SnippetDocTag&gt;{CMD}</span><span class="doxyHighlight">               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;snippetName += yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1184</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1185</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;SnippetDocTag&gt;(\n|{CMD}"ilinebr")</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)yyleng-1;i&gt;=0;i--) unput(yytext[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;snippetName = yyextra-&gt;snippetName.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> blockId = </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">+yyextra-&gt;snippetName+</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>(yyscanner,yyextra-&gt;snippetFileName,blockId))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1190</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1191</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(IncludeFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;includeCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1196</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1197</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeDoc,SnippetDoc&gt;\n</span><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1202</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">// missing file name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1203</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightComment">//warn(yyextra-&gt;fileName,yyextra-&gt;lineNr,"Found \\include{{doc}} command without valid file name argument");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;includeCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeDoc,SnippetDoc&gt;.</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// invalid character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1208</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;includeCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1209</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]"cond"/[^a-z_A-Z0-9]</span><span class="doxyHighlight">           { </span><span class="doxyHighlightComment">// conditional section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;condCtx = YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(CondLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1214</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]"endcond"/[^a-z_A-Z0-9]</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// end of conditional section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1215</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> oldSkip=yyextra-&gt;skip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a34860cedec3675010f3293403abd9bd3">endCondSection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==CComment &amp;&amp; oldSkip &amp;&amp; !yyextra-&gt;skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">//printf("** Adding start of comment!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1220</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lang!=SrcLangExt::Python &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1221</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;lang!=SrcLangExt::VHDL &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;lang!=SrcLangExt::Markdown &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;lang!=SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">                                         yyextra-&gt;col+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">                                         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;specialComment)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">                                         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;outBuf+=</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">                                         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1235</span><span class="doxyLineContent"><span class="doxyHighlight">                                    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1236</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CondLine&gt;[!()&amp;| \ta-z_A-Z0-9.\-]+</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a332228bad6aeea89cff9fe039cf62738">handleCondSectionId</a>(yyscanner,yytext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile&gt;[\\@]"cond"{WSopt}/\n</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;condCtx=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a332228bad6aeea89cff9fe039cf62738">handleCondSectionId</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// fake section id causing the section to be hidden unconditionally</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CondLine&gt;\n</span><span class="doxyHighlight">                       |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1244</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CondLine&gt;.</span><span class="doxyHighlight">                        { </span><span class="doxyHighlightComment">// forgot section id?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1245</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a332228bad6aeea89cff9fe039cf62738">handleCondSectionId</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// fake section id causing the section to be hidden unconditionally</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*yytext==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile,Verbatim,VerbatimCode&gt;[\\@][a-z_A-Z][a-z_A-Z0-9-]*</span><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// expand alias without arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>(yyscanner,yytext,YY_START==ReadLine &amp;&amp; yyextra-&gt;readLineCtx==SComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1251</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile,Verbatim,VerbatimCode&gt;{B}?{CMD}"ilinebr"{B}[\\@]"ialias{"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// expand alias with arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1252</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastBlockContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraSpace = (yytext[0]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">? 1:0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString=yytext+9+extraSpace;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasCmd=yytext+9+extraSpace;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1257</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1258</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN( ReadAliasArgs );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CComment,ReadLine,IncludeFile,Verbatim,VerbatimCode&gt;[\\@][a-z_A-Z][a-z_A-Z0-9-]*"{"</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">// expand alias with arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastBlockContext=YY_START;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1262</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;blockCount=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1263</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasCmd=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN( ReadAliasArgs );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1267</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1268</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;^[ \t]*"*"</span><span class="doxyHighlight">          { </span><span class="doxyHighlightComment">// skip leading *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;^[ \t]*{CPPC}[/!]/[^\n]*</span><span class="doxyHighlight">   { </span><span class="doxyHighlightComment">// skip leading special comments (see bug 618079)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;[^{}\n\\\*]+</span><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1273</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1274</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;"\\"</span><span class="doxyHighlight">                {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lastEscaped)  yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1278</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">                yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1279</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;[\\@]("endverbatim"|"endiliteral"|"endlatexonly"|"endhtmlonly"|"endxmlonly"|"enddocbookonly"|"endrtfonly"|"endmanonly"|"f$"|"f]"|"f}"|"f)")</span><span class="doxyHighlight"> { </span><span class="doxyHighlightComment">/* end of verbatim block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inVerbatim &amp;&amp; &amp;yytext[1]==yyextra-&gt;blockName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// For verbatim sections we do not support matching end block markers inside</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// alias arguments. Instead this will end the verbatim block.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// This is needed to support an alias definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// like startalign=" \latexonly\noalign{\endlatexonly" were otherwise</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// the scanner would try to find a matching closing brace for noalign and then</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// skip over the \endlatexonly command.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yyextra-&gt;aliasString.view());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inVerbatim=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(yyextra-&gt;lastCommentContext);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;\n</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;inVerbatim) </span><span class="doxyHighlightComment">// for verbatim sections we do not support multi-line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">                                                              </span><span class="doxyHighlightComment">// alias arguments.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yyextra-&gt;aliasString.view());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1303</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN( yyextra-&gt;lastBlockContext );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;"{"</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1308</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;lastEscaped) yyextra-&gt;blockCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;"}"</span><span class="doxyHighlight">                 {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;lastEscaped) yyextra-&gt;blockCount--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;blockCount==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>(yyscanner,yyextra-&gt;aliasString.view(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;lastBlockContext==ReadLine &amp;&amp; yyextra-&gt;readLineCtx==SComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN( yyextra-&gt;lastBlockContext );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadAliasArgs&gt;.</span><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;aliasString+=yytext;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;lastEscaped=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine&gt;.</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;CopyLine&gt;\n</span><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">                                     yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">                                     BEGIN(yyextra-&gt;readLineCtx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine&gt;```</span><span class="doxyHighlight">                      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine&gt;`[^`]+`</span><span class="doxyHighlight">                  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine&gt;{CMD}{CMD}</span><span class="doxyHighlight">               |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;ReadLine&gt;.</span><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeFile&gt;.</span><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;IncludeFile&gt;\n</span><span class="doxyHighlight">                    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a514e0fc34f72927bb6d0ad62e0eca7b3">insertCommentStart</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;*&gt;.</span><span class="doxyHighlight">                               {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,yytext,yyleng);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">&lt;&lt;EOF&gt;&gt;</span><span class="doxyHighlight">                            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START == ReadAliasArgs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">                                           </span><span class="doxyHighlightStringLiteral">"Reached end of file while still searching closing '}}' of an alias argument (probable start: '{}')"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">                                           yyextra-&gt;aliasCmd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;includeStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;insertCppCommentMarker=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#ac3286b18a2e91b4571b97df96a118e84">yyterminate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// switch back to parent file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">                                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">                                       std::unique_ptr&lt;commentcnv_FileState&gt; &amp;fs = yyextra-&gt;includeStack.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">                                       YY_BUFFER_STATE oldBuf = YY_CURRENT_BUFFER;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yy_switch_to_buffer(fs-&gt;bufState, yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yy_delete_buffer(oldBuf, yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">                                       BEGIN(fs-&gt;oldState);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;fileName      = fs-&gt;oldFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;lineNr        = fs-&gt;oldLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inBuf         = fs-&gt;oldFileBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;inBufPos      = fs-&gt;oldFileBufPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;includeCtx    = fs-&gt;oldIncludeCtx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineStr= </span><span class="doxyHighlightStringLiteral">" \\ifile \""</span><span class="doxyHighlight">+yyextra-&gt;fileName+</span><span class="doxyHighlightStringLiteral">"\" \\iline "</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(yyextra-&gt;lineNr)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs-&gt;oldRaiseLvl!=yyextra-&gt;raiseLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">                                          lineStr+=</span><span class="doxyHighlightStringLiteral">"\\iraise "</span><span class="doxyHighlight"> + std::to_string(fs-&gt;oldRaiseLvl)+ </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fs-&gt;oldRaiseLbl!=yyextra-&gt;raiseLabel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">                                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">                                          lineStr+=</span><span class="doxyHighlightStringLiteral">"\\iprefix \""</span><span class="doxyHighlight"> + fs-&gt;oldRaiseLbl + </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">                                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">                                       lineStr+=</span><span class="doxyHighlightStringLiteral">"\\ilinebr "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;raiseLevel    = fs-&gt;oldRaiseLvl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;raiseLabel    = fs-&gt;oldRaiseLbl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">                                       <a href="#a2314542f53572b0bab685a608ea5b249">copyToOutput</a>(yyscanner,lineStr.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">                                       yyextra-&gt;includeStack.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">//printf("&lt;&lt;EOF&gt;&gt; switch back to %s line %d inbufPos=%d outbufPos=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">//    qPrint(yyextra-&gt;fileName),yyextra-&gt;lineNr,yyextra-&gt;inBufPos,yyextra-&gt;outBuf.curPos());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">                                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">                                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlightComment">&lt;*&gt;\n  { fprintf(stderr,"Lex scanner %s (%s) default rule newline for state %s.\n", __FILE__, qPrint(yyextra-&gt;fileName),stateToString(YY_START));}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlightComment">  */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">%%</span></span></div>

</div>

</div>
</div>

### yyread() {#a5edfc25f0c460f3263fdb340f7a02b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int yyread (<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner, char * buf, int max_size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1923 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5edfc25f0c460f3263fdb340f7a02b03">1923</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(<a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *buf,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> max_size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bytesInBuf = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(yyextra-&gt;inBuf-&gt;size())-yyextra-&gt;inBufPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bytesToCopy = std::min(max_size,bytesInBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">  memcpy(buf,yyextra-&gt;inBuf-&gt;data()+yyextra-&gt;inBufPos,bytesToCopy);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inBufPos+=bytesToCopy;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> bytesToCopy;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### YY\_BUF\_SIZE {#ae7e51116e747d3390e7a6cfc6532834c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_BUF_SIZE&nbsp;&nbsp;&nbsp;10*1024*1024</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7e51116e747d3390e7a6cfc6532834c">19</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  #define YY_BUF_SIZE 10*1024*1024  </span><span class="doxyHighlightComment">// 10Mb should be sufficient for a source file</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ab0ed44ca62a9c1f9a33f3be549b9bd2f">DocTokenizer::pushContext</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a> and <a href="#acb71ba8a95e7beb78c1e3a685d8696ed">readIncludeFile</a>.</p>

</div>
</div>

### YY\_INPUT {#aacfdca45fa4beb8b06172525a53c424a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_INPUT(buf, result, max_size)&nbsp;&nbsp;&nbsp;result=<a href="/web-doxygen/docs/api/files/src/code-l/#a5edfc25f0c460f3263fdb340f7a02b03">yyread</a>(yyscanner,buf,max_size);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacfdca45fa4beb8b06172525a53c424a">163</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_INPUT(buf,result,max_size) result=yyread(yyscanner,buf,max_size);</span></span></div>

</div>

</div>
</div>

### YY\_NO\_INPUT {#a85523a0c7d95c059d251b4e9829947aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_NO_INPUT&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85523a0c7d95c059d251b4e9829947aa">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_INPUT 1</span></span></div>

</div>

</div>
</div>

### YY\_NO\_UNISTD\_H {#ae78ac56cd1f29572e967ed7636952d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_NO_UNISTD_H&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae78ac56cd1f29572e967ed7636952d15">59</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_NO_UNISTD_H 1</span></span></div>

</div>

</div>
</div>

### YY\_TYPEDEF\_YY\_SCANNER\_T {#a5d5508008cac8fb66fca3baa4e9b6584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define YY_TYPEDEF_YY_SCANNER_T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d5508008cac8fb66fca3baa4e9b6584">29</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define YY_TYPEDEF_YY_SCANNER_T</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
