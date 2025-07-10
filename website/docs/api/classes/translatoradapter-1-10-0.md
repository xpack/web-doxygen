---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/translatoradapter-1-10-0
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TranslatorAdapter_1_10_0` Class Reference



## Declaration

<div class="doxyDeclaration">
class TranslatorAdapter_1_10_0 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/translator-adapter-h">src/translator_adapter.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatoradapter-1-11-0">TranslatorAdapter_1_11_0</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8">TranslatorAdapter_1_9_8</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a095ccfc1e12a1d38e719c4ef32ae9">updateNeededMessage</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e317b08926807712deaf072a8e6b5e0">trCopyToClipboard</a> () override</td>
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


<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### trCopyToClipboard() {#a6e317b08926807712deaf072a8e6b5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapter_1_10_0::trCopyToClipboard ()</td>
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



<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e317b08926807712deaf072a8e6b5e0">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6e317b08926807712deaf072a8e6b5e0">trCopyToClipboard</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a75fd1d1116debf9adacfef772a04a7b1">english</a>.trCopyToClipboard(); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a75fd1d1116debf9adacfef772a04a7b1">TranslatorAdapterBase::english</a>.</p>

</div>
</div>

### updateNeededMessage() {#ac4a095ccfc1e12a1d38e719c4ef32ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapter_1_10_0::updateNeededMessage ()</td>
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


<p>Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4a095ccfc1e12a1d38e719c4ef32ae9">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac4a095ccfc1e12a1d38e719c4ef32ae9">updateNeededMessage</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage</a>(<a href="/web-doxygen/docs/api/classes/translator/#af1d1a225ccc757c51c6cecfeda886b93">idLanguage</a>(),</span><span class="doxyHighlightStringLiteral">"release 1.10.0"</span><span class="doxyHighlight">); }</span></span></div>

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
