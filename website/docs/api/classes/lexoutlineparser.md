---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/lexoutlineparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LexOutlineParser` Class Reference

<p>Lex language parser using state-based lexical scanning. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LexOutlineParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/lexscanner-h">src/lexscanner.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512e2156570948dccc8907824aa9c0e0">~LexOutlineParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac842abb13f0168eeec20c4a6de1d79b8">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#ac842abb13f0168eeec20c4a6de1d79b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc7decd92206d3b66f49d1b8eb077db">needsPreprocessing</a> (const QCString &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a6fc7decd92206d3b66f49d1b8eb077db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11918ad54a7236f660857362c30f477">parsePrototype</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function called by the comment block scanner. <a href="#af11918ad54a7236f660857362c30f477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/lexoutlineparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a></td>
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

<p>Lex language parser using state-based lexical scanning.</p>


<p>This is the Lex language parser for doxygen.</p>


<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LexOutlineParser() {#a1c3dd92666badfafa45cb0e5295cd511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexOutlineParser::LexOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>, definition at line 1003 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-l">lexscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c3dd92666badfafa45cb0e5295cd511">1003</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser::LexOutlineParser</a>() : <a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>(std::make_unique&lt;<a href="#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser</a>::<a href="/web-doxygen/docs/api/structs/lexoutlineparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">  lexscannerYYlex_init_extra(&amp;<a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>-&gt;state,&amp;<a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">  lexscannerYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">Debug::Lex_lexscanner</a>)?1:0,<a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">Debug::Lex_lexscanner</a>, <a href="#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser</a> and <a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>.</p>


<p>Referenced by <a href="#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LexOutlineParser() {#a512e2156570948dccc8907824aa9c0e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LexOutlineParser::~LexOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>, definition at line 1011 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-l">lexscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a512e2156570948dccc8907824aa9c0e0">1011</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a512e2156570948dccc8907824aa9c0e0">LexOutlineParser::~LexOutlineParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">  lexscannerYYlex_destroy(<a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#a6fc7decd92206d3b66f49d1b8eb077db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LexOutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
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


<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6fc7decd92206d3b66f49d1b8eb077db">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6fc7decd92206d3b66f49d1b8eb077db">needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* extension */</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; };</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### parseInput() {#ac842abb13f0168eeec20c4a6de1d79b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexOutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
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

<p>Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>, definition at line 1016 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-l">lexscanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac842abb13f0168eeec20c4a6de1d79b8">1016</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac842abb13f0168eeec20c4a6de1d79b8">LexOutlineParser::parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">                                  <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> *clangParser)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">Debug::Lex_lexscanner</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">::parseMain</a>(<a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>-&gt;yyscanner,fileName,fileBuf,root,clangParser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">Debug::Lex_lexscanner</a>, <a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.</p>

</div>
</div>

### parsePrototype() {#af11918ad54a7236f660857362c30f477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LexOutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback function called by the comment block scanner.</p>


<p>It provides a string <em>text</em> containing the prototype of a function or variable. The parser should parse this and store the information in the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> node that corresponds with the node for which the comment block parser was invoked.</p>


<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af11918ad54a7236f660857362c30f477">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af11918ad54a7236f660857362c30f477">parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* text */</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a63d579cc2b0db08ab8057e022146b7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; LexOutlineParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63d579cc2b0db08ab8057e022146b7d9">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a63d579cc2b0db08ab8057e022146b7d9">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1c3dd92666badfafa45cb0e5295cd511">LexOutlineParser</a>, <a href="#ac842abb13f0168eeec20c4a6de1d79b8">parseInput</a> and <a href="#a512e2156570948dccc8907824aa9c0e0">~LexOutlineParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/lexscanner-h">lexscanner.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/lexscanner-l">lexscanner.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
