---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/coutlineparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `COutlineParser` Class Reference

<p>C-like language parser using state-based lexical scanning. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class COutlineParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/scanner-h">src/scanner.h</a>&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd6fc2ec32133131cf2d9acc24103cc">COutlineParser</a> (const COutlineParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26820c1350588280ed19427402101b01">COutlineParser</a> (COutlineParser &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd28baae7e14ef1a7ad0faeaf7c15909">~COutlineParser</a> () override</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f953ba6200e6f5a74559b589ef8536">operator=</a> (COutlineParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3598b1aae5012852ef6ecc43b7cd83f5">operator=</a> (COutlineParser &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf5190ffb4fc52b45fc6b22895a6fbf">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#a5bf5190ffb4fc52b45fc6b22895a6fbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11fbf8a139c8880d6b6cb796b9c882c">needsPreprocessing</a> (const QCString &amp;extension) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#af11fbf8a139c8880d6b6cb796b9c882c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a615bf5108382e0d35d3f0d46306a3667">parsePrototype</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function called by the comment block scanner. <a href="#a615bf5108382e0d35d3f0d46306a3667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/coutlineparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a></td>
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

<p>C-like language parser using state-based lexical scanning.</p>


<p>This is the language parser for doxygen. It is somewhat fuzzy and supports C++ and various languages that are closely related to C++, such as C, C#, Objective-C, Java, PHP, and IDL.</p>


<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### COutlineParser() {#a5d4323648b52f514ea8c0c71537359a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COutlineParser::COutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>, definition at line 8403 of file <a href="/web-doxygen/docs/api/files/src/scanner-l">scanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d4323648b52f514ea8c0c71537359a5">8403</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser::COutlineParser</a>() : <a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>(std::make_unique&lt;<a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>::<a href="/web-doxygen/docs/api/structs/coutlineparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8404</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8405</span><span class="doxyLineContent"><span class="doxyHighlight">  scannerYYlex_init_extra(&amp;<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;state,&amp;<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8406</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8407</span><span class="doxyLineContent"><span class="doxyHighlight">  scannerYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">Debug::Lex_scanner</a>)?1:0,<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8408</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8409</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">Debug::Lex_scanner</a> and <a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>.</p>


<p>Referenced by <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>, <a href="#abcd6fc2ec32133131cf2d9acc24103cc">COutlineParser</a>, <a href="#a26820c1350588280ed19427402101b01">COutlineParser</a>, <a href="#a3598b1aae5012852ef6ecc43b7cd83f5">operator=</a> and <a href="#a54f953ba6200e6f5a74559b589ef8536">operator=</a>.</p>

</div>
</div>

### COutlineParser() {#abcd6fc2ec32133131cf2d9acc24103cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COutlineParser::COutlineParser (const <a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>.</p>


<p>Reference <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>.</p>

</div>
</div>

### COutlineParser() {#a26820c1350588280ed19427402101b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COutlineParser::COutlineParser (<a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>.</p>


<p>Reference <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~COutlineParser() {#acd28baae7e14ef1a7ad0faeaf7c15909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COutlineParser::~COutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>, definition at line 8411 of file <a href="/web-doxygen/docs/api/files/src/scanner-l">scanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd28baae7e14ef1a7ad0faeaf7c15909">8411</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#acd28baae7e14ef1a7ad0faeaf7c15909">COutlineParser::~COutlineParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8412</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8413</span><span class="doxyLineContent"><span class="doxyHighlight">  scannerYYlex_destroy(<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8414</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a54f953ba6200e6f5a74559b589ef8536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COutlineParser &amp; COutlineParser::operator= (<a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>.</p>


<p>Reference <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>.</p>

</div>
</div>

### operator=() {#a3598b1aae5012852ef6ecc43b7cd83f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">COutlineParser &amp; COutlineParser::operator= (<a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>.</p>


<p>Reference <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#af11fbf8a139c8880d6b6cb796b9c882c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool COutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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


<p>Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>, definition at line 8431 of file <a href="/web-doxygen/docs/api/files/src/scanner-l">scanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af11fbf8a139c8880d6b6cb796b9c882c">8431</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af11fbf8a139c8880d6b6cb796b9c882c">COutlineParser::needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8432</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8433</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fe=extension.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8434</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(extension);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (SrcLangExt::Cpp == lang) || (SrcLangExt::Lex == lang) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8436</span><span class="doxyLineContent"><span class="doxyHighlight">   !( fe==</span><span class="doxyHighlightStringLiteral">".java"</span><span class="doxyHighlight"> || fe==</span><span class="doxyHighlightStringLiteral">".as"</span><span class="doxyHighlight">  || fe==</span><span class="doxyHighlightStringLiteral">".d"</span><span class="doxyHighlight">    || fe==</span><span class="doxyHighlightStringLiteral">".php"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8437</span><span class="doxyLineContent"><span class="doxyHighlight">      fe==</span><span class="doxyHighlightStringLiteral">".php4"</span><span class="doxyHighlight"> || fe==</span><span class="doxyHighlightStringLiteral">".inc"</span><span class="doxyHighlight"> || fe==</span><span class="doxyHighlightStringLiteral">".phtml"</span><span class="doxyHighlight">|| fe==</span><span class="doxyHighlightStringLiteral">".php5"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8438</span><span class="doxyLineContent"><span class="doxyHighlight">    );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8439</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>.</p>

</div>
</div>

### parseInput() {#a5bf5190ffb4fc52b45fc6b22895a6fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
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

<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>, definition at line 8416 of file <a href="/web-doxygen/docs/api/files/src/scanner-l">scanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5bf5190ffb4fc52b45fc6b22895a6fbf">8416</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5bf5190ffb4fc52b45fc6b22895a6fbf">COutlineParser::parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8417</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8418</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8419</span><span class="doxyLineContent"><span class="doxyHighlight">                                <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> *clangParser)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8420</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8421</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8422</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8423</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;thisParser = </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8424</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8425</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">Debug::Lex_scanner</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8426</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8427</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">::parseMain</a>(<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;yyscanner,fileName,fileBuf,root,clangParser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8428</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">Debug::Lex_scanner</a>, <a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.</p>

</div>
</div>

### parsePrototype() {#a615bf5108382e0d35d3f0d46306a3667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void COutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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


<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>, definition at line 8441 of file <a href="/web-doxygen/docs/api/files/src/scanner-l">scanner.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a615bf5108382e0d35d3f0d46306a3667">8441</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a615bf5108382e0d35d3f0d46306a3667">COutlineParser::parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8442</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8443</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a615bf5108382e0d35d3f0d46306a3667">::parsePrototype</a>(<a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>-&gt;yyscanner,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">8444</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a> and <a href="#a615bf5108382e0d35d3f0d46306a3667">parsePrototype</a>.</p>


<p>Referenced by <a href="#a615bf5108382e0d35d3f0d46306a3667">parsePrototype</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aa7f3b6aee86ee2d08d7a8804a96904dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; COutlineParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aa7f3b6aee86ee2d08d7a8804a96904dc">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5d4323648b52f514ea8c0c71537359a5">COutlineParser</a>, <a href="#a5bf5190ffb4fc52b45fc6b22895a6fbf">parseInput</a>, <a href="#a615bf5108382e0d35d3f0d46306a3667">parsePrototype</a> and <a href="#acd28baae7e14ef1a7ad0faeaf7c15909">~COutlineParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/scanner-h">scanner.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/scanner-l">scanner.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
