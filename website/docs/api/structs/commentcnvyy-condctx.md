---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/commentcnvyy-condctx
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `commentcnvYY_CondCtx` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct commentcnvYY_CondCtx { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad42c4b9beb5777586cad3c3af3977794">commentcnvYY_CondCtx</a> (int line, const QCString &amp;id, bool b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6788d979220d7bcd5ed1eaf232060e29">lineNr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1eed597f41d62965e72a0f1a4961d4d">sectionId</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a056399be29b38e047fb83f1d0682fa">skip</a></td>
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


<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### commentcnvYY&#95;CondCtx() {#ad42c4b9beb5777586cad3c3af3977794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">commentcnvYY_CondCtx::commentcnvYY_CondCtx (int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, bool b)</td>
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


<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad42c4b9beb5777586cad3c3af3977794">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad42c4b9beb5777586cad3c3af3977794">commentcnvYY_CondCtx</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">    : <a href="#a6788d979220d7bcd5ed1eaf232060e29">lineNr</a>(line),<a href="#ae1eed597f41d62965e72a0f1a4961d4d">sectionId</a>(id), <a href="#a4a056399be29b38e047fb83f1d0682fa">skip</a>(b) {}</span></span></div>

</div>


References <a href="#a6788d979220d7bcd5ed1eaf232060e29">lineNr</a>, <a href="#ae1eed597f41d62965e72a0f1a4961d4d">sectionId</a> and <a href="#a4a056399be29b38e047fb83f1d0682fa">skip</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### lineNr {#a6788d979220d7bcd5ed1eaf232060e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int commentcnvYY_CondCtx::lineNr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6788d979220d7bcd5ed1eaf232060e29">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a6788d979220d7bcd5ed1eaf232060e29">lineNr</a>;</span></span></div>

</div>


Referenced by <a href="#ad42c4b9beb5777586cad3c3af3977794">commentcnvYY&#95;CondCtx</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>.
</div>
</div>

### sectionId {#ae1eed597f41d62965e72a0f1a4961d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString commentcnvYY_CondCtx::sectionId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1eed597f41d62965e72a0f1a4961d4d">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae1eed597f41d62965e72a0f1a4961d4d">sectionId</a>;</span></span></div>

</div>


Referenced by <a href="#ad42c4b9beb5777586cad3c3af3977794">commentcnvYY&#95;CondCtx</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>.
</div>
</div>

### skip {#a4a056399be29b38e047fb83f1d0682fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool commentcnvYY_CondCtx::skip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a056399be29b38e047fb83f1d0682fa">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4a056399be29b38e047fb83f1d0682fa">skip</a>;</span></span></div>

</div>


Referenced by <a href="#ad42c4b9beb5777586cad3c3af3977794">commentcnvYY&#95;CondCtx</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a34860cedec3675010f3293403abd9bd3">endCondSection</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/commentcnv-l">commentcnv.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
