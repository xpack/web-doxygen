---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/vhdl/parser/jjcalls
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `JJCalls` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct vhdl::parser::JJCalls { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">vhdlparser/VhdlParser.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953e9b05e336c11f8e2435b3ea506bc1">~JJCalls</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d25b6278ae014a14a0f5be2678f663c">gen</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952889761822083d0eb8175cc62e6b7f">arg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/vhdl/parser/jjcalls">JJCalls</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0994fa11976ac659180bf73c1068783e">first</a></td>
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


Definition at line 12 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxySectionDef">

## Public Constructors

### JJCalls() {#aaaa2b2b81198a1e2a706a91baa09712c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::JJCalls::JJCalls ()</td>
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



Definition at line 18 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaaa2b2b81198a1e2a706a91baa09712c">18</a></span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a>() { <a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; <a href="#a952889761822083d0eb8175cc62e6b7f">arg</a> = 0; <a href="#a5d25b6278ae014a14a0f5be2678f663c">gen</a> = -1; <a href="#a0994fa11976ac659180bf73c1068783e">first</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; }</span></span></div>

</div>


References <a href="#a952889761822083d0eb8175cc62e6b7f">arg</a>, <a href="#a0994fa11976ac659180bf73c1068783e">first</a>, <a href="#a5d25b6278ae014a14a0f5be2678f663c">gen</a> and <a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~JJCalls() {#a953e9b05e336c11f8e2435b3ea506bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vhdl::parser::JJCalls::~JJCalls ()</td>
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



Definition at line 17 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a953e9b05e336c11f8e2435b3ea506bc1">17</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a953e9b05e336c11f8e2435b3ea506bc1">~JJCalls</a>() { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a>) </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> <a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a>; }</span></span></div>

</div>


Reference <a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### arg {#a952889761822083d0eb8175cc62e6b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::JJCalls::arg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 14 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a952889761822083d0eb8175cc62e6b7f">14</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">        <a href="#a952889761822083d0eb8175cc62e6b7f">arg</a>;</span></span></div>

</div>


Referenced by <a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a>.
</div>
</div>

### first {#a0994fa11976ac659180bf73c1068783e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token* vhdl::parser::JJCalls::first</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 16 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0994fa11976ac659180bf73c1068783e">16</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a>*     <a href="#a0994fa11976ac659180bf73c1068783e">first</a>;</span></span></div>

</div>


Referenced by <a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a>.
</div>
</div>

### gen {#a5d25b6278ae014a14a0f5be2678f663c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::JJCalls::gen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 13 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d25b6278ae014a14a0f5be2678f663c">13</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">        <a href="#a5d25b6278ae014a14a0f5be2678f663c">gen</a>;</span></span></div>

</div>


Referenced by <a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a>.
</div>
</div>

### next {#a6b6a95b77fab1e71ce05bd43da1b8f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JJCalls* vhdl::parser::JJCalls::next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 15 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">15</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a>*   <a href="#a6b6a95b77fab1e71ce05bd43da1b8f67">next</a>;</span></span></div>

</div>


Referenced by <a href="#aaaa2b2b81198a1e2a706a91baa09712c">JJCalls</a> and <a href="#a953e9b05e336c11f8e2435b3ea506bc1">\~JJCalls</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
