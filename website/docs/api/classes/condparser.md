---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/condparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CondParser` Class Reference

Copyright (C) 1997-2015 by Dimitri van Heesch. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class CondParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/condparser-h">src/condparser.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TOKENTYPE { <a href="#a49fd9c96ce822ecb68d8ab4489bb484b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OPERATOR_ID { <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66c">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28282ad4ee865a4601722ae5c4f7ea97">CondParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af254c02cc742b034cf62a9846b7b9749">parse</a> (const QCString &amp;fileName, int lineNr, const QCString &amp;expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Copyright (C) 1997-2015 by Dimitri van Heesch. <a href="#af254c02cc742b034cf62a9846b7b9749">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Get next token in the current string expr. <a href="#a767f34907250fdaaeaae44c37d82c3de">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
conditional operators AND and OR <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
NOT. <a href="#a42e0e9ce1665b6be5de97c16c26d353c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
parenthesized expression or variable <a href="#af63a661f43a32b9343e6b222661bf206">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">evalOperator</a> (const int opId, bool lhs, bool rhs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
evaluate an operator for given values <a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eacc43d99d9d65ba89361b9846b0c6f">evalVariable</a> (const QCString &amp;varName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
evaluate a variable <a href="#a6eacc43d99d9d65ba89361b9846b0c6f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a4c0a1dc2325a61a6555c4d48f8869">getOperatorId</a> (const QCString &amp;opName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns the id of the given operator returns -1 if the operator is not recognized <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448f211b15963afd7fc97413c135d021">m_err</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
error state <a href="#a448f211b15963afd7fc97413c135d021">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f8516736be27414bab7ff62030c4b2">m_expr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
holds the expression <a href="#ab5f8516736be27414bab7ff62030c4b2">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
points to a character in expr <a href="#ad6be9806676e4c982291efc8a43e3c50">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b7c2efbc206f720c384413f2630790">m_token</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
holds the token <a href="#a34b7c2efbc206f720c384413f2630790">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a49fd9c96ce822ecb68d8ab4489bb484b">TOKENTYPE</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
type of the token <a href="#a5bcf72a37dcd8bff1730267da0587697">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

Copyright (C) 1997-2015 by Dimitri van Heesch.


Permission to use, copy, modify, and distribute this software and its documentation under the terms of the GNU General Public License is hereby granted. No representations are made about the suitability of this software for any purpose. It is provided "as is" without express or implied warranty. See the GNU General Public License for more details.

Documents produced by <a href="/web-doxygen/docs/api/classes/doxygen">Doxygen</a> are derivative works derived from the input used in their production; they are not affected by this license.

C++ Expression parser for ENABLED\_SECTIONS in <a href="/web-doxygen/docs/api/classes/doxygen">Doxygen</a>

Features used: Operators: &amp;&amp; AND operator || OR operator ! NOT operator

Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxySectionDef">

## Enumerations

### OPERATOR\_ID {#a5aa74df7a6a3bdd9a8f5eecc10efa66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum CondParser::OPERATOR_ID </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN_OP<a id="a5aa74df7a6a3bdd9a8f5eecc10efa66cac8110a4c12bb2f7863a1f21a7cc5e322"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND<a id="a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR<a id="a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOT<a id="a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66cac8110a4c12bb2f7863a1f21a7cc5e322">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66cac8110a4c12bb2f7863a1f21a7cc5e322">UNKNOWN_OP</a> = -1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a> = 1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3">NOT</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

### TOKENTYPE {#a49fd9c96ce822ecb68d8ab4489bb484b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum CondParser::TOKENTYPE </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOTHING<a id="a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DELIMITER<a id="a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VARIABLE<a id="a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="a49fd9c96ce822ecb68d8ab4489bb484ba2f8004dacf1ef246d3fc618e428716d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a> = -1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2">VARIABLE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49fd9c96ce822ecb68d8ab4489bb484ba2f8004dacf1ef246d3fc618e428716d9">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a49fd9c96ce822ecb68d8ab4489bb484ba2f8004dacf1ef246d3fc618e428716d9">UNKNOWN</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CondParser() {#a28282ad4ee865a4601722ae5c4f7ea97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CondParser::CondParser ()</td>
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



Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28282ad4ee865a4601722ae5c4f7ea97">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a28282ad4ee865a4601722ae5c4f7ea97">CondParser</a>() : <a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>(nullptr), <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a>(<a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a>) {}</span></span></div>

</div>


References <a href="#ad6be9806676e4c982291efc8a43e3c50">m\_e</a>, <a href="#a5bcf72a37dcd8bff1730267da0587697">m\_tokenType</a> and <a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#af254c02cc742b034cf62a9846b7b9749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::parse (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; expr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Copyright (C) 1997-2015 by Dimitri van Heesch.


Permission to use, copy, modify, and distribute this software and its documentation under the terms of the GNU General Public License is hereby granted. No representations are made about the suitability of this software for any purpose. It is provided "as is" without express or implied warranty. See the GNU General Public License for more details.

Documents produced by <a href="/web-doxygen/docs/api/classes/doxygen">Doxygen</a> are derivative works derived from the input used in their production; they are not affected by this license.

C++ Expression parser for ENABLED\_SECTIONS in <a href="/web-doxygen/docs/api/classes/doxygen">Doxygen</a>

Features used: Operators: &amp;&amp; AND operator || OR operator ! NOT operator parses and evaluates the given expression.

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><ul class="doxyList ">
<li>On error, an error message is returned.</li>
<li>On success, the result of the expression is either "1" or "0".</li>
</ul>
</dd>
</dl>


Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af254c02cc742b034cf62a9846b7b9749">36</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af254c02cc742b034cf62a9846b7b9749">CondParser::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;expr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (expr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab5f8516736be27414bab7ff62030c4b2">m_expr</a>      = expr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// initialize all variables</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a> = <a href="#ab5f8516736be27414bab7ff62030c4b2">m_expr</a>.data();    </span><span class="doxyHighlightComment">// let m_e point to the start of the expression</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> answer=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a>==<a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a> &amp;&amp; <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// empty expression: answer==FALSE</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a448f211b15963afd7fc97413c135d021">m_err</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    answer = <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a448f211b15963afd7fc97413c135d021">m_err</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(fileName,lineNr,</span><span class="doxyHighlightStringLiteral">"problem evaluating expression '{}': {}"</span><span class="doxyHighlight">, expr, <a href="#a448f211b15963afd7fc97413c135d021">m_err</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("expr='%s' answer=%d\n",expr,answer);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> answer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ad6be9806676e4c982291efc8a43e3c50">m\_e</a>, <a href="#a448f211b15963afd7fc97413c135d021">m\_err</a>, <a href="#ab5f8516736be27414bab7ff62030c4b2">m\_expr</a>, <a href="#a34b7c2efbc206f720c384413f2630790">m\_token</a>, <a href="#a5bcf72a37dcd8bff1730267da0587697">m\_tokenType</a>, <a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a>, <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a048c00592e372edb8bd1cd16389b57a9">handleGuard</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a> and <a href="/web-doxygen/docs/api/files/src/pre-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evalOperator() {#ad4fcf0ce5b9644fb6ff130cf7e335730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::evalOperator (const int opId, bool lhs, bool rhs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

evaluate an operator for given values

Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">263</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">CondParser::evalOperator</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> opId, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> lhs, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> rhs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (opId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a>: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> lhs &amp;&amp; rhs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> lhs || rhs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a448f211b15963afd7fc97413c135d021">m_err</a> = </span><span class="doxyHighlightStringLiteral">"Internal error unknown operator: id="</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(opId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a448f211b15963afd7fc97413c135d021">m\_err</a>, <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>.

Referenced by <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a>.
</div>
</div>

### evalVariable() {#a6eacc43d99d9d65ba89361b9846b0c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::evalVariable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; varName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

evaluate a variable

Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6eacc43d99d9d65ba89361b9846b0c6f">279</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6eacc43d99d9d65ba89361b9846b0c6f">CondParser::evalVariable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;varName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;list = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(ENABLED_SECTIONS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::find(list.begin(),list.end(),varName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>())!=list.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config\_getList</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>.
</div>
</div>

### getOperatorId() {#af8a4c0a1dc2325a61a6555c4d48f8869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int CondParser::getOperatorId (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; opName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

returns the id of the given operator returns -1 if the operator is not recognized

Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8a4c0a1dc2325a61a6555c4d48f8869">90</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">CondParser::getOperatorId</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;opName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// level 2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opName==</span><span class="doxyHighlightStringLiteral">"&amp;&amp;"</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opName==</span><span class="doxyHighlightStringLiteral">"||"</span><span class="doxyHighlight">) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a>;  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// not operator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opName==</span><span class="doxyHighlightStringLiteral">"!"</span><span class="doxyHighlight">)  { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3">NOT</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66cac8110a4c12bb2f7863a1f21a7cc5e322">UNKNOWN_OP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a>, <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3">NOT</a>, <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a> and <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66cac8110a4c12bb2f7863a1f21a7cc5e322">UNKNOWN\_OP</a>.

Referenced by <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a> and <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>.
</div>
</div>

### getToken() {#a767f34907250fdaaeaae44c37d82c3de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CondParser::getToken ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Get next token in the current string expr.


Uses the data in m\_expr pointed to by m\_e to produce m\_tokenType and m\_token, set m\_err in case of an error

Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a767f34907250fdaaeaae44c37d82c3de">107</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a767f34907250fdaaeaae44c37d82c3de">CondParser::getToken</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("\tgetToken e:{%c}, ascii=%i, col=%i\n", *e, *e, e-expr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// skip over whitespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a> == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a> == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a> == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)     </span><span class="doxyHighlightComment">// space or tab or newline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for end of expression</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>==</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// token is still empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for parentheses</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a> == </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight"> || *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a> == </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a> += *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for operators (delimiters)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/condparser-cpp/#a51b274f2d0a9dc8d6a7896a7b1960bf7">isDelimiter</a>(*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/condparser-cpp/#a51b274f2d0a9dc8d6a7896a7b1960bf7">isDelimiter</a>(*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a> += *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for variables</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/condparser-cpp/#ae0c69620b1ff6e7ceafd3461ccf2d142">isAlpha</a>(*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2">VARIABLE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/condparser-cpp/#a729d53d4881f206bfd8de6b4ebf99787">isAlphaNumSpec</a>(*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a> += *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// something unknown is found, wrong characters -&gt; a syntax error</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> = <a href="#a49fd9c96ce822ecb68d8ab4489bb484ba2f8004dacf1ef246d3fc618e428716d9">UNKNOWN</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a> += *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a448f211b15963afd7fc97413c135d021">m_err</a> = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"Syntax error in part '"</span><span class="doxyHighlight">)+<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>+</span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>, <a href="/web-doxygen/docs/api/files/src/condparser-cpp/#ae0c69620b1ff6e7ceafd3461ccf2d142">isAlpha</a>, <a href="/web-doxygen/docs/api/files/src/condparser-cpp/#a729d53d4881f206bfd8de6b4ebf99787">isAlphaNumSpec</a>, <a href="/web-doxygen/docs/api/files/src/condparser-cpp/#a51b274f2d0a9dc8d6a7896a7b1960bf7">isDelimiter</a>, <a href="#ad6be9806676e4c982291efc8a43e3c50">m\_e</a>, <a href="#a448f211b15963afd7fc97413c135d021">m\_err</a>, <a href="#a34b7c2efbc206f720c384413f2630790">m\_token</a>, <a href="#a5bcf72a37dcd8bff1730267da0587697">m\_tokenType</a>, <a href="#a49fd9c96ce822ecb68d8ab4489bb484babcaf3be350d7a11e470f9d7cef66e891">NOTHING</a>, <a href="#a49fd9c96ce822ecb68d8ab4489bb484ba2f8004dacf1ef246d3fc618e428716d9">UNKNOWN</a> and <a href="#a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2">VARIABLE</a>.

Referenced by <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a>, <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a>, <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>, <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a> and <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>.
</div>
</div>

### parseLevel1() {#a6fb4d64e51915d819ab6bbcdc40a387b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::parseLevel1 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

conditional operators AND and OR

Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6fb4d64e51915d819ab6bbcdc40a387b">172</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">CondParser::parseLevel1</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ans = <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> opId = <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">getOperatorId</a>(<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (opId==<a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a> || opId==<a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    ans = <a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">evalOperator</a>(opId, ans, <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">    opId = <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">getOperatorId</a>(<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ans;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66caa6deda36f663e46ae740b13fbf4e79f4">AND</a>, <a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">evalOperator</a>, <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">getOperatorId</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#a34b7c2efbc206f720c384413f2630790">m\_token</a>, <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca1876531ccdd04cb91a5c786dc77198ce">OR</a> and <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>.

Referenced by <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a> and <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a>.
</div>
</div>

### parseLevel2() {#a42e0e9ce1665b6be5de97c16c26d353c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::parseLevel2 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

NOT.

Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 190 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42e0e9ce1665b6be5de97c16c26d353c">190</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a42e0e9ce1665b6be5de97c16c26d353c">CondParser::parseLevel2</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> opId = <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">getOperatorId</a>(<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opId == <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3">NOT</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af8a4c0a1dc2325a61a6555c4d48f8869">getOperatorId</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#a34b7c2efbc206f720c384413f2630790">m\_token</a>, <a href="#a5aa74df7a6a3bdd9a8f5eecc10efa66ca3dd545603f097982a39111714ebd3cd3">NOT</a> and <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a>.

Referenced by <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a>.
</div>
</div>

### parseLevel3() {#af63a661f43a32b9343e6b222661bf206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::parseLevel3 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

parenthesized expression or variable

Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af63a661f43a32b9343e6b222661bf206">208</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af63a661f43a32b9343e6b222661bf206">CondParser::parseLevel3</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check if it is a parenthesized expression</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a> == <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>==</span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ans = <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a>!=<a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a> || <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>!=</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a448f211b15963afd7fc97413c135d021">m_err</a>=</span><span class="doxyHighlightStringLiteral">"Parenthesis ) missing"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ans;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if not parenthesized then the expression is a variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a49fd9c96ce822ecb68d8ab4489bb484bab8fea9f3274addd57d0b8ebfd1bd907e">DELIMITER</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#a448f211b15963afd7fc97413c135d021">m\_err</a>, <a href="#a34b7c2efbc206f720c384413f2630790">m\_token</a>, <a href="#a5bcf72a37dcd8bff1730267da0587697">m\_tokenType</a>, <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a> and <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>.

Referenced by <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>.
</div>
</div>

### parseVar() {#ae984d41f533dbf4306ddbffe725e272e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CondParser::parseVar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>, definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae984d41f533dbf4306ddbffe725e272e">232</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae984d41f533dbf4306ddbffe725e272e">CondParser::parseVar</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ans = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2">VARIABLE</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// this is a variable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">      ans = <a href="#a6eacc43d99d9d65ba89361b9846b0c6f">evalVariable</a>(<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// syntax error or unexpected end of expression</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a448f211b15963afd7fc97413c135d021">m_err</a>=</span><span class="doxyHighlightStringLiteral">"Unexpected end of expression"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a448f211b15963afd7fc97413c135d021">m_err</a>=</span><span class="doxyHighlightStringLiteral">"Value expected"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ans;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6eacc43d99d9d65ba89361b9846b0c6f">evalVariable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#a448f211b15963afd7fc97413c135d021">m\_err</a>, <a href="#a34b7c2efbc206f720c384413f2630790">m\_token</a>, <a href="#a5bcf72a37dcd8bff1730267da0587697">m\_tokenType</a> and <a href="#a49fd9c96ce822ecb68d8ab4489bb484baa23d749d95982f9481de025aeb453bb2">VARIABLE</a>.

Referenced by <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_e {#ad6be9806676e4c982291efc8a43e3c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* CondParser::m_e</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

points to a character in expr

Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6be9806676e4c982291efc8a43e3c50">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ad6be9806676e4c982291efc8a43e3c50">m_e</a>;                </span><span class="doxyHighlightComment">//!&lt; points to a character in expr</span></span></div>

</div>


Referenced by <a href="#a28282ad4ee865a4601722ae5c4f7ea97">CondParser</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a> and <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a>.
</div>
</div>

### m\_err {#a448f211b15963afd7fc97413c135d021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString CondParser::m_err</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

error state

Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a448f211b15963afd7fc97413c135d021">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a448f211b15963afd7fc97413c135d021">m_err</a>;                 </span><span class="doxyHighlightComment">//!&lt; error state</span></span></div>

</div>


Referenced by <a href="#ad4fcf0ce5b9644fb6ff130cf7e335730">evalOperator</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a>, <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a> and <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>.
</div>
</div>

### m\_expr {#ab5f8516736be27414bab7ff62030c4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString CondParser::m_expr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

holds the expression

Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5f8516736be27414bab7ff62030c4b2">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab5f8516736be27414bab7ff62030c4b2">m_expr</a>;                </span><span class="doxyHighlightComment">//!&lt; holds the expression</span></span></div>

</div>


Referenced by <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a>.
</div>
</div>

### m\_token {#a34b7c2efbc206f720c384413f2630790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString CondParser::m_token</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

holds the token

Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34b7c2efbc206f720c384413f2630790">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a34b7c2efbc206f720c384413f2630790">m_token</a>;               </span><span class="doxyHighlightComment">//!&lt; holds the token</span></span></div>

</div>


Referenced by <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a>, <a href="#a6fb4d64e51915d819ab6bbcdc40a387b">parseLevel1</a>, <a href="#a42e0e9ce1665b6be5de97c16c26d353c">parseLevel2</a>, <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a> and <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>.
</div>
</div>

### m\_tokenType {#a5bcf72a37dcd8bff1730267da0587697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TOKENTYPE CondParser::m_tokenType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

type of the token

Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5bcf72a37dcd8bff1730267da0587697">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a49fd9c96ce822ecb68d8ab4489bb484b">TOKENTYPE</a> <a href="#a5bcf72a37dcd8bff1730267da0587697">m_tokenType</a>;          </span><span class="doxyHighlightComment">//!&lt; type of the token</span></span></div>

</div>


Referenced by <a href="#a28282ad4ee865a4601722ae5c4f7ea97">CondParser</a>, <a href="#a767f34907250fdaaeaae44c37d82c3de">getToken</a>, <a href="#af254c02cc742b034cf62a9846b7b9749">parse</a>, <a href="#af63a661f43a32b9343e6b222661bf206">parseLevel3</a> and <a href="#ae984d41f533dbf4306ddbffe725e272e">parseVar</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/condparser-cpp">condparser.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/condparser-h">condparser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
