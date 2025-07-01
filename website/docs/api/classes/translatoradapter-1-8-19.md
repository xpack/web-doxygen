---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/translatoradapter-1-8-19
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TranslatorAdapter_1_8_19` Class Reference



## Declaration

<div class="doxyDeclaration">
class TranslatorAdapter_1_8_19 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/translator-adapter-h">src/translator_adapter.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2">TranslatorAdapter_1_9_2</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15">TranslatorAdapter_1_8_15</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe735ce5dabb33d67927f6a1de8e290">updateNeededMessage</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add37bc1e4a48a8ca3771d7c77d0ddf0a">trDesignUnitDocumentation</a> () override</td>
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


Definition at line 193 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### trDesignUnitDocumentation() {#add37bc1e4a48a8ca3771d7c77d0ddf0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapter_1_8_19::trDesignUnitDocumentation ()</td>
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



Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add37bc1e4a48a8ca3771d7c77d0ddf0a">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#add37bc1e4a48a8ca3771d7c77d0ddf0a">trDesignUnitDocumentation</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a75fd1d1116debf9adacfef772a04a7b1">english</a>.trDesignUnitDocumentation(); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a75fd1d1116debf9adacfef772a04a7b1">TranslatorAdapterBase::english</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/translatorafrikaans/#a6e037a5fc979fba91dcb770979676084">TranslatorAfrikaans::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorarabic/#ab1dd2497e15f03f6ec7969045ab266c9">TranslatorArabic::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorarmenian/#a2e65f4f44d448821a9babc3afd26a057">TranslatorArmenian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorcatalan/#a4ad827ecdbaf2922578184bce26a9397">TranslatorCatalan::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorchinesetraditional/#a29d6c69aac7462a3ab785bc764e1b984">TranslatorChinesetraditional::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorcroatian/#ae34666847138a860c2b1a459695608a0">TranslatorCroatian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatordanish/#ad3f1d8eced794307a561e4b15558d99b">TranslatorDanish::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoresperanto/#a5ab608e8a822ec52744d607815991c2f">TranslatorEsperanto::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorfinnish/#a3916f2f51d6b03915d115ae9eb83f69a">TranslatorFinnish::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorhungarian/#aec4cdb13117af263205f7c506ccff9e5">TranslatorHungarian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorindonesian/#ad64799c16b54eef4c1801bf860b5a5e7">TranslatorIndonesian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorjapanese/#a1e2aa16953afbf836a0c95bf3b8010f2">TranslatorJapanese::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorkorean/#a38bb63b8dbf7fbe4b6091e07bca3a745">TranslatorKorean::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorlatvian/#a1585480ad24e582d427e570178f987fc">TranslatorLatvian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorlithuanian/#ac1ad88d518436b82b5abd65d3a81987b">TranslatorLithuanian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatormacedonian/#ae9b33c3a184bd7005bc15637196ee8b5">TranslatorMacedonian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatornorwegian/#a3daa1b1c4e7f550d124a65d1c0a2e80e">TranslatorNorwegian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorpersian/#a4363bcf7fc00223534ad1852874c0be0">TranslatorPersian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorromanian/#ac444f21f3900057253582996b818ed64">TranslatorRomanian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorserbian/#aad3fc6d6675c350b26e6fa6bc4115a6e">TranslatorSerbian::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorserbiancyrillic/#a0d90936e2881d744b2551afeec99639b">TranslatorSerbianCyrillic::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorturkish/#a2b4dc69ec41d6e067a65982bd75825bc">TranslatorTurkish::trClassDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatorukrainian/#ada38d45d657e523a2563b261f96cf73b">TranslatorUkrainian::trClassDocumentation</a> and <a href="/web-doxygen/docs/api/classes/translatorvietnamese/#a20304d360d77b72040304b85c8c1c209">TranslatorVietnamese::trClassDocumentation</a>.
</div>
</div>

### updateNeededMessage() {#a0fe735ce5dabb33d67927f6a1de8e290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapter_1_8_19::updateNeededMessage ()</td>
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




This method is used to generate a warning message to signal the user that the translation of his/her language of choice needs updating. It must be implemented by the translator adapter class (pure virtual).

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage()</a>
</dd>
</dl>


Definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fe735ce5dabb33d67927f6a1de8e290">196</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0fe735ce5dabb33d67927f6a1de8e290">updateNeededMessage</a>()</span><span class="doxyHighlightKeyword"> override</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage</a>(<a href="/web-doxygen/docs/api/classes/translator/#af1d1a225ccc757c51c6cecfeda886b93">idLanguage</a>(),</span><span class="doxyHighlightStringLiteral">"release 1.8.19"</span><span class="doxyHighlight">); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/translatoradapterbase/#a71493b87a34d6e4c232e540734aba698">TranslatorAdapterBase::createUpdateNeededMessage</a> and <a href="/web-doxygen/docs/api/classes/translator/#af1d1a225ccc757c51c6cecfeda886b93">Translator::idLanguage</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
