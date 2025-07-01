---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/errorhandler
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ErrorHandler` Class Reference



## Declaration

<div class="doxyDeclaration">
class vhdl::parser::ErrorHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">vhdlparser/ErrorHandler.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler">VhdlErrorHandler</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b0456d8c4d2541b7ff734563cbe6be">ErrorHandler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a8bed6e39180859e6fda8b0543b6222">~ErrorHandler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225f9289de15d675ad8c019c1b451e8e">handleUnexpectedToken</a> (int expectedKind, const JJString &amp;expectedToken, Token *actual, VhdlParser *parser)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7181808effb5d884333ec6b97d7eb0">handleParseError</a> (Token *last, Token *unexpected, const JJSimpleString &amp;production, VhdlParser *parser)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c83075a30c8b0ad7eca7aa59621a202">getErrorCount</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64d99ee7d7560900ebef80322afdf19">handleOtherError</a> (const JJString &amp;message, VhdlParser *parser)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a></td>
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


Definition at line 17 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxySectionDef">

## Friends

### VhdlParser {#a8bbb7acf78e67f3b3706943bf268ceed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


Definition at line 19 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8bbb7acf78e67f3b3706943bf268ceed">19</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a>;</span></span></div>

</div>


Reference <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a>.

Referenced by <a href="#ad64d99ee7d7560900ebef80322afdf19">handleOtherError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#a5561c37f9abb893684f5537ad72f04cf">vhdl::parser::VhdlErrorHandler::handleOtherError</a>, <a href="#aac7181808effb5d884333ec6b97d7eb0">handleParseError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#a34a9d364e135aef879b4d24c5b165c6c">vhdl::parser::VhdlErrorHandler::handleParseError</a>, <a href="#a225f9289de15d675ad8c019c1b451e8e">handleUnexpectedToken</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#aeedd721b392d999dd9d2ba5944154c23">vhdl::parser::VhdlErrorHandler::handleUnexpectedToken</a> and <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a>.
</div>
</div>

### VhdlParserTokenManager {#aff28441094086f5cbf8ee8f34a8bc9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


Definition at line 18 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff28441094086f5cbf8ee8f34a8bc9a4">18</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>;</span></span></div>

</div>


Reference <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>.

Referenced by <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ErrorHandler() {#a72b0456d8c4d2541b7ff734563cbe6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::ErrorHandler::ErrorHandler ()</td>
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



Definition at line 47 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72b0456d8c4d2541b7ff734563cbe6be">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a72b0456d8c4d2541b7ff734563cbe6be">ErrorHandler</a>() { <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a> = 0; }</span></span></div>

</div>


Reference <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error\_count</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ErrorHandler() {#a1a8bed6e39180859e6fda8b0543b6222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual vhdl::parser::ErrorHandler::~ErrorHandler ()</td>
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



Definition at line 46 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a8bed6e39180859e6fda8b0543b6222">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> <a href="#a1a8bed6e39180859e6fda8b0543b6222">~ErrorHandler</a>() {}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getErrorCount() {#a8c83075a30c8b0ad7eca7aa59621a202}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual int vhdl::parser::ErrorHandler::getErrorCount ()</td>
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



Definition at line 40 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c83075a30c8b0ad7eca7aa59621a202">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8c83075a30c8b0ad7eca7aa59621a202">getErrorCount</a>() {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


Reference <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error\_count</a>.
</div>
</div>

### handleOtherError() {#ad64d99ee7d7560900ebef80322afdf19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::ErrorHandler::handleOtherError (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; message, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> * parser)</td>
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



Definition at line 43 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad64d99ee7d7560900ebef80322afdf19">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad64d99ee7d7560900ebef80322afdf19">handleOtherError</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; message, <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a> *<a href="/web-doxygen/docs/api/namespaces/vhdl/parser">parser</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">        fprintf(stderr, </span><span class="doxyHighlightStringLiteral">"Error: %s\n"</span><span class="doxyHighlight">, (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)message.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


Reference <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a>.
</div>
</div>

### handleParseError() {#aac7181808effb5d884333ec6b97d7eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::ErrorHandler::handleParseError (<a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> * last, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> * unexpected, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ae58db75f8ecd9f0ea05a95357b2c80d7">JJSimpleString</a> &amp; production, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> * parser)</td>
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



Definition at line 36 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac7181808effb5d884333ec6b97d7eb0">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac7181808effb5d884333ec6b97d7eb0">handleParseError</a>(<a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *last, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *unexpected, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ae58db75f8ecd9f0ea05a95357b2c80d7">JJSimpleString</a>&amp; production, <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a> *<a href="/web-doxygen/docs/api/namespaces/vhdl/parser">parser</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">        fprintf(stderr, </span><span class="doxyHighlightStringLiteral">"Encountered: %s at: %d:%d while parsing: %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/namespaces/vhdl/parser/#a1a036cc8724eb4d83f741e24a5050d73">addUnicodeEscapes</a>(unexpected-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">image</a>).c_str(), unexpected-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">beginLine</a>, unexpected-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a6fc8fab679c3f9110cb17c520836d02c">beginColumn</a>, production.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/vhdl/parser/#a1a036cc8724eb4d83f741e24a5050d73">vhdl::parser::addUnicodeEscapes</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a6fc8fab679c3f9110cb17c520836d02c">vhdl::parser::Token::beginColumn</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">vhdl::parser::Token::beginLine</a>, <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error\_count</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">vhdl::parser::Token::image</a> and <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a>.
</div>
</div>

### handleUnexpectedToken() {#a225f9289de15d675ad8c019c1b451e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::ErrorHandler::handleUnexpectedToken (int expectedKind, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; expectedToken, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> * actual, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> * parser)</td>
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



Definition at line 28 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a225f9289de15d675ad8c019c1b451e8e">28</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a225f9289de15d675ad8c019c1b451e8e">handleUnexpectedToken</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> expectedKind, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; expectedToken, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *actual, <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a> *<a href="/web-doxygen/docs/api/namespaces/vhdl/parser">parser</a>) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">        fprintf(stderr, </span><span class="doxyHighlightStringLiteral">"Expecting %s at: %d:%d but got %s\n"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/namespaces/vhdl/parser/#a1a036cc8724eb4d83f741e24a5050d73">addUnicodeEscapes</a>(expectedToken).c_str(), actual-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">beginLine</a>, actual-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a6fc8fab679c3f9110cb17c520836d02c">beginColumn</a>, <a href="/web-doxygen/docs/api/namespaces/vhdl/parser/#a1a036cc8724eb4d83f741e24a5050d73">addUnicodeEscapes</a>(actual-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">image</a>).c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/vhdl/parser/#a1a036cc8724eb4d83f741e24a5050d73">vhdl::parser::addUnicodeEscapes</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a6fc8fab679c3f9110cb17c520836d02c">vhdl::parser::Token::beginColumn</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a7fdeaf5cb35f8a5ecab251ddcd4b5909">vhdl::parser::Token::beginLine</a>, <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error\_count</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a48cc7b3f8164956fd940b2d53b792043">vhdl::parser::Token::image</a> and <a href="#a8bbb7acf78e67f3b3706943bf268ceed">VhdlParser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### error\_count {#ada8cb3fd4fa2dead863dc00edc1b9587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::ErrorHandler::error_count</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 21 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada8cb3fd4fa2dead863dc00edc1b9587">21</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ada8cb3fd4fa2dead863dc00edc1b9587">error_count</a>;</span></span></div>

</div>


Referenced by <a href="#a72b0456d8c4d2541b7ff734563cbe6be">ErrorHandler</a>, <a href="#a8c83075a30c8b0ad7eca7aa59621a202">getErrorCount</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#a5561c37f9abb893684f5537ad72f04cf">vhdl::parser::VhdlErrorHandler::handleOtherError</a>, <a href="#aac7181808effb5d884333ec6b97d7eb0">handleParseError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#a34a9d364e135aef879b4d24c5b165c6c">vhdl::parser::VhdlErrorHandler::handleParseError</a>, <a href="#a225f9289de15d675ad8c019c1b451e8e">handleUnexpectedToken</a> and <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#aeedd721b392d999dd9d2ba5944154c23">vhdl::parser::VhdlErrorHandler::handleUnexpectedToken</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
