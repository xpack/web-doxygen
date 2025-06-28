---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/fortranoutlineparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `FortranOutlineParser` Class Reference

<p>Fortran language parser using state-based lexical scanning. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class FortranOutlineParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/fortranscanner-h">src/fortranscanner.h</a>&gt;
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/fortranoutlineparserfixed">FortranOutlineParserFixed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/fortranoutlineparserfree">FortranOutlineParserFree</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7c8dd89e81d6704c92a052dba364ac8">FortranOutlineParser</a> (FortranFormat format=FortranFormat::Unknown)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2e6484f64e984fb8e5d1cb0a0ef5d2d">~FortranOutlineParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e1c6efa3eba5f4d30934eac0cd0aa3">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#af3e1c6efa3eba5f4d30934eac0cd0aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715ceab8e5e5c872065367e3f88c0df5">needsPreprocessing</a> (const QCString &amp;extension) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a715ceab8e5e5c872065367e3f88c0df5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe1b29c5797729e3aa2dcd693e46755">parsePrototype</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function called by the comment block scanner. <a href="#abbe1b29c5797729e3aa2dcd693e46755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/fortranoutlineparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a></td>
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

<p>Fortran language parser using state-based lexical scanning.</p>


<p>This is the Fortran language parser for doxygen.</p>

<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### FortranOutlineParser() {#ad7c8dd89e81d6704c92a052dba364ac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FortranOutlineParser::FortranOutlineParser (<a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> format=<a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266a88183b946cc5f0e8c96b2e66e1c74a7e">FortranFormat::Unknown</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>, definition at line 3343 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7c8dd89e81d6704c92a052dba364ac8">3343</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad7c8dd89e81d6704c92a052dba364ac8">FortranOutlineParser::FortranOutlineParser</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3344</span><span class="doxyLineContent"><span class="doxyHighlight">   : <a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/fortranoutlineparser/private">Private</a>&gt;(format))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3345</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3346</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/fortranoutlineparserfixed/#a5f28fd868b92ae98d4dfced34475a874">FortranOutlineParserFixed::FortranOutlineParserFixed</a> and <a href="/web-doxygen/docs/api/classes/fortranoutlineparserfree/#a34fce3d84efdd2ff4ad6f2b0b33f333f">FortranOutlineParserFree::FortranOutlineParserFree</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~FortranOutlineParser() {#ac2e6484f64e984fb8e5d1cb0a0ef5d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FortranOutlineParser::~FortranOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>, definition at line 3348 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2e6484f64e984fb8e5d1cb0a0ef5d2d">3348</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ac2e6484f64e984fb8e5d1cb0a0ef5d2d">FortranOutlineParser::~FortranOutlineParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3349</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3350</span><span class="doxyLineContent"><span class="doxyHighlight">  fortranscannerYYlex_destroy(<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3351</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#a715ceab8e5e5c872065367e3f88c0df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FortranOutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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
<dd>
<p><a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput()</a></p>
</dd>
</dl>


<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>, definition at line 3366 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a715ceab8e5e5c872065367e3f88c0df5">3366</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a715ceab8e5e5c872065367e3f88c0df5">FortranOutlineParser::needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3367</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> extension!=extension.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>(); </span><span class="doxyHighlightComment">// use preprocessor only for upper case extensions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3369</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>.
</div>
</div>

### parseInput() {#af3e1c6efa3eba5f4d30934eac0cd0aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FortranOutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
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

<p>Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>, definition at line 3353 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3e1c6efa3eba5f4d30934eac0cd0aa3">3353</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af3e1c6efa3eba5f4d30934eac0cd0aa3">FortranOutlineParser::parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3354</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3355</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3356</span><span class="doxyLineContent"><span class="doxyHighlight">                                      <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * </span><span class="doxyHighlightComment">/*clangParser*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3357</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3358</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3359</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;thisParser = </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3360</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3361</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">Debug::Lex_fortranscanner</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3362</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3363</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">::parseMain</a>(<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner,fileName,fileBuf,root,<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;format);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3364</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">Debug::Lex&#95;fortranscanner</a>, <a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.
</div>
</div>

### parsePrototype() {#abbe1b29c5797729e3aa2dcd693e46755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FortranOutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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

<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>, definition at line 3371 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbe1b29c5797729e3aa2dcd693e46755">3371</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abbe1b29c5797729e3aa2dcd693e46755">FortranOutlineParser::parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3372</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3374</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>(<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3375</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;parsingPrototype = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3376</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(Prototype);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3377</span><span class="doxyLineContent"><span class="doxyHighlight">  fortranscannerYYlex(<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3378</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;parsingPrototype = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3379</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a66d8cb63c9460264113152b30a8c4afb">popBuffer</a>(<a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3380</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a66d8cb63c9460264113152b30a8c4afb">popBuffer</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a7b7d6850dfe712b2f29bccd9b9caffd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; FortranOutlineParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a7b7d6850dfe712b2f29bccd9b9caffd9">p</a>;</span></span></div>

</div>


Referenced by <a href="#ad7c8dd89e81d6704c92a052dba364ac8">FortranOutlineParser</a>, <a href="#af3e1c6efa3eba5f4d30934eac0cd0aa3">parseInput</a>, <a href="#abbe1b29c5797729e3aa2dcd693e46755">parsePrototype</a> and <a href="#ac2e6484f64e984fb8e5d1cb0a0ef5d2d">~FortranOutlineParser</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/fortranscanner-h">fortranscanner.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
