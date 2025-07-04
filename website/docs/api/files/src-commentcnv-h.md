---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/commentcnv-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `commentcnv.h` File Reference

<p>First pass comment processing. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include &lt;string&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

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

## Description {#details}

<p>First pass comment processing.</p>

<div class="doxySectionDef">

## Functions

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


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">inBuf</td>
<td class="doxyParamItemDescription"><p>input buffer holding the file content.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">outBuf</td>
<td class="doxyParamItemDescription"><p>output buffer to which the results after conversion are written to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">fn</td>
<td class="doxyParamItemDescription"><p>the name of the file from which the comments originate.</p></td>
</tr>
</table>
</dd>
</dl>

<p>The following is converted:</p>


<ul class="doxyList ">
<li>C++ style multiline doxygen comments are converted to C style doxygen comments.</li>
<li>conditional sections are processed.</li>
<li>aliases are expanded.</li>
</ul>

<p>This function does three things:</p>


<ol class="doxyList" type="1">
<li>It converts multi-line C++ style comment blocks (that are aligned) to C style comment blocks (if MULTILINE_CPP_IS_BRIEF is set to NO).</li>
<li>It replaces aliases with their definition (see ALIASES)</li>
<li>It handles conditional sections (cond...endcond blocks)</li>
</ol>

<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-h">commentcnv.h</a>, definition at line 1964 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4706ae57556b5cab395e8d2c8ec666b9">1964</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;inBuf,std::string &amp;outBuf,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fn)</span></span></div>
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
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>(yyscanner);</span></span></div>
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


<p>References <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ac28578b1034a1f4803dd53216ab2bfda">clearCommentStack</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">Debug::CommentCnv</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#acb642f5212285f22eca041cbf6a927c1">convertFileNameFortranParserCode</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">Debug::Lex_commentcnv</a>, <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#a6788d979220d7bcd5ed1eaf232060e29">commentcnvYY_CondCtx::lineNr</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/structs/commentcnvyy-condctx/#ae1eed597f41d62965e72a0f1a4961d4d">commentcnvYY_CondCtx::sectionId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a9a7bd1b3d14701eb97c03f3ef34deff1">yylex</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#a248b40256877fc3c467046ebf1835a8f">generateHtmlForComment</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
