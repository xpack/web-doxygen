---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/translatoradapter-1-11-0
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TranslatorAdapter_1_11_0` Class Reference



## Declaration

<div class="doxyDeclaration">
class TranslatorAdapter_1_11_0 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/translator-adapter-h">src/translator_adapter.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatoradapterbase">TranslatorAdapterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base of the translator adapter tree. <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatoradapter-1-10-0">TranslatorAdapter_1_10_0</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdedf3866f4148b4161f7956f9d3ddd3">updateNeededMessage</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90330144fe12976d2bdfd515c4648421">trImportant</a> () override</td>
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


<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### trImportant() {#a90330144fe12976d2bdfd515c4648421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapter_1_11_0::trImportant ()</td>
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



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90330144fe12976d2bdfd515c4648421">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a90330144fe12976d2bdfd515c4648421">trImportant</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a75fd1d1116debf9adacfef772a04a7b1">english</a>.trImportant(); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a75fd1d1116debf9adacfef772a04a7b1">TranslatorAdapterBase::english</a>.</p>

</div>
</div>

### updateNeededMessage() {#acdedf3866f4148b4161f7956f9d3ddd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapter_1_11_0::updateNeededMessage ()</td>
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




<p>This method is used to generate a warning message to signal the user that the translation of his/her language of choice needs updating. It must be implemented by the translator adapter class (pure virtual).</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage()</a></p></dd>
</dl>


<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acdedf3866f4148b4161f7956f9d3ddd3">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#acdedf3866f4148b4161f7956f9d3ddd3">updateNeededMessage</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage</a>(<a href="/web-doxygen/docs/api/classes/translator/#af1d1a225ccc757c51c6cecfeda886b93">idLanguage</a>(),</span><span class="doxyHighlightStringLiteral">"release 1.11.0"</span><span class="doxyHighlight">); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">TranslatorAdapterBase::createUpdateNeededMessage</a> and <a href="/web-doxygen/docs/api/classes/translator/#af1d1a225ccc757c51c6cecfeda886b93">Translator::idLanguage</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
