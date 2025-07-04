---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/pythonoutlineparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PythonOutlineParser` Class Reference

<p>Python Language parser using state-based lexical scanning. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class PythonOutlineParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/pyscanner-h">src/pyscanner.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for outline parsers. <a href="/web-doxygen/docs/api/classes/outlineparserinterface/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabcb09d0e641c2c5d3661069aeea286c">~PythonOutlineParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3b64521d1851e39a58043826b11a95">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#a5a3b64521d1851e39a58043826b11a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ad0ad24a8f0fd0e8cb537c63c6254f">needsPreprocessing</a> (const QCString &amp;extension) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a10ad0ad24a8f0fd0e8cb537c63c6254f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">parsePrototype</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function called by the comment block scanner. <a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/pythonoutlineparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bdb60eb490e5775ef03811344532e98">p</a></td>
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

<p>Python Language parser using state-based lexical scanning.</p>


<p>This is the Python language parser for doxygen.</p>


<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PythonOutlineParser() {#a8a5a1f367924785b005bd7e010e98614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PythonOutlineParser::PythonOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>, definition at line 2343 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a5a1f367924785b005bd7e010e98614">2343</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser::PythonOutlineParser</a>() : <a href="#a5bdb60eb490e5775ef03811344532e98">p</a>(std::make_unique&lt;<a href="#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser</a>::<a href="/web-doxygen/docs/api/structs/pythonoutlineparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYlex_init_extra(&amp;<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;state,&amp;<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">Debug::Lex_pyscanner</a>)?1:0,<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">Debug::Lex_pyscanner</a>, <a href="#a5bdb60eb490e5775ef03811344532e98">p</a> and <a href="#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser</a>.</p>


<p>Referenced by <a href="#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PythonOutlineParser() {#aabcb09d0e641c2c5d3661069aeea286c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PythonOutlineParser::~PythonOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>, definition at line 2351 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabcb09d0e641c2c5d3661069aeea286c">2351</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aabcb09d0e641c2c5d3661069aeea286c">PythonOutlineParser::~PythonOutlineParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">  pyscannerYYlex_destroy(<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a5bdb60eb490e5775ef03811344532e98">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#a10ad0ad24a8f0fd0e8cb537c63c6254f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PythonOutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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

<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput()</a></p></dd>
</dl>


<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>, definition at line 2371 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10ad0ad24a8f0fd0e8cb537c63c6254f">2371</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a10ad0ad24a8f0fd0e8cb537c63c6254f">PythonOutlineParser::needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.</p>

</div>
</div>

### parseInput() {#a5a3b64521d1851e39a58043826b11a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PythonOutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
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

<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileName</td>
<td class="doxyParamItemDescription"><p>The full name of the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileBuf</td>
<td class="doxyParamItemDescription"><p>The contents of the file (zero terminated).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] root</td>
<td class="doxyParamItemDescription"><p>The root of the tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *nodes representing the information extracted from the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] clangParser</td>
<td class="doxyParamItemDescription"><p>The clang translation unit parser object or nullptr if disabled.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>, definition at line 2357 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a3b64521d1851e39a58043826b11a95">2357</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5a3b64521d1851e39a58043826b11a95">PythonOutlineParser::parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * </span><span class="doxyHighlightComment">/*clangParser*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;thisParser = </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">Debug::Lex_pyscanner</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">::parseMain</a>(<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;yyscanner, fileName,fileBuf,root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// May print the AST for debugging purposes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// printAST(global_root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">Debug::Lex_pyscanner</a>, <a href="#a5bdb60eb490e5775ef03811344532e98">p</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.</p>

</div>
</div>

### parsePrototype() {#aacc082bbcc64e3b3fe83a1f7ce66804b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PythonOutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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

<p>Callback function called by the comment block scanner.</p>


<p>It provides a string <em>text</em> containing the prototype of a function or variable. The parser should parse this and store the information in the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> node that corresponds with the node for which the comment block parser was invoked.</p>


<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>, definition at line 2376 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">2376</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">PythonOutlineParser::parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">::parsePrototype</a>(<a href="#a5bdb60eb490e5775ef03811344532e98">p</a>-&gt;yyscanner,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a5bdb60eb490e5775ef03811344532e98">p</a> and <a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">parsePrototype</a>.</p>


<p>Referenced by <a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">parsePrototype</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a5bdb60eb490e5775ef03811344532e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; PythonOutlineParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5bdb60eb490e5775ef03811344532e98">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a5bdb60eb490e5775ef03811344532e98">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5a3b64521d1851e39a58043826b11a95">parseInput</a>, <a href="#aacc082bbcc64e3b3fe83a1f7ce66804b">parsePrototype</a>, <a href="#a8a5a1f367924785b005bd7e010e98614">PythonOutlineParser</a> and <a href="#aabcb09d0e641c2c5d3661069aeea286c">~PythonOutlineParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/pyscanner-h">pyscanner.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/pyscanner-l">pyscanner.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
