---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/doctokenizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocTokenizer` Class Reference



## Declaration

<div class="doxyDeclaration">
class DocTokenizer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/doctokenizer-h">src/doctokenizer.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6384abe92f96fc6fa9c2fd47ce057b6e">DocTokenizer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d2b66a1db91742f0de4c9239192fce">~DocTokenizer</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060403865cc48ca7f55af46d8272282c">token</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf8532d281e202aaf58eb8daa3e5742">resetToken</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ffd450e14852a41762e405e33efed7d">setLineNr</a> (int lineno)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5366d3fa4095f81903bcc38ca7c88c7">getLineNr</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e052e3732a2c7bb469ac4834cb1819">pushState</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b3ac28b0574b550069906f1b758a30">popState</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640bce791d53e83dcbd47f7ab01620e8">findSections</a> (const QCString &amp;input, const Definition *d, const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ef42f7f738e8eef6801d5f701b4b8f">init</a> (const char *input, const QCString &amp;fileName, bool markdownSupport, bool insideHtmlLink)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1416a695181d2b7475649fcfa6328afc">cleanup</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ed44ca62a9c1f9a33f3be549b9bd2f">pushContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2407880f57f0b80f4f803d369776189">popContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286239d4401fbbfb8b183a7e9c521866">lex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8df06c9b8d04453c03cd380baa8e0b8">unputString</a> (const QCString &amp;tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c97a1c50f2345ed8a821b064752e4c">setStatePara</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2">setStateTitle</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6da566ad128beaf9ccb68aa8d1c705">setStateTitleAttrValue</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34431cb2cd05302e5f119e040a769f37">setStateCode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcff1fd7726a10245844d66db38958c">setStateICode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8885a45a72652256b2889ada34466ef">setStateXmlCode</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac363da2884c9fac4485a41f4c62f30ec">setStateHtmlOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b58ee7b91c9386f23990ae2a3aac4d6">setStateManOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809628767bfb37617b67e8909177c379">setStateLatexOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9d0c6ca2a16fa2b0d11aaca48d29f7">setStateXmlOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd6696245928c12d39088589853903f0">setStateDbOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663752c3113ff8c63348c9efb7dc48ab">setStateRtfOnly</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746075b39ec5494c78a415f58d9a31a2">setStateVerbatim</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2eaeb1ff17b18714dba1df124638e0">setStateIVerbatim</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176080102d22a57cf6b954cd0fd800ed">setStateILiteral</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146a51289b61c4a07eae63f20a70c47c">setStateILiteralOpt</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2726da7c2b27d07e2a8ab92a280b73f6">setStateDot</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34eda462c7101585f7632608537fbaa5">setStateMsc</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b84c53eb58ffa4536429f435af7dc7e">setStateParam</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa411158a25cb6c8180ed3b371d5c76c0">setStateXRefItem</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800041c36835be7289de964cd48966cf">setStateFile</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42356130c7f62e388d487606719fcaa4">setStateIFile</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d618f840d6483ebe02c2eb19b66531">setStatePattern</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e912a405a74470ff41c7cd66dd7d8d">setStateLink</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccf706bbc6ef5c6dc46020feef92b48">setStateCite</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6c257f79f2b4cfebeb232710ea89b3">setStateDoxyConfig</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a480480bc983e0a6b3982516e39f0a0e7">setStateRef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3823e30efb8777b24236bf28c1fac52">setStateInternalRef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace7e3d8edd67ef73441256379557aea">setStateText</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59640a5ec3ad9cbad272a6925f189542">setStateSkipTitle</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61dcd0ef63e1d16cf7fe47ecf5bc8892">setStateAnchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8546fd68f4a34986e4fb9adeca44a7">setInsidePre</a> (bool b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff805b06ccfab10b895659c51afb5829">pushBackHtmlTag</a> (const QCString &amp;tag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e486e33ea997eb77a714fa5ff47f60d">setStateSnippet</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354d1d1fc89286290f7cbcd0e2e1d3b0">startAutoList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41327ee370bdbdf5e367328e8e83a23b">endAutoList</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84231059e79d7a987d450315ea4c555">setStatePlantUML</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af231e89152d53e5c666cf3e18aaadb8f">setStateSetScope</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605b63eab0905368b46d73b38f2d04e6">setStatePlantUMLOpt</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad361dcd21e016d2b11b9547025eb940e">setStateOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0e4aba378bcd41427c01c1aed84650">setStateBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fbe30cd437ccd6c1b1ab3273bbb13ea">setStateEmoji</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb3c15b818a362e992e1a29cd7cba0b">setStateILine</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde6d5b20c7ce890471cf3624183d4d0">setStateQuotedString</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2996962fd97f18550674846502274b">setStateShowDate</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f55af9e8e2d60d02519b04f247ca2b9">setStatePrefix</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/doctokenizer/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede113d286596811d42ad1fab08996e4">p</a></td>
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


<p>Definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocTokenizer() {#a6384abe92f96fc6fa9c2fd47ce057b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocTokenizer::DocTokenizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1752 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6384abe92f96fc6fa9c2fd47ce057b6e">1752</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a6384abe92f96fc6fa9c2fd47ce057b6e">DocTokenizer::DocTokenizer</a>() : <a href="#aede113d286596811d42ad1fab08996e4">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/doctokenizer/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:DocTokenizer::DocTokenizer()\n",(void*)this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">  doctokenizerYYlex_init_extra(&amp;<a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;extra,&amp;<a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  doctokenizerYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">Debug::Lex_doctokenizer</a>)?1:0,<a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">Debug::Lex_doctokenizer</a> and <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DocTokenizer() {#a70d2b66a1db91742f0de4c9239192fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocTokenizer::~DocTokenizer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1761 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70d2b66a1db91742f0de4c9239192fce">1761</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a70d2b66a1db91742f0de4c9239192fce">DocTokenizer::~DocTokenizer</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p:DocTokenizer::~DocTokenizer()\n",(void*)this);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">  doctokenizerYYlex_destroy(<a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cleanup() {#a1416a695181d2b7475649fcfa6328afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::cleanup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2148 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1416a695181d2b7475649fcfa6328afc">2148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1416a695181d2b7475649fcfa6328afc">DocTokenizer::cleanup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_delete_buffer( YY_CURRENT_BUFFER, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### endAutoList() {#a41327ee370bdbdf5e367328e8e83a23b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::endAutoList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 242 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2183 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41327ee370bdbdf5e367328e8e83a23b">2183</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41327ee370bdbdf5e367328e8e83a23b">DocTokenizer::endAutoList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;autoListLevel--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>.</p>

</div>
</div>

### findSections() {#a640bce791d53e83dcbd47f7ab01620e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::findSections (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1779 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a640bce791d53e83dcbd47f7ab01620e8">1779</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a640bce791d53e83dcbd47f7ab01620e8">DocTokenizer::findSections</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">                                </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">Debug::Lex_doctokenizer</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString = input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("parsing ---&gt;'%s'&lt;---\n",input);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPos    = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;definition  = d;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName    = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Sections);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;yyLineNr = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">  doctokenizerYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">Debug::Lex_doctokenizer</a>, <a href="#aede113d286596811d42ad1fab08996e4">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a0fc0d3e4ca95dd0dc254d0efb1fd045a">docFindSections</a>.</p>

</div>
</div>

### getLineNr() {#ae5366d3fa4095f81903bcc38ca7c88c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocTokenizer::getLineNr (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2197 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5366d3fa4095f81903bcc38ca7c88c7">2197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae5366d3fa4095f81903bcc38ca7c88c7">DocTokenizer::getLineNr</a>(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> yyextra-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>.</p>

</div>
</div>

### init() {#a27ef42f7f738e8eef6801d5f701b4b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::init (const char * input, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool markdownSupport, bool insideHtmlLink)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1797 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27ef42f7f738e8eef6801d5f701b4b8f">1797</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a27ef42f7f738e8eef6801d5f701b4b8f">DocTokenizer::init</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *input,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideHtmlLink)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;autoListLevel = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString = input;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPos    = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName    = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insidePre   = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;markdownSupport = markdownSupport;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideHtmlLink = insideHtmlLink;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Para);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>.</p>

</div>
</div>

### lex() {#a286239d4401fbbfb8b183a7e9c521866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocTokenizer::lex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1767 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a286239d4401fbbfb8b183a7e9c521866">1767</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> doctokenizerYYlex(<a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8cdd911ef9ea557d2fd2a0f034efcaa4">DocPara::handleILine</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/dochref/#a2a9332a0da85f6e0596e3d46cea53fe5">DocHRef::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a4f952166357e3d6d33312208d4a768f3">DocHtmlCaption::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a6f4ae9d09701b93305b6e90260bc5662">DocHtmlTable::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternalref/#ab9cc38fde444889a618974f396bf36ed">DocInternalRef::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a> and <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>.</p>

</div>
</div>

### popContext() {#ae2407880f57f0b80f4f803d369776189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocTokenizer::popContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1731 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2407880f57f0b80f4f803d369776189">1731</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae2407880f57f0b80f4f803d369776189">DocTokenizer::popContext</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1732</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1733</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocTokenizer::popContext() stack=%zu\n",yyextra-&gt;lexerStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;lexerStack.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ctx = yyextra-&gt;lexerStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;autoListLevel = ctx-&gt;autoListLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPos      = ctx-&gt;inputPos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString   = ctx-&gt;inputString;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token         = ctx-&gt;token;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_delete_buffer(YY_CURRENT_BUFFER, yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_switch_to_buffer(ctx-&gt;state, yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(ctx-&gt;rule);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lexerStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#aede113d286596811d42ad1fab08996e4">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### popState() {#ad3b3ac28b0574b550069906f1b758a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::popState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2211 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3b3ac28b0574b550069906f1b758a30">2211</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad3b3ac28b0574b550069906f1b758a30">DocTokenizer::popState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(!yyextra-&gt;stateStack.empty());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(yyextra-&gt;stateStack.top());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;stateStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### pushBackHtmlTag() {#aff805b06ccfab10b895659c51afb5829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::pushBackHtmlTag (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2162 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff805b06ccfab10b895659c51afb5829">2162</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aff805b06ccfab10b895659c51afb5829">DocTokenizer::pushBackHtmlTag</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tagName = tag;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(tagName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">  unput(</span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=l-1;i&gt;=0;i--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">    unput(tag[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">  unput(</span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dochtmldesclist/#a74ff0b5b4a4173213a643d6897d7f9c2">DocHtmlDescList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#ab8fc1655d43a50f996a8878eb66e0dc7">DocHtmlList::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllist/#a53b4acdb633ea0dea82a74cafd533e31">DocHtmlList::parseXml</a> and <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>.</p>

</div>
</div>

### pushContext() {#ab0ed44ca62a9c1f9a33f3be549b9bd2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::pushContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1716 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0ed44ca62a9c1f9a33f3be549b9bd2f">1716</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab0ed44ca62a9c1f9a33f3be549b9bd2f">DocTokenizer::pushContext</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1717</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DocTokenizer::pushContext() stack=%zu\n",yyextra-&gt;lexerStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lexerStack.push(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">      std::make_unique&lt;DocLexerContext&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;token,YY_START,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;autoListLevel,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;inputPos,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">        yyextra-&gt;inputString,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">        YY_CURRENT_BUFFER));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">  yy_switch_to_buffer(yy_create_buffer(0, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>, yyscanner), yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aede113d286596811d42ad1fab08996e4">p</a> and <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#ae7e51116e747d3390e7a6cfc6532834c">YY_BUF_SIZE</a>.</p>

</div>
</div>

### pushState() {#a32e052e3732a2c7bb469ac4834cb1819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::pushState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2204 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32e052e3732a2c7bb469ac4834cb1819">2204</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a32e052e3732a2c7bb469ac4834cb1819">DocTokenizer::pushState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;stateStack.push(YYSTATE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### resetToken() {#aeaf8532d281e202aaf58eb8daa3e5742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenInfo * DocTokenizer::resetToken ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1818 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeaf8532d281e202aaf58eb8daa3e5742">1818</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> *<a href="#aeaf8532d281e202aaf58eb8daa3e5742">DocTokenizer::resetToken</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token = <a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;yyextra-&gt;token;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>.</p>

</div>
</div>

### setInsidePre() {#a9a8546fd68f4a34986e4fb9adeca44a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setInsidePre (bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2155 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a8546fd68f4a34986e4fb9adeca44a7">2155</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a8546fd68f4a34986e4fb9adeca44a7">DocTokenizer::setInsidePre</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insidePre = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>.</p>

</div>
</div>

### setLineNr() {#a2ffd450e14852a41762e405e33efed7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setLineNr (int lineno)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2190 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ffd450e14852a41762e405e33efed7d">2190</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2ffd450e14852a41762e405e33efed7d">DocTokenizer::setLineNr</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineno)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;yyLineNr = lineno;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>.</p>

</div>
</div>

### setStateAnchor() {#a61dcd0ef63e1d16cf7fe47ecf5bc8892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateAnchor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 237 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2074 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a61dcd0ef63e1d16cf7fe47ecf5bc8892">2074</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a61dcd0ef63e1d16cf7fe47ecf5bc8892">DocTokenizer::setStateAnchor</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### setStateBlock() {#a5f0e4aba378bcd41427c01c1aed84650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2111 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f0e4aba378bcd41427c01c1aed84650">2111</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5f0e4aba378bcd41427c01c1aed84650">DocTokenizer::setStateBlock</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Block);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>.</p>

</div>
</div>

### setStateCite() {#a1ccf706bbc6ef5c6dc46020feef92b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateCite ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 231 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2032 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ccf706bbc6ef5c6dc46020feef92b48">2032</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1ccf706bbc6ef5c6dc46020feef92b48">DocTokenizer::setStateCite</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Cite);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>.</p>

</div>
</div>

### setStateCode() {#a34431cb2cd05302e5f119e040a769f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateCode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1848 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34431cb2cd05302e5f119e040a769f37">1848</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34431cb2cd05302e5f119e040a769f37">DocTokenizer::setStateCode</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_CodeOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateDbOnly() {#abd6696245928c12d39088589853903f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateDbOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 217 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1908 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd6696245928c12d39088589853903f0">1908</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd6696245928c12d39088589853903f0">DocTokenizer::setStateDbOnly</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_DbOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateDot() {#a2726da7c2b27d07e2a8ab92a280b73f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateDot ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1956 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2726da7c2b27d07e2a8ab92a280b73f6">1956</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2726da7c2b27d07e2a8ab92a280b73f6">DocTokenizer::setStateDot</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Dot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateDoxyConfig() {#add6c257f79f2b4cfebeb232710ea89b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateDoxyConfig ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2039 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add6c257f79f2b4cfebeb232710ea89b3">2039</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#add6c257f79f2b4cfebeb232710ea89b3">DocTokenizer::setStateDoxyConfig</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_DoxyConfig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>.</p>

</div>
</div>

### setStateEmoji() {#a1fbe30cd437ccd6c1b1ab3273bbb13ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateEmoji ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2119 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fbe30cd437ccd6c1b1ab3273bbb13ea">2119</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1fbe30cd437ccd6c1b1ab3273bbb13ea">DocTokenizer::setStateEmoji</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Emoji);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>.</p>

</div>
</div>

### setStateFile() {#a800041c36835be7289de964cd48966cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2003 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a800041c36835be7289de964cd48966cf">2003</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a800041c36835be7289de964cd48966cf">DocTokenizer::setStateFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_File);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>.</p>

</div>
</div>

### setStateHtmlOnly() {#ac363da2884c9fac4485a41f4c62f30ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateHtmlOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1875 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac363da2884c9fac4485a41f4c62f30ec">1875</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac363da2884c9fac4485a41f4c62f30ec">DocTokenizer::setStateHtmlOnly</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_HtmlOnlyOption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateICode() {#acfcff1fd7726a10245844d66db38958c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateICode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1857 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfcff1fd7726a10245844d66db38958c">1857</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acfcff1fd7726a10245844d66db38958c">DocTokenizer::setStateICode</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_iCodeOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateIFile() {#a42356130c7f62e388d487606719fcaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateIFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 228 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2010 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42356130c7f62e388d487606719fcaa4">2010</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a42356130c7f62e388d487606719fcaa4">DocTokenizer::setStateIFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_IFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### setStateILine() {#accb3c15b818a362e992e1a29cd7cba0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateILine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2127 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accb3c15b818a362e992e1a29cd7cba0b">2127</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#accb3c15b818a362e992e1a29cd7cba0b">DocTokenizer::setStateILine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_ILine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a8cdd911ef9ea557d2fd2a0f034efcaa4">DocPara::handleILine</a>.</p>

</div>
</div>

### setStateILiteral() {#a176080102d22a57cf6b954cd0fd800ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateILiteral ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1924 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a176080102d22a57cf6b954cd0fd800ed">1924</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a176080102d22a57cf6b954cd0fd800ed">DocTokenizer::setStateILiteral</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_ILiteral);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateILiteralOpt() {#a146a51289b61c4a07eae63f20a70c47c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateILiteralOpt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1932 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a146a51289b61c4a07eae63f20a70c47c">1932</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a146a51289b61c4a07eae63f20a70c47c">DocTokenizer::setStateILiteralOpt</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_ILiteralOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateInternalRef() {#ac3823e30efb8777b24236bf28c1fac52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateInternalRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2053 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3823e30efb8777b24236bf28c1fac52">2053</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac3823e30efb8777b24236bf28c1fac52">DocTokenizer::setStateInternalRef</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_IntRef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### setStateIVerbatim() {#aeb2eaeb1ff17b18714dba1df124638e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateIVerbatim ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1948 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb2eaeb1ff17b18714dba1df124638e0">1948</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeb2eaeb1ff17b18714dba1df124638e0">DocTokenizer::setStateIVerbatim</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_iVerbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateLatexOnly() {#a809628767bfb37617b67e8909177c379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateLatexOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1916 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a809628767bfb37617b67e8909177c379">1916</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a809628767bfb37617b67e8909177c379">DocTokenizer::setStateLatexOnly</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_LatexOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateLink() {#a75e912a405a74470ff41c7cd66dd7d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateLink ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 230 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2025 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75e912a405a74470ff41c7cd66dd7d8d">2025</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a75e912a405a74470ff41c7cd66dd7d8d">DocTokenizer::setStateLink</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Link);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a> and <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>.</p>

</div>
</div>

### setStateManOnly() {#a8b58ee7b91c9386f23990ae2a3aac4d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateManOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1884 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b58ee7b91c9386f23990ae2a3aac4d6">1884</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8b58ee7b91c9386f23990ae2a3aac4d6">DocTokenizer::setStateManOnly</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_ManOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateMsc() {#a34eda462c7101585f7632608537fbaa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateMsc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1964 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34eda462c7101585f7632608537fbaa5">1964</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34eda462c7101585f7632608537fbaa5">DocTokenizer::setStateMsc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Msc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateOptions() {#ad361dcd21e016d2b11b9547025eb940e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateOptions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2103 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad361dcd21e016d2b11b9547025eb940e">2103</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad361dcd21e016d2b11b9547025eb940e">DocTokenizer::setStateOptions</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Options);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>.</p>

</div>
</div>

### setStatePara() {#ae3c97a1c50f2345ed8a821b064752e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStatePara ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1826 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3c97a1c50f2345ed8a821b064752e4c">1826</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3c97a1c50f2345ed8a821b064752e4c">DocTokenizer::setStatePara</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;insideHtmlLink = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Para);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a10a22fde1124375bf9f58cbea8eadf84">DocPara::handleCite</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a724e489c954b750341d697b29e98033f">DocPara::handleEmoji</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2c5971c7bbbb5bd01e02ac7d93600281">DocPara::handleFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a3a7bca787f76b9c7cd05429fe738e790">DocPara::handleIFile</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8cdd911ef9ea557d2fd2a0f034efcaa4">DocPara::handleILine</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a> and <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>.</p>

</div>
</div>

### setStateParam() {#a5b84c53eb58ffa4536429f435af7dc7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateParam ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 225 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1989 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b84c53eb58ffa4536429f435af7dc7e">1989</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b84c53eb58ffa4536429f435af7dc7e">DocTokenizer::setStateParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Param);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>.</p>

</div>
</div>

### setStatePattern() {#a34d618f840d6483ebe02c2eb19b66531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStatePattern ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2017 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34d618f840d6483ebe02c2eb19b66531">2017</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a34d618f840d6483ebe02c2eb19b66531">DocTokenizer::setStatePattern</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Pattern);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a7c235343a063e005bfee6c68b14a835e">DocPara::handleIncludeOperator</a>.</p>

</div>
</div>

### setStatePlantUML() {#ae84231059e79d7a987d450315ea4c555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStatePlantUML ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1981 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae84231059e79d7a987d450315ea4c555">1981</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae84231059e79d7a987d450315ea4c555">DocTokenizer::setStatePlantUML</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_PlantUML);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStatePlantUMLOpt() {#a605b63eab0905368b46d73b38f2d04e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStatePlantUMLOpt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1972 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a605b63eab0905368b46d73b38f2d04e6">1972</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a605b63eab0905368b46d73b38f2d04e6">DocTokenizer::setStatePlantUMLOpt</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.sectionId=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_PlantUMLOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStatePrefix() {#a1f55af9e8e2d60d02519b04f247ca2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStatePrefix ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2081 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f55af9e8e2d60d02519b04f247ca2b9">2081</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f55af9e8e2d60d02519b04f247ca2b9">DocTokenizer::setStatePrefix</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Prefix);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### setStateQuotedString() {#adde6d5b20c7ce890471cf3624183d4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateQuotedString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2134 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adde6d5b20c7ce890471cf3624183d4d0">2134</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adde6d5b20c7ce890471cf3624183d4d0">DocTokenizer::setStateQuotedString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_QuotedString);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>.</p>

</div>
</div>

### setStateRef() {#a480480bc983e0a6b3982516e39f0a0e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 233 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2046 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a480480bc983e0a6b3982516e39f0a0e7">2046</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a480480bc983e0a6b3982516e39f0a0e7">DocTokenizer::setStateRef</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Ref);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a> and <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>.</p>

</div>
</div>

### setStateRtfOnly() {#a663752c3113ff8c63348c9efb7dc48ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateRtfOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1892 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a663752c3113ff8c63348c9efb7dc48ab">1892</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a663752c3113ff8c63348c9efb7dc48ab">DocTokenizer::setStateRtfOnly</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_RtfOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateSetScope() {#af231e89152d53e5c666cf3e18aaadb8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateSetScope ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2096 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af231e89152d53e5c666cf3e18aaadb8f">2096</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af231e89152d53e5c666cf3e18aaadb8f">DocTokenizer::setStateSetScope</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_SetScope);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateShowDate() {#a8d2996962fd97f18550674846502274b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateShowDate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2141 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d2996962fd97f18550674846502274b">2141</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8d2996962fd97f18550674846502274b">DocTokenizer::setStateShowDate</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_ShowDate);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#ad112877bd5902d918781a9f2d5e0f703">DocPara::handleShowDate</a>.</p>

</div>
</div>

### setStateSkipTitle() {#a59640a5ec3ad9cbad272a6925f189542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateSkipTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2067 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59640a5ec3ad9cbad272a6925f189542">2067</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a59640a5ec3ad9cbad272a6925f189542">DocTokenizer::setStateSkipTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_SkipTitle);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a2bb5ccde078a4388fbd245dd98b466bf">DocPara::handleSection</a>.</p>

</div>
</div>

### setStateSnippet() {#a1e486e33ea997eb77a714fa5ff47f60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateSnippet ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2088 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e486e33ea997eb77a714fa5ff47f60d">2088</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1e486e33ea997eb77a714fa5ff47f60d">DocTokenizer::setStateSnippet</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Snippet);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1bb9289a32b8c06de83c728786bb0669">DocPara::handleInclude</a>.</p>

</div>
</div>

### setStateText() {#aace7e3d8edd67ef73441256379557aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateText ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 235 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2060 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aace7e3d8edd67ef73441256379557aea">2060</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aace7e3d8edd67ef73441256379557aea">DocTokenizer::setStateText</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/doctext/#aada5a740aa0832964895e683340b76a5">DocText::parse</a>.</p>

</div>
</div>

### setStateTitle() {#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1834 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2">1834</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2">DocTokenizer::setStateTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dochtmlsummary/#a4768457c4357b86443890d950cb3e740">DocHtmlSummary::parse</a>, <a href="/web-doxygen/docs/api/classes/docindexentry/#a788ff313987522a9be055abe2fdb1592">DocIndexEntry::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecrefitem/#a35c9d6d150e7faaa88ea9ddfbeadb777">DocSecRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a12306a4f4de4310c8201fac9d29eb627">DocTitle::parse</a> and <a href="/web-doxygen/docs/api/classes/docvhdlflow/#afe55c9c5bf1a823e78d6aa3ea3f0777b">DocVhdlFlow::parse</a>.</p>

</div>
</div>

### setStateTitleAttrValue() {#a0b6da566ad128beaf9ccb68aa8d1c705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateTitleAttrValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 209 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1841 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b6da566ad128beaf9ccb68aa8d1c705">1841</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b6da566ad128beaf9ccb68aa8d1c705">DocTokenizer::setStateTitleAttrValue</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_TitleV);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### setStateVerbatim() {#a746075b39ec5494c78a415f58d9a31a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateVerbatim ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1940 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a746075b39ec5494c78a415f58d9a31a2">1940</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a746075b39ec5494c78a415f58d9a31a2">DocTokenizer::setStateVerbatim</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_Verbatim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateXmlCode() {#ab8885a45a72652256b2889ada34466ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateXmlCode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1866 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8885a45a72652256b2889ada34466ef">1866</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8885a45a72652256b2889ada34466ef">DocTokenizer::setStateXmlCode</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.name=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_XmlCode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>.</p>

</div>
</div>

### setStateXmlOnly() {#aeb9d0c6ca2a16fa2b0d11aaca48d29f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateXmlOnly ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1900 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeb9d0c6ca2a16fa2b0d11aaca48d29f7">1900</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeb9d0c6ca2a16fa2b0d11aaca48d29f7">DocTokenizer::setStateXmlOnly</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;token.verb=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_XmlOnly);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### setStateXRefItem() {#aa411158a25cb6c8180ed3b371d5c76c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::setStateXRefItem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1996 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa411158a25cb6c8180ed3b371d5c76c0">1996</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa411158a25cb6c8180ed3b371d5c76c0">DocTokenizer::setStateXRefItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(St_XRefItem);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>.</p>

</div>
</div>

### startAutoList() {#a354d1d1fc89286290f7cbcd0e2e1d3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::startAutoList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 241 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 2176 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a354d1d1fc89286290f7cbcd0e2e1d3b0">2176</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a354d1d1fc89286290f7cbcd0e2e1d3b0">DocTokenizer::startAutoList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;autoListLevel++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docautolist/#a8eef0f06619e7a80df0c5dd10e83cb2b">DocAutoList::parse</a>.</p>

</div>
</div>

### token() {#a060403865cc48ca7f55af46d8272282c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TokenInfo * DocTokenizer::token ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1811 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a060403865cc48ca7f55af46d8272282c">1811</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/tokeninfo">TokenInfo</a> *<a href="#a060403865cc48ca7f55af46d8272282c">DocTokenizer::token</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;yyextra-&gt;token;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aede113d286596811d42ad1fab08996e4">p</a>.</p>

</div>
</div>

### unputString() {#ab8df06c9b8d04453c03cd380baa8e0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocTokenizer::unputString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>, definition at line 1772 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8df06c9b8d04453c03cd380baa8e0b8">1772</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8df06c9b8d04453c03cd380baa8e0b8">DocTokenizer::unputString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tag)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#aede113d286596811d42ad1fab08996e4">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a86da2f5e3360caa90276fc24433d9512">unput_string</a>(tag.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),tag.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#aede113d286596811d42ad1fab08996e4">p</a> and <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a86da2f5e3360caa90276fc24433d9512">unput_string</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#adbe932c521ee8cde5ccc5cdca438fa5f">checkIfHtmlEndTagEndsAutoList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aede113d286596811d42ad1fab08996e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; DocTokenizer::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aede113d286596811d42ad1fab08996e4">256</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aede113d286596811d42ad1fab08996e4">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1416a695181d2b7475649fcfa6328afc">cleanup</a>, <a href="#a6384abe92f96fc6fa9c2fd47ce057b6e">DocTokenizer</a>, <a href="#a41327ee370bdbdf5e367328e8e83a23b">endAutoList</a>, <a href="#a640bce791d53e83dcbd47f7ab01620e8">findSections</a>, <a href="#ae5366d3fa4095f81903bcc38ca7c88c7">getLineNr</a>, <a href="#a27ef42f7f738e8eef6801d5f701b4b8f">init</a>, <a href="#a286239d4401fbbfb8b183a7e9c521866">lex</a>, <a href="#ae2407880f57f0b80f4f803d369776189">popContext</a>, <a href="#ad3b3ac28b0574b550069906f1b758a30">popState</a>, <a href="#aff805b06ccfab10b895659c51afb5829">pushBackHtmlTag</a>, <a href="#ab0ed44ca62a9c1f9a33f3be549b9bd2f">pushContext</a>, <a href="#a32e052e3732a2c7bb469ac4834cb1819">pushState</a>, <a href="#aeaf8532d281e202aaf58eb8daa3e5742">resetToken</a>, <a href="#a9a8546fd68f4a34986e4fb9adeca44a7">setInsidePre</a>, <a href="#a2ffd450e14852a41762e405e33efed7d">setLineNr</a>, <a href="#a61dcd0ef63e1d16cf7fe47ecf5bc8892">setStateAnchor</a>, <a href="#a5f0e4aba378bcd41427c01c1aed84650">setStateBlock</a>, <a href="#a1ccf706bbc6ef5c6dc46020feef92b48">setStateCite</a>, <a href="#a34431cb2cd05302e5f119e040a769f37">setStateCode</a>, <a href="#abd6696245928c12d39088589853903f0">setStateDbOnly</a>, <a href="#a2726da7c2b27d07e2a8ab92a280b73f6">setStateDot</a>, <a href="#add6c257f79f2b4cfebeb232710ea89b3">setStateDoxyConfig</a>, <a href="#a1fbe30cd437ccd6c1b1ab3273bbb13ea">setStateEmoji</a>, <a href="#a800041c36835be7289de964cd48966cf">setStateFile</a>, <a href="#ac363da2884c9fac4485a41f4c62f30ec">setStateHtmlOnly</a>, <a href="#acfcff1fd7726a10245844d66db38958c">setStateICode</a>, <a href="#a42356130c7f62e388d487606719fcaa4">setStateIFile</a>, <a href="#accb3c15b818a362e992e1a29cd7cba0b">setStateILine</a>, <a href="#a176080102d22a57cf6b954cd0fd800ed">setStateILiteral</a>, <a href="#a146a51289b61c4a07eae63f20a70c47c">setStateILiteralOpt</a>, <a href="#ac3823e30efb8777b24236bf28c1fac52">setStateInternalRef</a>, <a href="#aeb2eaeb1ff17b18714dba1df124638e0">setStateIVerbatim</a>, <a href="#a809628767bfb37617b67e8909177c379">setStateLatexOnly</a>, <a href="#a75e912a405a74470ff41c7cd66dd7d8d">setStateLink</a>, <a href="#a8b58ee7b91c9386f23990ae2a3aac4d6">setStateManOnly</a>, <a href="#a34eda462c7101585f7632608537fbaa5">setStateMsc</a>, <a href="#ad361dcd21e016d2b11b9547025eb940e">setStateOptions</a>, <a href="#ae3c97a1c50f2345ed8a821b064752e4c">setStatePara</a>, <a href="#a5b84c53eb58ffa4536429f435af7dc7e">setStateParam</a>, <a href="#a34d618f840d6483ebe02c2eb19b66531">setStatePattern</a>, <a href="#ae84231059e79d7a987d450315ea4c555">setStatePlantUML</a>, <a href="#a605b63eab0905368b46d73b38f2d04e6">setStatePlantUMLOpt</a>, <a href="#a1f55af9e8e2d60d02519b04f247ca2b9">setStatePrefix</a>, <a href="#adde6d5b20c7ce890471cf3624183d4d0">setStateQuotedString</a>, <a href="#a480480bc983e0a6b3982516e39f0a0e7">setStateRef</a>, <a href="#a663752c3113ff8c63348c9efb7dc48ab">setStateRtfOnly</a>, <a href="#af231e89152d53e5c666cf3e18aaadb8f">setStateSetScope</a>, <a href="#a8d2996962fd97f18550674846502274b">setStateShowDate</a>, <a href="#a59640a5ec3ad9cbad272a6925f189542">setStateSkipTitle</a>, <a href="#a1e486e33ea997eb77a714fa5ff47f60d">setStateSnippet</a>, <a href="#aace7e3d8edd67ef73441256379557aea">setStateText</a>, <a href="#a7b9c9df4ada21e5fb5c5a7d5eac0fbd2">setStateTitle</a>, <a href="#a0b6da566ad128beaf9ccb68aa8d1c705">setStateTitleAttrValue</a>, <a href="#a746075b39ec5494c78a415f58d9a31a2">setStateVerbatim</a>, <a href="#ab8885a45a72652256b2889ada34466ef">setStateXmlCode</a>, <a href="#aeb9d0c6ca2a16fa2b0d11aaca48d29f7">setStateXmlOnly</a>, <a href="#aa411158a25cb6c8180ed3b371d5c76c0">setStateXRefItem</a>, <a href="#a354d1d1fc89286290f7cbcd0e2e1d3b0">startAutoList</a>, <a href="#a060403865cc48ca7f55af46d8272282c">token</a>, <a href="#ab8df06c9b8d04453c03cd380baa8e0b8">unputString</a> and <a href="#a70d2b66a1db91742f0de4c9239192fce">~DocTokenizer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/doctokenizer-h">doctokenizer.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/doctokenizer-l">doctokenizer.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
