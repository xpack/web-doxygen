---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/preprocessor
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Preprocessor` Class Reference



## Declaration

<div class="doxyDeclaration">
class Preprocessor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/pre-h">src/pre.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada966c8b83e7c3bcd8759549c3cdf688">Preprocessor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c16724bc9e18b12a45f5a7fe2752b1b">~Preprocessor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3f6062c1f94727e3d51963720d13417">processFile</a> (const QCString &amp;fileName, const std::string &amp;input, std::string &amp;output)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc55933ed845c9b089f305b365d8e6b">addSearchDir</a> (const QCString &amp;dir)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/preprocessor/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a></td>
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


<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Preprocessor() {#ada966c8b83e7c3bcd8759549c3cdf688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Preprocessor::Preprocessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>, definition at line 4000 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada966c8b83e7c3bcd8759549c3cdf688">4000</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ada966c8b83e7c3bcd8759549c3cdf688">Preprocessor::Preprocessor</a>() : <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/preprocessor/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4001</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4002</span><span class="doxyLineContent"><span class="doxyHighlight">  preYYlex_init_extra(&amp;<a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;state,&amp;<a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4003</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adfc55933ed845c9b089f305b365d8e6b">addSearchDir</a>(</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4004</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#adfc55933ed845c9b089f305b365d8e6b">addSearchDir</a> and <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Preprocessor() {#a3c16724bc9e18b12a45f5a7fe2752b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Preprocessor::~Preprocessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>, definition at line 4006 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c16724bc9e18b12a45f5a7fe2752b1b">4006</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a3c16724bc9e18b12a45f5a7fe2752b1b">Preprocessor::~Preprocessor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4007</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4008</span><span class="doxyLineContent"><span class="doxyHighlight">  preYYlex_destroy(<a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSearchDir() {#adfc55933ed845c9b089f305b365d8e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Preprocessor::addSearchDir (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>, definition at line 3993 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfc55933ed845c9b089f305b365d8e6b">3993</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adfc55933ed845c9b089f305b365d8e6b">Preprocessor::addSearchDir</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;dir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3994</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3995</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(<a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3996</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(dir.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3997</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa941e087c82c28ff498d9d3dec551b1f">isDir</a>()) state-&gt;pathList.push_back(fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3998</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#aa941e087c82c28ff498d9d3dec551b1f">FileInfo::isDir</a>, <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a> and <a href="#ada966c8b83e7c3bcd8759549c3cdf688">Preprocessor</a>.</p>

</div>
</div>

### processFile() {#ab3f6062c1f94727e3d51963720d13417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Preprocessor::processFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const std::string &amp; input, std::string &amp; output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>, definition at line 4011 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3f6062c1f94727e3d51963720d13417">4011</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;input,std::string &amp;output)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4012</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4013</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"fileName={}"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4014</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4015</span><span class="doxyLineContent"><span class="doxyHighlight">  YY_EXTRA_TYPE state = preYYget_extra(<a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4016</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4017</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4018</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4019</span><span class="doxyLineContent"><span class="doxyHighlight">  preYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8">Debug::Lex_pre</a>)?1:0,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4020</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4021</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4022</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8">Debug::Lex_pre</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4023</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("##########################\n%s\n####################\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4024</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(input));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4025</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4026</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;macroExpansion = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MACRO_EXPANSION);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4027</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;expandOnlyPredef = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXPAND_ONLY_PREDEF);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4028</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;skip=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4029</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;curlyCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4030</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;lexRulesPart=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4031</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;nospaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4032</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;inputBuf=&amp;input;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4033</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;inputBufPos=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4034</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;outputBuf=&amp;output;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4035</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;includeStack.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4036</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;expandedDict.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4037</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;contextDefines.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4038</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;pragmaSet.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!state-&gt;condStack.empty()) state-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4040</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4041</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/pre-l/#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>(yyscanner,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4042</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4043</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;inputFileDef = state-&gt;yyFileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4044</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//yyextra-&gt;defineManager.startContext(state-&gt;fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4045</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4046</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>(yyscanner,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4047</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4048</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;yyLineNr = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4049</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;yyColNr  = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4050</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;ifcount  = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4051</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4052</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( Start );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4053</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4054</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;expectGuard = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>(fileName).isHeader();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4055</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;guardName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4056</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;lastGuardName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4057</span><span class="doxyLineContent"><span class="doxyHighlight">  state-&gt;guardExpr.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4058</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4059</span><span class="doxyLineContent"><span class="doxyHighlight">  preYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4060</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4061</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!state-&gt;condStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4062</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4063</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;preYY_CondCtx&gt; &amp;ctx = state-&gt;condStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4064</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sectionInfo = </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4065</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx-&gt;sectionId!=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">) sectionInfo.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">" with label '%s' "</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(ctx-&gt;sectionId.stripWhiteSpace()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4066</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(ctx-&gt;fileName,ctx-&gt;lineNr,</span><span class="doxyHighlightStringLiteral">"Conditional section{}does not have "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4067</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"a corresponding \\endcond command within this file."</span><span class="doxyHighlight">,sectionInfo);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4068</span><span class="doxyLineContent"><span class="doxyHighlight">    state-&gt;condStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4069</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4070</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// make sure we don't extend a \cond with missing \endcond over multiple files (see bug 624829)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4071</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/pre-l/#a96730086e79b6790b6269d07152a1735">forceEndCondSection</a>(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4072</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4073</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!state-&gt;levelGuard.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4074</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4075</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(state-&gt;fileName,state-&gt;yyLineNr,</span><span class="doxyHighlightStringLiteral">"More #if's than #endif's found (might be in an included file)."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4076</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4077</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4078</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4079</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4080</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/pre-l/#afa74555c39c3f592f0d6113ba0dc6aa9">g_debugMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4081</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"Preprocessor output of {} (size: {} bytes):\n"</span><span class="doxyHighlight">,fileName,output.<a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">size</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4082</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string contents;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4083</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da1e4864dcfb33d0155b7c8b2506fa7c62">Debug::NoLineNo</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4084</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4085</span><span class="doxyLineContent"><span class="doxyHighlight">      contents=output;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4086</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4087</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// need to add line numbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4088</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4089</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4090</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> startOfLine = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4091</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> content_size = output.size() +</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4092</span><span class="doxyLineContent"><span class="doxyHighlight">                            output.size()*6/40; </span><span class="doxyHighlightComment">// assuming 40 chars per line on average</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4093</span><span class="doxyLineContent"><span class="doxyHighlight">                                                </span><span class="doxyHighlightComment">// and 6 chars extra for the line number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4094</span><span class="doxyLineContent"><span class="doxyHighlight">      contents.reserve(content_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4095</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4096</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;output.size())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4097</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4098</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startOfLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4099</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4100</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lineNrStr[15];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4101</span><span class="doxyLineContent"><span class="doxyHighlight">          snprintf(lineNrStr,15,</span><span class="doxyHighlightStringLiteral">"%05d "</span><span class="doxyHighlight">,line++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4102</span><span class="doxyLineContent"><span class="doxyHighlight">          contents+=lineNrStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4103</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4104</span><span class="doxyLineContent"><span class="doxyHighlight">        contents   += output[pos];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4105</span><span class="doxyLineContent"><span class="doxyHighlight">        startOfLine = output[pos]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4106</span><span class="doxyLineContent"><span class="doxyHighlight">        pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4107</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4108</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4109</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>[2]={0,0};</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4110</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!contents.empty() &amp;&amp; contents[contents.length()-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4111</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4112</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>[0]=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4114</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"---------\n{}{}---------\n"</span><span class="doxyHighlight">,contents,<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4115</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;contextDefines.size()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4116</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4117</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"Macros accessible in this file ({}):\n"</span><span class="doxyHighlight">, fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4118</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"---------\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4119</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;kv : yyextra-&gt;contextDefines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4120</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4121</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"{} "</span><span class="doxyHighlight">,kv.second.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4122</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4123</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;kv : yyextra-&gt;localDefines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4124</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4125</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"{} "</span><span class="doxyHighlight">,kv.second.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4126</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4127</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"\n---------\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4128</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4130</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4131</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>,0,</span><span class="doxyHighlightStringLiteral">"No macros accessible in this file ({}).\n"</span><span class="doxyHighlight">, fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4132</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4133</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4134</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4135</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4136</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/pre-l/#abbb87735f2e6370eeb5934dc1476cd7b">g_updateGlobals</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4137</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;inc : state-&gt;includeRelations)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4138</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4139</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> toKind = [](</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> local,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> imported) -&gt; <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8">IncludeKind</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4140</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4141</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (local)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4142</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4143</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imported)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4144</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4145</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">IncludeKind::ImportLocalObjC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4146</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4147</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4148</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4149</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imported)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4150</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4151</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">IncludeKind::ImportSystemObjC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4152</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4153</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeKind::IncludeSystem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4154</span><span class="doxyLineContent"><span class="doxyHighlight">      };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4155</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inc-&gt;fromFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4156</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4157</span><span class="doxyLineContent"><span class="doxyHighlight">        inc-&gt;fromFileDef-&gt;addIncludeDependency(inc-&gt;toFileDef,inc-&gt;includeName,toKind(inc-&gt;local,inc-&gt;imported));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4158</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inc-&gt;toFileDef &amp;&amp; inc-&gt;fromFileDef)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4160</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4161</span><span class="doxyLineContent"><span class="doxyHighlight">        inc-&gt;toFileDef-&gt;addIncludedByDependency(inc-&gt;fromFileDef,inc-&gt;fromFileDef-&gt;docName(),toKind(inc-&gt;local,inc-&gt;imported));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4162</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4163</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// add the macro definition for this file to the global map</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4165</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#ac6caf5a4de22f8ae50c8abb089aa6f19">Doxygen::macroDefinitions</a>.emplace(state-&gt;fileName.str(),std::move(state-&gt;macroDefinitions));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4166</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4167</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//yyextra-&gt;defineManager.endContext();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">4169</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a96730086e79b6790b6269d07152a1735">forceEndCondSection</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#afa74555c39c3f592f0d6113ba0dc6aa9">g_debugMutex</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#abbb87735f2e6370eeb5934dc1476cd7b">g_updateGlobals</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a99344d48bf61e8b0948b39680259cf11">guessSection</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8aaf0b778b0e0af69011f06c8734fdb891">ImportLocalObjC</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a850b5d27cd4e40d0405c4b7a0d76ab94">ImportSystemObjC</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeLocal</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8ab0ead0aebf84f57889aab39d528f34b4">IncludeSystem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8">Debug::Lex_pre</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ac6caf5a4de22f8ae50c8abb089aa6f19">Doxygen::macroDefinitions</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da1e4864dcfb33d0155b7c8b2506fa7c62">Debug::NoLineNo</a>, <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a3cd40076f3904d6c6ea657b00df39cc6">setFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">QCString::size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#afa129d4a1fdbf2e8afc644aac43b7da8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; Preprocessor::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa129d4a1fdbf2e8afc644aac43b7da8">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">   std::unique_ptr&lt;Private&gt; <a href="#afa129d4a1fdbf2e8afc644aac43b7da8">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adfc55933ed845c9b089f305b365d8e6b">addSearchDir</a>, <a href="#ada966c8b83e7c3bcd8759549c3cdf688">Preprocessor</a>, <a href="#ab3f6062c1f94727e3d51963720d13417">processFile</a> and <a href="#a3c16724bc9e18b12a45f5a7fe2752b1b">~Preprocessor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/pre-h">pre.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
