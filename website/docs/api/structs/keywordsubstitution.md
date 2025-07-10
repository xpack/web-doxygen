---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/keywordsubstitution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `KeywordSubstitution` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct KeywordSubstitution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/util-h">src/util.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352000fcf120333cc133d260f0bf27a4">GetValue</a> = std::function&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcdda1b5e616cf9f5267d7c36b508c5">GetValueWithParam</a> = std::function&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19508ca34828a3c7d6f31b5ba7c204c">keyword</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::variant&lt; <a href="#a352000fcf120333cc133d260f0bf27a4">GetValue</a>, <a href="#adbcdda1b5e616cf9f5267d7c36b508c5">GetValueWithParam</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7f26bd59911316a638ee9e98488c84">getValueVariant</a></td>
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


<p>Definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### GetValue {#a352000fcf120333cc133d260f0bf27a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using KeywordSubstitution::GetValue =  std::function&lt;QCString()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a352000fcf120333cc133d260f0bf27a4">243</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a352000fcf120333cc133d260f0bf27a4">GetValue</a>          = std::function&lt;<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()&gt;;</span></span></div>

</div>

</div>
</div>

### GetValueWithParam {#adbcdda1b5e616cf9f5267d7c36b508c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using KeywordSubstitution::GetValueWithParam =  std::function&lt;QCString(const QCString &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbcdda1b5e616cf9f5267d7c36b508c5">244</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#adbcdda1b5e616cf9f5267d7c36b508c5">GetValueWithParam</a> = std::function&lt;<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### getValueVariant {#a8c7f26bd59911316a638ee9e98488c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::variant&lt;GetValue,GetValueWithParam&gt; KeywordSubstitution::getValueVariant</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c7f26bd59911316a638ee9e98488c84">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::variant&lt;GetValue,GetValueWithParam&gt; <a href="#a8c7f26bd59911316a638ee9e98488c84">getValueVariant</a>;</span></span></div>

</div>

</div>
</div>

### keyword {#af19508ca34828a3c7d6f31b5ba7c204c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* KeywordSubstitution::keyword</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af19508ca34828a3c7d6f31b5ba7c204c">242</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#af19508ca34828a3c7d6f31b5ba7c204c">keyword</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/util-h">util.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
