---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/commentscanner
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CommentScanner` Class Reference



## Declaration

<div class="doxyDeclaration">
class CommentScanner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/commentscan-h">src/commentscan.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cc03eb4b903175c815dbbe1c9caa027">CommentScanner</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa006b1543c5de0b520f2ee928e88871c">~CommentScanner</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e48aae075e2f44ddd785428b4099f4a">parseCommentBlock</a> (OutlineParserInterface *parser, Entry *curEntry, const QCString &amp;comment, const QCString &amp;fileName, int &amp;lineNr, bool isBrief, bool isJavadocStyle, bool isInbody, Protection &amp;prot, int &amp;position, bool &amp;newEntryNeeded, bool markdownEnabled, GuardedSectionStack *guards)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invokes the comment block parser with the request to parse a single comment block. <a href="#a2e48aae075e2f44ddd785428b4099f4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f7ae2b80985063ee4a58fcb3ec2aec">initGroupInfo</a> (Entry *entry)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd752e50202fc1d4d2929595b003c8c9">enterFile</a> (const QCString &amp;fileName, int lineNr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7b5eed8e5966a5023d12fd9b31efb7d">leaveFile</a> (const QCString &amp;fileName, int lineNr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955869dba74b22b97c0e86bcdc4b544b">enterCompound</a> (const QCString &amp;fileName, int line, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0c65d943ed68cacf891b2ec38db5fe">leaveCompound</a> (const QCString &amp;fileName, int line, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfece08838426aae997a4faa419cc6c">open</a> (Entry *e, const QCString &amp;fileName, int line, bool implicit=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a109f854249ba68441071ceb95a4b159e">close</a> (Entry *e, const QCString &amp;fileName, int line, bool foundInline, bool implicit=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/commentscanner/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bf2d143820f6862f172772b3f22b98e">p</a></td>
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


<p>Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CommentScanner() {#a4cc03eb4b903175c815dbbe1c9caa027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CommentScanner::CommentScanner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4703 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cc03eb4b903175c815dbbe1c9caa027">4703</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a4cc03eb4b903175c815dbbe1c9caa027">CommentScanner::CommentScanner</a>() : <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/commentscanner/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4704</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4705</span><span class="doxyLineContent"><span class="doxyHighlight">  commentscanYYlex_init_extra(&amp;<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;extra,&amp;<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4706</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4707</span><span class="doxyLineContent"><span class="doxyHighlight">  commentscanYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">Debug::Lex_commentscan</a>)?1:0,<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4708</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4709</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">Debug::Lex_commentscan</a> and <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CommentScanner() {#aa006b1543c5de0b520f2ee928e88871c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CommentScanner::~CommentScanner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4711 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa006b1543c5de0b520f2ee928e88871c">4711</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa006b1543c5de0b520f2ee928e88871c">CommentScanner::~CommentScanner</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4712</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4713</span><span class="doxyLineContent"><span class="doxyHighlight">  commentscanYYlex_destroy(<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4714</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### close() {#a109f854249ba68441071ceb95a4b159e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::close (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, bool foundInline, bool implicit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 117 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4934 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a109f854249ba68441071ceb95a4b159e">4934</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a109f854249ba68441071ceb95a4b159e">CommentScanner::close</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> foundInline,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> implicit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4935</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4937</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.close(e,fileName,lineNr,foundInline,implicit);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4938</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

### enterCompound() {#a955869dba74b22b97c0e86bcdc4b544b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::enterCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 114 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4916 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a955869dba74b22b97c0e86bcdc4b544b">4916</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a955869dba74b22b97c0e86bcdc4b544b">CommentScanner::enterCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4917</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4919</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.enterCompound(fileName,lineNr,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4920</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

### enterFile() {#abd752e50202fc1d4d2929595b003c8c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::enterFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 112 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4904 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd752e50202fc1d4d2929595b003c8c9">4904</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd752e50202fc1d4d2929595b003c8c9">CommentScanner::enterFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4905</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4906</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4907</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.enterFile(fileName,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#a248b40256877fc3c467046ebf1835a8f">generateHtmlForComment</a>.</p>

</div>
</div>

### initGroupInfo() {#a75f7ae2b80985063ee4a58fcb3ec2aec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::initGroupInfo (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 111 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4898 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75f7ae2b80985063ee4a58fcb3ec2aec">4898</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a75f7ae2b80985063ee4a58fcb3ec2aec">CommentScanner::initGroupInfo</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *entry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4899</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4900</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4901</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.initGroupInfo(entry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4902</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

### leaveCompound() {#a1c0c65d943ed68cacf891b2ec38db5fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::leaveCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4922 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c0c65d943ed68cacf891b2ec38db5fe">4922</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c0c65d943ed68cacf891b2ec38db5fe">CommentScanner::leaveCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4923</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4924</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4925</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.leaveCompound(fileName,lineNr,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4926</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

### leaveFile() {#ac7b5eed8e5966a5023d12fd9b31efb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::leaveFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4910 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7b5eed8e5966a5023d12fd9b31efb7d">4910</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac7b5eed8e5966a5023d12fd9b31efb7d">CommentScanner::leaveFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4911</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4913</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.leaveFile(fileName,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4914</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#a248b40256877fc3c467046ebf1835a8f">generateHtmlForComment</a>.</p>

</div>
</div>

### open() {#a1dfece08838426aae997a4faa419cc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CommentScanner::open (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, bool implicit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4928 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1dfece08838426aae997a4faa419cc6c">4928</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1dfece08838426aae997a4faa419cc6c">CommentScanner::open</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> implicit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4929</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4930</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4931</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.open(e,fileName,lineNr,implicit);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4932</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>.</p>

</div>
</div>

### parseCommentBlock() {#a2e48aae075e2f44ddd785428b4099f4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CommentScanner::parseCommentBlock (<a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a> * parser, <a href="/web-doxygen/docs/api/classes/entry">Entry</a> * curEntry, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; comment, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int &amp; lineNr, bool isBrief, bool isJavadocStyle, bool isInbody, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> &amp; prot, int &amp; position, bool &amp; newEntryNeeded, bool markdownEnabled, <a href="/web-doxygen/docs/api/files/src/commentscan-h/#abae3f4527720c3a0368e313ea4a5e575">GuardedSectionStack</a> * guards)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invokes the comment block parser with the request to parse a single comment block.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] parser</td>
<td class="doxyParamItemDescription"><p>The language parse that invoked this function. The comment block parse may invoke ParserInterface::parsePrototype() in order to parse the argument of a @fn command.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] curEntry</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-doxygen/docs/api/classes/entry">Entry</a> to which the comment block belongs. Any information (like documentation) that is found in the comment block will be stored in this entry.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] comment</td>
<td class="doxyParamItemDescription"><p>A string representing the actual comment block. Note that leading *'s are already stripped from the comment block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileName</td>
<td class="doxyParamItemDescription"><p>The name of the file in which the comment is found. Mainly used for producing warnings.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] lineNr</td>
<td class="doxyParamItemDescription"><p>The line number at which the comment block was found. When the function returns it will be set to the last line parsed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] isBrief</td>
<td class="doxyParamItemDescription"><p>TRUE iff this comment block represents a brief description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] isJavadocStyle</td>
<td class="doxyParamItemDescription"><p>TRUE iff this comment block is in "Javadoc" style. This means that it starts as a brief description until the end of the sentences is found and then proceeds as a detailed description.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] isInbody</td>
<td class="doxyParamItemDescription"><p>TRUE iff this comment block is located in the body of a function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] prot</td>
<td class="doxyParamItemDescription"><p>The protection level in which this comment block was found. Commands in the comment block may override this.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] position</td>
<td class="doxyParamItemDescription"><p>The character position within <em>comment</em> where the comment block starts. Typically used in case the comment block contains multiple structural commands.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] newEntryNeeded</td>
<td class="doxyParamItemDescription"><p>Boolean that is TRUE if the comment block parser finds that a the comment block finishes the entry and a new one needs to be started.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] markdownEnabled</td>
<td class="doxyParamItemDescription"><p>Indicates if markdown specific processing should be done.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] guards</td>
<td class="doxyParamItemDescription"><p>Tracks nested conditional sections (if,ifnot,..)</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>TRUE if the comment requires further processing. The parameter <em>newEntryNeeded</em> will typically be true in this case and <em>position</em> will indicate the offset inside the <em>comment</em> string where to proceed parsing. FALSE indicates no further processing is needed.</p></dd>
</dl>


<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>, definition at line 4716 of file <a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e48aae075e2f44ddd785428b4099f4a">4716</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>(</span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a> *parser,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4717</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *curEntry,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4718</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4719</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4720</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in,out */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">  &amp;lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4721</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isBrief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4722</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isAutoBriefOn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4723</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isInbody,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4724</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in,out */</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> &amp;prot,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4725</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in,out */</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;position,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4726</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* out */</span><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;newEntryNeeded,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4727</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* in */</span><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4728</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightComment">/* inout */</span><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-h/#abae3f4527720c3a0368e313ea4a5e575">GuardedSectionStack</a> *guards</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4729</span><span class="doxyLineContent"><span class="doxyHighlight">                      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4730</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4731</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"comment='{}' fileName={} lineNr={} isBrief={} isAutoBriefOn={} inInbody={}"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4732</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightStringLiteral">" prot={} markdownSupport={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>),fileName,lineNr,isBrief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4733</span><span class="doxyLineContent"><span class="doxyHighlight">             isAutoBriefOn,isInbody,prot,markdownSupport);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4734</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4736</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4737</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4738</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;guards = guards;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4739</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;langParser     = parser;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4740</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current        = curEntry;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4741</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">docLine</a> = (lineNr &gt; 1 ? lineNr : 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>.isEmpty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// avoid empty strings</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4743</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString    = <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4744</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString.append(</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4745</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition  = position;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4746</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNr         = lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4747</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName       = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4748</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;protection     = prot;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4749</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;needNewEntry   = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4750</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;xrefKind       = <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a30f370adb2525f6629a44ad8fb972186ae309e5d84833a7111c361e657e75bc88">XRef_None</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4751</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;xrefAppendFlag = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4752</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insidePre      = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4753</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;parseMore      = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4754</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inBody         = isInbody;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4755</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;markdownSupport= markdownSupport;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4756</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;outputXRef.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4757</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isBrief &amp;&amp; !isAutoBriefOn &amp;&amp; !yyextra-&gt;current-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4758</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// add newline separator between detailed comment blocks</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4759</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;doc += </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4760</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4761</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3de3cea0489d29101ce232bbc41789da">setOutput</a>(yyscanner, isBrief || isAutoBriefOn ? <a href="/web-doxygen/docs/api/files/src/commentscan-l/#acc0f0d2f60038c5acff5f6480bc80e45ab0588c8b5fb2c84034afe1809365f040">OutputBrief</a> : <a href="/web-doxygen/docs/api/files/src/commentscan-l/#acc0f0d2f60038c5acff5f6480bc80e45a7798ee65e8ba26c91dcea378c28347a6">OutputDoc</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4762</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;briefEndsAtDot = isAutoBriefOn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4763</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;condCount    = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4764</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;sectionLevel = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4765</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;spaceBeforeCmd.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4766</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;spaceBeforeIf.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4767</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;htmlContextStack.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4768</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4769</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">Debug::Lex_commentscan</a>, __FILE__, !fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName): </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4770</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;current-&gt;inbodyDocs.isEmpty() &amp;&amp; isInbody) </span><span class="doxyHighlightComment">// separate in body fragments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4771</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cmd[30];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4773</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>(cmd,30,</span><span class="doxyHighlightStringLiteral">"\n\n\\iline %d \\ilinebr "</span><span class="doxyHighlight">,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4774</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;inbodyDocs+=cmd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4775</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4776</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4777</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504">Debug::CommentScan</a>,0,</span><span class="doxyHighlightStringLiteral">"-----------\nCommentScanner: {}:{}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4778</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"input=[\n{}]\n"</span><span class="doxyHighlight">,fileName,lineNr,yyextra-&gt;inputString</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4779</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4780</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4781</span><span class="doxyLineContent"><span class="doxyHighlight">  commentscanYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4782</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( Comment );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4783</span><span class="doxyLineContent"><span class="doxyHighlight">  commentscanYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4784</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3de3cea0489d29101ce232bbc41789da">setOutput</a>(yyscanner, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#acc0f0d2f60038c5acff5f6480bc80e45a7798ee65e8ba26c91dcea378c28347a6">OutputDoc</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4785</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4786</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (YY_START==OverloadParam) </span><span class="doxyHighlightComment">// comment ended with \overload</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4787</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4788</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aacd050a578098847da993bc206dc7586">addOutput</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8c71fbab856bc37ae54d2d369535b3b">getOverloadDocs</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4789</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4790</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;insideParBlock)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4792</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4793</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4794</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"Documentation block ended while inside a \\parblock. Missing \\endparblock"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4795</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4796</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4797</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;doc=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>(yyextra-&gt;current-&gt;doc,yyextra-&gt;current-&gt;docLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4798</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;current-&gt;brief=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>(yyextra-&gt;current-&gt;brief,yyextra-&gt;current-&gt;docLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4799</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4800</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;section.isFileDoc() &amp;&amp; yyextra-&gt;current-&gt;doc.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4801</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4802</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// to allow a comment block with just a @file command.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4803</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;current-&gt;doc=</span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4804</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4805</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4806</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;current-&gt;section.isMemberGrp() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4807</span><span class="doxyLineContent"><span class="doxyHighlight">      yyextra-&gt;docGroup.isEmpty()) </span><span class="doxyHighlightComment">// @name section but no group started yet</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4808</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4809</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;docGroup.open(yyextra-&gt;current,yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4810</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4811</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4812</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504">Debug::CommentScan</a>,0,</span><span class="doxyHighlightStringLiteral">"-----------\nCommentScanner: {}:{}\noutput=[\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4813</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"brief=[line={}\n{}]\ndocs=[line={}\n{}]\ninbody=[line={}\n{}]\n]\n===========\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4814</span><span class="doxyLineContent"><span class="doxyHighlight">               fileName,lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4815</span><span class="doxyLineContent"><span class="doxyHighlight">               yyextra-&gt;current-&gt;briefLine,yyextra-&gt;current-&gt;brief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4816</span><span class="doxyLineContent"><span class="doxyHighlight">               yyextra-&gt;current-&gt;docLine,yyextra-&gt;current-&gt;doc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4817</span><span class="doxyLineContent"><span class="doxyHighlight">               yyextra-&gt;current-&gt;inbodyLine,yyextra-&gt;current-&gt;inbodyDocs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4818</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4819</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4820</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#affc21459e67958aac09bcb4d942439d4">checkFormula</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4821</span><span class="doxyLineContent"><span class="doxyHighlight">  prot = yyextra-&gt;protection;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4822</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4823</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;docGroup.addDocs(curEntry);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4824</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4825</span><span class="doxyLineContent"><span class="doxyHighlight">  newEntryNeeded = yyextra-&gt;needNewEntry;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4826</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4827</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if we did not proceed during this call, it does not make</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// sense to continue, since we get stuck. See bug 567346 for situations</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4829</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// were this happens</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4830</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;parseMore &amp;&amp; position==yyextra-&gt;inputPosition) yyextra-&gt;parseMore=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4831</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4832</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;parseMore &amp;&amp; !yyextra-&gt;guards-&gt;empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4833</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4834</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(yyextra-&gt;fileName,yyextra-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Documentation block ended in the middle of a conditional section!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4835</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4836</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4837</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;parseMore) position=yyextra-&gt;inputPosition; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> position=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4838</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4839</span><span class="doxyLineContent"><span class="doxyHighlight">  lineNr = yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4840</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"position={} parseMore={} newEntryNeeded={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4841</span><span class="doxyLineContent"><span class="doxyHighlight">      position,yyextra-&gt;parseMore,newEntryNeeded);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4842</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4843</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> yyextra-&gt;parseMore;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4844</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aacd050a578098847da993bc206dc7586">addOutput</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#affc21459e67958aac09bcb4d942439d4">checkFormula</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ae8c2c4e6dab650ca0dbc32956838ddd9">comment</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504">Debug::CommentScan</a>, <a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">Entry::docLine</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8c71fbab856bc37ae54d2d369535b3b">getOverloadDocs</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">Debug::Lex_commentscan</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#acc0f0d2f60038c5acff5f6480bc80e45ab0588c8b5fb2c84034afe1809365f040">OutputBrief</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#acc0f0d2f60038c5acff5f6480bc80e45a7798ee65e8ba26c91dcea378c28347a6">OutputDoc</a>, <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3de3cea0489d29101ce232bbc41789da">setOutput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a> and <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a30f370adb2525f6629a44ad8fb972186ae309e5d84833a7111c361e657e75bc88">XRef_None</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#a248b40256877fc3c467046ebf1835a8f">generateHtmlForComment</a> and <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a7bf2d143820f6862f172772b3f22b98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; CommentScanner::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bf2d143820f6862f172772b3f22b98e">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a7bf2d143820f6862f172772b3f22b98e">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a109f854249ba68441071ceb95a4b159e">close</a>, <a href="#a4cc03eb4b903175c815dbbe1c9caa027">CommentScanner</a>, <a href="#a955869dba74b22b97c0e86bcdc4b544b">enterCompound</a>, <a href="#abd752e50202fc1d4d2929595b003c8c9">enterFile</a>, <a href="#a75f7ae2b80985063ee4a58fcb3ec2aec">initGroupInfo</a>, <a href="#a1c0c65d943ed68cacf891b2ec38db5fe">leaveCompound</a>, <a href="#ac7b5eed8e5966a5023d12fd9b31efb7d">leaveFile</a>, <a href="#a1dfece08838426aae997a4faa419cc6c">open</a>, <a href="#a2e48aae075e2f44ddd785428b4099f4a">parseCommentBlock</a> and <a href="#aa006b1543c5de0b520f2ee928e88871c">~CommentScanner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/commentscan-l">commentscan.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
