---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/translatoradapterbase
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TranslatorAdapterBase` Class Reference

Base of the translator adapter tree. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class TranslatorAdapterBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/translator-adapter-h">src/translator_adapter.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translator">Translator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Abstract base class for all translatable text fragments. <a href="/web-doxygen/docs/api/classes/translator/#details">More...</a>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e991f74f504d2a017f1f6a28a9d9380">updateNeededMessage</a> () override=0</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage</a> (const QCString &amp;languageName, const QCString &amp;versionString)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/translatorenglish">TranslatorEnglish</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75fd1d1116debf9adacfef772a04a7b1">english</a></td>
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

## Description {#details}

Base of the translator adapter tree.


This abstract class provides access to the english translations, to be used as a substitute for not implemented local translations.

Definition at line 13 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### updateNeededMessage() {#a6e991f74f504d2a017f1f6a28a9d9380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual QCString TranslatorAdapterBase::updateNeededMessage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




This method is used to generate a warning message to signal the user that the translation of his/her language of choice needs updating. It must be implemented by the translator adapter class (pure virtual).

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage()</a></dd>
</dl>


Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### createUpdateNeededMessage() {#a71493b87a34d6e4c232e540734aba698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString TranslatorAdapterBase::createUpdateNeededMessage (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; languageName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; versionString)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




An auxiliary inline method used by the <a href="#a6e991f74f504d2a017f1f6a28a9d9380">updateNeededMessage()</a> for building a warning message.

Definition at line 21 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71493b87a34d6e4c232e540734aba698">21</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a71493b87a34d6e4c232e540734aba698">createUpdateNeededMessage</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; languageName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlight">                                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; versionString)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"The selected output language \""</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlight">             + languageName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">             + </span><span class="doxyHighlightStringLiteral">"\" has not been updated\nsince "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">             + versionString</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">             + </span><span class="doxyHighlightStringLiteral">".  As a result some sentences may appear in English.\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/translatoradapter-1-10-0/#ac4a095ccfc1e12a1d38e719c4ef32ae9">TranslatorAdapter\_1\_10\_0::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-11-0/#acdedf3866f4148b4161f7956f9d3ddd3">TranslatorAdapter\_1\_11\_0::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-4-6/#ae9fb378c1e066585a2176405ee66fc6c">TranslatorAdapter\_1\_4\_6::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a60a555e2a3148b87c47425d3eaeeab15">TranslatorAdapter\_1\_6\_0::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#a6dc08332af85f6a6544c0aafa907f144">TranslatorAdapter\_1\_7\_5::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#a895b4e6b6e3da314e46f2f104d449d0a">TranslatorAdapter\_1\_8\_0::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ad5b9152a47e6df4123ac00048c437991">TranslatorAdapter\_1\_8\_15::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-19/#a0fe735ce5dabb33d67927f6a1de8e290">TranslatorAdapter\_1\_8\_19::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a6d612653b55e995756801d247e99c408">TranslatorAdapter\_1\_8\_2::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#a74183234bd2567b3313fc8de83517779">TranslatorAdapter\_1\_8\_4::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#aa9f043c9934470919e56ed0b21b905bd">TranslatorAdapter\_1\_9\_2::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-4/#a4347c9f5c8a72bd1333cc83dd414b81c">TranslatorAdapter\_1\_9\_4::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-5/#adc4cd28fae5387221ef1680c47540832">TranslatorAdapter\_1\_9\_5::updateNeededMessage</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-6/#a523d3dc5dc8c5a886cc40fcefcf15903">TranslatorAdapter\_1\_9\_6::updateNeededMessage</a> and <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a00aaaee570523d31e14c4b6b7a1faaba">TranslatorAdapter\_1\_9\_8::updateNeededMessage</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### english {#a75fd1d1116debf9adacfef772a04a7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TranslatorEnglish TranslatorAdapterBase::english</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 16 of file <a href="/web-doxygen/docs/api/files/src/translator-adapter-h">translator_adapter.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75fd1d1116debf9adacfef772a04a7b1">16</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/translatorenglish">TranslatorEnglish</a> <a href="#a75fd1d1116debf9adacfef772a04a7b1">english</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#a4050986f462b7c79b8a281229761d27e">TranslatorAdapter\_1\_8\_0::trAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#a58abe237950464dc27fc4851d7265bce">TranslatorAdapter\_1\_8\_0::trAndMore</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-4-6/#ade19ba8b9984c67d6c0473dbbc1faf26">TranslatorAdapter\_1\_4\_6::trCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#a731b7bbc177670387374e6159a0c9df1">TranslatorAdapter\_1\_7\_5::trCiteReferences</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a3bb5b7050b0d4464cbcb0fcf98eda6c4">TranslatorAdapter\_1\_8\_2::trClassMethods</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a2fbaf9a4a967265021154368c3322c20">TranslatorAdapter\_1\_6\_0::trCompoundIndexFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a0c88472e4cec1b21c895c5e33d1c56c7">TranslatorAdapter\_1\_6\_0::trCompoundListDescriptionFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a7153b8a1fb3038498367d0e076604053">TranslatorAdapter\_1\_6\_0::trCompoundListFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a015d6f583ac3db0bd71e0c98e6b84d72">TranslatorAdapter\_1\_6\_0::trCompoundMembersDescriptionFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a89676bb4be4be462619aa662af4be06a">TranslatorAdapter\_1\_6\_0::trCompoundMembersFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a701c8c695f6f957b90feb1881acc0e8b">TranslatorAdapter\_1\_6\_0::trCompoundReferenceFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a56c31404f572b42763c0c300bed1172c">TranslatorAdapter\_1\_8\_15::trCompoundReferenceSlice</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-6/#ad88472fd943fd39495a8e829472b91d7">TranslatorAdapter\_1\_9\_6::trCompoundType</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#a62e8031bd1e3f9c0a25142e716ef21f1">TranslatorAdapter\_1\_9\_2::trConcept</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#a74353f142ba0b8b0abeb93b3234bc554">TranslatorAdapter\_1\_9\_2::trConceptDefinition</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#ae6861ab75f348c9c104468ba2f091e69">TranslatorAdapter\_1\_9\_2::trConceptDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#a3a2a9a62713c10387464dadeb816098c">TranslatorAdapter\_1\_9\_2::trConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#a5c7f71864052d4162445a7a88d00bc06">TranslatorAdapter\_1\_9\_2::trConceptList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#a31fd01c8286a85826af50d76322dae00">TranslatorAdapter\_1\_9\_2::trConceptListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-2/#a409d24476a020f90416ce2ca6d7213d0">TranslatorAdapter\_1\_9\_2::trConceptReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ae36f9379cc8f5239063b2da121bf9dff">TranslatorAdapter\_1\_8\_15::trConstantDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#aaef665603f85e9acae2ed9b8a572cc86">TranslatorAdapter\_1\_8\_4::trConstantGroupReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#a8104275979303f7db837d92d7729aeda">TranslatorAdapter\_1\_8\_4::trConstantGroups</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ad6e4da4b72da2ec28cd800a004447916">TranslatorAdapter\_1\_8\_15::trConstants</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#a0666871e11766487c24c0dcfac0e3335">TranslatorAdapter\_1\_7\_5::trCopyright</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-10-0/#a6e317b08926807712deaf072a8e6b5e0">TranslatorAdapter\_1\_10\_0::trCopyToClipboard</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a16a3e3f8e74c8141cf1f1a6c3173ee9f">TranslatorAdapter\_1\_8\_15::trCustomReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ab6ebdec042574ccd5564e94bbfb3c388">TranslatorAdapter\_1\_8\_15::trDataMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a3a2d0e6ced6a8866a09f83bc6a2c1bab">TranslatorAdapter\_1\_8\_15::trDataMembers</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a29b16e581f14d66d62563f7f933f6415">TranslatorAdapter\_1\_6\_0::trDataTypes</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#a62a2a67b7463b033d26a6e6bc9858c0d">TranslatorAdapter\_1\_7\_5::trDateTime</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#aa22a597166db9f1069b22082cd5de734">TranslatorAdapter\_1\_7\_5::trDayPeriod</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-6/#acd7eee06a5aa0f205f71755cb1fe3f0b">TranslatorAdapter\_1\_9\_6::trDeclaration</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-6/#a29da73c285223b32325756daf7c35b34">TranslatorAdapter\_1\_9\_6::trDefinition</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-19/#add37bc1e4a48a8ca3771d7c77d0ddf0a">TranslatorAdapter\_1\_8\_19::trDesignUnitDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ac3e6b9bafe48cc13b060ff3a4941d87f">TranslatorAdapter\_1\_8\_15::trDesignUnitHierarchy</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#aacd7797e29bf2ab2f2eb26747718d876">TranslatorAdapter\_1\_8\_15::trDesignUnitIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a456a75a6f029c44407201cd4cd455fc9">TranslatorAdapter\_1\_8\_15::trDesignUnitList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#afd2600f0d8e70d85d5740aa345b3b6a1">TranslatorAdapter\_1\_8\_15::trDesignUnitListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a11d578bee263b072d88f0f00495e23a2">TranslatorAdapter\_1\_8\_15::trDesignUnitMembers</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#acd41f1f414a18526b5a0f24dfd1f1801">TranslatorAdapter\_1\_8\_15::trDesignUnits</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#aa35437f429a5f29e6f0ff2b1017e425a">TranslatorAdapter\_1\_8\_0::trDetailLevel</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a6d1f3dc6de5bfbdee41cd85363aaf5d0">TranslatorAdapter\_1\_8\_15::trDictionaries</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a5ed4a10dafb66dded59d82a369252f67">TranslatorAdapter\_1\_8\_15::trDictionaryDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#a9fd692d7cae641aa6b25c50c0df59c31">TranslatorAdapter\_1\_7\_5::trDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#aa8b4b2f8beb86395d8d25e7c90947de4">TranslatorAdapter\_1\_6\_0::trDirRelation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-4-6/#a572251cdd3aa2518a0b7725cb7769ea1">TranslatorAdapter\_1\_4\_6::trEnumerationValueDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#a33227ccc8b5d6d7ef909cbb157973299">TranslatorAdapter\_1\_8\_0::trEnumGeneratedFromFiles</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#aa97309261c4f50688132c22ee742c548">TranslatorAdapter\_1\_8\_0::trEnumReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#abafa018e8728231826415a6aa0d12a8a">TranslatorAdapter\_1\_8\_15::trExceptionDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a563a6ad0c1b5d9cab115ce2fcd07eae7">TranslatorAdapter\_1\_8\_15::trExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ad76f409045d1cddb191d2780085b13a1">TranslatorAdapter\_1\_8\_15::trExceptionHierarchyDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a980a1c0e0ebde33fe4d0b42aabe656fb">TranslatorAdapter\_1\_8\_15::trExceptionIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ab282b9036aeaa0b85fa7d6a0606eeba1">TranslatorAdapter\_1\_8\_15::trExceptionList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a648e2f3d2c4c07a18028952762e0104a">TranslatorAdapter\_1\_8\_15::trExceptionListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a177d40fd49d56ec3df44b07976d237a8">TranslatorAdapter\_1\_9\_8::trExportedModules</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a5a023717cab3784adf36c4bd5d8e1e48">TranslatorAdapter\_1\_8\_2::trExtendsClass</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#ae10e111c888ec8b48603b9e28a7b5546">TranslatorAdapter\_1\_7\_5::trFileIn</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-5/#a04f26147aafa6744b03ce0eced3430f8">TranslatorAdapter\_1\_9\_5::trFlowchart</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a5bebdb7a2dbfa1202c303a38bd36c2ef">TranslatorAdapter\_1\_8\_15::trFunctionAndProc</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a11b1dfaef9a5f44fa2a091b410d316be">TranslatorAdapter\_1\_6\_0::trGeneratedFromFilesFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a1c0b8733ec3ea8875cad8eebcc5908f3">TranslatorAdapter\_1\_6\_0::trGlobalNamespace</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-11-0/#a90330144fe12976d2bdfd515c4648421">TranslatorAdapter\_1\_11\_0::trImportant</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-7-5/#a8d49879ffbfc7f1a8cbb9a3a8cd7102a">TranslatorAdapter\_1\_7\_5::trIncludesFileIn</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#ac85292ec177607e5f697133f976e9aac">TranslatorAdapter\_1\_8\_0::trInheritedFrom</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a0242f758b8aff6bf1681e7aa035129cd">TranslatorAdapter\_1\_8\_2::trInstanceMethods</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ad3a5bb7bd5aa029de5d8bb875a349430">TranslatorAdapter\_1\_8\_15::trInterfaceDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#ac6090bb02fe5744a85a96342d06166be">TranslatorAdapter\_1\_8\_15::trInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#aaf37482303655212c7d028c23980d9e7">TranslatorAdapter\_1\_8\_15::trInterfaceHierarchyDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#adbdfa93a14e5cd43963f553b7e03238f">TranslatorAdapter\_1\_8\_15::trInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#aa700593879a9ef1e3e52420578fd3aba">TranslatorAdapter\_1\_8\_15::trInterfaceList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a528cb1ecd5fb763e81545e0ab2184fc0">TranslatorAdapter\_1\_8\_15::trInterfaceListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#a7c7fd5e69069745e4684133458611bbb">TranslatorAdapter\_1\_8\_4::trInterfaces</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#ad31c71c0639d8c44847590e148d63506">TranslatorAdapter\_1\_6\_0::trLoading</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a81a70433a29918f29a271a3dc05a77b7">TranslatorAdapter\_1\_6\_0::trMemberFunctionDocumentationFortran</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a3cc5103457502de40d00424d0059e596">TranslatorAdapter\_1\_8\_2::trMethodDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a498c55a402637bee26fbc37aaba378c2">TranslatorAdapter\_1\_6\_0::trModule</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a4a297185f9ef1113ff49870c945a00a0">TranslatorAdapter\_1\_9\_8::trModuleMembersDescriptionTotal</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a1bb11a8f2cf6615ed5b9b3689b89a50e">TranslatorAdapter\_1\_6\_0::trModuleReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a0f2a2a17dabedeccf6a7f37a0a68450a">TranslatorAdapter\_1\_6\_0::trModulesIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a3863abee147389fe28573b6ba812bd5f">TranslatorAdapter\_1\_6\_0::trModulesList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a0cbe881fc2ea6a6cfff0015181853173">TranslatorAdapter\_1\_6\_0::trModulesListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a9e02be9b49e394250429bf5ec065377e">TranslatorAdapter\_1\_6\_0::trModulesMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#aa3499a2084321b6e311b202151567cc9">TranslatorAdapter\_1\_6\_0::trModulesMembers</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#affdbcfdeb1b9010eac256961acd37783">TranslatorAdapter\_1\_6\_0::trNoMatches</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a2bc255ab6013bff39c6c62886aefd5da">TranslatorAdapter\_1\_8\_15::trOperationDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a7576206d4adef22a8570657bafcfbbff">TranslatorAdapter\_1\_8\_15::trOperations</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-4/#ab77147e4cde51ce53637a6b322e4d417">TranslatorAdapter\_1\_9\_4::trPackageList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a6acc66b458c67a952279282ae742d19c">TranslatorAdapter\_1\_8\_2::trPanelSynchronisationTooltip</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-2/#a01de25773e588563fc998c0b83288aea">TranslatorAdapter\_1\_8\_2::trProvidedByCategory</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#aa354362e6e1900ac79f8f6b0120e887f">TranslatorAdapter\_1\_6\_0::trSearching</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a304b6e3e75fa6c0b1c865c831e6356a5">TranslatorAdapter\_1\_8\_15::trSequenceDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a7bd20019f684b6100c5656dd187e1a1a">TranslatorAdapter\_1\_8\_15::trSequences</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#aa0f1523cdaff3b98befa3bfc82d915e0">TranslatorAdapter\_1\_8\_4::trServiceGeneratedFromFiles</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#a7d3292e5446e5c04bb258766da513275">TranslatorAdapter\_1\_8\_4::trServiceReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#a5c0186ab5a823d296b572684054abbb8">TranslatorAdapter\_1\_8\_4::trServices</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#ab0b758a383730a6537b84ac4f29bd308">TranslatorAdapter\_1\_8\_4::trSingletonGeneratedFromFiles</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-4/#a3b2ca7e982ed95f415c8a4719a3b45e4">TranslatorAdapter\_1\_8\_4::trSingletonReference</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a466b9af82579a8d818b3810531236f87">TranslatorAdapter\_1\_8\_15::trSliceInterfaces</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a3be2442fa346ad4d2e8af910323a61ba">TranslatorAdapter\_1\_8\_15::trStructDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#aae4cfef65b6690b830b6bad14d15f2a0">TranslatorAdapter\_1\_8\_15::trStructIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a55410edc2d19a8dfff035c4ba06cd4ee">TranslatorAdapter\_1\_8\_15::trStructList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a72730c7641b1f899f21a74c653fc073c">TranslatorAdapter\_1\_8\_15::trStructListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a11065ccf89b66845313c9802c27317f6">TranslatorAdapter\_1\_8\_15::trStructs</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a0bb7f2b14bdedf6c3e4a9ec5e16221da">TranslatorAdapter\_1\_6\_0::trSubprogram</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a50bc903a254f317a7f75d857f1e551b9">TranslatorAdapter\_1\_6\_0::trSubprogramDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a710bc564171108a12f7f9759ed60f46d">TranslatorAdapter\_1\_6\_0::trSubprograms</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-0/#ae9abd6dfebca2aa03267bbf40f692937">TranslatorAdapter\_1\_8\_0::trTemplateParameters</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a6e2cb60614340d33cba2e3d780e1372c">TranslatorAdapter\_1\_9\_8::trTopicDocumentation</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a7efd025f196f95dc5f0b04ee1117a1a1">TranslatorAdapter\_1\_9\_8::trTopicIndex</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a6456b5ee3299b7f81ce233ce8bc29c1e">TranslatorAdapter\_1\_9\_8::trTopicList</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a90027ccaf66f59b1236c0c418059b93b">TranslatorAdapter\_1\_9\_8::trTopicListDescription</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-9-8/#a48bb219c4a12ea4c86549f34aa81615f">TranslatorAdapter\_1\_9\_8::trTopics</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#a1edd9e42c4ce4fc3d94283857dab0791">TranslatorAdapter\_1\_6\_0::trType</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#ae197c105864d5a4e9565548df4036219">TranslatorAdapter\_1\_6\_0::trTypeConstraints</a>, <a href="/web-doxygen/docs/api/classes/translatoradapter-1-6-0/#accb29a1af52dab4e39d51177649f546c">TranslatorAdapter\_1\_6\_0::trTypeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/translatoradapter-1-8-15/#a9cb3629c43748a948ffcc6cb43526b23">TranslatorAdapter\_1\_8\_15::trVhdlType</a>.
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
