---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/vhdltokenmanagererrorhandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VhdlTokenManagerErrorHandler` Class Reference



## Declaration

<div class="doxyDeclaration">
class vhdl::parser::VhdlTokenManagerErrorHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">vhdlparser/VhdlParserErrorHandler.hpp</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenmanagererrorhandler">TokenManagerErrorHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1617061f43a0ececa71db05e4ca28b">VhdlTokenManagerErrorHandler</a> (const char *fileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae746ea76c9ae4d27e1c9200c74caa960">lexicalError</a> (bool EOFSeen, int, int errorLine, int, const JJString &amp;errorAfter, JJChar curChar, VhdlParserTokenManager *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c533dc72c65480b225f1515216317de">lexicalError</a> (const JJString &amp;errorMessage, VhdlParserTokenManager *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a></td>
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


<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VhdlTokenManagerErrorHandler() {#a4d1617061f43a0ececa71db05e4ca28b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::VhdlTokenManagerErrorHandler::VhdlTokenManagerErrorHandler (const char * fileName)</td>
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



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d1617061f43a0ececa71db05e4ca28b">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4d1617061f43a0ececa71db05e4ca28b">VhdlTokenManagerErrorHandler</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName) : <a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>(fileName) {}</span></span></div>

</div>


<p>Reference <a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lexicalError() {#ae746ea76c9ae4d27e1c9200c74caa960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::VhdlTokenManagerErrorHandler::lexicalError (bool EOFSeen, int, int errorLine, int, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; errorAfter, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> curChar, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a> *)</td>
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



<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae746ea76c9ae4d27e1c9200c74caa960">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae746ea76c9ae4d27e1c9200c74caa960">lexicalError</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> EOFSeen, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* lexState */</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> errorLine, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* errorColumn */</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; errorAfter, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> curChar, <a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenmanagererrorhandler/#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>* </span><span class="doxyHighlightComment">/* token_manager */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(<a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>,errorLine,</span><span class="doxyHighlightStringLiteral">"Lexical error, Encountered: '{:c}' after: '{}'"</span><span class="doxyHighlight">,(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">)curChar, (EOFSeen? </span><span class="doxyHighlightStringLiteral">"EOF"</span><span class="doxyHighlight"> : (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)errorAfter.c_str()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenmanagererrorhandler/#aff28441094086f5cbf8ee8f34a8bc9a4">vhdl::parser::TokenManagerErrorHandler::VhdlParserTokenManager</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### lexicalError() {#a6c533dc72c65480b225f1515216317de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::VhdlTokenManagerErrorHandler::lexicalError (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; errorMessage, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a> *)</td>
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



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c533dc72c65480b225f1515216317de">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6c533dc72c65480b225f1515216317de">lexicalError</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; errorMessage, <a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenmanagererrorhandler/#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>* </span><span class="doxyHighlightComment">/* token_manager */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(<a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>,-1,</span><span class="doxyHighlightStringLiteral">"Unknown error: '{}'"</span><span class="doxyHighlight">, (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)errorMessage.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenmanagererrorhandler/#aff28441094086f5cbf8ee8f34a8bc9a4">vhdl::parser::TokenManagerErrorHandler::VhdlParserTokenManager</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_fileName {#af7902c267118f16feb1484a97f949c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlTokenManagerErrorHandler::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparsererrorhandler-hpp">VhdlParserErrorHandler.hpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7902c267118f16feb1484a97f949c62">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af7902c267118f16feb1484a97f949c62">m_fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae746ea76c9ae4d27e1c9200c74caa960">lexicalError</a>, <a href="#a6c533dc72c65480b225f1515216317de">lexicalError</a> and <a href="#a4d1617061f43a0ececa71db05e4ca28b">VhdlTokenManagerErrorHandler</a>.</p>

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
