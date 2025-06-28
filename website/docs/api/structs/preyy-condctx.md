---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/preyy-condctx
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `preYY_CondCtx` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct preYY_CondCtx { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8816dc8d6a8891850c41b82f50a3a39">preYY_CondCtx</a> (const QCString &amp;file, int line, const QCString &amp;id, bool b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0886db350b865344ce61171643dda73c">fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45f3b7e7dec05097d5811dd6e54cd4d">lineNr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f60a7f03190217c9925ae3e680643b">sectionId</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36f4e6aaa4260598344d930c2c7e1e64">skip</a></td>
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


<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### preYY&#95;CondCtx() {#ae8816dc8d6a8891850c41b82f50a3a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">preYY_CondCtx::preYY_CondCtx (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, bool b)</td>
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


<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8816dc8d6a8891850c41b82f50a3a39">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae8816dc8d6a8891850c41b82f50a3a39">preYY_CondCtx</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    : <a href="#a0886db350b865344ce61171643dda73c">fileName</a>(file), <a href="#af45f3b7e7dec05097d5811dd6e54cd4d">lineNr</a>(line), <a href="#a95f60a7f03190217c9925ae3e680643b">sectionId</a>(id), <a href="#a36f4e6aaa4260598344d930c2c7e1e64">skip</a>(b) {}</span></span></div>

</div>


References <a href="#a0886db350b865344ce61171643dda73c">fileName</a>, <a href="#af45f3b7e7dec05097d5811dd6e54cd4d">lineNr</a>, <a href="#a95f60a7f03190217c9925ae3e680643b">sectionId</a> and <a href="#a36f4e6aaa4260598344d930c2c7e1e64">skip</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fileName {#a0886db350b865344ce61171643dda73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString preYY_CondCtx::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0886db350b865344ce61171643dda73c">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0886db350b865344ce61171643dda73c">fileName</a>;</span></span></div>

</div>


Referenced by <a href="#ae8816dc8d6a8891850c41b82f50a3a39">preYY&#95;CondCtx</a>.
</div>
</div>

### lineNr {#af45f3b7e7dec05097d5811dd6e54cd4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int preYY_CondCtx::lineNr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af45f3b7e7dec05097d5811dd6e54cd4d">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af45f3b7e7dec05097d5811dd6e54cd4d">lineNr</a>;</span></span></div>

</div>


Referenced by <a href="#ae8816dc8d6a8891850c41b82f50a3a39">preYY&#95;CondCtx</a>.
</div>
</div>

### sectionId {#a95f60a7f03190217c9925ae3e680643b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString preYY_CondCtx::sectionId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a95f60a7f03190217c9925ae3e680643b">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a95f60a7f03190217c9925ae3e680643b">sectionId</a>;</span></span></div>

</div>


Referenced by <a href="#ae8816dc8d6a8891850c41b82f50a3a39">preYY&#95;CondCtx</a>.
</div>
</div>

### skip {#a36f4e6aaa4260598344d930c2c7e1e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool preYY_CondCtx::skip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36f4e6aaa4260598344d930c2c7e1e64">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a36f4e6aaa4260598344d930c2c7e1e64">skip</a>;</span></span></div>

</div>


Referenced by <a href="#ae8816dc8d6a8891850c41b82f50a3a39">preYY&#95;CondCtx</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
