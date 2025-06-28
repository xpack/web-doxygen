---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdl/parser/tokenmgrerror
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TokenMgrError` Class Reference



## Declaration

<div class="doxyDeclaration">
class vhdl::parser::TokenMgrError { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">vhdlparser/TokenMgrError.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860806ee07d5e8223004cc4dae5386e9">TokenMgrError</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>No arg constructor. <a href="#a860806ee07d5e8223004cc4dae5386e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58e9b420bb0e53d5944cc96e8a8b349">TokenMgrError</a> (const JJString &amp;message, int reason)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor with message and reason. <a href="#aa58e9b420bb0e53d5944cc96e8a8b349">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f6a2866b37dc073293f43eaafafdbf">TokenMgrError</a> (bool EOFSeen, int lexState, int errorLine, int errorColumn, const JJString &amp;errorAfter, JJChar curChar, int reason)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Full Constructor. <a href="#a73f6a2866b37dc073293f43eaafafdbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50f498a288427b988cd7021a977378f8">LexicalError</a> (bool EOFSeen, int lexState, int errorLine, int errorColumn, const JJString &amp;errorAfter, JJChar curChar)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a detailed message for the Error when it is thrown by the token manager to indicate a lexical error. <a href="#a50f498a288427b988cd7021a977378f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a5265b1c68b955c03c15e142346250">getMessage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>You can also modify the body of this method to customize your error messages. <a href="#a17a5265b1c68b955c03c15e142346250">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac142542be128305d21d59277db52eb93">errorCode</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates the reason why the exception is thrown. <a href="#ac142542be128305d21d59277db52eb93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd946e2e5c74b2c9bcf818e66dd60e0">message</a></td>
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


<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### TokenMgrError() {#a860806ee07d5e8223004cc4dae5386e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::TokenMgrError::TokenMgrError ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>No arg constructor.</p>

<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>
</div>
</div>

### TokenMgrError() {#aa58e9b420bb0e53d5944cc96e8a8b349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::TokenMgrError::TokenMgrError (const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; message, int reason)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Constructor with message and reason.</p>

<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>

Reference <a href="#a4dd946e2e5c74b2c9bcf818e66dd60e0">message</a>.
</div>
</div>

### TokenMgrError() {#a73f6a2866b37dc073293f43eaafafdbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::TokenMgrError::TokenMgrError (bool EOFSeen, int lexState, int errorLine, int errorColumn, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; errorAfter, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> curChar, int reason)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Full Constructor.</p>

<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMessage() {#a17a5265b1c68b955c03c15e142346250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString vhdl::parser::TokenMgrError::getMessage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>You can also modify the body of this method to customize your error messages.</p>


<p>For example, cases like LOOP_DETECTED and INVALID_LEXICAL_STATE are not of end-users concern, so you can return something like :</p>


<pre><code>"Internal Error : Please file a bug report .... "
</code></pre>


<p>from this method for such cases in the release version of your parser.</p>

<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>
</div>
</div>

### LexicalError() {#a50f498a288427b988cd7021a977378f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString vhdl::parser::TokenMgrError::LexicalError (bool EOFSeen, int lexState, int errorLine, int errorColumn, const <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> &amp; errorAfter, <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a> curChar)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns a detailed message for the Error when it is thrown by the token manager to indicate a lexical error.</p>


<p>Parameters : EOFSeen : indicates if EOF caused the lexical error curLexState : lexical state in which this error occurred errorLine : line number when the error occurred errorColumn : column number when the error occurred errorAfter : prefix that was seen before this error occurred curchar : the offending character Note: You can customize the lexical error message by modifying this method.</p>

<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### errorCode {#ac142542be128305d21d59277db52eb93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::TokenMgrError::errorCode = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Indicates the reason why the exception is thrown.</p>


<p>It will have one of the above 4 values.</p>

<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac142542be128305d21d59277db52eb93">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ac142542be128305d21d59277db52eb93">errorCode</a> = -1;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### message {#a4dd946e2e5c74b2c9bcf818e66dd60e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJString vhdl::parser::TokenMgrError::message</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4dd946e2e5c74b2c9bcf818e66dd60e0">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a53453cc4dabae8211762d8e348cf7a00">JJString</a> <a href="#a4dd946e2e5c74b2c9bcf818e66dd60e0">message</a>;</span></span></div>

</div>


Referenced by <a href="#aa58e9b420bb0e53d5944cc96e8a8b349">TokenMgrError</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/tokenmgrerror-h">TokenMgrError.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
