---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/vhdlerrorhandler
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `VhdlErrorHandler` Class Reference



## Declaration

<div class="doxyDeclaration">
class vhdl::parser::VhdlErrorHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">vhdlparser/VhdlParserErrorHandler.hpp</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler">ErrorHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa037c122abd8147de3a81459519d622">VhdlErrorHandler</a> (const char *fileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeedd721b392d999dd9d2ba5944154c23">handleUnexpectedToken</a> (int, const JJString &amp;, Token *actual, VhdlParser *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a9d364e135aef879b4d24c5b165c6c">handleParseError</a> (Token *last, Token *unexpected, const JJSimpleString &amp;, VhdlParser *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5561c37f9abb893684f5537ad72f04cf">handleOtherError</a> (const JJString &amp;message, VhdlParser *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f762940359a017a9f7a903f4a66f6f4">m_fileName</a></td>
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


Definition at line 16 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.

<div class="doxySectionDef">

## Public Constructors

### VhdlErrorHandler() {#afa037c122abd8147de3a81459519d622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::VhdlErrorHandler::VhdlErrorHandler (const char * fileName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 19 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa037c122abd8147de3a81459519d622">19</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afa037c122abd8147de3a81459519d622">VhdlErrorHandler</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName) : <a href="#a7f762940359a017a9f7a903f4a66f6f4">m_fileName</a>(fileName) {}</span></span></div>

</div>


Reference <a href="#a7f762940359a017a9f7a903f4a66f6f4">m\_fileName</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### handleOtherError() {#a5561c37f9abb893684f5537ad72f04cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::VhdlErrorHandler::handleOtherError (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; message, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> *)</td>
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



Definition at line 35 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5561c37f9abb893684f5537ad72f04cf">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5561c37f9abb893684f5537ad72f04cf">handleOtherError</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; message, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a> * </span><span class="doxyHighlightComment">/* parser */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(<a href="#a7f762940359a017a9f7a903f4a66f6f4">m_fileName</a>, -1, </span><span class="doxyHighlightStringLiteral">"unexpected error: '{}'"</span><span class="doxyHighlight">, (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)message.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">throw</span><span class="doxyHighlight"> std::exception();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#ada8cb3fd4fa2dead863dc00edc1b9587">vhdl::parser::ErrorHandler::error\_count</a>, <a href="#a7f762940359a017a9f7a903f4a66f6f4">m\_fileName</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a8bbb7acf78e67f3b3706943bf268ceed">vhdl::parser::ErrorHandler::VhdlParser</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.
</div>
</div>

### handleParseError() {#a34a9d364e135aef879b4d24c5b165c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::VhdlErrorHandler::handleParseError (<a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> * last, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> * unexpected, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ae58db75f8ecd9f0ea05a95357b2c80d7">JJSimpleString</a> &amp;, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> *)</td>
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



Definition at line 28 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34a9d364e135aef879b4d24c5b165c6c">28</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34a9d364e135aef879b4d24c5b165c6c">handleParseError</a>(<a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *last, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *unexpected, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ae58db75f8ecd9f0ea05a95357b2c80d7">JJSimpleString</a>&amp; </span><span class="doxyHighlightComment">/* production */</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a> * </span><span class="doxyHighlightComment">/* parser */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(<a href="#a7f762940359a017a9f7a903f4a66f6f4">m_fileName</a>,last-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">beginLine</a>,</span><span class="doxyHighlightStringLiteral">"unexpected token: '{}'"</span><span class="doxyHighlight">, (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)unexpected-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">image</a>.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">throw</span><span class="doxyHighlight"> std::exception();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">vhdl::parser::Token::beginLine</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#ada8cb3fd4fa2dead863dc00edc1b9587">vhdl::parser::ErrorHandler::error\_count</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">vhdl::parser::Token::image</a>, <a href="#a7f762940359a017a9f7a903f4a66f6f4">m\_fileName</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a8bbb7acf78e67f3b3706943bf268ceed">vhdl::parser::ErrorHandler::VhdlParser</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.
</div>
</div>

### handleUnexpectedToken() {#aeedd721b392d999dd9d2ba5944154c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::VhdlErrorHandler::handleUnexpectedToken (int, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp;, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> * actual, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> *)</td>
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



Definition at line 21 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeedd721b392d999dd9d2ba5944154c23">21</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeedd721b392d999dd9d2ba5944154c23">handleUnexpectedToken</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* expectedKind */</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; </span><span class="doxyHighlightComment">/* expectedToken */</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *actual, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a> * </span><span class="doxyHighlightComment">/* parser */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(<a href="#a7f762940359a017a9f7a903f4a66f6f4">m_fileName</a>,actual-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">beginLine</a>,</span><span class="doxyHighlightStringLiteral">"syntax error '{}'"</span><span class="doxyHighlight">,(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)actual-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">image</a>.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">throw</span><span class="doxyHighlight"> std::exception();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">vhdl::parser::Token::beginLine</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#ada8cb3fd4fa2dead863dc00edc1b9587">vhdl::parser::ErrorHandler::error\_count</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">vhdl::parser::Token::image</a>, <a href="#a7f762940359a017a9f7a903f4a66f6f4">m\_fileName</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a8bbb7acf78e67f3b3706943bf268ceed">vhdl::parser::ErrorHandler::VhdlParser</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_fileName {#a7f762940359a017a9f7a903f4a66f6f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlErrorHandler::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 43 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7f762940359a017a9f7a903f4a66f6f4">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7f762940359a017a9f7a903f4a66f6f4">m_fileName</a>;</span></span></div>

</div>


Referenced by <a href="#a5561c37f9abb893684f5537ad72f04cf">handleOtherError</a>, <a href="#a34a9d364e135aef879b4d24c5b165c6c">handleParseError</a>, <a href="#aeedd721b392d999dd9d2ba5944154c23">handleUnexpectedToken</a> and <a href="#afa037c122abd8147de3a81459519d622">VhdlErrorHandler</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
