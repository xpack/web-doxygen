---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/tokenparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TokenParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class vhdl::parser::TokenParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlparser/vhdlstring.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> Manager. <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5cb74c3a7c9a7f4620c34d939da9fbc">setLexParser</a> (VhdlParser *p)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686a5c4c377513d56ee5588f9727314a">parser</a> = nullptr</td>
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


<p>Definition at line 17 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### setLexParser() {#ac5cb74c3a7c9a7f4620c34d939da9fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void vhdl::parser::TokenParser::setLexParser (<a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> * p)</td>
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


<p>Definition at line 20 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5cb74c3a7c9a7f4620c34d939da9fbc">20</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">   <a href="#ac5cb74c3a7c9a7f4620c34d939da9fbc">setLexParser</a>(<a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a>* p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">21</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a686a5c4c377513d56ee5588f9727314a">parser</a> = p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


Reference <a href="#a686a5c4c377513d56ee5588f9727314a">parser</a>.

Referenced by <a href="/web-doxygen/docs/api/structs/vhdloutlineparser/private/#a09e1a5b366fadb1761f46049e67df6c5">VHDLOutlineParser::Private::parseVhdlfile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### parser {#a686a5c4c377513d56ee5588f9727314a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlParser* vhdl::parser::TokenParser::parser = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 19 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a686a5c4c377513d56ee5588f9727314a">19</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a>* <a href="#a686a5c4c377513d56ee5588f9727314a">parser</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ac5cb74c3a7c9a7f4620c34d939da9fbc">setLexParser</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
