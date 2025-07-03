---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/parseexception
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ParseException` Class Reference

<p>This exception is thrown when parse errors are encountered. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class vhdl::parser::ParseException { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">vhdlparser/ParseException.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251f016d7ba95ffb185e46047c5360e8">ParseException</a> (Token currentTokenVal, int **expectedTokenSequencesVal, JJString *tokenImageVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor is used by the method "generateParseException" in the generated parser. <a href="#a251f016d7ba95ffb185e46047c5360e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8dbc5d8f42a4cc3375d7d21340dc95e">ParseException</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The following constructors are for use by you for whatever purpose you can think of. <a href="#aa8dbc5d8f42a4cc3375d7d21340dc95e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b393421747680d5de70a6932110d9da">ParseException</a> (const JJString &amp;message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor with message. <a href="#a1b393421747680d5de70a6932110d9da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12ecc8cb7ffc35c8f8dc85b98bf37ef">initialise</a> (Token currentToken, int **expectedTokenSequences, JJString *tokenImage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It uses "currentToken" and "expectedTokenSequences" to generate a parse error message and returns it. <a href="#aa12ecc8cb7ffc35c8f8dc85b98bf37ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b857653fcb33df53b87503a48616a70">add_escapes</a> (const JJString &amp;str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to convert raw characters to their escaped version when these raw version cannot be used as part of an ASCII string literal. <a href="#a2b857653fcb33df53b87503a48616a70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd2253ddf7f1c87444d51fc22efd9fe">currentToken</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the last token that has been consumed successfully. <a href="#aadd2253ddf7f1c87444d51fc22efd9fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int **</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28848a83d7553352654dd5ccb7ed40ef">expectedTokenSequences</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each entry in this array is an array of integers. <a href="#a28848a83d7553352654dd5ccb7ed40ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1bf4ce3b2d3dc5d984ee5ec2956ae51">tokenImage</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a reference to the "tokenImage" array of the generated parser within which the parse error occurred. <a href="#af1bf4ce3b2d3dc5d984ee5ec2956ae51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This exception is thrown when parse errors are encountered.</p>


<p>You can explicitly create objects of this exception type by calling the method generateParseException in the generated parser.</p>


<p>You can modify this class to customize your error reporting mechanisms so long as you retain the fields.</p>


<p>Definition at line 21 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ParseException() {#a251f016d7ba95ffb185e46047c5360e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::ParseException::ParseException (<a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> currentTokenVal, int ** expectedTokenSequencesVal, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> * tokenImageVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor is used by the method "generateParseException" in the generated parser.</p>


<p>Calling this constructor generates a new object of this type with the fields "currentToken", "expectedTokenSequences", and "tokenImage" set.</p>


<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>

</div>
</div>

### ParseException() {#aa8dbc5d8f42a4cc3375d7d21340dc95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::ParseException::ParseException ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The following constructors are for use by you for whatever purpose you can think of.</p>


<p>Constructing the exception in this manner makes the exception behave in the normal way - i.e., as documented in the class "Throwable". The fields "errorToken", "expectedTokenSequences", and "tokenImage" do not contain relevant information. The JavaCC generated code does not use these constructors.</p>


<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>

</div>
</div>

### ParseException() {#a1b393421747680d5de70a6932110d9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::ParseException::ParseException (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; message)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor with message.</p>

<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### add\_escapes() {#a2b857653fcb33df53b87503a48616a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString vhdl::parser::ParseException::add_escapes (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to convert raw characters to their escaped version when these raw version cannot be used as part of an ASCII string literal.</p>

<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>

</div>
</div>

### initialise() {#aa12ecc8cb7ffc35c8f8dc85b98bf37ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString vhdl::parser::ParseException::initialise (<a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> currentToken, int ** expectedTokenSequences, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> * tokenImage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It uses "currentToken" and "expectedTokenSequences" to generate a parse error message and returns it.</p>


<p>If this object has been created due to a parse error, and you do not catch it (it gets thrown from the parser) the correct error message gets displayed.</p>


<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>


<p>References <a href="#aadd2253ddf7f1c87444d51fc22efd9fe">currentToken</a>, <a href="#a28848a83d7553352654dd5ccb7ed40ef">expectedTokenSequences</a> and <a href="#af1bf4ce3b2d3dc5d984ee5ec2956ae51">tokenImage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### currentToken {#aadd2253ddf7f1c87444d51fc22efd9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token vhdl::parser::ParseException::currentToken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the last token that has been consumed successfully.</p>


<p>If this object has been created due to a parse error, the token following this token will (therefore) be the first error token.</p>


<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aadd2253ddf7f1c87444d51fc22efd9fe">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> <a href="#aadd2253ddf7f1c87444d51fc22efd9fe">currentToken</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa12ecc8cb7ffc35c8f8dc85b98bf37ef">initialise</a>.</p>

</div>
</div>

### expectedTokenSequences {#a28848a83d7553352654dd5ccb7ed40ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int** vhdl::parser::ParseException::expectedTokenSequences = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each entry in this array is an array of integers.</p>


<p>Each array of integers represents a sequence of tokens (by their ordinal values) that is expected at this point of the parse.</p>


<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28848a83d7553352654dd5ccb7ed40ef">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">** <a href="#a28848a83d7553352654dd5ccb7ed40ef">expectedTokenSequences</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#aa12ecc8cb7ffc35c8f8dc85b98bf37ef">initialise</a>.</p>

</div>
</div>

### tokenImage {#af1bf4ce3b2d3dc5d984ee5ec2956ae51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString* vhdl::parser::ParseException::tokenImage = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a reference to the "tokenImage" array of the generated parser within which the parse error occurred.</p>


<p>This array is defined in the generated ...Constants class.</p>


<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1bf4ce3b2d3dc5d984ee5ec2956ae51">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>* <a href="#af1bf4ce3b2d3dc5d984ee5ec2956ae51">tokenImage</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#aa12ecc8cb7ffc35c8f8dc85b98bf37ef">initialise</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/parseexception-h">ParseException.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
