---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/tokenmanagererrorhandler
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TokenManagerErrorHandler` Class Reference



## Declaration

<div class="doxyDeclaration">
class vhdl::parser::TokenManagerErrorHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">vhdlparser/ErrorHandler.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdltokenmanagererrorhandler">VhdlTokenManagerErrorHandler</a></td>
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

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0afc3cb894583ee40c53a3a5c54495dc">~TokenManagerErrorHandler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27aa05445202b2d20d5cd95983d8fd86">lexicalError</a> (bool EOFSeen, int lexState, int errorLine, int errorColumn, const JJString &amp;errorAfter, JJChar curChar, VhdlParserTokenManager *token_manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0dffd5c5809a0bf16881b19c5786fc3">lexicalError</a> (const JJString &amp;errorMessage, VhdlParserTokenManager *token_manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2fbf9bff5de1775a78dc4872ccdca5">error_count</a></td>
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


<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.</p>


<div class="doxySectionDef">

## Friends

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


<p>Definition at line 52 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff28441094086f5cbf8ee8f34a8bc9a4">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>;</span></span></div>

</div>


<p>Reference <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>.</p>


<p>Referenced by <a href="#a27aa05445202b2d20d5cd95983d8fd86">lexicalError</a>, <a href="#af0dffd5c5809a0bf16881b19c5786fc3">lexicalError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdltokenmanagererrorhandler/#ae746ea76c9ae4d27e1c9200c74caa960">vhdl::parser::VhdlTokenManagerErrorHandler::lexicalError</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdltokenmanagererrorhandler/#a6c533dc72c65480b225f1515216317de">vhdl::parser::VhdlTokenManagerErrorHandler::lexicalError</a> and <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TokenManagerErrorHandler() {#a0afc3cb894583ee40c53a3a5c54495dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual vhdl::parser::TokenManagerErrorHandler::~TokenManagerErrorHandler ()</td>
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



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0afc3cb894583ee40c53a3a5c54495dc">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> <a href="#a0afc3cb894583ee40c53a3a5c54495dc">~TokenManagerErrorHandler</a>() {}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### lexicalError() {#a27aa05445202b2d20d5cd95983d8fd86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::TokenManagerErrorHandler::lexicalError (bool EOFSeen, int lexState, int errorLine, int errorColumn, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; errorAfter, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> curChar, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a> * token_manager)</td>
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



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27aa05445202b2d20d5cd95983d8fd86">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a27aa05445202b2d20d5cd95983d8fd86">lexicalError</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> EOFSeen, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lexState, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> errorLine, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> errorColumn, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; errorAfter, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> curChar, <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>* token_manager) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// by default, we just print an error message and return.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">        fprintf(stderr, </span><span class="doxyHighlightStringLiteral">"Lexical error at: %d:%d. Encountered: %c after: %s.\n"</span><span class="doxyHighlight">, errorLine, errorColumn, curChar, (EOFSeen? </span><span class="doxyHighlightStringLiteral">"EOF"</span><span class="doxyHighlight"> : (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)errorAfter.c_str()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


<p>Reference <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>.</p>

</div>
</div>

### lexicalError() {#af0dffd5c5809a0bf16881b19c5786fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void vhdl::parser::TokenManagerErrorHandler::lexicalError (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; errorMessage, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a> * token_manager)</td>
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



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0dffd5c5809a0bf16881b19c5786fc3">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeyword">virtual</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af0dffd5c5809a0bf16881b19c5786fc3">lexicalError</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a>&amp; errorMessage, <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>* token_manager) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">        fprintf(stderr, </span><span class="doxyHighlightStringLiteral">"%s\n"</span><span class="doxyHighlight">, (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)errorMessage.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


<p>Reference <a href="#aff28441094086f5cbf8ee8f34a8bc9a4">VhdlParserTokenManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### error\_count {#a6d2fbf9bff5de1775a78dc4872ccdca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::TokenManagerErrorHandler::error_count</td>
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



<p>Definition at line 54 of file <a href="/web-doxygen/docs/api/files/vhdlparser/errorhandler-h">ErrorHandler.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d2fbf9bff5de1775a78dc4872ccdca5">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a6d2fbf9bff5de1775a78dc4872ccdca5">error_count</a>;</span></span></div>

</div>

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
