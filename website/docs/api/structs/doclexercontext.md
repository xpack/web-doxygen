---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/doclexercontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DocLexerContext` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct DocLexerContext { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a> (const TokenInfo &amp;tk, int r, int lvl, yy_size_t pos, const char *s, YY_BUFFER_STATE bs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d036164334e9185f473bbc24a865a9">token</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e9a68a5dac05327ccc406c1a8e2669">rule</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af642c9d98d61a5f08c615d79a0c4fcd1">autoListLevel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">yy_size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad213136475bcdea433cfb13e30ec5f2e">inputPos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2635bb7ec48f95756b72f5ce53d19500">inputString</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">YY_BUFFER_STATE</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff59ac36da3634c543277ef8b5575aca">state</a></td>
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


<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocLexerContext() {#adea932b01c5c23ea0d08df4d0220d560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocLexerContext::DocLexerContext (const <a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> &amp; tk, int r, int lvl, yy_size_t pos, const char * s, YY_BUFFER_STATE bs)</td>
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



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adea932b01c5c23ea0d08df4d0220d560">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> &amp;tk,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> r,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lvl,yy_size_t pos,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,YY_BUFFER_STATE bs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    : <a href="#a24d036164334e9185f473bbc24a865a9">token</a>(tk), <a href="#af2e9a68a5dac05327ccc406c1a8e2669">rule</a>(r), <a href="#af642c9d98d61a5f08c615d79a0c4fcd1">autoListLevel</a>(lvl), <a href="#ad213136475bcdea433cfb13e30ec5f2e">inputPos</a>(pos), <a href="#a2635bb7ec48f95756b72f5ce53d19500">inputString</a>(s), <a href="#aff59ac36da3634c543277ef8b5575aca">state</a>(bs) {}</span></span></div>

</div>


<p>References <a href="#af642c9d98d61a5f08c615d79a0c4fcd1">autoListLevel</a>, <a href="#ad213136475bcdea433cfb13e30ec5f2e">inputPos</a>, <a href="#a2635bb7ec48f95756b72f5ce53d19500">inputString</a>, <a href="#af2e9a68a5dac05327ccc406c1a8e2669">rule</a>, <a href="#aff59ac36da3634c543277ef8b5575aca">state</a> and <a href="#a24d036164334e9185f473bbc24a865a9">token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### autoListLevel {#af642c9d98d61a5f08c615d79a0c4fcd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocLexerContext::autoListLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af642c9d98d61a5f08c615d79a0c4fcd1">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af642c9d98d61a5f08c615d79a0c4fcd1">autoListLevel</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>.</p>

</div>
</div>

### inputPos {#ad213136475bcdea433cfb13e30ec5f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yy_size_t DocLexerContext::inputPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad213136475bcdea433cfb13e30ec5f2e">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  yy_size_t <a href="#ad213136475bcdea433cfb13e30ec5f2e">inputPos</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>.</p>

</div>
</div>

### inputString {#a2635bb7ec48f95756b72f5ce53d19500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* DocLexerContext::inputString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2635bb7ec48f95756b72f5ce53d19500">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a2635bb7ec48f95756b72f5ce53d19500">inputString</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>.</p>

</div>
</div>

### rule {#af2e9a68a5dac05327ccc406c1a8e2669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocLexerContext::rule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2e9a68a5dac05327ccc406c1a8e2669">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af2e9a68a5dac05327ccc406c1a8e2669">rule</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>.</p>

</div>
</div>

### state {#aff59ac36da3634c543277ef8b5575aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">YY_BUFFER_STATE DocLexerContext::state</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff59ac36da3634c543277ef8b5575aca">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">  YY_BUFFER_STATE <a href="#aff59ac36da3634c543277ef8b5575aca">state</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>.</p>

</div>
</div>

### token {#a24d036164334e9185f473bbc24a865a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenInfo DocLexerContext::token</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24d036164334e9185f473bbc24a865a9">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> <a href="#a24d036164334e9185f473bbc24a865a9">token</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adea932b01c5c23ea0d08df4d0220d560">DocLexerContext</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
