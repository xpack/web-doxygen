---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/token
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Token` Class Reference

Describes the input token stream. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class vhdl::parser::Token { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/token-h">vhdlparser/Token.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c8d87a0456cd4ce8a65662fa507bb1">Token</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
No-argument constructor. <a href="#af4c8d87a0456cd4ce8a65662fa507bb1">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3111dc253c0e2eb0a0cf128914ec4a44">Token</a> (int kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Constructs a new token for the specified <a href="/web-doxygen/docs/api/classes/image">Image</a>. <a href="#a3111dc253c0e2eb0a0cf128914ec4a44">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac43282de75e17a9e7376f41483492ef7">Token</a> (int kind, const JJString &amp;image)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Constructs a new token for the specified <a href="/web-doxygen/docs/api/classes/image">Image</a> and Kind. <a href="#ac43282de75e17a9e7376f41483492ef7">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de88d652a1ec6f9af406db8f960d757">~Token</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2e437f6aeef2e6d195ebfe51ae2bb0">getValue</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
An optional attribute value of the <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>. <a href="#adf2e437f6aeef2e6d195ebfe51ae2bb0">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8a89affaca037a701ddbca2dff6767d">toString</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the image. <a href="#ab8a89affaca037a701ddbca2dff6767d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021bfae89b9eec39a87db9577508916c">kind</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
An integer that describes the kind of this token. <a href="#a021bfae89b9eec39a87db9577508916c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fdeaf5cb35f8a5ecab251ddcd4b5909">beginLine</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The line number of the first character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>. <a href="#a7fdeaf5cb35f8a5ecab251ddcd4b5909">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc8fab679c3f9110cb17c520836d02c">beginColumn</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The column number of the first character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>. <a href="#a6fc8fab679c3f9110cb17c520836d02c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae891f2c047fc387a551a1ef49036a685">endLine</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The line number of the last character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>. <a href="#ae891f2c047fc387a551a1ef49036a685">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac61778db323adf6f0b89f9eed2b672cf">endColumn</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The column number of the last character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>. <a href="#ac61778db323adf6f0b89f9eed2b672cf">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48cc7b3f8164956fd940b2d53b792043">image</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The string image of the token. <a href="#a48cc7b3f8164956fd940b2d53b792043">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b2c4853d3ce100b0fee664d8460b69">next</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
A reference to the next regular (non-special) token from the input stream. <a href="#a82b2c4853d3ce100b0fee664d8460b69">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d02434823908bf848cdc9bb14f52b73">specialToken</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
This field is used to access special tokens that occur prior to this token, but after the immediately preceding regular (non-special) token. <a href="#a9d02434823908bf848cdc9bb14f52b73">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d01fa6f4dff4a18568da6b789662f94">newToken</a> (int ofKind, const JJString &amp;image)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a new <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> void \*, by default. <a href="#a6d01fa6f4dff4a18568da6b789662f94">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0f91605566a8b2862a8fd0f8726c93">newToken</a> (int ofKind)</td>
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

Describes the input token stream.

Definition at line 16 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxySectionDef">

## Public Constructors

### Token() {#af4c8d87a0456cd4ce8a65662fa507bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::Token::Token ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

No-argument constructor.

Definition at line 78 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

Referenced by <a href="#a7e0f91605566a8b2862a8fd0f8726c93">newToken</a> and <a href="#a6d01fa6f4dff4a18568da6b789662f94">newToken</a>.
</div>
</div>

### Token() {#a3111dc253c0e2eb0a0cf128914ec4a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::Token::Token (int kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Constructs a new token for the specified <a href="/web-doxygen/docs/api/classes/image">Image</a>.

Definition at line 83 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

Reference <a href="#a021bfae89b9eec39a87db9577508916c">kind</a>.
</div>
</div>

### Token() {#ac43282de75e17a9e7376f41483492ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::Token::Token (int kind, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; image)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Constructs a new token for the specified <a href="/web-doxygen/docs/api/classes/image">Image</a> and Kind.

Definition at line 88 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

References <a href="#a48cc7b3f8164956fd940b2d53b792043">image</a> and <a href="#a021bfae89b9eec39a87db9577508916c">kind</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Token() {#a7de88d652a1ec6f9af406db8f960d757}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual vhdl::parser::Token::~Token ()</td>
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



Definition at line 90 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getValue() {#adf2e437f6aeef2e6d195ebfe51ae2bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * vhdl::parser::Token::getValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

An optional attribute value of the <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>.


Tokens which are not used as syntactic sugar will often contain meaningful values that will be used later on by the compiler or interpreter. This attribute value is often different from the image. Any subclass of <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> that actually wants to return a non-NULL value can override this method as appropriate.

Definition at line 73 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.
</div>
</div>

### toString() {#ab8a89affaca037a701ddbca2dff6767d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const JJString &amp; vhdl::parser::Token::toString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns the image.

Definition at line 95 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### beginColumn {#a6fc8fab679c3f9110cb17c520836d02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::Token::beginColumn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

The column number of the first character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>.

Definition at line 30 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6fc8fab679c3f9110cb17c520836d02c">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a6fc8fab679c3f9110cb17c520836d02c">beginColumn</a> = 0;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#aac7181808effb5d884333ec6b97d7eb0">vhdl::parser::ErrorHandler::handleParseError</a> and <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a225f9289de15d675ad8c019c1b451e8e">vhdl::parser::ErrorHandler::handleUnexpectedToken</a>.
</div>
</div>

### beginLine {#a7fdeaf5cb35f8a5ecab251ddcd4b5909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::Token::beginLine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

The line number of the first character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>.

Definition at line 28 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fdeaf5cb35f8a5ecab251ddcd4b5909">28</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7fdeaf5cb35f8a5ecab251ddcd4b5909">beginLine</a> = 0;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#aac7181808effb5d884333ec6b97d7eb0">vhdl::parser::ErrorHandler::handleParseError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#a34a9d364e135aef879b4d24c5b165c6c">vhdl::parser::VhdlErrorHandler::handleParseError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a225f9289de15d675ad8c019c1b451e8e">vhdl::parser::ErrorHandler::handleUnexpectedToken</a> and <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#aeedd721b392d999dd9d2ba5944154c23">vhdl::parser::VhdlErrorHandler::handleUnexpectedToken</a>.
</div>
</div>

### endColumn {#ac61778db323adf6f0b89f9eed2b672cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::Token::endColumn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

The column number of the last character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>.

Definition at line 34 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac61778db323adf6f0b89f9eed2b672cf">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ac61778db323adf6f0b89f9eed2b672cf">endColumn</a> = 0;</span></span></div>

</div>

</div>
</div>

### endLine {#ae891f2c047fc387a551a1ef49036a685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::Token::endLine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

The line number of the last character of this <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>.

Definition at line 32 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae891f2c047fc387a551a1ef49036a685">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae891f2c047fc387a551a1ef49036a685">endLine</a> = 0;</span></span></div>

</div>

</div>
</div>

### image {#a48cc7b3f8164956fd940b2d53b792043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString vhdl::parser::Token::image</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

The string image of the token.

Definition at line 39 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a48cc7b3f8164956fd940b2d53b792043">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> <a href="#a48cc7b3f8164956fd940b2d53b792043">image</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#aac7181808effb5d884333ec6b97d7eb0">vhdl::parser::ErrorHandler::handleParseError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#a34a9d364e135aef879b4d24c5b165c6c">vhdl::parser::VhdlErrorHandler::handleParseError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/errorhandler/#a225f9289de15d675ad8c019c1b451e8e">vhdl::parser::ErrorHandler::handleUnexpectedToken</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler/#aeedd721b392d999dd9d2ba5944154c23">vhdl::parser::VhdlErrorHandler::handleUnexpectedToken</a>, <a href="#a6d01fa6f4dff4a18568da6b789662f94">newToken</a> and <a href="#ac43282de75e17a9e7376f41483492ef7">Token</a>.
</div>
</div>

### kind {#a021bfae89b9eec39a87db9577508916c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::Token::kind = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

An integer that describes the kind of this token.


This numbering system is determined by JavaCCParser, and a table of these numbers is stored in the file ...Constants.java.

Definition at line 25 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a021bfae89b9eec39a87db9577508916c">25</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a021bfae89b9eec39a87db9577508916c">kind</a> = 0;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser/#a0a310348ea4c5c718075984ca4231512">vhdl::parser::VhdlParser::checkListTok</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser/#a471597c9f6f6d723c407de960a87ec88">vhdl::parser::VhdlParser::checkNextTok</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a251d5cfa601b855d867ca28f7c149644">VHDLOutlineParser::error\_skipto</a>, <a href="#a3111dc253c0e2eb0a0cf128914ec4a44">Token</a> and <a href="#ac43282de75e17a9e7376f41483492ef7">Token</a>.
</div>
</div>

### next {#a82b2c4853d3ce100b0fee664d8460b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token* vhdl::parser::Token::next = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

A reference to the next regular (non-special) token from the input stream.


If this is the last token from the input stream, or if the token manager has not read tokens beyond this one, this field is set to NULL. This is true only if this token is also a regular token. Otherwise, see below for a description of the contents of this field.

Definition at line 49 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82b2c4853d3ce100b0fee664d8460b69">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af4c8d87a0456cd4ce8a65662fa507bb1">Token</a> *<a href="#a82b2c4853d3ce100b0fee664d8460b69">next</a> = 0;</span></span></div>

</div>

</div>
</div>

### specialToken {#a9d02434823908bf848cdc9bb14f52b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token* vhdl::parser::Token::specialToken = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

This field is used to access special tokens that occur prior to this token, but after the immediately preceding regular (non-special) token.


If there are no such special tokens, this field is set to NULL. When there are more than one such special token, this field refers to the last of these special tokens, which in turn refers to the next previous special token through its specialToken field, and so on until the first special token (whose specialToke\_ field is NULL). The next fields of special tokens refer to other special tokens that immediately follow it (without an intervening regular token). If there is no such token, this field is NULL.

Definition at line 63 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9d02434823908bf848cdc9bb14f52b73">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af4c8d87a0456cd4ce8a65662fa507bb1">Token</a> *<a href="#a9d02434823908bf848cdc9bb14f52b73">specialToken</a> = 0;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### newToken() {#a6d01fa6f4dff4a18568da6b789662f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token * vhdl::parser::Token::newToken (int ofKind, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; image)</td>
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

Returns a new <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> void \*, by default.


However, if you want, you can create and return subclass objects based on the value of ofKind. Simply add the cases to the switch for all those special cases. For example, if you have a subclass of <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> called IDToken that you want to create if ofKind is ID, simply add something like :

case MyParserConstants.ID : return new IDToken(ofKind, image);

to the following switch statement. Then you can cast matchedToken variable to the appropriate type and use sit in your lexical actions.

Definition at line 110 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

References <a href="#a48cc7b3f8164956fd940b2d53b792043">image</a> and <a href="#af4c8d87a0456cd4ce8a65662fa507bb1">Token</a>.
</div>
</div>

### newToken() {#a7e0f91605566a8b2862a8fd0f8726c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token * vhdl::parser::Token::newToken (int ofKind)</td>
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



Definition at line 112 of file <a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a>.

Reference <a href="#af4c8d87a0456cd4ce8a65662fa507bb1">Token</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/token-h">Token.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
